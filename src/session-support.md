# ~~Angular~~ Web Full Stack

Ingesup Mx / YNOV / 2018

---

## Household

- Mickael Tardy
- mickael.a.tardy@gmail.com
- https://www.linkedin.com/in/mickael-tardy-54723235
- https://github.com/miketardy-ynov-classroom/ynov-mx-js-support

---

## Household
### Tools 

- Slideshow: markdown & reveal-md
- Graphs and Whiteboard: draw.io
- IDE: atom.io, visual studio code or whatever
- Trello, Github, gitlab

---

## Don't expect

- 90h of coding
- 90h of Angular
- Tech tutorials
- Wordpress

---

## Course design

- 90 hours 
- Mixing English and French
- Mixing lectures and Practice

---

## Course design

- Mixing Frontend and Backend
- Mixing system design, database design and coding
- DevOps

---

## Approach 

- Understand the basics
- Don't panic
- Don't get overexcited 
- Stay curious

---

## Approach

*“Give me six hours to chop down a tree and I will spend the first four sharpening the axe.”* — Abraham Lincoln.

---

## Project 

- Identify
- Design
- Develop
- Deploy

---

# April 5th

---

# Introduction

---

## What is full-stack 

- Everything developer
- Front-end, Back-end, Continuous Integration, Infrastructure

---

## Full-stack developer in real world

- Candidate 1: *Java/JEE, MySQL, Angular 1.x*

- Candidate 2: *Javascript, Python, React, Vue, Docker and whatever with 10 years experience*

- How I get my first job as developer ([google it](https://www.google.fr/search?rls=en&q=how+I+get+my+first+job+as+developer&ie=UTF-8&oe=UTF-8))

---

## Full-stack 

- Stay focused
- Be efficient
- Right tool for right use

---

## Full-stack 

- Best practices
- [Clean Code](https://books.google.fr/books/about/Clean_Code.html?id=hjEFCAAAQBAJ&redir_esc=y&hl=en)

---

# Tech stack

---

## OS

- \*n\*x: 
- CoreOS, CentOS, Ubuntu, 

---

## Scripting 

- bash, shell
- powershell
- python

---

## Version control

- **git**
- TFS, Mercury...

---

## Format

- HTML, css
- Markdown
- LateX
- json, yml

---

## Coding

- JavaScript, Java, Python, PHP...

---

## Databases

- MySQL, MongoDB
- Neo4J
- Redis
- InfluxDB

---

## Frameworks

- AngularJS, Vuejs, React, Preact
- Spring, Laravel, Express, Django

---

## Package Management

- npm, yarn, maven, pip

---

## Build mangement

- node, gulp grunt, webpack, parcel

---

## Build and Continuous integration

- Jenkins, TravisCI, Bamboo, CircleCI, Gitlab

---

## DevOps

- Docker, Rkt, Kubernetees, VirtualBox, 
- vmware esxi
- Heroku

---

# Agile Development

---

## Approach 

- BDD / TDD
- Clean code

---

## Definitions

- Kanban
- Scrum

---

## Basics 

- Iterative 
- Regular
- Adjustable
- Clear scope

---

## Tools 

- Gitflow
- Waffle, Trello, Taiga

---

# Project packaging / scoring

---

## Project management

- Kanban
- Links (waffle, github)

---

## Documentation 

- Functional Specifications 
- Technical Specifications 

---

## App Sources 

- Repo link
- Everything required to build the app
- Database model (if needed)

---

## Sources 

- Quality

---

## Infrastructure Sources

- Scripts 
- Docker files
- Ansible (?)

---

## Deployment 

- Link

---

# April 6th

---

# Dataflow

---

## Data assessment
### Data Identification 

- Data item types => confidentiality, integrity, and availability needs.

---

## Data assessment
### Data Ownership and users 

- The data item owners and users => confidentiality, integrity, and possibly availability needs

---

## Data assessment
### Data Confidentiality 

- The need to keep the data secret from unauthorized persons. 
- how much damage would be done if the data were obtained by unauthorized persons.
- None/Low/Medium/High

---

## Data assessment
### Data Integrity 

- The need to keep the data accurate and not allow unauthorized persons to change it. 
- Consider the impact if the data were not correct.
- None/Low/Medium/High

---

## Data assessment
### Data Availability 

- The need for the data to be available to authorized users. 
- Data owners should consider how their business processes would be impacted if they could not access their data for some period of time and what periods of time would be critical.
- None/Low/Medium/High

---

## Data assessment
### Data Criticality 

- How essential the data is to the operation of the organization.

---

## Data assessment
### Data Access Determination 

- Determining minimum access needs.

---

## Data assessment
### Data and Application Location 

- Risks of sending data across the network 
- Mitigation and transfer risk.

---

## Datatypes

- Structured data: user accounts, posts

---

## Datatypes 

- Unstructured data: images, documents

---

## Datatypes 

- Metrtics: Logs, resources consumption 

---

## Data relationship 

- Relationship
- Isolated data 
- Corelations 

---

## Data storage

- Persistent 
- Volatile 

---

## Data recipes 
### Data store

- Classics: Mysql, mongodb
- In-memory: [Redis](https://redis.io)
- Graphs: Neo4J

---

## Data recipes 
### Local data store

- [Browser Local/Session storage](https://www.w3schools.com/html/html5_webstorage.asp)
- (Local browser) Data store: [PouchDB](https://pouchdb.com)
- (Special occasion) Java: [wix-embedded-mysql](https://github.com/wix/wix-embedded-mysql), [flapdoodle](https://github.com/flapdoodle-oss/de.flapdoodle.embed.mongo), derbydb
- Native script: [Nativescript-couchbase](https://github.com/couchbaselabs/nativescript-couchbase)


---

## Data recipes 
### Logs 

- node: [winston](https://github.com/winstonjs/winston), [winston transports](https://github.com/winstonjs/winston/blob/master/docs/transports.md)
- Java: slf4j, log4j, logback (and [appenders](https://logback.qos.ch/manual/appenders.html))
- Overall: Logstash

---

## Data recipes 
### Logs and Time series

- InfluxDB
- Graphite
- Prometheus
- ELK (Elasticsearch, Logstash, Kibana)
https://db-engines.com/en/system/Elasticsearch%3BGraphite%3BInfluxDB%3BPrometheus

---

## Resources 

- https://books.google.fr/books/about/Clean_Code.html?id=hjEFCAAAQBAJ&redir_esc=y&hl=en