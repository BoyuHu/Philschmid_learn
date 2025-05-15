AI agents. Agentic AI. Agentic architectures. Agentic workflows. Agentic patterns. Agents are everywhere. But what exactly are they, and how do we build robust and effective agentic systems? While the term "agent" is used broadly, a key characteristic is their ability to dynamically plan and execute tasks, often leveraging external tools and memory to achieve complex goals.

This post aims to explore common design patterns. Think of these patterns as blueprints or reusable templates for building AI applications. Understanding them provides a mental model for tackling complex problems and designing systems that are scalable, modular, and adaptable.

We'll dive into several common patterns, differentiating between more structured workflows and more dynamic agentic patterns. Workflows typically follow predefined paths, while agents have more autonomy in deciding their course of action.

Why Do (Agentic) Patterns Matter?

Patterns provide a structured way to think and design systems.
Patterns allow us to build and grow AI applications in complexity and adapt to changing requirements. Modular designs based on patterns are easier to modify and extend.
Patterns help manage the complexity of coordinating multiple agents, tools, and workflows by offering proven, reusable templates. They promote best practices and shared understanding among developers.
When (and When Not) to Use Agents?

Before diving into patterns, it's crucial to consider when an agentic approach is truly necessary.

Always seek the simplest solution first. If you know the exact steps required to solve a problem, a fixed workflow or even a simple script might be more efficient and reliable than a agent.
Agentic systems often trade increased latency and computational cost for potentially better performance on complex, ambiguous, or dynamic tasks. Be sure the benefits outweigh these costs.
Use workflows for predictability and consistency when dealing with well-defined tasks where the steps are known.
Use agents when flexibility, adaptability, and model-driven decision-making are needed.
Keep it Simple (Still): Even when building agentic systems, strive for the simplest effective design. Overly complex agent can become difficult to debug and manage.
Agency introduces inherent unpredictability and potential errors. Agentic systems must incorporate robust error logging, exception handling, and retry mechanisms, allowing the system (or the underlying LLM) a chance to self-correct.