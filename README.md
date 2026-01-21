AI-Powered Football Analysis Chatbot
This academic project was developed by me and 3 colleagues at the Université Internationale de Rabat. The application transforms natural questions into complex database queries to provide analysis about football. This project is an integration of data engineering, graph modeling and generative AI

Source of data : Web scraping football data providers, and structuring them in JSON files

Neo4j : models the complex relationships between different data, it uses [:PLAYED_IN] to store performance metrics

Artificial Intelligence : Google Gemini is the system brain, it translates user intent into Cypher queries, a way to interpret results into tactical narratives

Backend : FastAPI (Python) handles the synchronization between the LLM and the database

Frontend: Next.js and Tailwind CSS provide the "Premier League" themed user interface

Security: A custom Cypher Guard module validates queries to prevent unwanted command execution, such as commands that would drop tables, delete data or attempt injection attacks.
