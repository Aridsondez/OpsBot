# OpsBot 


## Overview 
- OpsBot treats AI code changes as operations instead of just file diffs. When AI refactors your auth system or adds a feature, OpsBot records why it happened—not just what changed. This lets you revert, replay, or refine changes based on intent.
Think: git tracks file history. OpsBot tracks decision history.


## How it works
Operations: Every AI change becomes a semantic unit you can roll back or replay
Context awareness: Maintains a live model of your codebase, git branches, and dependencies
Structured memory: Remembers your services, env vars, and project quirks
Action execution: Runs tests and commands directly—no copy-paste
### Tech Stack
Backend: Java (JGit, SQLite, Picocli)
AI Layer: Python (FastAPI, Tree-sitter, LLM APIs)
Frontend: React + TypeScript + Tailwind
Storage: SQLite (local-first) 


### Why did I build this?

Well I sort of wanted something fun and intuitive to work on during my senior year. I have countless projects that I am working on for my senior year but none of them my own. 
I wanted to do something that sorts of pushes me to be like a little bit better as a programmer 
while still allowing me to learn. Java is something that I haven't touched in a while and I wanted to touch up on some of that.
I also wanted to build something that was sort of kinda useful. I think a big issue I have is the whole version control thing.
Like okay version control is great and all but times are changing and now we are not producing features one commit at a time but now ideas.
How do you enscapsolate an idea when pushing code. How do you keep track of those ideas. How do you revert those ideas? those are the questions 
that I had. Why not build something that proves those questions possible. 


Another thing I noticed, was how much time I was wasting repeating commands. Migrating DB's. Making the frontend then making the backend. Just using the CLI to do the same thing 
over and over again. It gets tedious. Like I dont have to keep typing `make backend` and `make frontend` and that's just with makefiles. Imagine having to run `univcord reload:app --blah blah blah` 
every time you want to run an application. How much hours i've wasted debugging something and failing countless times because I wrote the wrong message. Lets fix that issue as well. 

Lastly, sort of wanted to work on a Devtool. I think Ops is a growing field especially with AI. Hop on the train to replace developers so I can get a job. Making devs easier I guess. It makes my life easier 
having something like this. Maybe it will make Devs lives easier or some claude agent somewhere with an open api key sitting on the internets life easier. Anyway lets code.
