# Sasha Firsov

sfirsov@simulationworks.com | (925) 407-7596 | bay Area, CA | https://www.linkedin.com/in/sasha-firsov | 
---|---|---|--

## SUMMARY
Senior Full-Stack Engineer / Tech Lead / Architect with 20+ years building and modernizing web platforms across UI, APIs, and data layers. Lead for multi-team delivery: architecture, monorepos/CI, quality gates, and developer enablement. AI-assisted architecture, design, and development (Claude, Codex) to accelerate delivery, improve code quality, and scale developer productivity. Deep in React/NextJS, Node/TypeScript, GraphQL (federation), cloud delivery, and accessibility-first theming (dark/light/high-contrast). Active W3C Community Group contributor: XSLT 4.0, Web Components on Declarative Web Components topics (links below).

**EDUCATION**:	Master in CS,  Computer Systems and Networks, National Technical University of Ukraine( Igor Sikorsky Kyiv Polytechnic Institute), 6 years

**PATENTS**: US20140089446 ADVANCED CLOUD COMPUTING DEVICE FOR THE CONTROL OF MEDIA, TELEVISION AND COMMUNICATIONS SERVICES (link below)

References furnished on request.

## CORE SKILLS
Frontend / UI Engineering
- React, Next.js, React Native, Web Components
- TypeScript, JavaScript (ES6+), HTML5, CSS3
- Micro-frontends, Web Components, Design Systems, Token-based theming
- Accessibility: WCAG 2.1 AA, inclusive UX patterns
  
Backend / API
- Node.js, GraphQL (Federation), Apollo Gateway, Hasura
- GraphQL, REST APIs, service integration, API design & versioning

Data / Messaging
- MongoDB, Mongoose; PostgreSQL, ACL
- Kafka; event-driven / streaming integration

Cloud / DevOps
- Azure; Docker, Docker Compose
- Kubernetes, Helm
- CI/CD: GitHub Actions; monorepos (Nx)

Quality / Delivery
- Testing: Playwright; automated test strategy; coverage-driven quality
- Architecture, technical leadership, cross-functional delivery


## PROFESSIONAL EXPERIENCE

Sr Full Stack Developer| Cargomatic | San Francisco, CA | 06/2025 - Current
---|---|---|--

Cargomatic is a local freight logistics platform that connects shippers with a large network of professional drivers/fleets to move shipments (drayage, intermodal, LTL/FTL, and final-mile) across major U.S. markets. 

Worked in a large codebase, including a 12-year-old legacy Node.js backend and React/React Native frontends. 
- Modernized legacy Node/React/React Native codebase: CoffeeScript → JS/TS; Introduced TS & JSDoc types
- Migrated runtime to Node 24 and upgraded Mongoose patterns from callback-style to async/await. 
- Performance tuning: optimized MongoDB queries; added offline processing via Kafka; EDI    integrations. 
- Strengthened reliability: production troubleshooting, logging/observability improvements, and test coverage for each fix/feature.
- Used LLM-assisted development to accelerate migrations while maintaining test coverage.
- Implemented Leg-based shipment order to streamline the ordering and billing process.


Tech Lead | MSI/Deloitte for Kaiser Permanente | Pleasanton, CA | 03/2024 - 05/2025
---|---|---|--

Designed & built a multi-vendor HealthOS platform from scratch. 
Based on DDD and evolutionary architecture design guided architecture and delivery alignment across 3 teams from ground up to production.
- Defined canonical Health Care domain model (patient/vendor/insurance) as docs with entities model diagram
- Entities implemented via Springboot Java with PostgreSQL in Azure Cloud for DB schema init and upgrade
- Created Synthetic Persona data for all entities to be used as test data set in all environments smoke test and base for unit tests. The DB schema and seed data propagated by SpringBoot application
- Introduced the low-code BFF tier to expose data from databases via Hasura GraphQL. It allowed us to reduce the back-end work to bare minimum. 
- Apollo Gateway federating Hasura + vendor APIs into a unified graph and set as a platform with unified GraphQL view into 3rd party data including Epic API and Kaiser web services
- Most entities are exposed as embeddable microapplications in Adobe AEM and Builder.IO CMS and as standalone web applications. UI was designed in Figma and the team created over 40 business components as microapplications using NextJS React stack. 
- Added the UI regression check with Chromatic GitHub integration
- Established quality gates: 80%+ coverage in CI. To keep the strict types and data integrity, the MSW mock service workers supplied data flow in tests identically  to the live environment. UI applications have mock data mode to be validated without back-end allowing to pinpoint the FE vs BE issues.
- The functional tests were accompanied by visual with Storybook as TDD test driven platform for visual components development.  
- All tiers design and development orchestration. I have created the Nx monorepo and CLI to generate components and modules for all tiers from DB entities in SpringBoot to React components. - Organized the training and orchestrated the development by up to 21 developers.
- Organized and supported CI/CD with GitHub actions, deployed to Azure Cloud using Helm charts and locally developed with Docker Compose.
- Delivered semantic multi-brand UI theming incl. dark/light/high-contrast modes across web/mobile.

With some wrapping the tech stack of Typescript Testing Library allows the same tests to run as in Playwright e2e checks as in Storybook/Vitest unit tests. Due to unification of tech stack, same team members were utilized in development of all tiers, code, and tests eliminating the need for dedicated QA.

Sr Principal Software Engineer | Bluescape | Redwood City, CA	| 12/2021 - 12/2023
---|---|---|--

Acted As Architecture Council member, Security and Infrastructure Champion. 

Owned vulnerability intake/triage and remediation tracking across a ~2M+ LOC, 6-team monorepo; contributed to FedRAMP authorization readiness by maintaining SSP/POA&M, coordinating evidence collection, and tracking remediation through assessment findings - FedRAMP Authorized on 12/13/2022; authored an RFI response for the Office of the National Cyber Director on Bluescape behalf.

Evaluated and completed the WCAG 2.1 AA per Amazon policy for shared library and management apps for high-contrast/dark/light mode, screen reader, keyboard navigation - Bluescape app passed Amazon’s accessibility review. Created Semantic Theming documenting the concept, creating Architectural Proposal, implemented POC and integrated into shared lib and some applications.

Held the ownership of several apps: identity client, shared lib, GraphQL managing CLI.

Full stack apps design and development. GraphQL server & client DAL development, React components shared library design & development, TDD with Storybook unit & regression testing,  UI semantic theme design and implementation, monorepo project layer development, OCLIF based CLI with web UI, macOS, Windows, Linux executables - design & development. Member of architect council, security champions, performance & scalability groups. TypeScript, JavaScript, Web Components, React, CSS, HTML, SQL, GraphQL.

Tech Lead | Rose International/ Kaiser Permanente | Pleasanton, CA | 02/2020 - 11/2021
---|---|---|--

Kaiser Permanente as client. Front-door and inner-door projects front-end development full SDLC: prototyping, integration with AEM build toolchain, unit test and coverage, pixel-perfect design implementation. Web components based UI from scratch and migration from Angular project. Active Member of UI chapter and UI Tokens board. OSGI java container micro-applications design and development.

Liferay Expert | Randstad Technologies for Bank of the West | San Ramon, CA  | 10/2018 - 02/2020 
---|---|---|--

Enterprise environment consulting. Designed and developed applications from ground up: Liferay as a common bank application platform, Women Entrepreneurs site & Document Exchange suite, Antivirus proxy Server. Liferay Java portal backend, OSGI API modules, Angular and PolymerJs+Vaadin front-end. Integration of web components and 3rd party JS frameworks into Liferay 7. Java Portlets, IBM FileNet integration, Webpack, Node.js, ES6, CSS, cross-browser support. Helping line of businesses to fit apps and teams into LR portal platform via MicroApplication SDLC patterns.

Sr Full-stack Software Developer | John Muir Hospital | Walnut Creek CA | 04/2015 - 09/2018
---|---|---|--

John Muir Health is a hospital network serving Contra Costa County and surrounding communities.
All hands software developer. Implemented Find a Doctor and Front-page portal. Integration of various 3rd party services into a portal on heavy legacy multi-framework codebase: Grails, Spring, Bootstrap CSS, JQuery, MySQL, RESTful web services, JSP. Participated in design and creation of new products based on Mule API gateway, Angular2, Node.js, AMD, Adobe AEM, React Boilerplate. Mobile (iOS, Android) responsive UX & apps.

consulting, listed only bigger projects | Simulation Works | Lafayette CA  | 06/2009 – 04/2015
---|---|---|--

Lead Developer | Simulation Works for Boy Scouts of America | Dallas TX | 04/2012 - 03/2014
---|---|---|--

Acted as architect, lead and software developer. Designed and developed various software modules. Dojo Toolkit based UI widgets, shopping cart+Inventory, 0-level (BE API , own UI) payment gateway integration, Security and logging suite over WCF .NET, RESTful JSON to SQL mapping, versioning deployment tracking, etc. The development has been done on all tiers starting from MS SQL to UI. On each tier the design, performance tuning, test cases with 80+% coverage written to support the volume of millions users.

 2 projects consulting | CISCO | San Jose, CA | 12/2009 - 03/2012
---|---|---|--

**CiscoBlue** – Scientific Atlanta/CISCO. 
Set-top Box UI and Ant Galio browser performance tuning. Static HTML layout, JS dynamic DOM and CSS tuning. NSAPI plugin for Guide (EPG) UI design and implementation. Implemented of SAIL and MDA API, cross-platform platform API implementation and development suite (emulator) development. Embedded Linux, Win32. ISDP Settop box performance and reliability tuning. ANT Galio and MDA code review using profilers and Coverity code analyzer.

**Cisco Quad** collaboration suite (merged with WebEx). Dojo toolkit expert. In-browser performance tuning, packaging, cross-browser troubleshooting. Liferay java web portal. FedRAMP Cyber Security compliance review on each tier.


Ad Server – Radius Marketing, inc.                                                                                                                       06/2009 - 11/2009
---|---|---|--

UI and middle tier of reporting management suite. Based on DHTMLX and JQuery interactive front-end, XSLT and PHP middle tier. Lazy POST-based tracking instead of img.

Senior Software Developer, Ask.Com, Oakland CA,                             	    	                  11/2007 - 05/2009
ASK.COM is a search engine and answering-focused e-business founded in 1997.
Application analysis, design and development. 
- Sr. Software Developer creation of news.ask.com site. J2EE, XML web services, JavaScript and DHTML
- Sr. System Analyst. SWAT team. Cross-vendor maps API and licenses comparison and winner (Bing maps) implementation. Lead development for transition of city.ask.com and maps.ask.com from deCarta to MS Live maps. Google Maps API, MapQuest API, MS Live Maps API, Java/J2EE/Servlet/JSTL, SOAP, XML, AJAX
city.ask.com, maps.ask.com, news.ask.com development and MS Live maps integration. Web 2.0 JS/AJAX-based heavy client DHTML development, JQuery, J2EE, JAVA servlet/JSP TAG library development and support.
- HTTP firewall and real-time traffic analysis project. 
Replaced 4-days 10Tb volume analytics with real-time actions capable of DoS attack protection. Cohort and client behavioral profiling. Knowledge base utility support. 10K requests per second without significant impact on CPU load.
Java to XML serializer, POJO web service framework. SAX, XSLT, AJAX, DHTML, JavaScript
- Knowledge base UI upgrade and tuning. SQL, C++, STL, multithreading, sockets, Linux, XML web services, C# ASP .NET Visual Studio, linux, IIS ISAPI and CGI.

2006. Radio2Go. Spare time project.
Internet radio player and recorder. Synchronized with server play list allows to play and record to MP3 player songs. User’s rating, customized Playlists and record history allow users to make suggestions for personalized profiles. Windows 32 application C++, DHTML + MFC UI.
SPECIAL EXPERIENCE

Imaging Programmed all following: extraction of skin, muscles, bone damage, blood streams from X-Ray. X-ray threat identification(security scanning) algorithms. Fly over moon 3D view. Golf courses import from geospatial data and conversion to 3D. Golf course fly over video renderer for file preview in videogames. 3D landscape editor.

LINKS
W3C Community Group contributor: XSLT 4.0, Web Components
PATENTS: US20140089446 
NPM: 	https://www.npmjs.com/~sasha-firsov
GitHub: https://github.com/sashafirsov
