# Understanding Scale Rag
            Users
              |
            Load Balancer
              |
            Application Services
              |
            Caching Layer
              |
            Database layer(vector dbs)
              |
            Async Workers / Queues
              |
            Logging / Monitoring / Analytics


# Current Architecture

Backend/
|---- app/
|---- routers/
|---- utils/
Frontend
|--- src/
     |---> (Currently Thinking about using Typescript)


# Stacks

Current Thoughtouts:
- **Python**
- **TypeScript**
- **FastAPI**
- **Redis**
- **Weaviate**

# How do i Plan to Approach This Project ?

- Step 1: Make a Simple RAG Chatbot.
- Step 2: Stop if cannot futher updates else Find Limitations of the current system.
- Step 3: Research And Make Changes
- Step 4: Go to step 2.
