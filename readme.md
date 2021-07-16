## Before Technical Interview

### Information which is good to know before technical interview

* Current role (Developer, QA Engineer, Technical Lead, Architect, ...)
* Current responsibilities and daily activities (Meetings, Codding, Tasks assigment, ...)
* Candidate's preferences and wishes
    * Want to be a Dev, Lead, Architect, ...
    * 80/20 back-end/front-end, ...
    * 50/50 management/tech, ...
    * Want to work in a small team, ...
    * How do you feel when the requirements are being changed frequently? (to check agile mindset)

<br>

## Technical Interview (Technical Leads, Architects, ...)

### Step 1. Speak about the last project (engagement)

| Topic to discuss  | Expected words in the answer |
| -------------------- | ------------------------- |
| The exact tech stack | AWS, .net core, react, MS SQL, ... |
| Architecture | Monolith, SOA, Microservices, Serverless, ... |
| Hosting | On-Prem, AWS, Azure, Docker, Mixed... |
| Dev process and Releases | CI/CD, FTP, DevOps, ... |
| Monitoring in production | Logs, Metrics, Alerts, Tracing, ... |

<br>

---
> :warning: **The next steps depend on the candidate's answers**
---
<br>

### Step 2. Speak about Cloud

* AWS, Azure, GCP, ...
* IaaS, PaaS, SaaS, ...

> Interesting questions in this area:
> * TODO

<br>

### Step 3. Speak about .NET and Web.

* Solve the [Tasks](c-sharp-tasks.cs)
* SOLID

> Interesting questions in this area:
> * TODO

<br>

### Step 4. Speak about Front-End.

* Solve the [Tasks](js-tasks.js)
* Webpack and Bundles
* Caching

> Interesting questions in this area:
> * What if bundle is being downloaded too slow?

<br>

### Step 5. Speak about Databases.

* SQL vs NoSQL
* ACID
* CAP Theorem
* Replication
* Sharding
* Normalization vs Denormalization
* Caching

> Interesting questions in this area:
> * You need to run a migration script in production, but it takes 10+ mins. How to run it without a downtime? 
> * You have to choose the database for your startup. What it will be and why?
> * What would you suggest to do with the table which has super huge amount of data?

<br>

### Step 6. Speak about Architecture and Infrastructure

* Microservices and Serverless
* Availability, Durability, Resilience
* CDN
* Load Balancing
* Scaling
* Monitoring
* Decoupling and Message Brokers (RabbitMQ vs Kafka, SNS vs SQS, ...)

> Interesting questions in this area:
> * Some customers (more than 1) cannot hit the website, but for the rest everything works as expected. What could be an issue?
> * According to the metrics and logs, a production is alive, but a lot of customers say that production is down. How it can be and what would you suggest to do to predict this in the future?

<br>

### Step 7. Speak about CI/CD

* Environments
* Testing (including security testing, load testing)
* Releases and Rollbacks

> Interesting questions in this area:
> * How to release without a downtime?
> * How the best pipeline should look like and what tools should be used there?

<br>

### Step 8. Speak about Security

* OAuth vs OpenID
* WAF and DDoS
* Ratelimiting, Bot protection, ...
* OWASP and GDPR

> Interesting questions in this area:
> * How would you suggest protect your website against bots and similar tools?

<br>

### Step 9. Spend 2 minutes on [Blitz](blitz.txt) to cover random topics

<br>

### Step 10. Speak in English

* Estimation
    * How to estimate a huge task
    * Deadline is tomorrow, but the team needs 1 month more to finish
* For Leads
    * There is a toxic person in the team
    * What if seniors disagree with a suggested solution
    * ***What if you need to build a team of 5 engineers. What the setup will be and why? (for instance 1 TL, 1 Sr, 2
      Mids, 1 Jr)
* For Devs
    * What if you stuck with your task?
