

Project Name: Vehicle Loan Application Chatbot

Team Member: 1 (Christina Stephen)

Project Description: Loan application agent chatbot will create a loan application based on personal, employment, income, loan details collected from customer  to submit a loan application. The agent answers any questions customer may have while creating the application.

Problem Statement: Loan application process can be lengthy and cumbersome for customers and processing officers leading to incomplete applications with data entry errors, missing documents and duplicate data and data entry errors. Slow application status updates impacts customer experience. Repeated customer questions and manual prescreening reduces operational efficiency for loan processing and underwriting officers.

Solution: Vehicle Loan Application Chatbot can improve customer experience and operational efficiency by making the process less overwhelming, increase application completion rate, reduce processing time, collect accurate customer information and answer customer questions during the process.

Proposal: Vibe coding for vehicle loan application chatbot agentic workflow.
	
	1) Architecture:
		Customer
		│
		▼
	Web / Mobile UI
		│
		▼
	Loan Application Agent (LLM)
		│
		├── Identity Verification
		├── Income Verification
		├── Credit Score Service
		├── Vehicle Valuation Service
		├── Fraud Detection
		├── Loan Decision Engine
		└── Document Generator
				   │
				   ▼
			  Approval Letter
			  Loan Contract
			  Rejection Notice
		
	2) Multi-agent design using Langraph
	
		START
		  │
		  ▼
		Intake Agent
		  │
		  ▼
		Identity Agent
		  │
		  ▼
		Credit Agent
		  │
		  ▼
		Vehicle Agent
		  │
		  ▼
		Fraud Agent
		  │
		  ▼
		Decision Agent
		  │
		  ▼
		Offer Agent
		  │
		  ▼
		END
	
	
	3)Set up agent workflow
		START
		  │
		  ▼
		Greeting
		  │
		  ▼
		Collect Personal Information
		  │
		  ▼
		Collect Employment Information
		  │
		  ▼
		Collect Income Information
		  │
		  ▼
		Collect Vehicle Information
		  │
		  ▼
		Calculate Eligibility
		  │
		  ▼
		Present Loan Decision
		  │
		  ▼
		Generate Application Summary
		  │
		  ▼
		END
		
	4) Set up Conversational Design
		
			Greeting -> Personal Information-> Vehicle Information ->.....
			
	5) Business rules: Loan evaluation logic
		
	6) Capture Agent States to answer FAQA
		
	7) Tech stack: AIstudio + FastAPI + OpenAI/Azure OpenAI + React


Datasets:

	1) Loan/credit risk datasets (for approval recommendations)
	
		https://www.kaggle.com/datasets/mamtadhaker/lt-vehicle-loan-default-prediction
		
	2) Conversational datasets (for chatbot behavior)
	
		https://huggingface.co/datasets/InfoBayAI/AI_Prompt_and_Conversation_Dataset
		
	3) Domain knowledge datasets (vehicle, lending, compliance, FAQs)
	
		https://www.consumerfinance.gov/consumer-tools/auto-loans/answers/


