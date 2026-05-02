# Interview Script

The following is the interview script. We designed the interview script to reduce research-induced bias. We move from general open-ended questions to specific technical probes. We refrained from introducing specific technical terms until participants had first articulated their own thoughts.

## Introduction

Thank you for participating in this inerview. We are researching how independent AI agent developers understand, practise and face challenges related to privacy and security during the development process. Today's conversation will be divided into four parts: your understanding of privacy and security, your practices in actual development, the challenges you face, and your expectations and suggestions regarding platforms and regulations. We will audio-record the entire interview, and the recording will only be used for research analysis, and will not be made public. If needed, a transcript of the recording can be provided to you. During the interview, you are welcome to ask questions or share any thoughts at any time. 

### Part 1: General understanding and definition

- In your opinion, how do you define AI agent? (What are its components? How does it operate?)

- In the design and operation of your AI agent, what privacy or security issues might be involved? Could you provide specific examples?

- How do you define user privacy? (For example, what constitutes user privacy? To what extent should user data be utilized to ensure privacy protection? Which categories of user data are you particularly concerned about?)

- Mental model

  - What user data does your AI agent collect?

  - When your AI agent interacts with users or their environment (for example, perceiving data or acquiring information), how do you understand where the data flows first and what happens to it within your agent system or the platform you use (for example, local storage, cloud, passed to an LLM, transformed)?
  
  - In your understanding, when an AI agent receives input information or perceives the environment (such as text input, cameras, searches), how is this data processed?

  - If the agent performs certain actions (such as sending emails, fetching information, controlling devices), how does this data interact with external services? Where is this data stored when the AI agent interacts with users and the environment? How does the platform handle this data?

  - Do you think this data will be transmitted to APIs like OpenAI? Do you use APIs like OpenAI yourself?

  - Do you think you will use external knowledge bases or RAG functionality to assist the agent? What user information might be involved?

  - Do you think there will be calls to other third-party APIs? What user information might be involved?

- In your opinion, how underlying platforms (e.g., OpenAI, a cloud provider, an agent framework) might use the data generated from agent interactions? (e.g., model training, system improvements, analytics)

- What is your understanding of an agent's memory or knowledge base? How is this information stored and accessed, and who can access it? (e.g., fine-tuning data, persistent conversational history, or custom instructions)

- How did you establish these understandings? Where do they come from? (e.g., official documents, news, training, others' experiences, or your own speculation)

### Part 2: Development practices and tools

- When developing AI agents, what stages are typically involved?

- At which stages are privacy and security issues considered?

- What specific tools are used for privacy and security consideration and mitigation?

- Have any legal and regulatory requirements been considered?

- How would you communicate privacy issues to users, inform them of potential privacy risks, and what considerations would you take into account?

### Part 3: Probe privacy and security scenarios

- If your AI agent performs actions (e.g, sending an email, controlling a smart device, making a purchase), how do you envision the data flowing between your agent and those external services?

- Data leakage and misuse risks:

  - Whether or not you think your agent might engage in excessive data collection, and why?
 
  - Whether or not do you think your agent might create user profiles, and (if applicable) what kind of user profiles the agents might create? Whether or not would that pose privacy risks to users?
 
  - Whether or not do you think your agent might experience data leaks or share data with third parties?
 
- System security and malicious attacks:

  - Whether or not you think your agent might be vulnerable to prompt injection attacks?
 
  - Whether or not you think your agent might face data poisoning issues?
 
  - Whether or not you think your agent might be susceptible to attacks like privacy theft?
 
  - Whether or not you think your agent might encounter issues of misuse or unauthorized access?
 
### Part 4: Expectations

- From the platform's perspective

  - What specific tools, features, or guidelines do you wish AI agent development platforms (e.g., OpenAI or other frameworks) would provide to help you build safer and more privacy-focused agents?
 
  - Whether or not you think current platforms offer support for individual developers in understanding and implementing security and privacy best practices for agents? (If applicable) What are your expectations?
 
  - How, if any, do you suggest platforms to clarify the division of responsibilities between themselves and individual AI agent developers regarding privacy and security?
 
  - What role do you believe platforms should play in supporting individual developers or their agents?
 
- From the law's perspective

  - What role do you believe legal factors can play, what are the current shortcomings, and what kind of support is needed?
 
- From the tool's perspective

  - What specific tools do you believe are needed, what roles can these tools play, and what kind of support do you need them to provide to you?
 
- From others' perspective

  - In your opinion, what other types of support do you need?
 


