# MODULE 7: Ethics and the Societal Impact of Your AI Designs

This course explores why AI developers must prioritize ethical considerations, offering practical tools like the "Tarot Cards of Tech" and "Black Mirror Writers Room" to identify potential issues. You'll also learn how to integrate ethics into your design process, articulate risks, and develop actionable principles to mitigate them, ensuring your innovations align with societal values and responsibility.
- Articulate why we need to consider ethical impacts of AI-based products
- Be able to deploy techniques for foreseeing and mitigating ethical and societal risks
- Integrate principles based on ethical considerations into the design and development of AI-based products

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

</details>