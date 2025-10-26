# AZ-204 Study Plan Checklist (8 Weeks)

> **Goal**: Pass the **AZ-204: Developing Solutions for Microsoft Azure** exam  
> **Duration**: 8 weeks (~10–15 hrs/week)  
> **Track progress**: Check off tasks as completed  
> **GitHub Tip**: Save this file as `AZ-204-Study-Plan.md` in your repo and use GitHub Issues or Projects to track weekly milestones.

---

## Resources Setup
- [ ] Create a **free Azure account** (with $200 credit)
- [ ] Bookmark [Microsoft Learn AZ-204 Path](https://learn.microsoft.com/en-us/credentials/certifications/exams/az-204#two-ways-to-prepare)
- [ ] Install **Azure CLI**, **Visual Studio Code**, **.NET SDK**, **Azure Storage Explorer**
- [ ] Join **r/AZURE** on Reddit & **Microsoft Q&A**
- [ ] (Optional) Purchase **Exam Ref AZ-204** book or **Udemy/Whizlabs practice tests**

---

## Week 1: Foundations & Compute (Part 1)
### Azure Basics
- [ ] Complete: *Introduction to Azure for developers* (Microsoft Learn)
- [ ] Navigate Azure Portal: Resource Groups, Subscriptions, Tags

### Containers
- [ ] Module: *Deploy and manage containers in Azure*
- [ ] Lab: Build Docker image locally
- [ ] Lab: Push image to **Azure Container Registry (ACR)**
- [ ] Lab: Deploy to **Azure Container Instances (ACI)**
- [ ] Lab: Deploy to **Azure Container Apps (ACA)**

### App Service (Intro)
- [ ] Module: *Host a web app with Azure App Service*
- [ ] Lab: Deploy sample .NET/Node.js app to **Web App**
- [ ] Enable **diagnostic logs**

### Review
- [ ] Take **Week 1 Quiz** (Microsoft Learn)
- [ ] Note weak areas in `WEEK1_NOTES.md`

---

## Week 2: Compute (Part 2) – App Service & Functions
### App Service (Advanced)
- [ ] Configure **deployment slots** (staging → production swap)
- [ ] Set up **autoscaling rules**
- [ ] Configure **custom domains & TLS**
- [ ] Lab: Deploy container to Web App for Containers

### Azure Functions
- [ ] Module: *Create serverless logic with Azure Functions*
- [ ] Lab: Create **HTTP-triggered function**
- [ ] Lab: Create **Timer-triggered function**
- [ ] Implement **input/output bindings** (Blob, Cosmos DB)
- [ ] Deploy Functions via **VS Code extension**

### Review
- [ ] Compare: ACI vs ACA vs App Service vs Functions
- [ ] Hands-on: Call Function from Web App
- [ ] Take **Compute Section Quiz**
- [ ] Update `WEEK2_NOTES.md`

---

## Week 3: Azure Storage
### Azure Cosmos DB
- [ ] Module: *Work with Azure Cosmos DB*
- [ ] Understand **partitioning & consistency levels**
- [ ] Lab: Create Cosmos DB account (SQL API)
- [ ] Lab: CRUD operations via **.NET/Python SDK**
- [ ] Lab: Implement **Change Feed**

### Blob Storage
- [ ] Module: *Store data in Azure*
- [ ] Lab: Upload/download blobs via SDK
- [ ] Configure **lifecycle management policy**
- [ ] Set **access tiers** (Hot/Cool/Archive)
- [ ] Generate **SAS token**

### Review
- [ ] Project: App that saves user data to Cosmos DB + files to Blob
- [ ] Take **Storage Quiz**
- [ ] Update `WEEK3_NOTES.md`

---

## Week 4: Azure Security
### Authentication & Authorization
- [ ] Module: *Secure your cloud applications in Azure*
- [ ] Register app in **Microsoft Entra ID**
- [ ] Implement **OAuth 2.0 / OpenID Connect**
- [ ] Lab: Authenticate Function with Entra ID
- [ ] Use **Microsoft Graph** to read user profile

### Secrets Management
- [ ] Create **Azure Key Vault**
- [ ] Store secret, key, certificate
- [ ] Lab: Access secret from Function using **Managed Identity**
- [ ] Generate **SAS for Blob** with limited permissions

### Review
- [ ] Understand **least privilege** & **RBAC**
- [ ] Take **Security Quiz**
- [ ] Update `WEEK4_NOTES.md`

---

## Week 5: Monitor, Troubleshoot & Optimize
### Application Insights
- [ ] Module: *Monitor Azure resources with Azure Monitor*
- [ ] Instrument app with **Application Insights SDK**
- [ ] View **live metrics, logs, traces**
- [ ] Set up **availability web test**
- [ ] Create **alert rule** (e.g., CPU > 80%)

### Troubleshooting
- [ ] Debug cold start in Functions
- [ ] Analyze **failed requests** in App Service
- [ ] Use **Kudu** (App Service debug console)

### Review
- [ ] Retake quizzes from **Weeks 1–4**
- [ ] Update `WEEK5_NOTES.md`

---

## Week 6: Integration (Part 1) – API Management & Events
### API Management (APIM)
- [ ] Module: *Publish APIs with Azure API Management*
- [ ] Create APIM instance
- [ ] Import OpenAPI spec
- [ ] Add **rate limiting & JWT validation policy**
- [ ] Test via **Developer Portal**

### Event Grid & Event Hubs
- [ ] Module: *Implement event-based cloud solutions*
- [ ] Create **Event Grid topic**
- [ ] Set up **WebHook subscription**
- [ ] Lab: Trigger Function from Event Grid
- [ ] Intro to **Event Hubs** (capture & replay)

### Review
- [ ] Build: Blob upload → Event Grid → Function
- [ ] Take **APIM & Events Quiz**
- [ ] Update `WEEK6_NOTES.md`

---

## Week 7: Integration (Part 2) – Messaging
### Service Bus & Queue Storage
- [ ] Module: *Implement message-based solutions*
- [ ] Create **Service Bus namespace**
- [ ] Send/receive messages (queues & topics)
- [ ] Implement **sessions & duplicate detection**
- [ ] Lab: Process messages with Functions
- [ ] Compare: Service Bus vs Queue Storage vs Event Grid

### End-to-End Project
- [ ] Build:  
  Web App → API Management → Function → Service Bus → Storage → Cosmos DB  
  (with auth, logging, monitoring)

### Review
- [ ] Take **Integration Section Quiz**
- [ ] Update `WEEK7_NOTES.md`

---

## Week 8: Final Review & Exam Prep
### Full Review
- [ ] Revisit **all weak areas** from notes
- [ ] Review **skills measured** (official exam page)
- [ ] Memorize key CLI/PowerShell commands

### Practice Exams
- [ ] Take **Microsoft Official Practice Test**
- [ ] Take **1–2 third-party timed exams** (aim for 80%+)
- [ ] Review **every wrong answer** in detail

### Final Prep
- [ ] Practice **interactive lab scenarios**
- [ ] Create **flashcards**: consistency levels, bindings, auth flows
- [ ] Rest well the day before

### Exam Day
- [ ] Schedule exam via **Pearson VUE**
- [ ] Bring ID, arrive early
- [ ] **You’ve got this!**

---

## Post-Exam
- [ ] Celebrate! 🎉
- [ ] Share your success on LinkedIn / Twitter
- [ ] Plan renewal (free annual assessment on Microsoft Learn)
