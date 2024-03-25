# Multi-Agent Content Generation: Let GPT agents collaborate to create perfect content for you

Use multi-agent architectures with Azure OpenAI to automate text generation through agent collaboration and fully capture LLM capabilities within your application. This repo can be used to create content for newspaper articles, social media posts, press releases, technical documentation, etc.



## Content Generation Roundtable

There are **7 GPT agents** discussing together to create the perfect content for your specific newspaper brand. Here are the roles of each agent:
- **Group chat manager** controls the conversation and gives turns to other agents to speak
- **User proxy** imitates the human user and decides when the article is complete (based on feedback from other experts)
- **Outline generator** creates a suitable outline for the writer to work upon
- **Writer** is responsible for writing the first draft and creating new versions of the article based on feedback from others
- **Newspaper style checker** compares writer's article to other published articles from your newspaper brand and gives feedback about suitability
- **Stylist** gives feedback about curiosity of the article, use of writing tools (questions, action words etc.) and maintaining engagement
- **Editor** gives feedback about the flow and tonality of the article
![image](https://github.com/duihub/multi-agent-text-generation/assets/117650819/5c71bb51-6239-4548-9107-f57a4b234bc0)
AutoGen is used as the LLM agent framework in this repository.


## Multi-Agent Frameworks

**What is an agent?**
- An AI assistant designed to interact with the real world
- Driven by an LLM
- Has access to a set of tools (knowledge base, database, etc.)
- Has a specific system message to define its behavior

**Why to use a multi-agent architecture?**
- Customizable and conversable agents within a group chat
- Agents collectively performing tasks autonomously
- Easy integration of human feedback
- Next-gen LLM applications with minimal effort
- Simple orchestration and optimization of complex LLM architectures

**Open-source frameworks:**
- AutoGen (developed by Microsoft)
https://microsoft.github.io/autogen/
https://github.com/microsoft/autogen/tree/main
- LangGraph
https://python.langchain.com/docs/langgraph
- Semantic Kernel (developed by Microsoft)
https://github.com/microsoft/semantic-kernel
https://techcommunity.microsoft.com/t5/educator-developer-blog/microsoft-semantic-kernel-and-autogen-open-source-frameworks-for/ba-p/4051305



## Other Autogen examples:

### Code execution including error debugging

<img width="844" alt="image" src="https://github.com/duihub/multi-agent-text-generation/assets/117650819/8eb1298a-ab41-4f96-88e0-76dc6feca090">
(find code here https://github.com/microsoft/autogen/blob/main/notebook/agentchat_auto_feedback_from_code_execution.ipynb)


### Complex task resolution using "expert" agents called on demand

<img width="1129" alt="image" src="https://github.com/duihub/multi-agent-text-generation/assets/117650819/f914bd34-2181-4133-aaee-62840132d12e">
(find code here https://github.com/microsoft/autogen/blob/main/notebook/agentchat_two_users.ipynb)
