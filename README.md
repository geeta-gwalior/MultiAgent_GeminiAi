# MultiAgent_GeminiAi
This code sets up a multi-agent system using CrewAI and Gemini AI (via the ChatGoogleGenerativeAI model) to perform a structured workflow for researching and writing. The system consists of two main agents: Researcher and Writer, each with distinct goals and roles. The Researcher agent gathers insights on a given topic using AI-powered tools, while the Writer agent transforms those insights into a comprehensive article.

The Researcher agent is tasked with gathering important points and insights on the assigned topic (e.g., "how AI is replacing jobs") using the SerperDevTool for web-based research. The Writer agent then formats the research into a readable and engaging markdown article.

A sequential process is defined using CrewAI, where the Researcher first completes the research task, and the Writer follows up by generating the final output in a markdown file. This setup demonstrates how AI agents can collaborate to streamline research and content creation processes.





