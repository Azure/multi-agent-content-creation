# Multi-Agent Content Generation: Let GPT agents collaborate for you

Use multi-agent architectures with Azure OpenAI to automate text generation through agent collaboration and fully capture LLM capabilities within your application.

## Content Generation Roundtable

There are 7 GPT agents discussing together to create the perfect content for your specific newspaper brand. Here are the roles of each agent:
- Group chat manager controls the conversation and gives turns to other agents to speak
- User proxy imitates the human user and decides when the article is complete (based on feedback from other experts)
- Outline generator creates a suitable outline for the writer to work upon
- Writer is responsible for writing the first draft and creating new versions of the article based on feedback from others
- Newspaper style checker compares writer's article to other published articles from your newspaper brand and gives feedback about suitability
- Stylist gives feedback about curiosity of the article, use of writing tools (questions, action words etc.) and maintaining engagement
- Editor gives feedback about the flow and tonality of the article
![image](https://github.com/duihub/multi-agent-text-generation/assets/117650819/5c71bb51-6239-4548-9107-f57a4b234bc0)



## Other Autogen examples:

### Code execution including error debugging

<img width="844" alt="image" src="https://github.com/duihub/multi-agent-text-generation/assets/117650819/8eb1298a-ab41-4f96-88e0-76dc6feca090">
(find code here https://github.com/microsoft/autogen/blob/main/notebook/agentchat_auto_feedback_from_code_execution.ipynb)


### Complex task resolution using "expert" agents called on demand

<img width="1129" alt="image" src="https://github.com/duihub/multi-agent-text-generation/assets/117650819/f914bd34-2181-4133-aaee-62840132d12e">
(find code here https://github.com/microsoft/autogen/blob/main/notebook/agentchat_two_users.ipynb)
