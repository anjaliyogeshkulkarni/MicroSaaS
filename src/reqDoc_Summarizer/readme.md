###################################################################################################
Problem statement : 

Automate QA processes using Agent workflows
1. Agent 1: Create an Agent workflow which will read a requirements document in a doc / txt format   
       Input : Requirements document
       Output : Point wise Summary of Document

2. Agent 2: Based on summarized Requirements document create testcases in a Gherkin format (Given - When - Then)    
       Input : Point wise Summary of Document
       Output : Testcases in Gherkin format
3. Agent 3: Create Selenium testscripts for each scenario in the Gherkin output from Agent 2
       Input : Gherkin testcases
       Output : Selenium automation test scripts 


###################################################################################################
Tech Stack:
Groq API
LLM model - gemma2-9b-it
Agent framework - Langchain
UI - Streamlit
###################################################################################################