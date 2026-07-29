<div align="center">

# Hi, I'm Julio Gutiérrez Morales

### Full Stack Engineer | AWS Certified Solutions Architect – Associate

I build cloud-native products with **Angular, Node.js, serverless AWS, Terraform, and Generative AI**.

[![Portfolio](https://img.shields.io/badge/Portfolio-View%20my%20work-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white)](https://d1qm6hv407vrgm.cloudfront.net/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/julio-gutierrez-morales0302)
[![Email](https://img.shields.io/badge/Email-Contact%20me-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:juliogutierrezdev@gmail.com)

![AWS](https://img.shields.io/badge/AWS-Serverless-232F3E?logo=amazonwebservices&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-14%20to%2019-DD0031?logo=angular&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-Backend-339933?logo=nodedotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-Full%20Stack-3178C6?logo=typescript&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-IaC-844FBA?logo=terraform&logoColor=white)
![Amazon Bedrock](https://img.shields.io/badge/Amazon%20Bedrock-Generative%20AI-FF9900?logo=amazonwebservices&logoColor=white)

📍 Costa Rica · Open to remote opportunities and selected freelance projects

</div>

## About me

I am a **Full Stack Engineer with 3+ years of software-development experience** building production web applications and cloud-native systems on AWS. My strongest stack is **Angular and TypeScript on the frontend, Node.js on the backend, and serverless AWS services for APIs, data, automation, security, and observability**.

I work across the complete delivery lifecycle: understanding the business problem, designing the solution, building responsive interfaces and REST APIs, modeling SQL and NoSQL data, orchestrating asynchronous workflows, monitoring production systems, and supporting deployments across multiple environments.

Before moving into technology, I spent more than ten years in fitness, physical therapy, team leadership, and operations. That background gives me practical domain expertise for health and fitness products, as well as strong communication with clients, managers, business owners, and non-technical stakeholders.

## Selected impact

- Contributed to the growth of a multi-tenant e-commerce platform from its startup stage to **15+ affiliated merchants**, including solutions used by organizations such as **Boston Scientific, Coopenae, and Comercial de Seguros**.
- Built and maintained **100+ Node.js AWS Lambda functions** supporting production workloads across API Gateway, DynamoDB, Aurora/MySQL, SQS, EventBridge, Step Functions, S3, and Cognito.
- Supported APIs processing approximately **1,000–10,000 requests per day**, with key endpoints operating below **200 ms**.
- Designed AI-assisted workflows that reduced workout-plan creation from **more than 90 minutes to under 60 seconds**, a reduction of approximately **97%**, for a platform with **40+ registered users**.
- Used Amazon Bedrock to translate, classify, and enrich a catalog of **2,000+ real exercises**, producing structured bilingual data for downstream application workflows.
- Automated catalog ingestion and web-data processing for an e-commerce operation handling approximately **15,000 catalog records** and **3,000 product pages**.

## Professional experience

### MobyDyg — Full Stack Developer

**October 2023 – Present | Costa Rica**

- Develop and maintain a multi-tenant e-commerce ecosystem using **Angular, TypeScript, Node.js, AWS Lambda, API Gateway, and Aurora/MySQL**.
- Deliver end-to-end modules for product catalogs, categories, inventory, suppliers, taxes, promotions, gift cards, orders, point of sale, checkout configuration, reports, themes, reviews, and transactional email templates.
- Build reusable Angular components, responsive interfaces, multi-level navigation, role-based views, and integrations with RESTful APIs.
- Design serverless and event-driven workflows with **SQS, EventBridge, Step Functions, S3, and DynamoDB** for product ingestion, scheduled jobs, asynchronous processing, and AI-assisted features.
- Implement identity and access flows with **Amazon Cognito and AWS Amplify**, including role-based authorization, custom attributes, session handling, and MFA.
- Develop and optimize **MySQL stored procedures**, API payloads, and frontend data transformations to improve performance and reduce duplicated application logic.
- Use **CloudWatch logs, metrics, and alarms** to diagnose Lambda, API Gateway, and asynchronous-processing issues in production.
- Collaborate through GitHub pull requests, code reviews, Agile workflows, and coordinated releases across development, testing, and production environments.

## Featured projects

### SpeedUp Coach — AI-powered fitness platform

**Angular 19 · Node.js · Amazon Bedrock · Lambda · API Gateway · Step Functions · DynamoDB · S3 · Cognito · CloudWatch**

- Designed a serverless, multi-tenant platform for coaches to manage clients, exercises, assessments, and workout plans.
- Built an Angular web application and client-facing PWA with responsive interfaces, drag-and-drop plan creation, and inline editing.
- Orchestrated AI plan generation by session with Step Functions and specialized Lambda functions, avoiding large monolithic requests and making each stage observable.
- Grounded AI generation in a catalog of real exercises and enforced structured JSON outputs before saving or displaying results.
- Used S3 for intermediate results and reusable outputs, while the Angular client retrieved long-running results asynchronously.

### Automated product-ingestion and scraping pipeline

**Lambda · S3 · SQS · EventBridge · Step Functions · Aurora/MySQL · CloudWatch**

- Built a scheduled pipeline that combines large Excel catalog imports with product-page scraping and database synchronization.
- Used S3 events and SQS to decouple ingestion from processing, control workload volume, and improve reliability.
- Applied Standard and FIFO queue patterns, retries, visibility settings, and dead-letter queues according to ordering and throughput requirements.
- Automated recurring updates and cleanup processes while preserving external URLs, images, SKU relationships, and product availability data.

### AWS portfolio and knowledge explorer

**Angular 19 · TypeScript · Tailwind CSS · PrimeNG · Mermaid · YAML · S3 · CloudFront**

- Built an AWS Console-inspired portfolio that presents practical experience across serverless, data, integration, security, observability, AI, and infrastructure-as-code services.
- Created a searchable, filterable knowledge explorer backed by typed models and YAML instead of hardcoded template content.
- Documented AWS architectures and workflows with reusable components and Mermaid diagrams.
- Published the application as a static Angular deployment using S3 and CloudFront.

### Earlier full stack projects

- **Nomad Solutions:** MERN e-commerce application with React, Node.js, Express, MongoDB, Bootstrap, and Stripe checkout integration.
- **Dojo Music App:** Full stack music application with Tailwind CSS, Node.js, Express, authentication, and an AWS EC2 backend deployment.

> Some production repositories are private because they contain proprietary client and company code. Public architecture summaries and project demonstrations are available in my [portfolio](https://d1qm6hv407vrgm.cloudfront.net/).

## Technical toolkit

| Area | Technologies and practices |
| --- | --- |
| **Frontend** | Angular 14–19, TypeScript, JavaScript, HTML5, CSS3, SCSS, Angular Material, PrimeNG, Tailwind CSS, Bootstrap, React |
| **Backend and APIs** | Node.js, Express.js, RESTful APIs, serverless functions, API Gateway proxy and non-proxy integrations, VTL mapping templates |
| **Data** | Aurora/MySQL, Amazon RDS, stored procedures, DynamoDB, DynamoDB Streams, MongoDB, SQL and NoSQL data modeling |
| **AWS cloud** | Lambda, API Gateway, S3, SQS, SNS, EventBridge, Step Functions, Cognito, SES, CloudFront, CloudWatch, EC2, Amplify, IAM |
| **AI and automation** | Amazon Bedrock, Generative AI integration, prompt engineering, structured LLM outputs, data enrichment, Amazon Textract |
| **DevOps and IaC** | Terraform, CloudFormation, GitHub Actions, AWS CodePipeline, CI/CD, Git, GitHub, multi-environment deployments |
| **Engineering practices** | Event-driven architecture, least-privilege IAM, observability, performance optimization, code review, Agile/Scrum, SDLC |

## AWS and architecture strengths

- Designing Lambda functions around events, permissions, runtime behavior, memory, timeouts, shared dependencies, and observability.
- Choosing between relational and NoSQL storage based on access patterns and business requirements.
- Designing synchronous REST APIs and asynchronous workflows with queues, schedulers, state machines, retries, and dead-letter handling.
- Managing Cognito authentication, application roles, custom attributes, MFA, and protected frontend flows.
- Building secure S3 workflows with structured object paths, bucket policies, event triggers, and pre-signed URLs.
- Controlling CloudFront cache behavior and invalidations for reliable frontend releases.
- Using Terraform modules, variables, locals, outputs, providers, and `init`/`plan`/`apply` workflows, with exposure to DevOps-managed production deployments across multiple environments.
- Integrating Generative AI into business workflows with real data, controlled prompts, structured outputs, validation, persistence, and monitoring.

## Education and certifications

- **AWS Certified Solutions Architect – Associate** — Amazon Web Services, 2025
- **Generative AI with Amazon Bedrock & Prompt Engineering** — AWS, 2025
- **Terraform Basics: Infrastructure as Code** — HashiCorp, 2025
- **Claude Code: Software Engineering with Generative AI Agents** — Vanderbilt University, professional coursework
- **Full Stack Software Developer, MERN** — Coding Dojo, 2023
- **Diploma in Full Stack Software Development** — Tech University, 2022
- **Software Engineering** — Universidad Fidélitas

## Current focus

I am continuing to deepen my skills in:

- production-ready **Terraform** and reusable infrastructure modules;
- **AWS CloudOps**, monitoring, reliability, and cost-aware architecture;
- advanced serverless and event-driven system design;
- practical Generative AI integrations with Amazon Bedrock;
- technical English for international and distributed teams.

## Languages

- **Spanish:** Native
- **English:** Intermediate (B1–B2), actively improving

## Let's connect

I am open to remote roles and selected freelance projects in **full stack development, backend engineering, AWS cloud/serverless engineering, automation, and applied Generative AI**.

- **Portfolio:** [d1qm6hv407vrgm.cloudfront.net](https://d1qm6hv407vrgm.cloudfront.net/)
- **LinkedIn:** [Julio Gutiérrez Morales](https://www.linkedin.com/in/julio-gutierrez-morales0302)
- **GitHub:** [juliogutierrezm](https://github.com/juliogutierrezm)
- **Email:** [juliogutierrezdev@gmail.com](mailto:juliogutierrezdev@gmail.com)

