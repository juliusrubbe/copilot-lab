# Task 05: Leverage knowledge sources, AI knowledge, and custom instructions

In this exercise, you'll learn how to enhance your agent's intelligence by integrating it with various knowledge sources. You'll then utilize the Conversational Boosting system topic to improve your agent's conversational abilities and set custom prompt instructions to tailor the responses to your specifications.

Objectives

After this exercise, you'll be able to:

Make your agent instantly smart by pointing to your website and other knowledge sources.

Navigate to the Generative AI settings.

Navigate to the Conversational Boosting system topic.

Set custom prompt instructions.

Knowledge sources

Knowledge in Microsoft Copilot Studio allows you to add enterprise data from Power Platform, Dynamics 365, and external systems, so your agents can provide relevant information and insights for your end users. In addition, knowledge can be incorporated with generative answers in agents. Published agents that contain knowledge use the configured knowledge sources to ground themselves.

Supported knowledge sources:

| **Name**                          | **Quelle**  | **Beschreibung**                                                                                                   | **# Inputs (Q&A)**                                      | **Auth**                                 |
|-----------------------------------|-------------|---------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------|------------------------------------------|
| Public Website                    | External    | Searches the query input on Bing, only returns results from provided websites                                       | 4 public URLs (e.g. microsoft.com)                      | None                                     |
| Documents                         | Internal    | Searches documents uploaded to Dataverse, returns results from the document contents                                | Limited by Dataverse file-storage allocation            | None                                     |
| SharePoint                        | Internal    | Connects to a SharePoint URL, uses GraphSearch to return results                                                    | 4 URLs                                                  | Copilot user’s Entra ID                  |
| OneDrive for Business             | Internal    | Connects to a OneDrive URL, uses GraphSearch to return results                                                      | 4 URLs                                                  | Copilot user’s Entra ID                  |
| Dataverse                         | Internal    | Connects to the connected Dataverse environment, uses retrieval-augmented generation                                | 2 Dataverse sources (max 15 Tables je Quelle)           | Copilot user’s Entra ID                  |
| Enterprise data (Graph connections) | Internal    | Connects to the connected Dataverse environment, uses retrieval-augmented generation                                | 2 pro Agent                                            | Copilot user’s Entra ID                  |



** **
Hier geht es zum nächsten Task: [Task 06 – Question / Message / Condition](task06.md)

Hier findest du alle Tasks des Workshops:

1. [Task 01 – Prompt-Agent](task01.md)  
2. [Task 02 – Unternehmensdaten](task02.md)  
3. [Task 03 – Pre-built Agent](task03.md)  
4. [Task 04 – Copilot-Topic](task04.md)  
5. [Task 05 – Knowledge & Boosting](task05.md)  
6. [Task 06 – Question / Message / Condition](task06.md)




