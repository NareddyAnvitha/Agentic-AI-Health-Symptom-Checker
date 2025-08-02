# Agentic-AI-Health-Symptom-Checker
# Overview
An AI-powered health assistant that assists users with symptom checking, initial guidance, and recommendations for preventive care. developed with the help of agentic AI concepts to enable smooth user interaction and intelligent decision-making.
# Problem Statement
 An Agentic AI Health Symptom Checker helps users understand their health conditions 
by analyzing symptoms and providing probable causes, preventive advice, and care recommendations. 
It retrieves verified medical data, symptom databases, and guidelines from trusted sources like WHO, 
government health portals, and medical journals. 
Users can input symptoms in natural language such as “I have a sore throat and fever,” and the agent 
provides possible conditions, urgency level, home remedies, and when to consult a doctor. 
It supports multi-language interaction and avoids self-diagnosis risks by offering educational and 
referral-based suggestions. 
This AI-driven assistant promotes early detection, reduces misinformation, and empowers users to take 
informed health actions.
# Solution Overview
This project is an advanced, agentic AI-powered health symptom checker built and deployed on the IBM watsonx.ai platform. It leverages watsonx's powerful foundation models and multi-agent orchestration capabilities to create a collaborative system of specialized AI agents. Each agent (e.g., General Practitioner Agent, Specialist Agent) works together to provide a more accurate, contextualized, and safer health assessment for users. The system is designed for enterprise-grade performance, security, and scalability.

**Key components:**

- **Built on IBM watsonx.ai**: Leverages the robust infrastructure of watsonx.ai, including its foundation models, prompt tuning, and agentic frameworks (like LangGraph).

- **Multi-Agent Architecture**: A system of autonomous, specialized AI agents orchestrated using watsonx's tools. Agents can autonomously reason, solve multi-step medical challenges, and make decisions about the next   steps.

- **Natural Language Understanding**:Utilizes watsonx.ai's capabilities to parse and understand complex user queries and symptoms described in natural language.

- **Personalized Assessment**: Agents are trained and fine-tuned to consider a user's unique health profile for more accurate and personalized health recommendations.

- **Triage and Recommendation Engine**: The system's collaborative output provides clear and responsible advice, guiding users on whether to self-care, consult a physician, or seek emergency care.

- **Enterprise-Grade Security & Compliance**: Benefits from watsonx.ai's built-in security features and governance tools, ensuring data privacy and compliance with regulations like HIPAA.

- **Extensibility**: The modular agentic framework allows for easy integration of new specialized agents and tools within the watsonx.ai environment.
# Technologies  Used:
- **IBM Cloud**:The foundational cloud platform.
- **IBM Cloud Object Storage**: For secure storage of the dataset.
- **IBM Watson Studio**: The integrated environment for data science and machine learning workflows.
- **AutoAI (within Watson Studio)**: Automated machine learning tool for building, training, and optimizing ML models.
- **IBM Watson Machine Learning**: Service for managing runtime environments and deploying models.1. Git & GitHub: For version control and repository hosting.
# How to Use/Run(Conceptual)
This project was primarily developed and deployed on IBM Cloud. To understand or reproduce the core steps:
* **Sign Up:** Create an IBM Cloud account(Lite plan) and access **watsonx.ai**.
* **Open Agent Lab:** Launch Agent Lab in watsonx.ai for building and managing agents.
* **AutoAI Setup:** Use AutoAI to automate data preparation, model training, and deployment.
* **Integrate Granite Models:** Configure **IBM Granite** for NLP and RAG capabilities.
* **Build Health Agent Workflow:** Connect data sources, verified medical APIs, and define symptom-analysis logic.
* **Deploy on IBM Cloud:** Publish the agent as an API or chatbot using IBM Cloud Lite services.
* **Access the Agent:** Interact through a web UI, chat interface, or API endpoint.
* **Input Symptoms:** Enter health-related queries in natural language.
* **Receive Results:** Get probable causes, precautions, and doctor referral guidance.
* **Monitor & Improve:** Use Agent Lab’s monitoring tools and AutoAI retraining for continuous improvements.
    # Model Performance
- **Accuracy**: Uses validated medical databases and IBM Granite to map symptoms to likely conditions with high accuracy.
- **Response Time**: Uses optimized RAG and NLP workflows to produce results in a matter of seconds.
-**Scalability**: Able to effectively manage several queries running at once on IBM Cloud Lite.
-**Language Support**: Uses IBM Watson Language Translator to maintain consistent performance across a number of languages.
-**Reliability**: Reduces misinformation by producing outputs that are consistent and medically verified.
- **Adaptability**: Constantly gets better with Watsonx.ai Agent Lab's AutoAI retraining.
- **User satisfaction**: By providing safe and practical advice, it guarantees high usability and trust.
  # Furture Enchancements
- **Wearable Device Integration**: Connect with smartwatches and health trackers for real-time data.
- **AI-driven Predictive Analytics**: Forecast potential health risks using historical data.
- **Voice and Conversational Interface**: Enable seamless voice-based interaction.
- **Telemedicine Integration**: Directly connect users with certified healthcare providers.
-**Advanced Personalization**: Create tailored health recommendations based on user history.
-**EHR and EMR Connectivity**: Sync with electronic health records for contextual analysis.
- **Expanded Knowledge Base**: Continuously integrate new medical guidelines and research data.
- **Offline Mode**: Provide limited functionality without internet access.

<img width="1920" height="878" alt="Screenshot (31)" src="https://github.com/user-attachments/assets/7dffe4e3-6a4a-4eda-bdb6-cd10489a952e" />

<img width="932" height="777" alt="Screenshot (30)" src="https://github.com/user-attachments/assets/217475cd-88cb-4816-be6a-c4e150e8497f" />
# Result
<img width="1920" height="897" alt="Screenshot (28)" src="https://github.com/user-attachments/assets/ac354d3c-2299-4328-918f-f43ae9156b40" />


  






