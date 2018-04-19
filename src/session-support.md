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
- https://db-engines.com/en/system/Elasticsearch%3BGraphite%3BInfluxDB%3BPrometheus

---

# Request and Routing

---

## Where

- Client-side
- Mono-Server
- Multi-server
- Mixed

---

## What

- Event / Request
- Asset (strings, array, map / html, json, image, stream, ...)

---

## Journey

- User-Request based

---

## Journey

- Event-Based

---

## Journey

- Time-Based

---

## Protocols

- HTTP(s)
- WebSockets
- SSH
- AMQP
- SMTP

---

## Paradigms

- REST
- [GraphQL](http://graphql.org)

---

## Tech recipes

- [GraphQL](http://graphql.org)
- [Socket.io](https://github.com/socketio/socket.io)
- [STOMP](http://stomp.github.io)
- [RabbitMQ](https://www.rabbitmq.com)
- [Spring Boot and Embedded MQ](https://memorynotfound.com/spring-boot-embedded-activemq-configuration-example/)

---

# Continuous Integration Pipeline

---

## Back to basics Basics

- scripts
- cron
- env vars
- ssh
- git hook

---

## Scripting

- bash, shell
- powershell
- python

---

## Basics
### SSH

- ssh-key ([doc](https://confluence.atlassian.com/bitbucketserver/creating-ssh-keys-776639788.html))
- scp

---

## Basics
### Cron

- Scheduling tool
- Exec whatever
```
1 0 * * * printf "" > ./error_log   .
```

---

## Basics
### Git Hooks

- Client side / Server side
- [Doc](https://www.git-scm.com/book/en/v2/Customizing-Git-Git-Hooks)
- [More doc](https://www.atlassian.com/git/tutorials/git-hooks)

---

## Build

- Git clone not enough
- Beware of scope
- Beware of dependencies

---

## Build

- Test sources
- Generate packaging

---

## Build

- mvn
- node ...
- shell
- docker build

---

## Test

- Unit testing (already done at deployment)
- Integration testing: is everything built correctly?
- Deployment test: does it run?

---

### Staging / Release

- Can I release what I built
- Shall I build again?

---

## Deploy

- ssh / scp
- [Ansible](https://www.ansible.com) (actually ssh)
- Docker (... and who runs docker run?)

---

# Pipeline Basics

---

## Unit test

exec stuff

---

## Build

exec more stuff

---

## Test

exec again

---

## Release

curl, wget, git clone, ... guess what? Exec again

---

# April 12th



---

## Project reminder

- Provide all kind of output: *specs, project management, sources, app, deployment urls*
- "Half-way" report: April 29th
- Oral presentation: May 25th

---

## Reminder

- Basics are essential
- Dataflow and UX/Request flow in the core of the app
- Tools don't matter

---

# Server side request handling

---

## Request handling
### Basics

- Action -> Reaction

---

## Request handling
### Request Journey

- Incoming request
- Request routing
- Response generation

---

## Request Journey
### Incoming request

- http -> mime type
- socket
- cron
- ampq
- whatever

---

## Request Journey
### Response generation

- Any response to incoming request
- http (mime type), socket, ampq, whatever
- May be indirect: generate another request  
  - save file  
  - send mail  

---

## Request Journey
### Request Routing

- Destination: Web server ([nodejs](https://nodejs.org/en/docs/guides/getting-started-guide/), jetty, tomcat, undertow)
- How to get there: Reverse proxy (apache http, nginx, iis)

---

## Request Journey
### Request Routing

- "Smart" routing: e.g. JBoss/Wildfly
- Replication
- Load Balancing

---

## Request Journey
### Request Routing

Global Server load balancing: [When the going gets tough](https://www.youtube.com/watch?v=lIxUKbV0UEM)

- DNS
- CDN

---

## Request Journey
### Request Routing

- Beware of the Load
- Beware of cache

---

## Request Journey
### Origins

- User: UX interaction
- Machine: automated response or result of interaction
- Different responses for different entities

---

## Request Origins
### User

- Browser
- App

---

## User Requests
### Scenarios

- Best-case scenario will never happen
- Browser restriction ([CORS](https://en.wikipedia.org/wiki/Cross-origin_resource_sharing))
- Parental control
- Firewalls/Infrastructure restriction

---

## Request Origins
### Machine

- (Web)service
- Bot/Search bot
- Malware/ransomware

---

## Machine Requests
### Scenarios

- Optimistic scenario: isolated application getting requests from web Server
- Real-life scenario: openly exposed services consumed by malicious entities

---

## Real life scenarios

- Something doesn't work as expected
- == Attacks

---

## Attacks  
### Machine Oriented

- (D)DoS
- Ping flood
- IP Spoofing
- etc.

---

## Attacks  
### User-orieted

- Phishing
- Spoofing
---

# Protection

---

## System-oriented protection
### Levels

- Web server
- Application
- Code

---

## System-oriented protection
### Tools & techniques

- Depend on the level
- Depend on the interface

---

## System-oriented protection
### Tools & techniques

- ssl encryption
- firewalls
- isolation

---

## User protection

- Not obvious
- Communication and education is needed

---

## User protection
### Tools & techniques

- Explicit TSL/SSL Certificates (https://letsencrypt.org)
- Multi-factor authentication

---

## User protection

- Authentication vs. Authorization
- OAuth and SSO

---

## User protection
### OAuth

- One account - multiple services
- One authorization per service

---

## User protection
### SSO

- One authentication for all
- http://www.passportjs.org


---

# April 13th

---

## Sensible data

- Handling
- Hiding

---

## Secrets
### Worst practices

- Hardcoded
- Config file

---

## Secrets
### Techniques

- Cryptography
- SHA*, bcrypt
- e.g. Salt and pepper

---

## Secrets
### Tools

- [crypto-js](https://www.npmjs.com/package/crypto-js)
- [Hashicorp Vault](https://www.vaultproject.io)
- [Docker Secrets](https://docs.docker.com/engine/swarm/secrets/)

---

## Secrets
### Real-life

- Separation of concerns
- ENV vars
- Crypt values

---

## Secrets
### Real-life

- Beware of server access
- Clean-up terminal history

---

---

# Twelve factor application

---

# Twelve factor application

- https://12factor.net

---

## Twelve factor application
### I. Codebase

One codebase tracked in revision control, many deploys

- == do not copy repositories

---

## Twelve factor application
### II. Dependencies

Explicitly declare and isolate dependencies

---

## Twelve factor application
### III. Config

Store config in the environment

- == no config in code

---

# Twelve factor application
### IV. Backing services

Treat backing services as attached resources

- No distinction between local and third party services.
- Everything as a service

---

# Twelve factor application

V. Build, release, run
Strictly separate build and run stages

---

## Twelve factor application
### VI. Processes

Execute the app as one or more stateless processes

- Twelve-factor processes are stateless and share-nothing

---

## Twelve factor application
### VII. Port binding

Export services via port binding

- Completely self-contained
- Consuming via HTTP port

---

## Twelve factor application
### VIII. Concurrency

Scale out via the process model

- handle concurrency on scale

---

## Twelve factor application
### IX. Disposability

Maximize robustness with fast startup and graceful shutdown

- Can be started or stopped at a moment’s notice
- robust against sudden death
- == easy to throw app

---

## Twelve factor application
### X. Dev/prod parity

Keep development, staging, and production as similar as possible

- Continuous deployment
- Beware of dependencies versions

---

## Twelve factor application
### XI. Logs

Treat logs as event streams

- A twelve-factor app never concerns itself with routing or storage of its output stream.
- == use tools such as logstash or fluentd

---

## Twelve factor application
### XII. Admin processes

Run admin/management tasks as one-off processes

- == Provide admin tools with your app

---

# User Experience

---

## User Experience
### Principles

- The user satisfaction is essential
- User retention is key to success
- Keep users by allowing them to spend less time with the app

---

## User Experience
### Principles

- Simplicity is the clue
- [Three-click rule](https://en.wikipedia.org/wiki/Three-click_rule)
- Give access to the essential information
- Mobile-first

---

## User experience
### Principles

- One step at a time
- Identify your priorities
- Be ready for the sacrifices

---

## User experience
### Failures

- Too complex
- Too slow

---

## User Experience
### Failures

- https://www.apple-pinklady.com/en/the-club/
- https://particuliers.societegenerale.fr
- https://drive.google.com/drive/my-drive
- https://portal.office.com/

---

## User experience
### Not so Failures: Standing out

- https://craigslist.org
- https://www.lingscars.com
- http://www.milliondollarhomepage.com


---

## User experience
### Not so Failures: Cultural differences

- http://www.ruten.com.tw
- https://www.rakuten.co.jp vs https://www.priceminister.com
- https://www.yahoo.co.jp vs https://fr.yahoo.com/?p=us
- https://www.goo.ne.jp

---

---

# Front-end development

---

## Front-end Development
### Basics

- html
- css
- javascript/typescript

---

## Front-end Development
### Basics

- development: javascript/typescript
- testing: mocha chai sinon, jest ...
- build: webpack, parcel

---

## Front-end Development
### UI Tools

- Bootstrap
- Material Components
- Semantic-ui
- ...Whatever

---

## Front-end Development
### Frameworks and libs

- Vuejs
- AngularJS
- ReactJS

---

## Front-end Development
### Mobile

- [Ionic](https://ionicframework.com)
- [NativeScript](https://www.nativescript.org)

---

## Front-end Development
### Desktop

- [Electron](https://electronjs.org)
- [NW.js](https://nwjs.io)

---

## Front-end Development
### Tools don't matter (a lot)

- Vue: [Native](https://nativescript-vue.org) vs [Ionic](https://github.com/wangdahoo/vonic)
- Vue: [Electron](https://github.com/SimulatedGREG/electron-vue) vs [nw.js](https://github.com/elegantweb/nwjs-vue)

---

## Front-end development
### CLI as a solution

- vue cli: npm install -g @vue/cli
- ng cli: npm i -g @angular/cli@latest
- react cli: npm i -g create-react-app

---

## Front-end development
### Vue baby steps

- https://vuejs.org/v2/guide/components.html
- https://vuejsdevelopers.com/2017/12/11/vue-ssr-router/

---

---

# April 19th

---

## Reminder

- Basics are essential
- Dataflow and UX/Request flow in the core of the app
- Tools don't matter

---

## Project reminder

- Provide all kind of output: *specs, project management, sources, app, deployment urls*
- "Half-way" report: April 29th
- Oral presentation: May 25th

---

# JavaScript Universe

---

## JavaScript Universe
### Getting started

- CLI: vue cli / ng cli / react cli
- Vanilla JS: IDE or text editor; npm init

---

## Javascript Universe
### Getting started: borderline and pervert stuff

- Yeoman: http://yeoman.io/
- Meteor:  
  - https://guide.meteor.com  
  - https://github.com/meteor-vue/vue-meteor  

---

## JavaScript Universe
### Isomorphic Javascript

- Render javascript everywhere

---

## JavaScript Universe
## Isomorphic Javascript

- Vue:
  - NUXT https://nuxtjs.org  
  - SSR https://vuejsdevelopers.com/2017/12/11/vue-ssr-router/
- Angular Universal:  
  - https://universal.angular.io  
  - https://angular.io/guide/universal  
- React: https://github.com/DavidWells/isomorphic-react-example

---

## JavaScript Universe
### Isomorphic Javascript: Different View

- Optimize
- DRY: Don't Repeat Yourself
- Dependencies management

---

## "Isomorphic" Javascript
### Optimize: SEO

- Meta-data and navigation is crucial

---

## "Isomorphic" Javascript
### Optimize: Performance

- You don't have to do everything client-side
- You don't know know who uses your app

---

## "Isomorphic" Javascript
### Optimize: Behavior/UX

- You want the app do the exactly that thing you dreamed of

---

## "Isomorphic" Javascript
### DRY: Principles

- You may have common features, tools, business
- These features may be used client- and server-side
- You should not copy-paste this kind of stuff

---

## "Isomorphic" Javascript
### DRY: Examples

- Consuming webservices
- Text/Data formatting

---

## "Isomorphic" Javascript
### DRY: etc

https://en.wikipedia.org/wiki/List_of_software_development_philosophies

---

## "Isomorphic" Javascript
### Dependencies management

- npm
- composer
- maven
- Docker

---

## "Isomorphic" Javascript
### Dependencies management


- NPM: https://gemfury.com/help/npm-registry/

- https://docs.npmjs.com/misc/registry


---

## "Isomorphic" Javascript
### Dependencies management: Tools

- Nexus OSS:  
  - https://hub.docker.com/r/sonatype/nexus3/  
  - https://help.sonatype.com/repomanager3
- Sinopia:  
  - https://www.npmjs.com/package/sinopia

---

---

# UI & Rendering: Making the right choice

---

## UI Best practices
### Meta-data

- Seo referencing
- Cache etc.

---

## UI Best practices
### Internationalization

- Angular: https://angular.io/guide/i18n
- Vue: https://github.com/kazupon/vue-i18n

---

## UI Best practices
### Widgets hell

- [Facebook](https://www.facebook.com)
- [linkedin](https://www.linkedin.com/feed/)
- [Amazon](https://www.amazon.fr)
- [Airbnb](https://www.airbnb.com)

---

## UI Best practices
### Interface Components

- Icons: https://www.flaticon.com
- Images: https://ccsearch.creativecommons.org

---

## UI Best Practices

- Forms: getting key info


---

## Resources

- https://books.google.fr/books/about/Clean_Code.html?id=hjEFCAAAQBAJ&redir_esc=y&hl=en12Ba
- https://www.symantec.com/connect/articles/security-11-part-3-various-types-network-attacks
- https://www.digitalocean.com/community/tutorials/7-security-measures-to-protect-your-servers
