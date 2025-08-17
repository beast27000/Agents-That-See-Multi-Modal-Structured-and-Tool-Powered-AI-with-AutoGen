# Agents That See – Multi-Modal, Structured, and Tool-Powered AI with AutoGen

The Agents That See project demonstrates the advanced capabilities of [AutoGen](https://microsoft.github.io/autogen/) agents, moving beyond simple text-based chat to emulate the workflows of real engineering teams. This lab explores agents that can process visual inputs, generate structured outputs, integrate with external tools, and dynamically discover capabilities—pushing toward true generalist AI systems.

## What This Project Explores

### Multi-Modal Understanding
- Agents process images as inputs, generating internal thoughts, commentary, and reasoning based on visual data.
- Demonstrates vision + text fusion, enabling intelligent visual reasoning for real-world applications.

### Structured Outputs
- Agents produce well-defined JSON or other structured formats instead of loose conversational replies.
- Ensures consistency, interoperability, and usability in downstream applications, dashboards, or APIs.

### Tool Use via Wrappers
- AutoGen agents are extended with external tools through wrappers, integrating with frameworks like [LangChain](https://www.langchain.com/).
- Proves AutoGen’s flexibility to bridge ecosystems and leverage diverse tools.

### MCP (Model Context Protocol) Integration
- Explores MCP as a mechanism for agents to dynamically discover and utilize external capabilities at runtime.
- Showcases a future where agents can seamlessly plug into arbitrary APIs and services, enhancing autonomy.

## Why This Matters

While most AI demos focus on conversation, this project pushes the boundaries by combining multiple advanced capabilities:
- **Vision**: Agents interpret and reason about visual inputs.
- **Structure**: Outputs are reliable and machine-friendly.
- **Action**: Tools and APIs extend agent functionality.
- **Connectivity**: MCP enables modular, pluggable intelligence.

This isn’t just a lab—it’s a proof of concept for production-ready agents that function as true engineering teammates, capable of perception, reasoning, and action in complex workflows.

## Setup & Running

### Installation
Ensure Python >=3.10 and <3.13 is installed. Install dependencies using:

```bash
pip install -r requirements.txt
```

For streamlined environment management, you can optionally use [uv](https://github.com/astral-sh/uv):

```bash
pip install uv
uv pip install -r requirements.txt
```

### Running the Notebook
1. Open the Jupyter notebook:

```bash
jupyter notebook notebooks/2_lab2_autogen_agentchat.ipynb
```

2. Run the cells sequentially to explore:
   - Multi-modal reasoning with image inputs.
   - Structured output enforcement.
   - LangChain tool wrapper integration.
   - MCP-driven dynamic capability discovery.

## Project Structure

```
2_agents_that_see/
├── notebooks/
│   └── 2_lab2_autogen_agentchat.ipynb  # Main notebook with project exploration
├── README.md                           # Project documentation
└── requirements.txt                    # Dependency list
```

## Configuration
- Add your LLM API key (e.g., `OPENAI_API_KEY`) to a `.env` file in the project root.
- Modify agent behaviors, tasks, or tool integrations directly in the notebook cells to experiment with different setups.

## Understanding Your Agents
The agents in this project are designed to:
- Collaborate in multi-agent setups with defined roles and goals.
- Execute structured tasks, from visual analysis to tool-driven actions.
- Integrate with external tools and APIs for extended functionality.

This framework is highly extensible, adaptable for tasks like image classification, data pipelines, or autonomous research workflows.

## Key Takeaway
Agents are evolving from simple chatbots into generalist collaborators. By combining multi-modal perception, structured outputs, tool integration, and MCP connectivity, this project offers a glimpse into a future where AI agents function as fully capable engineering teammates.

## Support
- Explore the [AutoGen Documentation](https://microsoft.github.io/autogen/docs/).
- Join [GitHub Discussions](https://github.com/microsoft/autogen/discussions) for community support.
- Contribute examples, experiments, or feedback to the AutoGen open-source community.

## Output

![WhatsApp Image 2025-07-16 at 13 59 19_f90ad8de](https://github.com/user-attachments/assets/93f98943-6c83-44ec-9434-3aed84cec4a0)

![WhatsApp Image 2025-07-16 at 13 59 30_6e6fe95c](https://github.com/user-attachments/assets/8a9e208b-3b81-4e8b-9452-e90381b3468c)



Start building the next generation of intelligent, multi-modal AI systems with Agents That See!

Made by Vishvvesh Nagappan
