**Lead Compass**

**Pre-requisites**
- Basic: Real estate knowledge
- Frontend Technology: React JS
- Backend Technology: Python
- Framework: FastAPI
- Searching Algorithms: Elastic search
- Database: Mongodb
- Tools: Git and GitHub

**Learning Resources:-**
- [Real Estate](https://en.wikipedia.org/wiki/Real_estate)
- [React JS](https://www.w3schools.com/react/) 
- [Python](https://www.w3schools.com/python/default.asp) 
- [FastAPI](https://fastapi.tiangolo.com/) 
- [Elastic Search](https://www.elastic.co/docs) 
- [MongoDB](https://www.w3schools.com/mongodb/index.php) 
- [Git](https://www.w3schools.com/git/) 
- [GitHub](https://docs.github.com/en/get-started) 

**Project Description:**
Lead-Compass is an innovative platform designed to streamline real estate investment opportunities by connecting investors with compatible borrowers and lenders based on their proven investment history. This user-friendly and secure environment allows you to find the right partners, filter properties based on key metrics, and collaborate efficiently throughout the investment process.

**Key Features of Lead-Compass:**
Targeted Connections: Our intelligent filtering system ensures you are matched with borrowers and lenders whose past investments align with your interests, eliminating wasted time and effort.
Data-Driven Decisions: Utilize property data integrations to gain valuable insights into market trends, enabling you to make informed investment choices. Note that Black Knight data integration is subject to separate licensing.
Streamlined Workflow: Manage your entire investment journey within Lead-Compass. From finding partners and filtering properties to secure collaboration and closing deals, everything is handled efficiently on our platform.

**Objectives:**
Facilitate Targeted Connections:
Match investors with borrowers and lenders whose past investments align with their interests, reducing wasted time and effort.

**Streamline the Investment Workflow:**
Provide a comprehensive platform to manage the entire investment journey, from finding partners and filtering properties to secure collaboration and closing deals efficiently.

**Ensure Data Accuracy and Consistency:**
Offer tools for manual data correction and fuzzy search to identify and rectify inconsistencies, improving the overall quality of project data.

Timeline: Started from December 2023 – till now. New features are implemented and further work on bug fixing is in progress.

**Project Domain:**
Lead-Compass operates within the domain of real estate investment facilitation and management. Specifically, it focuses on connecting investors with borrowers and lenders, facilitating data-driven investment decisions, and providing tools for efficient project management and collaboration within the real estate sector.

**Technical requirements:**
- Developer Requirements: 
- Real Estate 
- Python – Python 3.x
- FastAPI- Fastapi 0.105.0
- Elastic Search
- ReactJS
- Emilus Theme
- MongoDB
- Git/GitHub


**Software Requirements:**
Python- Python 3.x
FastAPI- Fastapi 0.105.0
MongoDB- Pymongo 4.6.1


**Code structure:**

**Backend Structure:**
The path to follow for API code is: lead-compass/api
Some folders which are often used are:	
1. /api/config:
Configuration files and settings for the application (e.g., environment variables, database settings).
 
2. /api/endpoints:
Contains business logic and service layer to manage application operations (e.g., user management, data processing), mainly API functions.
 
3. /api/managers:
Consists of all the python scripts, which run in the background to handle the data and all the clustering processes.
 
4. /api/routes:
Aggregates and organizes the API routes for different endpoints (e.g., user routes, project routes).
 
5. /api/schemas:
Defines Pydantic models and data validation schemas for request and response data.		

**Frontend Structure:**
The path to follow for UI code is: lead-compass/ui/src/

Some folders which are often used are:
1. /src/auth:
Handles authentication and authorization logic (e.g., login, token generation).
 
2. /src/components:
Reusable components, possibly including headers, footers, and layouts.
 
3. /src/configs:
Configuration files for environments and settings (e.g., database setup).
 
4. /src/routes:
Defines UI routes for different endpoints (e.g., user and project routes).
 
5. /src/services:
API logic and services for various operations (e.g., user and project handling).
 
6. /src/utils:
Utility functions and helpers (e.g., custom validators, exceptions).
 
7. /src/views:
Controllers that handle HTTP requests and responses for endpoints. It consists of all the view components which are on the UI.
