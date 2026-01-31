# Now How will i code this thing??

Okay lets see the architecture will look sum like this 

CLI/ WEB --> talks to ---> java runtime <---- python api then some sqslite in the middle

Everything will run through that runtime. It will be the brains of this operation. Python will do what python does best, hit some APIs, parse some data and RAG. retrieval augment generation. taking data and making data.

So something like this: 

┌─────────────┐
│   CLI/Web   │
└──────┬──────┘
       │
┌──────▼──────────┐         ┌──────────────┐
│  Java Runtime   │◄────────┤ Python AI    │
│  - Git parsing  │  API    │ - Embeddings │
│  - Operations   │         │ - AST parse  │
│  - Rollback     │         │ - RAG        │
└────────┬────────┘         └──────────────┘
         │
    ┌────▼────┐
    │ SQLite  │
    └─────────┘

Thanks claude 

/var/folders/hw/33tk284s12539cfvbkxzs5600000gn/T/TemporaryItems/NSIRD_screencaptureui_ggbJ7J/Screenshot\ 2026-01-31\ at\ 1.46.20 AM.png 


This is another picture I wonder if it shows up but yeah that is the impolimentation of it all pretty cool. 

For MVP i'll start with the backend stuff then move on to the flashy frontend cool stuff 

- setup javaruntime
- setup sqslite
- conntect python ai layer
- fine tune
- make a cli 
- make frontend 
- push to repo 
