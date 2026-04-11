Defining Agentic AI
Agentic AI is a software paradigm where a system takes a high-level goal and works toward completing it on its own with minimal human intervention.

It is characterized by its ability to plan its own path, use external tools to take actions, and adapt its strategy if the environment changes.

It transitions the human role from a "micromanager" who prompts every step to a "supervisor" who provides goals and approves high-risk actions.

Six Key Characteristics of an Agent
Autonomy: The ability to make decisions and execute actions without step-by-step instructions.

Goal-Oriented: Every action is strictly directed toward a persistent objective.

Planning: Decomposing a high-level goal into a structured sequence of sub-goals.

Reasoning: Interpreting information from the environment to draw conclusions and make logic-based decisions.

Adaptability: The capacity to modify plans in response to unexpected failures or new external feedback.

Context Awareness: Retaining and utilizing information from past interactions and current environmental states to improve decision-making.

High-Level Components of an Agent
The Brain (LLM): The core engine that handles reasoning, goal interpretation, and task decomposition.

The Orchestrator: The framework (like LangGraph) that manages the sequence of tasks, retry logic, and conditional routing.

Tools: The "hands" of the agent, such as APIs, search engines, and databases, that allow it to interact with the outside world.

Memory: The storage system that tracks short-term session progress and long-term user preferences and history.

Supervisor: The component that implements "Human-in-the-Loop" controls, enforcing guardrails and handling escalations for risky tasks.