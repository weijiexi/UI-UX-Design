# Module 6: Generative Agents: Simulating Human Behavior

- Generative agents: Autonomous software entities designed to simulate human behavior and decision making.  
- Soar architecture: Cognitive architecture used to model and simulate human cognition. It integrates various cognitive processes such as learning, problem solving, and decision making.  
- Memory stream: A sequence of actions and memories that are listed and stored for easier data handling and analysis.  
- Ackerman’s socio-technical gap: Refers to the divide between what we know we must support socially and what we can support technically.  

In this module, the focus will be on one of the most intriguing frontiers of AI: generative agents and their role in simulating human behavior. we will explore how these simulations can inform design decisions and the opportunities they present.
- Learn about generative agents and how human simulations drive design decisions
- Understand which problems may be solved through the use of generative agents
- Learn how to leverage LLMs for the creation of generative agents

<details>
  <summary>1. Motivations for Human Behavior Simulations</summary>

  Everything we do—every product we create, every organizational design we develop, and every policy we create as a government or civil society—is based on implicit assumptions about human behavior. Those assumptions generally concern how the design, policy, or marketing behavior will impact the behavioral responses of those affected by it.

 <details>
  <summary>Micromotives and Macrobehavior</summary>

  You're referring to a classic and foundational example in the field of agent-based modeling. In Micromotives and Macrobehavior, Thomas Schelling showed how individual preferences, even when mild or seemingly benign, can lead to unexpected collective outcomes—like widespread neighborhood segregation—through simple local interactions.

  This concept directly connects to the design of generative agents in modern AI systems:
  #### **Why It’s Relevant to Generative Agents**
  Generative agents simulate individual behaviors, preferences, and decision-making processes. Just like Schelling’s agents who move based on neighborhood composition, today's AI agents can be designed to simulate social dynamics, spread information, or mimic user behaviors.

  In pandemic modeling, for example, researchers used similar agent-based models to simulate how individual compliance (or non-compliance) with mask-wearing or lockdowns could shape population-level outcomes. This is a real-world application of how local rules and preferences can scale to macro behavior—a key insight also critical for designing trustworthy AI systems.

  ### **How to Reflect on This in Practice**
  - When designing generative agents, always ask: "What are the micro-behaviors or assumptions we’re embedding?"
  - Consider how small biases, even in agent logic or data, can lead to large-scale outcomes (good or bad).
  - Think about Schelling’s lesson when simulating user behavior, crowd dynamics, or social influence in your own tools—emergence matters.
  </details>

  computer science areas ranging from HCI to **AI have long created models that are inspired by human cognition**. These models include features such as **working memory** and **performance**. Other fields, like robotics, have also used cognitive architectures, such as the Soar architecture (Laird, 2012).

  #### **The Sims**
  The Sims that create fun environments where avatars interact, and the user is trying to shape the space to create certain types of responses. **These are fascinating simulations of human behavior, and the user can shape that behavior**.
  
  <details>
  <summary>Behavioral Simulation Empowers Science and Design</summary>

  those models will need to learn how to operate within our social environments. They need to be able to simulate how people will react to certain situations.

  Stanford has also been exploring how AI might help us prepare and engage in certain situations. In a paper by Krishna, Lee, Fei, & Bernstein (2022), the authors experimented by deploying an interactive agent on a large photo-sharing social network, where it had to learn how to ask questions about images in ways that were interesting enough to gather responses in the social network. This “socially situated AI” is representative of what many AIs will need to do in the future: **not just complete tasks, but do so while aware of the human element all around them**.

  **Example: Navigating Difficult Conversations**
  As another example, we could use AI to help us prepare for difficult conversations with our managers, so that when the conversations take place, we have already practiced reacting to the different directions the conversation might go in and how to respond in each scenario. Omar Shaikh, along with Diyi Yang and Michael Bernstein in Stanford Computer Science, and Michele Gelfand and Valentino Chai at the Stanford Business School, developed just such a system (Shaikh et al., 2024). **You can use the system to rehearse a conflict before you have that tough conversation with your boss**.**

  **to build better systems—whether we are talking about technological designs, organizational designs, institutions, or products—we need better simulations of human attitudes and behavior**.

  ### **Main reasons for building human simulations**
  - We wish to build models that allow us to **explore counterfactuals**. For example: “How would people respond to this change?”
  - Human simulation models help us recognize **second-order consequences of what we do**. For example: “My design improved on my desired metric, but my actions also created all these other negative consequences that I did not foresee.”
  - Human simulation models help us **iterate and reflect**. Sociologists have long talked about the importance of understanding that the way we design will cause purposive action. Are we getting the responses we hoped for or not?

  ### **Keep in mind**
  One of the main obstacles when building these models is that human behavior is—of course—very complicated. It is contingent; it varies from person to person; it depends on their surroundings and their situations. However, our existing simulation models are rigid. They are limited by complex interdependencies between manually specified parameters, making believable behavior difficult to create and steer.

  As a result, one option for building these models has been **establishing a few parameters specifying, mathematically, how a person behaves**. This approach, called agent-based modeling, is how social scientists have constructed these models until recently. However, these parameters create complex interdependencies that make it difficult to create or steer believable behavior outside of narrow bounds.

  An alternative would be to have a small set of manually crafted knowledge so that when the agents encounter certain circumstances, they know how to react. This can be realistic, but only for a small number of tasks. This is what powers programs like The Sims.
  </details>


  <details>
  <summary>LLMs and Human Behavior</summary>

  Generative AI offers an opportunity to reconsider these limitations. Large language models and modern AI systems have been trained on a variety of human behaviors: they have trained on essentially the entire public internet, drawing from websites, blog posts, and social media. This extensive training data allows **the LLMs to learn about our social world, allowing us to prompt them to adopt a variety of backgrounds, experiences, and traits**.

  If we go into a system like ChatGPT, we can ask it to provide information on famous characters, celebrities, or people with relevant online information. Furthermore, you can ask it to take the persona of a specific person and ask how they would react in certain situations. It might not be perfect, and there remain issues with stereotypes and bias, but it can often do a first-order approximation using that persona. By creating an entire crowd of such personas, you can create an entire crowd of different perspectives.

  **These LLM-powered agents allow us to simulate different people in different scenarios**. We can think of these as **“prompt agents”**, **where we ask ChatGPT with a prompt to pretend to be a person and have the model react to certain situations**. But, these prompt agents have real limitations. They generally work for single actions, such as dropping a single persona into a situation and having it react to that one moment in time. **To create better simulations, we need a system that can manage constantly growing memory as the simulation evolves, and thereby create cascading social dynamics. Additionally, the agents should also get to know each other. Stanford faculty—well, my colleagues and I—have been researching agents that could make this possible and we have come to call these generative agents**.
  </details>

</details>

<details>
  <summary>2. Generative Agents</summary>

  ### **Why Do We Call Them Generative Agents?**

  These agents draw on generative models like ChatGPT to simulate believable human behavior. We call these generative agents because they draw on generative models like ChatGPT to **simulate believable human behavior**. It’s important to emphasize the word believable. **Believable behavior does not always mean accurate behavior. Enhanced accuracy is the current horizon of this area**.

  However, believable behavior is still very powerful. These agents are capable of:
  - **Drawing inferences about themselves, other agents, and their environment**
  - **Creating daily plans that reflect their characteristics and experiences**
  - **Acting out those plans, reacting, and replanning**
  - **Responding when the end user changes the environment or interacts with them**
  
  These capabilities are now possible thanks to AI. So much so, that if we create a controllable avatar within that environment and influence the policies and parameters, **the agents will react in believable ways**.

  **These agents go about their day completing these tasks and they do it without having to manually specify what they are supposed to do. The user only provides them with broad descriptions of their routine and goals, but the agents are free to act and react according to their personalities, traits, and other characteristics**.
  - Defining Our Agents
    - Our team defined each agent completely through natural language. 
    - The agents produce natural language statements about what they are doing.
    - The LLM with parameters for an agent
  - User Control
    - We can interact with these agents by talking to them.
    - We can also teleport into the world and interact with other agents. These applications may range from somewhere between social environments, entertainment and video games, to simply direct training for specific scenarios, such as how to interact in social environments.
  - Non-Preprogrammed Behavior
    - the type of behavior displayed in Smallville is now possible without any type of explicit preprogramming. Without explicitly stating what the agents ought to do, they will go about their day according to their descriptions. As a result, they end up having compelling, believable behavior without any preprogrammed specificity of what they should do.
    - these agents will have conversations with each other, and the information they share gets stored in their memory.
</details>

<details>
  <summary>3. High-Level Architecture for Generative Agents</summary>

   He underlying technology behind virtual worlds like Smallville is **modern AI models, particularly large language models (LLMs)** and **the ability to construct small engineered systems on top of them**. This is what makes these systems so compelling. 
   
   As a designer, what do you need to know about what it takes to create generative agents? 
  
   **There are three key ideas**: 
   
   ### Memory
   Generative agents need memory. They need to remember who they have met and what they have done. However, it turns out that if you keep track of all these actions and perceptions that the agent has experienced, relevant information will get drowned out. In this case, what we need to do is implement something that we call a memory stream, and then retrieve the relevant information when we need it. We start by creating a record of everything that the agent has seen and heard during the simulation:

   #### **Memory Stream: A Full Record in Natural Language**
   This memory stream is a full record of what one of the agents perceives. As the agent navigates the environment, the memory stream keeps track of everything the agent sees. It is a lot of information, and much of it might not be particularly useful.

   From this stream, **the system needs to retrieve certain memories to make decisions**. 
   - Recency - If the memory was created or accessed recently, then it will be more likely to come back.
   - Importance - The importance of that memory will also be taken into account.
   - Relevance - Depending on the type of response required, some memories will be more relevant than others.

   By combining these factors, the system retrieves a subset of those memories and feeds that back to the agent.

   ### Reflection
   To achieve a reflective quality in our agents, we have them generate what we call “reflections” at regular intervals. You might think of reflections as shower thoughts. These reflections retrieve some of the agent's memories, such as the ones shown below, and then, we ask the AI model what it can infer from that information.
   
   ### Planning
   #### **Plan by conditioning on the agent’s summary and status**
   To achieve this, we need the agent to actively plan their day. This has been a longstanding challenge in AI. Our Smallville team addressed this by prompting the LLM with a description of the agent, their past actions, interests, and so on, and then asking the LLM to outline the agent’s plan for the near future (e.g., the agent’s plan for that day). This approach allows the agent to provide a broad plan of what they aim to accomplish.

 

</details>

<details>
  <summary>4. Agent Believability and Long-Term Behavior</summary>

  **Notable Errors from the Simulation**
  - If the agents fail to retrieve relevant memories, they may not act in believable ways.
  - Agents can hallucinate to embellish their memory.
  - Dialogue is overly formal, likely due to the model’s instruction tuning.
  - As a result of instruction tuning, agents may be overly cooperative.
</details>

<details>
  <summary>5. Applications for Generative Agents</summary>

  One of the foundational arguments in this module is that to build better systems, products, and institutions, we need better simulations of human attitudes and behavior. These allow us to ask important “what if” counterfactuals, recognize second-order consequences of an intervention, and empower tighter reflective loops in purposive social action. (Merton, 1939)

  Based on the Smallville simulation and other similar models, we can argue that:

  So far, models of human attitudes and behavior are possible and beneficial, and even that these models are necessary for design. Simulations like Smallville can be a great opportunity for the application of generative agents in social science, for example, by helping us understand what might happen as our features get deployed to large numbers of users.

  Moving forward, it is essential to consider models like these as part of our design loop. Ackerman’s socio-technical gap refers to the divide between what we know we must support socially and what we can support technically. In the past, we have caused significant harm by creating systems based on inadequate models of our social world. Bridging this gap requires improved models to ensure our designs effectively address both social and technical needs.

  Let’s take social networks as an example. Initially, these companies often do not understand how their designs will shape our behavior, but over the years, it has become clear how powerful their impact can be. As a response, we can separate agent-based models into two strategies:

  - Low-dimensional realism: Simple, abstract, and interpretable models with one or two parameters.
  - High-dimensional realism: Complex and broader models that are less interpretable.

  Traditionally, we have created low-dimensional, simple models. However, recent advancements in AI now allow for the development of high-dimensional realism models. While these are not perfect and lack complete accuracy, they enable the exploration of many questions through the creation of a general socio-cognitive unit that can, in a broad sense, behave like a person. If these types of advanced models existed when social networks were being developed and launched, there may have been additional insight into their potential impact on users and society.

  **What the Future Holds for Human Behavior Simulations**
 
  There are many things we need to aim for in the near future. Some of the principal questions regarding generative agents are:
  - How can we transition from believability to accuracy?
  - Can we replicate known behavioral science results?
  - Could we construct models of specific people and map out what these specific people would do?
  - How can we scale up these models from 25 agents to perhaps 25 million agents? How can this be technically achieved?
 
  One benefit of deeper and better descriptions of agents is that it can make the agents less vulnerable to prompt hacking (exploitation of vulnerabilities that influence how the LLM responds to prompts).

  Adding memory, reflection, and planning capabilities improves response accuracy, instead of potentially molding responses. This is because we are providing the agents with a broader set of experiences.

  As a key takeaway from this module, we can say that it is important to think about how these human simulations might empower decision-making by you and others around you.
</details>
