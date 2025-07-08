 # Module 3: User Control vs. Automation

 In this module, we will explore one of the main elements that influences this relationship: the tension between **user control** and **automation**. 

- **Accelerators**: AI interfaces that have high certainty on the user goal and either take automatic action or suggest action to the user.  
- **Design galleries**: Platforms that leverage artificial intelligence to provide a variety of design works for the user to choose from.  
- **Direct manipulation**: In computer science, it refers to an approach in which humans have direct control over a system’s actions.   
- **Interface agents**: Programs that proactively complete tasks on behalf of the user, often with the help of artificial intelligence.  
- **Mixed-initiative interaction**: A specific approach in Human Computer Interaction where both humans and AI-powered systems contribute to decision-making and task completion, - allowing for flexible interaction and shared control over the interaction process.  
- **Verifiers**: AI interfaces with low certainty on the user goal and opt for a direct manipulation approach from the user.  

 <details>
  <summary>1. The Great Debate: Agents vs. Direct Manipulation</summary>

  ### What Are Interface Agents?
  - **Interface agents** are programs that proactively complete tasks on behalf of the user, often with the help of artificial intelligence.
  - One of the main goals of proactive AI agents is to **automate tasks**. These systems should learn what you want to do and do it for you. 
    - Creating an AI agent that thinks multiple steps ahead when asked to coordinate tasks such as managing shopping returns. In this case, the agent would be able to search the user’s email for the purchase receipt, locate the order number from that email, fill out a return form, and schedule a pickup for the item to be returned.
  
  > “Now, why do we need software agents? 
  > Why does our software need to become more personalized? 
  > Why does our software need to take initiative to help us as a user? 
  > This needs to happen because our current computer environment is getting more and more complex, and the users are becoming more and more naive.” 
  > Pattie Maes. Scientist and Professor at MIT’s Media Arts and Sciences

  ### What Is Direct Manipulation?
  - **Direct manipulation** refers to an approach in which humans have direct control over a system’s actions.
  - [Direct manipulation vs. interface agents](https://drive.google.com/file/d/14EOEuMpgQIDvSGDgUH8Mfgd7YCtONB0p/view?usp=sharing)
  
  ### Importance of This Debate and the Case for Each Approach
  > We could also ask ourselves how much control and automation we think these models should have.  
  > Is there an ideal scenario or will it continue to depend on each particular case or perspective? 

VS

  > How much should the AI learn on its own? 
  > How can we ensure result accuracy from the AI?   
  > How can we avoid human replacement when it is not desired? 
</details>


<details>
  <summary>2. Resolving the Tension</summary>

  ### Mixed-Initiative Interaction
  A common design pattern has emerged to walk the line between direct manipulation and agents: **mixed-initiative interaction**.
  - Mixed-initiative interaction attempts to find the balance between automation and control and suggests that choosing between the two should not always be necessary. 
  - Mixed-initiative interaction requires the AI to make run-time decisions: if it has high confidence that it has guessed the user's intent correctly, it should automate the task. 
    - If it has low confidence, it should let the user do it. 
    - If it has medium confidence, it should ask the user. 
    - This means that the system dynamically automates tasks where possible and grants control to the user for tasks it cannot automate. In theory, this means there is more emphasis on high automation capabilities than user control.
  - Mixed-initiative interaction commonly refers to a simpler version of this original idea. It generally refers to designs that make recommendations to the user, who then confirms or rejects that action.
    - for example, of an AI autocomplete—you can keep typing manually, or you can tap the suggestion to complete the word or phrase you're typing.
    - All examples of mixed-initiative interaction we might encounter today:
      - When Google Maps suggests a faster route and we can decide whether to take it or not
      - When our phone sends a notification suggesting we turn off our daily alarm for an upcoming holiday
      - When Gmail prompts us to attach a file to an email, usually after detecting mentions of attachments in the email body
      - When autocomplete features are presented when drafting emails
      - Whenever a smartwatch notices that we are working out and asks if we want it to record the details of that workout

  ### Agency Plus Automation

  Another way to resolve this tension is to maintain high levels of user control as automation increases. In contrast to mixed-initiative interaction, this means there is more emphasis on user control than on automation.

  Shneiderman's argument is that, for many AI applications, there need not be a fundamental tradeoff between agency and automation.

  There are lots of contexts where you would want to use agency plus control, instead of just one or the other. 
</details>


<details>
  <summary>3. Effective Design Patterns for Managing the Direct Manipulation/Agents Tradeoff</summary>

  In response to the direct manipulation/agents tradeoff, designers have developed a few patterns that can be used as a strong starting point when designing an AI powered interface:

  ## Accelerators
  **A design pattern that guesses the user's intent and allows users to accept the system's suggestion with a single keypress**. Accelerators are autocomplete systems: they make it faster to complete the task if the AI guesses correctly, but if the system is wrong, the user can simply ignore it and continue their manual execution.
  - **Google Maps Faster Route Suggestion**

  ## Verifiers
  **The verifier design pattern** doesn't interfere with the user's workflow, except to pause the user if it is confident that they may be making an error: "Did you mean to...".
  - **IOS Alarm Assistant**

  ## Design Galleries
  **The design galleries pattern** generates multiple alternatives and visualizes them simultaneously in a list or table so that the user can choose the one that best suits their needs. 
  - **Image Generation: MidJourney and DALL-E** 

</details>
