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

# Fast and Furious development

a.k.a Quick and Dirty

---

## F&F development
### Principles

- [Worse is better](https://en.wikipedia.org/wiki/Worse_is_better)
- [Keep it simple, stupid](https://en.wikipedia.org/wiki/KISS_principle)
- "Copy-paste is not a crime"

---

## F&F development
### Principles

- Keep track
- Move forward
- Share

---

## F&F development
### Keep track: git

- git init / git add / git commit / git push

---

## F&F development
### Sharing scripts

- via https://raw.githubusercontent.com

- apt-get install curl
- curl ... | sh

---

## F&F development
### Docker as sharing tool

- Docker + Dockerfile
- Docker + script.sh

---

## F&F development
### Tunnelling services

- [ngrok](https://dashboard.ngrok.com/)


---

---

# April 20th

---

# Servers setup

---

## Project reminder

- "Half-way" report: April 29th
- Oral presentation: May 25th (slides, demo and whatever)
- Beware of the deadline

---

## Side notes
### Backend options

- Python: http://flask.pocoo.org
- Go: https://github.com/kataras/iris
- Haskell: https://www.yesodweb.com

---

# Progressive Web Applications (PWA)

---

## PWA
### Principles (by Google)

- Reliable - Load instantly and never show the downasaur, even in uncertain network conditions.
- Fast - Respond quickly to user interactions with silky smooth animations and no janky scrolling.
- Engaging - Feel like a natural app on the device, with an immersive user experience.

---

## PWA
### Principles (by Wikipedia) (1)

- Progressive - Work for every user, regardless of browser choice because they’re built with progressive enhancement as a core tenet.
- Responsive - Fit any form factor: desktop, mobile, tablet, or forms yet to emerge.
- Connectivity independent - Service workers allow work offline, or on low quality networks.
- App-like - Feel like an app to the user with app-style interactions and navigation.

---

## PWA
### Principles (by Wikipedia) (2)

- Fresh - Always up-to-date thanks to the service worker update process.
- Safe - Served via HTTPS to prevent snooping and ensure content hasn’t been tampered with.
- Discoverable - Are identifiable as “applications” thanks to W3C manifests[6] and service worker registration scope allowing search engines to find them.

---

## PWA
### Principles (by Wikipedia) (3)

- Re-engageable - Make re-engagement easy through features like push notifications.
- Installable - Allow users to “keep” apps they find most useful on their home screen without the hassle of an app store.
- Linkable - Easily shared via a URL and do not require complex installation.

---

## PWA
### Basics

- HTTPS
- [Web App manifest](https://developers.google.com/web/fundamentals/web-app-manifest/)
- [Service Workers](https://developers.google.com/web/fundamentals/primers/service-workers/)

---

## PWA
### Basics

- Secure (https)
- Works Offline (service workers cache)
- Push notifications (service workers)
- Add to Home Screen (Web app manifest)

---

## PWA
### Reports

- https://medium.com/progressive-web-apps/2018-state-of-progressive-web-apps-f7517d43ba70

---

## Service Workers
### Principles

- Install
- Listen to events: Request and cache
- Sync

---

## Service Workers
### Principles

- Download
- Install
- Activate

---

## Service Workers
### More stuff: Background Sync

- Queue data fetching
- Getting data in background

---

## Service Workers
### More stuff: Background Sync

- [Google Guide](https://developers.google.com/web/updates/2015/12/background-sync)
- [Tutorial](https://ponyfoo.com/articles/backgroundsync)

---

## Service Workers
### Beware of standards

- A lot of working draft
- [CanIUse.com](https://caniuse.com/#search=workers)
- [Non standard features](https://developer.mozilla.org/en-US/docs/Web/API/ServiceWorkerRegistration/sync)

---

## Service Workers
### Getting started

- [Google Guide](https://developers.google.com/web/fundamentals/primers/service-workers/)
- [Google Labs: Offline first](https://developers.google.com/web/ilt/pwa/lab-offline-quickstart)
- [Google Labs: Service Worker](https://developers.google.com/web/ilt/pwa/lab-scripting-the-service-worker)
- [Google Labs: Push Notifications](https://developers.google.com/web/ilt/pwa/lab-integrating-web-push)

---

## Service Workers
### Getting started: a touch of vue

- [Tutorial Part 1](https://blog.sicara.com/a-progressive-web-application-with-vue-js-webpack-material-design-part-1-c243e2e6e402)
- [Tutorial Part 2](https://medium.com/bam-tech/a-progressive-web-application-with-vue-js-webpack-material-design-part-2-a5f19e70e08b)

---

# April 26th, 6:30pm
## Valeuriad Data Science Event

---

# HTTP/2

---

## HTTP/2

- https://twitter.com/kosamari/status/859958929484337152?utm_source=syndicate&utm_medium=post&utm_campaign=scotch-jun172510

---

## HTTP
### From HTTP 1.1 to HTTP/2

- One pipe, multiple data
- Traffic optimization
- More efficient data exchange

---

## HTTP
### From HTTP 1.1 to HTTP/2

- All requests are downloaded in parallel, not in a queue
- HTTP headers are compressed
- Pages transfer as a binary, not as a text file, which is more efficient
- Servers can “push” data even without the user’s request, which improves speed for users with high latency

---

## HTTP/2
### Getting started

- npm i -g static-http2-server
- nginx https://www.nginx.com/blog/nginx-1-13-9-http2-server-push/

---

## HTTP/2
### Beyond the fun

- Not yet really useful in REST API
- Might be overkill in basic use cases

---

## HTTP/2
### Beyond the fun

- (Still) limited browser support
- [CanIUse](https://caniuse.com/#feat=http2)

---

---

# FrontEnd: HTML & CSS

---

## FrontEnd: HTML & CSS

- Don't stick to one framework

---

## HTML
### Master the basics

- Right tags for right purpose: tables, divs, lists

---

## HTML
### Master the basics

- Think about SEO: Title, meta, H*, img alt, links

---

## CSS
### Master the basics

- [Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)
- [Grid vs. flexbox](https://css-tricks.com/css-grid-replace-flexbox/)

---

## CSS & HTML
### Bootstrap

- [12 columns grid pattern](https://getbootstrap.com/docs/4.0/layout/grid/#horizontal-alignment)

---

---

# May 17th

---

## Project reminder

- ~~"Half-way" report: April 29th~~ - ok
- Presentation: May 25th (slides, demo and whatever)
- Beware of the deadline

---

## Project grading
### Mostly tech-oriented

- Technology choice
- Clarity of presentation
- Beware of the deadline

---

## Project grading
### Clarity of presentation

- Report
- Output

---

## Project grading
### Achievements

- Roadmap ambitions vs. reality
- Deliverables

---

## Project grading
### Project management

- Team roles
- Tasks management
- Scope definition

---

## Project grading
### Bonus

- Any outstanding feature

---

## Reminder

- Basics are essential
- Dataflow and UX/Request flow in the core of the app
- Tools don't matter

---

## Reminder

- Front-End: anything that can be read by a browser
- Back-End: any app able to do data processing

---

## Mentoring opportunity

- Project demo by Ingesup B1
- Technical challenging

---

---

# Building stuff

---

## Building
### Basics

- Scan sources
- Compile
- Generate output

---

## Building
### Principles

- Generate package
- Bundling vs. Task runners

---

## Building
### Tools

- Front-End Bundlers: Webpack, Parcel, RollUp
- Back-end: composer, cargo, maven...
- Task runners: Npm, make, grunt, gulp
- (https://survivejs.com/webpack/appendices/comparison/)

---

## Front-end Build
### Pipeline

- Assets management
- Pre/post process css
- Code splitting

---

## Front-end build
### Assets management

- Images: file vs. [base64](https://github.com/webpack-contrib/url-loader)
- Fonts
- Data (csv, xml) - [json not needed](https://github.com/webpack-contrib/json-loader)


---

## Front-end build
### CSS handling

- [CSS](https://medium.com/@ddprrt/deconfusing-pre-and-post-processing-d68e3bd078a3)

---

## Front-end build
### Webpack

- [Power-lifting bundler](https://webpack.js.org/guides/)

---

## Front-end build
### Parcel

- ["Zero-conf" bundler](https://github.com/parcel-bundler/parcel)

---

## Front-End build
### Frameworks

- Angular: [default](https://github.com/angular/angular-cli/wiki/build), [webpack](https://angular.io/guide/webpack)
- Nuxt: [config](https://nuxtjs.org/api/configuration-build/), [code](https://github.com/nuxt/nuxt.js/blob/dev/lib/builder/builder.js)

---

## Building
### Where to go from here

- Package Management (e.g. nexus)
- Production deploy (scp or [nexus](https://sdqali.in/blog/2017/08/17/uploading-a-standalone-artifact-to-nexus-3/))

---

---

#  Managing Deliverables

---

## Managing Deliverables
### Requirements

- Stable
- Versionable
- Archivable

---

## Managing Deliverables
### Requirements

- Knowing what was deployed and when

---

## Managing Deliverables
### Tools

- File server
- Git
- Artifactory
- Nexus
- [or else](https://binary-repositories-comparison.github.io)

---

## Managing Deliverables
### Nexus OSS

- ~~Everything~~ Most of what you may need

---

## Nexus OSS
### Deploying

- [Deploy npm](https://books.sonatype.com/nexus-book/2.13/reference/npm-deploying-packages.html)
- [Deploy Zip](https://sdqali.in/blog/2017/08/17/uploading-a-standalone-artifact-to-nexus-3/)

---

## Nexus OSS
### Consuming

- NPM: `npm i --registry ...`
- [Zip](https://support.sonatype.com/hc/en-us/articles/213465488-How-can-I-retrieve-a-snapshot-if-I-don-t-know-the-exact-filename-): `wget ...`, `mvn dependency:get`
- Beware of Nexus 3 ([1](https://stackoverflow.com/questions/39488834/nexus-3-rest-api-to-download-artifacts), [2](https://groups.google.com/a/glists.sonatype.com/forum/#!topic/nexus-users/xdsKXeveUL0))
- [Checkout Nexus API](http://localhost:8081/swagger-ui/#!/assets/getAssets)

---


---

# Audit and Metrics

---

## Audit and Metrics
### Why?

- Master application behavior
- Monitoring and diagnostic
- Continuous improvement
- Debug

---

## Audit and Metrics
### Centralize

- Logstash
- ELK
- Prometheus

---

## Audit and metrics
### Front end

- Monitoring user actions
- Beyond server Requests

---

## Audit and metrics
### Front end

- Plain DIY web service
- Turnkey solution: [logstash](https://www.elastic.co/blog/introducing-logstash-input-http-plugin), [beaver-logger](https://github.com/krakenjs/beaver-logger)

---

## Audit and metrics
### Front end: Be careful

- Bandwidth
- Performances
- Security
- You do not want make things worse

---

## Audit and metrics
### Back-end

- Any logging solution + logstash
- Middleware: e.g. [morgan](https://github.com/expressjs/morgan) 4 expressjs


---

## Audit and metrics
### Builds and updates

- Same stuff: get key/critical info
- Logstash, prometheus, or custom web services

---



---

# May 18th

---

## Project reminder

- ~~"Half-way" report: April 29th~~ - ok
- Presentation: May 25th (slide deck, demo and whatever)

---

## Project grading

- Beware: roles and task management
- Think about git, gitflow and individual contributions

---

# Testing

---

## Testing
### Why?

- Mastering the software
- Avoid breaking things
- Avoid (bad) surprises

---

## Testing
### How?

- Manual mode: open, view, note
- By writing software

---

## Testing
### How?

- Choose any tool you can work with

---

## Testing
### Tools

- PHP: PHPunit
- Java: JUnit, TestNG
- python: [unittest](https://docs.python.org/3/library/unittest.html)
- go: [testing](https://golang.org/pkg/testing/), [goblin](https://github.com/franela/goblin)
- C++: [CUnit](http://cunit.sourceforge.net/doc/writing_tests.html)
- JS: [mocha](https://medium.com/@jaysoifer/testing-vue-js-applications-with-karma-and-mocha-and-chai-14d9015f1889), chai, sinon, jasmin, karma, jest, [nightwatch](https://badacadabra.github.io/End-to-End-testing-with-Nightwatch-js-TDD-vs-BDD/), CasperJS

---

## Testing
### JS Frameworks

- Vue ([1](https://vue-test-utils.vuejs.org/en/guides/testing-SFCs-with-mocha-webpack.html), [2](https://vuejsdevelopers.com/2017/12/25/vue-js-test-driven-development-tdd/), [3](https://github.com/Techroombyjp/vue-bdd))
- Angular ([1](https://angular.io/guide/testing))


---

## Testing
### Back To Basics

- Well written tests may save ~~lives~~ time
- Bad tests are [PITA](https://www.urbandictionary.com/define.php?term=pita)

---

## Testing
### Back To Basics

- Avoid wasting time
- Stay efficient
- Do not spend all your time ~~testing~~ coding tests

---

## Testing
### Definitions

- Unit testing
- Integration testing
- Validation testing
- End-to-End testing

---

## Testing
### Definitions

- Mocking
- Test coverage
- TDD: Test Driven Development
- [BDD](https://www.infoq.com/news/2015/02/introducing-bdd): Behaviour Driven Development ([1](https://www.agilealliance.org/glossary/bdd/), [2](https://dannorth.net/introducing-bdd/), [3](https://www.atlassian.com/blog/software-teams/making-the-shift-to-behavior-driven-development))

---

## Testing
### Definitions

- [Blue/Green deployment](http://blog.christianposta.com/deploy/blue-green-deployments-a-b-testing-and-canary-releases/)
- [Canary deployment](https://octopus.com/docs/deployment-patterns/canary-deployments)

---

## Testing
### Back to Real Life

- Spaghetti testing code
- No tests whatsoever
- Testing evidence


---

## Testing
### Back to Real Life

$$
Tests = \frac{1}{Method Size}
$$

---

## Testing
### Back to Real Life

- [When the going gets tough](https://www.youtube.com/watch?v=lIxUKbV0UEM)

---

## Testing
### Making life easier

- Refactor
- Keep code alive
- Write tests continuously

---

## Testing
### Making life easier

- Think testing when coding
- Test anything you want to keep control of

---



---

# May 24th

---

## Project reminder

- Presentation: (slide deck, demo and whatever)
- May 25th 1PM - ...
- ~(20+20): ~20 for presentation + ~20 for Board and Audience questions

---

---

# Tech jungle

---

## Tech jungle
### Front-End

- Angular, React, Vue
- Inferno, Preact, Svelte
- jQuery, Backbone, Ember
- Example: Vue.js alternatives [1](https://www.slant.co/options/11378/alternatives/~vue-js-alternatives), [2](https://vuejs.org/v2/guide/comparison.html)

---

## Tech jungle
### Front-End / Changelogs

- [Angular](https://github.com/angular/angular/blob/master/CHANGELOG.md)
- [React](https://github.com/facebook/react/blob/master/CHANGELOG.md)
- [Vuejs](https://github.com/vuejs/vue/releases)

---

## Tech jungle
### Backend

- JavaScript (Node.js + express)
- PHP
- [Ruby On Rails](https://openclassrooms.com/paths/104-full-stack-developer)
- Python
- Java
- ...

---

## Tech jungle
### Databases

- MySQL
- PostreSQL
- MSSQL
- MongoDB
- ...

---

## Tech jungle
### DevOps

- [DevOps Periodic Table](https://xebialabs.com/periodic-table-of-devops-tools/)

---

## Tech jungle
### Bonus: Slide deck

- Powerpoint
- Open/Libre-Office
- [Slides](https://slides.com)
- [Beamer](https://en.wikipedia.org/wiki/Beamer_(LaTeX))
- [Reveal-md](https://github.com/webpro/reveal-md)
- ...

---

## Tech jungle

**The way out**

---

## Tech jungle
### The way out: Standards

Don't be too inventive

---

## The way out
### Standards

- **HTML/CSS**
- JSON
- XML/XSL
- *GraphQL*
- [DICOM](https://github.com/ivmartel/dwv)

---

## The way out
### Data structures, Algorithms, Big-O notation

Don't make your stuff uselessly complex

---

## The way out
### Data structures

- Think beyond arrays and maps
- Lists, queues, deques, stacks, Sets
- Pick the right one

---

## The way out
### Data structures

- Beware of data types
- Strings: size
- Numbers: precision

---

## The way out
### Algorithms

- Avoid N-nested loops

---

## The way out
### Big-O notation

- [Make an estimate of the complexity](http://web.mit.edu/16.070/www/lecture/big_o.pdf)

---

## The way out
### Don't waste your time on choices

Never bet on one horse

---

## The way out
### Don't waste your time on choices

- Big chances your choice become obsolete
- Master your dependencies
- [React License Drama](https://medium.com/@raulk/if-youre-a-startup-you-should-not-use-react-reflecting-on-the-bsd-patents-license-b049d4a67dd2)
- [Polymer](https://github.com/Polymer/polymer/wiki/Who%27s-using-Polymer%3F)
- [Ember](https://www.emberjs.com/ember-users/)

---

## The way out
### Understanding the technology

Master the intelligence under the hood

---

## The way out
### Understanding the technology

- [Virtual DOM](http://reactkungfu.com/2015/10/the-difference-between-virtual-dom-and-dom/)
- [Incremental DOM](https://medium.com/google-developers/introducing-incremental-dom-e98f79ce2c5f)

---

## The way out
### Best practices

Stay consistent no matter the context

---

## The way out
### Best practices

**From the inside**

- Software design
- Procedures
- Versioning
- Backups

---

## The way out
### Best practices

**Software Design**

- UML, Merise, or whatever
- Stay agile

---

## The way out
### Best practices

**Procedures**

- master your activity
- You don't have to automate everything

---

## The way out
### Best practices

**Always backup**

- ****: [rule of three](https://www.hanselman.com/blog/TheComputerBackupRuleOfThree.aspx)
- Something may go wrong

---

## The way out
### Best practices

**Versioning**

- git or whatever
- Keep track of your progress

---

## The way out
### Best practices

**From the outside**

- Care about your users
- Don't code for yourself

---

## The way out
### Care about your users

- Identify your users
- Know what they need / want
- Avoid to sell shit

---

## The way out
### Don't code for yourself

- Keep code [clean](https://books.google.fr/books/about/Clean_Code.html?id=hjEFCAAAQBAJ&redir_esc=y&hl=en12Ba)
- Comments etc.

---

---

# Software development as a craft

---

## Software development as a craft

[The Clean Coder](https://books.google.fr/books/about/The_Clean_Coder.html?id=ik0qCTVzl44C&source=kp_cover) *by Robert C. Martin*

Don't forget about [Clean Code](https://books.google.fr/books/about/Clean_Code.html?id=hjEFCAAAQBAJ&redir_esc=y&hl=en12Ba)

---

## Craftsmanship
### Cultural issues

---

## Craftsmanship
### Cultural issues

1. People who have no idea about IT

---

## Craftsmanship
### Cultural issues

2. People who make wrong ideas about IT

---

## Craftsmanship
### Team Work

---

## Craftsmanship
### Team Work

- Clear communication

---

## Craftsmanship
### Team work

- [Management](http://dilbert.com/strip/2018-04-20)
- Commitment

---

## Craftsmanship
### Team Work

- Saying Yes vs. Saying No

---

## Craftsmanship
### Team Work

**Fixing goals**

- DONE definition
- Milestones and deliverables

---

## Craftsmanship
### Time Estimation

---

## Craftsmanship
### Time Estimation

- Don't try to master Everything
- Don't be too optimistic/pessimistic

---

## Craftsmanship
### Time Estimation

- O: Optimistic estimate
- N: Neutral estimate
- P: Pessimistic estimate

---

## Craftsmanship
### Time Estimation

Consider:

- slowdowns: personal inefficiency
- debug, failures: lack of knowledge
- meeting loophole: talking about delays

---

## Craftsmanship
### Time Estimation

$$
\mu = \frac{O + 4N + P}{6}
$$


$$
\sigma = \frac{P - O}{6}
$$

---

## Craftsmanship
### Time Estimation: Everyday Reality

- 8 hours/day => 40 hours / week
- 20 min daily meeting
- Support request / legacy debug
- Unscheduled meetings

=> 30 hours max


---

## Craftsmanship
### Time Estimation: Project Reality

- 75 hours lectures + project
- 40% lectures
- 5% lateness / delays
- 40 hours * 5 people

=> 200 hours

---

## Craftsmanship
### Time management

---

## Craftsmanship
### Time management

- Fixing realistic objectives and deadlines
- Staying efficient

---

## Craftsmanship
### Time management

- Procrastination
- Avoidance
- Priority inversion

---

## Craftsmanship
### Time management: Performance estimation

- Tomatoes
- Tasks amount
- [Tasks/Story points](https://www.mountaingoatsoftware.com/blog/dont-estimate-the-sprint-backlog-using-task-points)

---

## Craftsmanship
### Coding

- Stay professional
- Don't rush
- Do not force

---

## Craftsmanship
### Collaboration

- Pair programming
- Meetups
- Exchange & share
- Ask for help

---

## Craftsmanship
### Keeping pace

- Learn
- Stay up to date
- Practice
- Put in extra hours

---

---

## Resources

- https://books.google.fr/books/about/Clean_Code.html?id=hjEFCAAAQBAJ&redir_esc=y&hl=en12Ba
- https://www.symantec.com/connect/articles/security-11-part-3-various-types-network-attacks
- https://www.digitalocean.com/community/tutorials/7-security-measures-to-protect-your-servers


- https://medium.freecodecamp.org/9-neat-javascript-tricks-e2742f2735c3
- https://survivejs.com/webpack/appendices/comparison/
