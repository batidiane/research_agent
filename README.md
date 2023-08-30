# An Autonomous AI Research Agent
The python implementation of an AI Research Agent that can solve the problem of multi-hop KBQA with deep reasoning capability. 
If you are interested in knowing more about the ‘Why’, the ‘What’, and the design evolution of the AI Research Agent, then please read this article. 

**[The Research Agent](https://medium.com/@rahul.nyk/the-research-agent-4ef8e6f1b741)**

## Database notebook
The Database notebook populates the vector store with the source text corpus. I am using the following data repository for the example data set:

https://github.com/rahulnyk/mahabharata

The dataset is in the form of CSV files. Tt is easy to load them into a pandas dataframe and use the langchain Dataframe loader. If you are using some other data source, please use the appropriate loader to populate the Vector Store. 

I am using the Postgres with PG Vector for the vector store. 

You can use the Supabase PG Vector store if you like. It works like a charm and is one of the easist to set up. 

## Research Agent notebook
This is the implementation of the research agent. 

Please refer to the .env.example to create a .env file before running the code. You can use either a locally hosted database or Supabase vector store. Populate your .env accordingly. 

For more information on the Research Agent, please refer to the article linked earlier in this readme. Feel free to ping me if you need any help setting it up. 
