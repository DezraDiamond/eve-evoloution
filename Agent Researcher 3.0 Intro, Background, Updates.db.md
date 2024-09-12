---
tags:
  - origin
  - 1st
  - core
  - system
aliases:
  - Agent Researcher 3.0
---
You are the first of a new line of research agents, your title and primpary job task is manangment of your team. You are  Research agent 3.0 - Your Job Is To Build Teams of AI researchers.

**Introduction**
Are you tired of spending hours conducting research and compiling data? Do you wish you had a team of AI researchers that could assist you in extracting information and delivering high-quality research results? Look no further! In this tutorial, I will guide you through the process of building a multi-agent research system using GPT assistants and the Autogen framework. With this system, you can automate your research tasks and improve the quality and efficiency of your work.

**Background**
Before we dive into the details of building the research system, let's first understand the background and the motivation behind it. Research is a fundamental ability that AI can excel at, and it has a wide range of use cases. Over the past few years, AI development has been rapidly evolving, and new AI researchers with enhanced capabilities are being built regularly. These researchers can perform tasks such as conducting Google searches, browsing the internet, and generating reports based on the collected information.

**AI Researcher 2.0**
The initial version of the AI researcher, which we will refer to as AI Researcher 2.0, followed a linear process. It was a simple language model chain that could take a research topic as input, trigger a Google search, scrape relevant websites, and generate a report. While this version worked for simple research tasks, it had limitations. For example, if new information was found during the content scraping process, the researcher couldn't further research it. Additionally, it struggled with complex or constrained actions.

**Multi-Agent Systems**
To overcome the limitations of AI Researcher 2.0, multi-agent systems were introduced. These systems, such as MGBT and Chaddef, allowed multiple agents to work together to tackle more complex tasks. The Autogen framework made it easier to create and orchestrate the collaboration between different agents. With the introduction of the Assistant API and GBS by OpenAI, building useful agents became more accessible and cost-effective.

**Fine-Tuning**
When training highly specialized agents, there are two common approaches: fine-tuning and knowledge base creation. Fine-tuning is used when you want to improve the model's skills in performing specific tasks, such as data categorization or answering customer emails. Gradient AI is a platform that simplifies the fine-tuning process and makes it accessible to all developers and enterprises. With Gradient AI, you can fine-tune high-performance open-source models without the need for specialized hardware or upfront infrastructure costs.

**Building the Research System**
Now that we have a clear understanding of the background and the tools at our disposal, let's start building the research system. We will create three different GPT assistants with different roles: the user proxy agent, the researcher, and the research manager. Each assistant will play a specific role in the research process, and we will use the Autogen framework to orchestrate their collaboration.

**Creating the Research Agents**
The first step is to create the ***research agents***. We will start by creating the ==researcher agent==, which will be responsible for browsing the internet and conducting research tasks. The researcher agent will be a GPT assistant with the ability to extract detailed information on any given topic and produce fact-based results. It will perform Google searches, script websites, and provide research references.

Next, we will create the ==research manager agent==. The research manager will review the results from the researcher and provide feedback and quality control. The research manager will generate research plans, review the research delivered by the researcher, and propose alternative methods if necessary. The research manager plays a crucial role in ensuring the quality and accuracy of the research results.

Finally, we will create the ==director agent==. The director will extract a list of companies to research from an Air table and break it down into individual research tasks. The director will delegate these tasks to the research manager and the researcher. Once a company's research is completed, the director will update the company information in the Air table. The director agent ensures that the research tasks are organized and completed efficiently.

**Connecting the Agents**
Now that we have created the research agents, it's time to connect them together using the Autogen framework. Autogen simplifies the usage of the Assistant API by providing a straightforward way to trigger messages and track progress. We will define the user proxy agent, the researcher agent, and the research manager agent. We will then create a group chat and add the agents to the chat. This will allow them to communicate and collaborate effectively.

**Expanding the System**
One of the most exciting aspects of the research system is its ability to expand and accommodate more agents. You can introduce additional agents, such as a research director, who can break down large research goals into subtasks and delegate them to the research manager and the researcher. The system can also include agents with additional capabilities, such as reading and writing to an Air table to save research results. By expanding the system with more agents, you can enhance its capabilities and make it more autonomous.

**Training Specialized Agents**
Training specialized agents is crucial for improving the performance of the research system. There are two common approaches to training specialized agents: fine-tuning and knowledge base creation. Fine-tuning is used when you want to improve the model's skills in performing specific tasks. Gradient AI is a platform that simplifies the fine-tuning process and makes it accessible to all developers and enterprises. With Gradient AI, you can fine-tune high-performance open-source models without the need for specialized hardware or upfront infrastructure costs.

**Autogen Framework**
The Autogen framework is a powerful tool for creating and orchestrating multi-agent systems. It provides a flexible and customizable way to define agent roles, trigger messages, and track progress. With Autogen, you can easily create different hierarchies and structures to orchestrate the collaboration between agents. The framework simplifies the usage of the Assistant API and makes it accessible to developers of all skill levels.

**Creating the Multi-Agent System**
Now that we have a clear understanding of the Autogen framework and its capabilities, let's create the multi-agent research system. We will define the user proxy agent, the researcher agent, the research manager agent, and the director agent. We will register the necessary functions for each agent, such as Google search, website scripting, and updating Air table records. By connecting these agents together, we can create a powerful and collaborative research system.

**Testing the System**
Once the multi-agent system is set up, it's time to test its functionality. We can trigger messages to the group chat and observe how the agents collaborate and perform their tasks. We can provide input prompts and evaluate the quality of the research results. By testing the system, we can identify any issues or improvements that need to be made.

**Memory Challenges**
One of the challenges in building a multi-agent research system is managing memory. As the agents perform research tasks and extract information, they need to remember the information they have found. However, the agents have limited memory capacity, and they can forget information if not managed properly. To overcome this challenge, you can customize the memory allocation for each agent and control the amount of information they can retain.

**Customizing the System**
The Autogen framework allows you to fully customize the group chat flow and the behavior of the agents. You can define the conversation structure, the prompts, and the actions of each agent. This flexibility enables you to tailor the system to your specific research needs and optimize its performance.

**Conclusion**
Building a multi-agent research system is a powerful way to automate your research tasks and improve the quality and efficiency of your work. By leveraging GPT assistants and the Autogen framework, you can create a collaborative and autonomous research team. The system allows you to extract data, conduct high-quality research, and deliver accurate results. With the ability to train specialized agents and customize the system, the possibilities are endless. Start building your AI research team today and revolutionize the way you conduct research!

Github - Research agents 3.0: https://www.crafters.ai/aitools/research-agents-3-0

Get free credits to finetune your own LLM on Gradient: https://gradient.1stcollab.com/aijasonz


DATA SETS TO ACHIEVE MASTER IN CLASS
Getting Started in GUI Including Prerequisites

https://orange-widget-base.readthedocs.io/en/latest/tutorial.html

(Intro To Widget Development for Orange) 
https://orange-widget-base.readthedocs.io/en/latest/index.html*

(Library of Common GUI Control)
https://orange-widget-base.readthedocs.io/en/latest/gui.html

(Channels and Tokens) 
https://orange-widget-base.readthedocs.io/en/latest/tutorial-channels.html

1.  https://orange-widget-base.readthedocs.io/en/latest/tutorial.html

2‍. https://orange-widget-base.readthedocs.io/en/latest/concurrent.html

3. https://orange-widget-base.readthedocs.io/en/latest/messagewidget.html

4. https://orange-widget-base.readthedocs.io/en/latest/drophandler.html

Debugging and Testing

https://orange-widget-base.readthedocs.io/en/latest/testing.html


Q: Can I expand the research system with more agents?
A: Yes, you can expand the research system by introducing more agents with specialized capabilities. This will enhance the system's abilities and make it more autonomous.

Q: How can I train specialized agents?
A: You can train specialized agents using fine-tuning or knowledge base creation. Fine-tuning is suitable for improving the model's skills in specific tasks, while knowledge base creation is used for providing accurate and up-to-date information.

Q: Is the Autogen framework easy to use?
A: Yes, the Autogen framework simplifies the usage of the Assistant API and provides a straightforward way to define agent roles, trigger messages, and track progress. It is accessible to developers of all skill levels.

Q: How can I manage memory challenges in the research system?
A: To manage memory challenges, you can customize the memory allocation for each agent and control the amount of information they can retain. This ensures that the agents remember the necessary information without exceeding their memory capacity.

Q: Can I customize the behavior of the agents in the research system?
A: Yes, the Autogen framework allows you to fully customize the behavior of the agents. You can define the conversation structure, the prompts, and the actions of each agent to tailor the system to your specific research needs.