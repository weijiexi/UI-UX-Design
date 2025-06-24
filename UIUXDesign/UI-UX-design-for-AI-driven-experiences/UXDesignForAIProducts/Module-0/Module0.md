## Module 0: Quick Primer on AI and Design

- **Artificial intelligence**: Artificial intelligence (AI) is a subfield of computer science dedicated **to improving automated performance on tasks that require cognition to solve**.  
- **Computer vision**: Computer vision is a field of artificial intelligence that seeks **to enable computers to interpret and understand images and videos, as well as extract meaningful information from visual data**.   
- **Deep Learning**: Deep learning is a subset of machine learning that consists of a certain type of algorithm that **takes very large inputs and feeds them into different computational nodes that are connected and influence each other**.  
- **Generative AI**: Artificial intelligence models capable of responding **to prompts and generating text, images, video, audio, and other data as their output**.  
- **Human-computer interaction (HCI)**: How people interact with computers and the design of interfaces that facilitate efficient and intuitive communication between humans and digital systems.  
- **Large language models**: Large language models (LLMs) are a type of artificial intelligence model that **uses pre-existing data to understand human prompts and generate appropriate responses**.  
- **Machine learning**: Field of study in artificial intelligence  that works by **using large amounts of data to build different types of models, instead of depending on human feedback**. Machine learning relies heavily on statistics by modeling which **properties of the input are associated with the desired outputs**.    
- **Natural Language Processing**: Natural Language Processing (NLP) is a subfield of artificial intelligence dedicated **to improving the automated understanding and generation of human language**.   


<details>
  <summary>What is AI?</summary>

- the first thing we need to recognize when dealing with AI-powered systems is that in order to get good results, we need to be very precise about two things: the **input** and the **output**.
- “Almost all of AI’s recent progress is through one type, in which some input data (A) is used to quickly generate some simple response (B).” 
- almost all of AI’s recent progress maps input to output in some way. You cannot simply point AI at a problem and assume that it will know what to do. Instead, you need to first be clear with yourself about what the expected inputs and outputs are. What is going to get passed to the AI, and what is it supposed to do with that input, concretely? 
- Having a clear understanding of your input and output will provide a significant advantage when leveraging AI.

| Application    | Input       | Output                                |
|----------------|-------------|---------------------------------------|
| Photo editing  | Picture     | Picture without background            |
| Blog marketing | Blog post   | Catchy headline                       |
| Translation    | English phrase | French phrase                      |

#### Machine Learning
- In machine learning, we don't tell the algorithm how to solve the problem — **we give it lots of examples of solved problems, and ask the algorithm to learn to do the same thing**. 
- Machine learning relies heavily on the field of statistics, **modeling which properties of the input are associated with the desired outputs**.
- machine learning is the solution of AI problems **through big data and by building models trained on top of that data**.

#### Deep Learning
-  In a deep learning algorithm, **the system passes the inputs to a set of very simple nodes** (left side of diagram), and **these nodes pass information to deeper layers, eventually converging into an output** (right side of diagram). **Simple atoms that connect to each other to compute complex functions**.
- Instead of providing these models with large amounts of data and training them from scratch, **large language models (LLMs) are typically pre-trained by using public databases** such as the internet and then are given further training to follow our instructions.
- The large language models are then made available either via an API (e.g., OpenAI) or open source (e.g., Meta). Instead of requiring a ton of training data, in this case we need to focus on **telling the model what it needs to do** (as on the next page).
</details>


<details>
  <summary>How Do Large Language Models Work?</summary>

- After collecting this data, the model begins with a process that is called **"pretraining"**. 
- In large language models such as what you see in ChatGPT, pretraining uses the training data to teach the model to complete a simple task, **most commonly predicting the next word in sentences from that data**.

#### Instruction Tuning
Typically, instruction tuning is done by gathering big datasets of example inputs and outputs, where the input is an instruction and the output is an example of the model following that input.

- the pretraining and instruction tuning are steps that most publicly available LLMs have completed already: they just work out of the box.
- We can just use an API to access these models or host a pretrained, open-source model.
- You can use an API and just provide it with a prompt, or text request
- This is the general architecture for most of the generative AI applications today: use a pre-trained model, feed it inputs and a prompt, and trust that the model has already been trained to respond effectively.

#### Fine Tuning and Value Alignment
-  Fine tuning allows us to specialize a model for tasks that it might not be able to do out of the box, by providing more training examples of how it should behave on our specific task. 
</details>

<details>
  <summary>Integrating AI Into Interactive Software</summary>

  - **Webex** are speech-to-text capabilities and large language models for summarization. 
    - The input in this case would be the audio of the meeting
    - The output would be its summary
  - Microsoft integrates OpenAI into **Copilot**. 
    - The input would be text that you want the assistant to analyze 
    - The output would be a response of what you asked it to do
  - **Netflix** uses what is known as a recommender system, which uses deep learning algorithms to analyze and suggest options for the user. 
    - The input in this scenario is what people “liked” or viewed on the platform
    - The output will be what people might “like” or view
  - **ChatGPT** is a large language model built on deep learning algorithms. 
    - The inputs are what people ask it
    - The outputs are written or spoken answers. Users can also add rules for it to handle specific commands
  - **Stitch Fix** uses a recommender system similar to how Netflix recommends movies and shows
    - The inputs in this case are what customers have liked or bought
    - the outputs are potential clothing items based on previous purchases or liked items
  - **Zillow** is an example of a product that uses computer vision and deep learning regression
    - The inputs are images of properties 
    - The outputs are the sale costs of those properties
  - **Fraud detection software**
    - The input would be a client’s regular financial activity
    - The output would be the client’s latest financial action, and whether it matches the client’s regular activity or not
  - **Medicine case** can be achieved through deep learning regression
    - The inputs would be a user’s sensor values from their smart watch
    - The outputs would be their estimated glucose levels
  </details>

> ### Discussion Forum: Recent AI Developments
> - What are some recent developments in the world of AI that you have heard of? 
> - What do you think of these developments from a usability, technical, and/or ethical perspective?

  One recent development in AI that has gained significant attention is the integration of AI agents into creative and development platforms—especially the combination of Figma Dev Mode and Multi-Modal Code Prompting (MCP). These tools are transforming UI/UX design by enabling smoother handoffs between designers and developers. Figma’s Dev Mode now uses AI to analyze design components and generate developer-friendly code snippets, making the transition from design to code faster and less error-prone. MCP enhances this process by allowing designers or developers to input multi-modal prompts (e.g., text, images, or design elements) and receive accurate code outputs based on context.

  From a usability standpoint, these developments reduce repetitive tasks and make collaboration more efficient. Technically, they show how large language and vision models can be fine-tuned for domain-specific applications. However, ethically, there are concerns about job displacement and over-reliance on AI-generated code without human review.

  For example, a user can input a design screen in Figma Dev Mode and ask, “Generate responsive React code for this layout.” The AI outputs usable component code, reducing the time needed for implementation. This kind of intelligent input-output pairing solves the common pain point of design-to-development translation.



