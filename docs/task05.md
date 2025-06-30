# Task 05: Ausblick Wissensquellen

In dieser Übung lernst du, wie du die Intelligenz deines Agenten erweiterst, indem du ihn mit verschiedenen Wissensquellen verknüpfst. Anschließend nutzt du das Systemthema **Conversational Boosting**, um die Gesprächsfähigkeiten deines Agenten zu verbessern, und definierst benutzerdefinierte Prompt-Anweisungen, um die Antworten an deine Vorgaben anzupassen.


## Wissensquellen

Mit **Wissen** in Microsoft Copilot Studio kannst du Unternehmensdaten aus Power Platform, Dynamics 365 und externen Systemen anbinden, damit deine Agenten relevante Informationen und Einblicke für Endnutzer*innen liefern. Wissen lässt sich zudem mit generativen Antworten kombinieren. Veröffentliche Agenten, die Wissensquellen enthalten, nutzen diese konfigurierten Quellen zur „Verankerung“ (Grounding) ihrer Antworten.

### Unterstützte Wissensquellen

| **Name** | **Quelle** | **Beschreibung** | **# Eingaben (Q&A)** | **Auth** |
|----------|-----------|------------------|----------------------|----------|
| Public Website | Extern | Durchsucht die Anfrage in Bing und liefert Ergebnisse nur von den angegebenen Websites. | 4 öffentliche URLs (z. B. microsoft.com) | Keine |
| Documents | Intern | Durchsucht Dokumente, die in Dataverse hochgeladen wurden, und liefert Ergebnisse aus deren Inhalt. | Begrenzung durch Dataverse-Speicher | Keine |
| SharePoint | Intern | Verbindet sich mit einer SharePoint-URL und nutzt GraphSearch zur Ergebnisrückgabe. | 4 URLs | Entra ID des Copilot-Users |
| OneDrive for Business | Intern | Verbindet sich mit einer OneDrive-URL und nutzt GraphSearch zur Ergebnisrückgabe. | 4 URLs | Entra ID des Copilot-Users |
| Dataverse | Intern | Verbindet sich mit der verbundenen Dataverse-Umgebung und nutzt Retrieval-Augmented Generation. | 2 Dataverse-Quellen (max. 15 Tabellen je Quelle) | Entra ID des Copilot-Users |
| Enterprise data (Graph connections) | Intern | Verbindet sich mit der verbundenen Dataverse-Umgebung und nutzt Retrieval-Augmented Generation. | 2 pro Agent | Entra ID des Copilot-Users |



** **

Hier findest du alle Tasks des Workshops:

1. [Task 01 – Prompt-Agent](task01.md)  
2. [Task 02 – Unternehmensdaten](task02.md)  
3. [Task 03: Überblick über die Benutzeroberfläche von Microsoft Copilot Studio](task03.md)  
4. [Task 04 – Copilot-Topic](task04.md)  
5. [Task 05: Ausblick Wissensquellen](task05.md)  




