### Investment Property Bot

#### Overview
This project aims to create an AI investment property bot using Crew AI, OpenHermes, and OLLAMA. The bot automates property research tasks by gathering data on potential investment properties, including mean prices, rental yields, vacancy rates, and background information on suburbs. 

#### Technologies Used
- **Crew AI**: Utilized for orchestrating autonomous AI agents to perform various tasks.
- **OpenHermes**: Enables natural language processing for interacting with the bot.
- **OLLAMA**: Provides language model capabilities for understanding and generating text.

#### Packages
- **Crew AI Tools**: Used for accessing the internet and retrieving property data.
- **LangChain**: Imports OLLAMA for language model capabilities.

#### Features
- **Agent-based Architecture**: Implements a multi-agent framework to manage different tasks efficiently.
- **Internet Access**: Utilizes Crew AI tools to search the internet for property data.
- **Task Definition**: Defines tasks for agents to perform, such as finding promising investment properties and summarizing property information.
- **Report Generation**: Generates detailed reports on potential investment properties, facilitating data-driven decision-making.

#### Usage
1. Install required packages using `pip install -r requirements.txt`.
2. Run the `flow.py` script to execute the investment property bot.

#### Future Improvements
- Enhance search algorithms to improve the accuracy of property data retrieval.
- Implement additional agents for handling different aspects of property investment research.
- Integrate data visualization tools for better analysis and presentation of property data.
