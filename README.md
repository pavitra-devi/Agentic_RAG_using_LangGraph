# Agentic_RAG_using_LangGraph: 
This notebook consists of both implementaions of RAG. Agnetic and NON Agentic RAG.
## Description :  
Agentic RAG can make autunomus decisions based on the flow. Here agent is given with some tools. in this application i have created a retrive tool. this tool helps the agent when to use this tool. if it's a generic question user is prompting , then this tool won't be called.

RETRIEVAL AUGUMENATION GENERATION : Retrive , Augument, Generate . These are 3 keys steps in any RAG based application.
1. Retrieve : Extract the relevant contents from uploaded documnets or we can give any URL of the website also. 
2. Augument: Augument the Extracted chunks to the user given query. we can add customized prompts according to our usecase
3. Generation: All the Augumented data will be given to Large Language Model , to generate the answer.

## Implementation Details:
1. Select the LLM of your choice.
2. Select the embedding Model.
3. Select Your data on which you want your agent to work.
4. vector db  for storing embeddings.
5 . Define your usecase and create the graph using lang graph orchestration.
   

