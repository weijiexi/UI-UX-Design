# MODULE 7: Ethics and the Societal Impact of Your AI Designs

This course explores why AI developers must prioritize ethical considerations, offering practical tools like the "Tarot Cards of Tech" and "Black Mirror Writers Room" to identify potential issues. You'll also learn how to integrate ethics into your design process, articulate risks, and develop actionable principles to mitigate them, ensuring your innovations align with societal values and responsibility.
- Articulate why we need to consider ethical impacts of AI-based products
- Be able to deploy techniques for foreseeing and mitigating ethical and societal risks
- Integrate principles based on ethical considerations into the design and development of AI-based products

- **Ethics and Society Review (ESR)**; A structured, iterative process designed to evaluate the ethical and societal implications of AI projects during early stages, requiring teams to articulate risks, develop mitigation principles, and implement ethical considerations before proceeding with development or funding.  
- **Bias and Fairness**; Ethical concerns in AI systems that arise when training data reflects historical biases, leading to discriminatory outcomes. Addressing these concerns involves auditing datasets, ensuring diverse representation, and implementing algorithms that promote equity and fairness.  
- **Privacy and Data Security**; The ethical requirement to handle personal data responsibly, ensuring robust protections against misuse and breaches, and adhering to regulations like GDPR to safeguard individuals' privacy rights.  
- **Transparency and Accountability**; Principles that mandate clear explanations of AI decision-making processes, enabling users to understand, challenge, and trust AI systems, particularly in impactful areas like hiring and credit scoring.  
- **Dual Use**; The potential for AI technologies to be exploited for harmful purposes, such as surveillance or cyberattacks, requiring developers to anticipate misuse and implement safeguards to prevent malicious applications.  
- **Black Mirror Writers Room**; A speculative fiction technique used to explore the societal and ethical implications of AI technologies by imagining dystopian scenarios, helping developers identify risks and design measures to mitigate negative outcomes.  

<details>
  <summary>1. Why Do AI Products Need to Be Concerned With Ethical Issues? (Why not "I'm Just an Engineer?")</summary>

  The shift from user-centered design to a broader notion of human-centered design requires societal consideration, underscoring the importance of understanding which user groups are prioritized and which are marginalized, so you can understand this by asking yourself the following question: Who do we envision as the end user, and which specific user groups are we designing for?

  Ultimately, the development of AI and other powerful technologies demands a deep commitment to understanding their potential consequences and a willingness to prioritize societal well-being. By doing so, we can harness the benefits of innovation while minimizing its drawbacks.

  Ethical considerations are paramount in the development and deployment of AI. As these systems become increasingly integrated into society, it is crucial to prioritize fairness, accountability, and transparency. Addressing concerns such as bias, privacy, and job displacement requires a multifaceted approach that involves collaboration between technologists, policymakers, and ethicists.

  By grounding AI development in strong ethical frameworks, we can harness its potential for good while mitigating its risks and ensuring that it benefits society. 
  
  Here are some key ethical issues regarding AI:
  - #### **Bias and fairness**
    One of the primary ethical concerns in AI development is the potential for bias and unfairness. AI systems learn from data, and if the training data contains historical biases, these biases will be perpetuated and even amplified by the AI. This is especially critical in applications such as hiring, lending, and law enforcement, where biased outcomes can have severe, discriminatory effects on marginalized groups. For example, Amazon developed and subsequently abandoned a hiring algorithm because it was biased against women. The algorithm was trained on resumes predominantly submitted by men, reflecting the company's existing workforce and thus perpetuating gender biases. Addressing these biases is essential to ensure that AI systems promote fairness and do not reinforce existing social inequalities.
  - #### **Privacy and data security**
    AI systems often require vast amounts of personal data to function effectively, raising significant privacy and data security concerns. The collection, storage, and use of this data must be handled responsibly to protect individuals' privacy rights and maintain public trust. Regulations like the General Data Protection Regulation (GDPR) in the European Union are designed to ensure that data is collected and processed with explicit consent and adequate protections. Developers must be vigilant in implementing robust data security measures to prevent misuse and breaches that could compromise sensitive information.
  - #### **Transparency and accountability**
    Many AI algorithms function as "black boxes," with decision-making processes that are opaque and difficult to interpret. This lack of transparency can erode user trust and make it challenging to hold AI systems accountable, especially when they make consequential decisions affecting people's lives. Ensuring transparency means providing clear explanations for how AI decisions are made and enabling users to understand and challenge those decisions. This is particularly important in areas such as credit scoring, where individuals need to know why they were denied a loan and what they can do to improve their chances in the future.
  - #### **Autonomy and control**
    As AI systems become more autonomous, there is an increasing risk of humans losing control over these technologies. This is particularly concerning in applications like autonomous vehicles and military drones, where the stakes are exceptionally high. It is crucial to maintain human oversight to ensure that AI systems serve human purposes and do not act in ways that are detrimental to human welfare. For instance, AI systems that influence voter behavior or nudge workers to extend their working hours can undermine human autonomy and freedom, leading to ethical and societal concerns.
  - #### **Job displacement and economic impact**
    AI-driven automation has the potential to displace jobs and exacerbate economic inequality. While AI can create new opportunities and efficiencies, it can also render certain jobs obsolete, disproportionately affecting workers in specific industries, such as customer service representatives, receptionists or accountants. Addressing these impacts involves ensuring a just transition for displaced workers, providing retraining programs, and creating opportunities for meaningful work. It is crucial to involve affected workers in developing and deploying AI systems to ensure that the benefits are equitably distributed and do not disproportionately harm vulnerable populations.
  - #### **Security and misuse**
    AI technologies can be exploited for malicious purposes, such as cyberattacks, surveillance, and misinformation campaigns. Preventing the misuse of AI requires robust security measures and ethical guidelines to ensure that AI is used responsibly. The potential for AI to be used in harmful ways underscores the importance of developing ethical frameworks that prioritize security and the public good.
  - #### **Legal and regulatory compliance**
    Navigating the complex legal landscape of AI use is another critical ethical concern. AI developers must ensure compliance with laws and regulations related to data privacy, intellectual property, and discrimination. Ethical considerations help to guide compliance and avoid legal repercussions, ensuring that AI systems operate within the bounds of the law and respect individuals' rights.
  - #### **Unintended consequences**
    The shift from user-centered design, as espoused by Human-Computer Interaction (HCI), to a broader societal consideration underscores the importance of understanding which user groups are prioritized and which are marginalized. Social media, for example, initially praised for fostering global connections, is now scrutinized for its role in spreading misinformation and impacting mental health. The unforeseen consequences of such technologies highlight the importance of ethical foresight in AI development.
  - #### **Sociological perspectives**
    Moreover, sociologist Robert Merton’s concept of the "unintended consequences of purposive social action" reminds us that predicting the societal impact of technological innovations is challenging but crucial. Given the profound capabilities of AI systems, there is a moral imperative to anticipate and mitigate potential risks. This requires a proactive approach to identifying ethical issues, incorporating diverse perspectives, and making informed design decisions that prioritize societal well-being.
</details>


<details>
  <summary>2. Two Techniques for Identifying Ethical Issues: Tarot Cards of Tech and Black Mirror Writers Room</summary>

  “Humans generate, design, develop, distribute, and monitor AI systems. Human decisions are impactful throughout the AI development life cycle, and those decisions, reflecting the developers’ values, impact the performance of AI systems in a significant way.” Justin Biddle, (n. d.)

  dentifying ethical issues related to artificial intelligence (AI) involves examining various concerns that arise from its development and deployment. It can be challenging but is essential for responsible innovation. Two effective techniques for this purpose are **the Tarot Cards of Tech** and **the Black Mirror Writers Room**.

  ### [The Tarot Cards of Tech](https://www.artefactgroup.com/resources/the-tarot-cards-of-tech/)
  The Tarot Cards of Tech serve as a tool to jump-start important conversations around the impacts of technology and the products we design. By encouraging designers to think critically about the potential outcomes technology can create—from unintended consequences to opportunities for positive change—the Tarot Cards of Tech help developers envision the future of their products and strive to make them the best they can be.

  This method involves using a set of cards designed **to generate thoughtful consideration of various ethical dilemmas associated with a product or technology**. 
  Each card presents a scenario or question that prompts developers to reflect on specific ethical considerations.
  - **The "Scandal" card** urges teams to imagine the worst possible headline about their technology, encouraging them to foresee and mitigate potential misuse. What's the worst headline that might arise from people using your system? For instance, if you are developing an AI-powered dating advice tool, what’s the worst-case scenario? How can we design the system to prevent such negative outcomes from occurring?
  - **The "Siren" card** highlights the risk of addiction, prompting developers to design in ways that prevent overuse.Is someone using your product too much? How do we mitigate this?
  - **The "Forgotten" card** challenges developers to consider who might have been excluded from their user base, promoting a more inclusive approach.Who are the users who are not included in your mental image of who this is for, and are there ways to bring broader groups into that picture?
  - **The "Big Bad Wolf" card** focuses on the potential for exploitation by malicious actors, encouraging developers to implement safeguards against misuse. What might a malicious actor do with your product? How could they exploit it or manipulate it to cause harm or achieve their own objectives?

  ### Black Mirror Writers Room
  "Black Mirror" is a thought-provoking anthology series that explores the dark and unsettling side of technology and modern society. Each standalone episode delves into dystopian futures and moral dilemmas, offering a chilling reflection on the consequences of our digital age.

  Whether in classrooms or workplace, the "Black Mirror Writers Room" offers a valuable framework for exploring the ethical implications of technology through imaginative and team-based exercises.

  #### **Benefits and Goals of the Black Mirror Writers Room**
  Some of the benefits that we can obtain from this technique include the following:
  - These activities are designed to cultivate a heightened awareness of the ethical aspects of technology among participants, prompting them to consider the effects of their work.
  - By using speculative fiction as a framework for discussion, participants can delve into complex issues in a stimulating and creative manner, rather than (typically) approaching ethics in a dry and analytical way.
  - These sessions offer opportunities for shared learning, where a variety of perspectives enrich the understanding of technological ethics.
</details>


<details>
  <summary>3. Ethics and Societal Review as a Structured Process for Early-Stage Projects Integrating AI Into Interactive Software</summary>

  The Ethics and Society Review (ESR) is a critical process that your organization can use to help ensure that projects are evaluated for their ethical and societal implications early on. This approach engages teams early, at a stage when their projects are still evolving, and encourages broad participation in ethical thinking rather than relying solely on self-motivated individuals.

  Team in organizations that use an ESR process must submit a brief ethical and societal impact statement along with their project proposals. This statement is intended to outline the project’s potential risks to society, specific subgroups within society, and other global communities. It also details the principles that will be used to mitigate these risks and describes how these principles are integrated into the research design.

  Here you can see a representation of the process:

  Project proposal, alongside ESR statement, submitted to management->Review by management->ESR panel review->Recommendation from ESR to management

  Feedback and iteration
  
  Once the organization (e.g., management) has reviewed the merit of the project and decided what to approve, staff, and resource, these projects are forwarded to the ESR for an ethics review before they launch. An interdisciplinary panel of experts at the organization then evaluates the proposed projects, focusing on the identified risks and proposed mitigation strategies in the context of the potential benefits to society. The ESR panel’s goal is not to eliminate all potential negative impacts—which can be impossible—but to collaborate with researchers to identify significant risks and develop reasonable mitigation strategies. This feedback may include articulating potential risks, developing mitigation strategies for these risks and implementing principles in your design.

  #### Step #1. Articulating potential risks
  The first step of The Ethics and Society Review (ESR) involves identifying and articulating the ethical and societal risks associated with a project. This means evaluating how the project might impact society and specific subgroups, including marginalized communities. It also includes considering potential risks to other societies around the world.

  While it's common to simply identify potential risks, a truly effective analysis goes deeper. It is essential to understand the potential impact of these risks, whom they might affect, and how severe the consequences could be. By carefully considering these factors, you can create a comprehensive picture that guides you in developing strategies to address and minimize these threats.

  #### Step #2. Developing principles to mitigate those risks
  Once the risks are articulated, the next step is to define the principles that designers should follow to mitigate the identified risks. Start by evaluating which ethical principles are most relevant to your project, based on the risks outlined in the first step. Consider what guidelines or best practices are commonly used in your industry to address similar issues.

  Think about how these principles can be applied practically in your project. For instance, if privacy is a concern, principles like transparency and user consent may be crucial. Develop actionable guidelines or policies that can be integrated into the design and development processes to ensure these principles are consistently applied. This helps ensure that ethical considerations are effectively addressed throughout the project.

  #### Step #3. Implement principles in your design
  The final step of The Ethics and Society Review (ESR) involves translating established ethical principles into concrete design decisions. This means implementing specific measures and features in the AI system to align with the ethical guidelines. How are you going to instantiate it? For example, if the principle is to ensure privacy, the design might include local data processing to prevent surveillance.

  Similarly, if the principle is to have representative training datasets, you would actively source data from diverse demographics, audit for inclusivity, and set up processes for ongoing representation. This step requires a commitment to ethical engineering practices, including technical adjustments, user interface modifications, and policy changes. By embedding these principles into the design, developers ensure that AI systems are both effective and socially responsible.

  Project leaders respond to the feedback through written responses or in-person discussions, which include their answers to the panel’s feedback and any new plans for managing risks. Once the ESR review is complete and feedback is addressed, the panel sends its final recommendation to the organization. The organization then gives the team the green light to proceed. This process ensures that ethical and societal issues are considered early on, making sure that projects align with societal values and expectations.

  The European Union also provides guidance on ethics self-assessments, stressing the importance of addressing ethical issues from the beginning of the proposal process. It recommends involving ethics advisors for projects with significant ethical concerns, which supports the ESR process and emphasizes the need for ongoing ethical review throughout the research.

  At institutions like Stanford, we use the ESR process for all projects funded by the Stanford Institute for Human-Centered Artificial Intelligence. In our case, researchers are required to identify potential risks, articulate ethical principles, and outline mitigation strategies early in their project planning. These plans undergo rigorous review by a panel of experts from engineering, medicine, the humanities, and social sciences, ensuring that research projects are built on a solid ethical foundation before they proceed.

  In the context of AI and other fields, common ethical considerations include:
  - **Potential harms** - Identifying groups that might be negatively impacted by the technology
  - **Inclusive design** - Ensuring that all relevant stakeholders are considered and involved
  - **Dual use** - Assessing the potential for misuse by malicious actors
  - **Data bias** - Evaluating the representativeness of the data used to train the AI system

  ### Case Study: Ethics and Society Review
  In a recent project that bridged engineering design and medicine, a team developed stress-sensing technology aimed at helping individuals manage workplace stress. The project involved creating tools, such as sensors embedded in keyboards and watches, to monitor and assess stress levels, to enhance employee well-being.

  During the project’s development, the team identified a significant ethical risk: the potential misuse of their technology for employee surveillance rather than its intended purpose of stress management. Recognizing this risk was crucial, but the team needed to address it more comprehensively.

  The Ethics and Society Review (ESR) process prompted the team to delve deeper into how to address this concern. They were encouraged to define a guiding principle that would safeguard against the misuse of their technology. The principle they established was that all data collection and processing should be conducted to preserve user privacy. Specifically, they decided that data would be processed locally on the user’s device—such as a smartphone—rather than being sent to a server where it could potentially be accessed by employers.

  To implement this principle, the team ensured that their technology was designed to handle all data on the device itself, thus preventing any direct surveillance by employers. This design choice was not only a technical decision but also a commitment to ethical standards. Furthermore, the team made it a point to clearly communicate this privacy-preserving approach in their public statements and discussions about the project. By doing so, they reinforced their commitment to ethical practices and ensured transparency regarding the safeguarding measures incorporated into their technology.


</details>