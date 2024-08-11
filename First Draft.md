**

# Introduction

Value Stream and Value Stream Mapping (VSM) are rapidly becoming some of the hottest topics in all business-oriented industries today. Rooted in the lean manufacturing methodologies pioneered by Toyota in the mid-20th century, VSM was originally intended to optimize production efficiency by minimizing waste. However, today, it maps out the entire production process from ideation to delivery, providing a holistic view that enables companies to streamline operations, enhance productivity, and increase production efficiency. This evolution has allowed VSM to transcend its manufacturing origins and become a versatile tool applied across multiple industries, including software development, healthcare, and finance.

This paper also takes a particular interest in the banking sector, which has undergone a significant digital transformation, moving away from its once-dominant transactional and physical operations. Traditional banking methods, centered around physical branches and paper-based transactions, have given way to a diverse array of online and omnichannel services. However, this crucial shift has primarily focused on enhancing the customer journey, often leading to a disconnect between outdated internal processes and the advanced digital fronts banks are trying to adopt.

In this context, we will explore the difference between the concepts of the customer journey and value stream management. While value streams focus on the internal flow of processes and resources necessary to deliver a service, customer journeys emphasize the external experiences and interactions that shape customer satisfaction and loyalty. We will discuss the potential integration of these concepts and the benefits banks can achieve by marrying them into a holistic new approach to banking.

To this end, we propose a novel framework and roadmap for banks to effectively implement value streams within their IT solutions. This approach aims to override some traditional practices with modern digital imperatives, facilitating a seamless transition that not only increases customer satisfaction but also enhances profitability.

# Value stream and value stream management
    

## Definitions 
    

### What is a value stream
    

#### Definition 
    

Value stream is the end to end process of sequencing the necessary activities to deliver value to a customer, whether them being internal or external. It includes all the stages from the trigger or the initial request of the value to its delivery to the beneficiary making it always start and end  with the customer. 

  

#### Objectives



##### Customer Centricity

>The most important single thing is to focus obsessively on the customer. Our goal is to be earth’s most customer-centric company. —Jeff Bezos  
  

The "[Project Management Institute](https://www.pmi.org/disciplined-agile/process/value-streams#:~:text=A%20value%20stream%20is%20the,(DA%E2%84%A2)%20tool%20kit.)" defines value as " ==**the set of actions that take place to add value for customers from the initial request through realization of value by the customers**==."
This being said, value stream being end and continue from the customer " from the initial request through realization of value by the customers". This nature makes it consequently one of the four layers of the [Disciplined Agile® (DA™)](https://www.pmi.org/disciplined-agile/introduction-to-disciplined-agile) tool kit. This tool kit offers practical guidance to optimize organizational processes, fostering business agility. It maps out how different departments collaborate, outlines their responsibilities, presents various approaches, and analyzes their trade-offs.

The following graph made by PMI represent the high-level workflow for a value stream. As we can see the value stream concept starts from the customer, goes through different stages ending up with the execution and value delivery to the customer. 

![[Value Streams DQ.webp]]

[SAFe ](https://scaledagileframework.com/customer-centricity/#:~:text=Customers%20are%20the%20ultimate%20beneficiaries,by%20a%20portfolio's%20value%20streams.) also emphasizes the the fact that customer centricity is a main pillar in the value stream concept. 

> "Customers are the ultimate beneficiaries of the value of the solutions created and maintained by a portfolio’s value streams."   _ © Scaled Agile, Inc.

Also, in the book _Business Process Improvement: The Breakthrough Strategy for Total Quality, Productivity, and Competitiveness_, by H. James Harrington argues that an efficient process is one that is able to meet the customer requirement. He explains that process, product and client go hand in hand and have a codependent relationship. 
##### [Value driven](https://digital-portfolio.opengroup.org/oaa-standard/latest/part2-building-blocks/value-streams.html) 
As one might notice from the name, VSM is mainly directed towards deriving value from processes, but what is value and who are its main stake holders.

Murman, in the book [_Lean Enterprise Value: Insights from the MIT’s Lean Aerospace Initiative_](https://link.springer.com/book/10.1057/9781403907509), defines value as: 

>“How various stakeholders find particular worth, utility, benefit, or reward in exchange for their respective contributions to the enterprise.”

This makes value streams a "[series of value adding steps](https://www.ardoq.com/knowledge-hub/value-streams#:~:text=A%20value%20stream%20is%20initiated,creating%20value%20for%20the%20stakeholder.)" that add up together to deliver value, whether it being by process improvement or value elimination. 

###### Waste elimination
While Process enhancement depends on the type of action being taken, waste can be generalized to fit into specific categories.
[Waste (or muda](https://www.process.st/muda/#:~:text=The%20elimination%20of%20waste%20is,customer%20will%20not%20pay%20for.)), defined as anything that adds cost or time without adding value. Waste is identified and categorized using the "seven wastes" framework from Toyota's TPS (Toyota Production System). They can be divided into: 

- Waste of overproducing
    
- Waste of waiting
    
- Waste of transport
    
- Waste of processing: Managed by ensuring interventions are comprehensive initially, reducing the need for additional procedures.
    
- Waste of inventory: Reduced by implementing a kanban system in the angio suite for demand-driven stent orders, eliminating excess stock.
    
- Waste of motion: Addressed through standard operating procedures (SOPs) and visual labeling to minimize unnecessary movements during procedures.
    
- Waste of defects and spoilage: Mitigated by improving staff expertise and supervision to prevent errors and reworks.
    

// TODO: where is the cue timer + speak about added value 



#### [Added Value of VSM](https://www.dozuki.com/blog/why-do-value-stream-mapping-benefits-examples#:~:text=Value%20stream%20mapping%2C%20or%20VSM,process%20for%20the%20customer's%20benefit.)

Some of the benefits of adopting VSM into the 

###  TODO: Grafical representation don’t think this 
    

[Value stream mapping](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3259414/)  is designed to map information flows along with material flows, making it more suitable for analyzing and improving complex processes like those in hospitals. VSM provides a holistic view that includes both value-adding and non-value-adding activities.

  

TODO: current maps vs future maps 

Keep this for later 

  

3. ### Value stream vs internal value chain
    

Value streams are usually visualized from the stakeholder’s viewpoint. And at this point we come the make the distinction between value streams and internal value chains. While value streams focus on how the value is achieved for the end customer, internal value chain describes the series of activities within an organization that add value to a product or service. In other terms  The value chain focuses on identifying the specific activities that add value to the organization’s products or services and seeks to optimize these activities to gain a competitive advantage. 

Thus, the main difference is that while the value chain focuses on internal processes and how they add value within the organization, while value streams encompass the entire flow of activities needed to deliver value to the customer, often crossing organizational boundaries. And in terms of objective, value chains are aimed at identifing and optimizing the internal activities for competitive advantage while value streams take a more holistic view aiming at improving the overall flow of value to the customer by eliminating waste and increasing efficiency.

TODO: keep before case study 

### [Value stream mapping VS Process maps](https://www.icagile.com/resources/value-stream-mapping-vs-process-mapping-definitions-features-benefits) 
    

Another confusion people tend to fall into is confusing VSM and process maps. So while VSM VSM zooms out to examine the entire value stream from start to finish identifying the possible waste and value, process mapping provides a detailed visual representation of individual organizational processes within a given value stream.

  

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXeoZQHZ6c_uMTu_G3zMgDWr3R65EHdNjUEb_t0VJjQ1OhiXcmzHXJLKagAfa_B6Lm7YzBoZ_AKmeMWJ6PLZnqVG-y26a94IY9f9I-L0GzLA88vWEwrmd2EnHy6vAJ0RRw3Uyyu81NzV6ZwnvS-EJYmDhnY?key=Nu8PMyX64obvw5Muh2vzug)

[Process mapping example from ICAgile](https://www.icagile.com/resources/value-stream-mapping-vs-process-mapping-definitions-features-benefits) 

## History 
    
### [Henry Ford and the model T](https://www.lean.org/the-lean-post/articles/jim-womack-explains-the-origins-and-value-of-value-stream-mapping/)
    

In the early twentieth century, when creating his Model T* car, Henry Ford* engineered the initial principles behind Value stream mapping. He started noticing the disfuncionality of production all around him, whether it might be the inefficiency of batch sizing, the order of production that imposed a lot of out of place start and end of production among other issues. Amid this chaos, one idea came to his mind: lining up all the processes related to the production of a product sequentially would make the production process a smoother one. This later gave rise to what we know today as the assembly line*. And as great of an innovation that was, what continued to live on from it is the actual fabrication steps as he lined up the processes that use to live separately such as casting, machining, painting, welding… together in a working sequence that created what he came to call “flow”* giving the first name to VSM “flow production”. 

The issue with Ford’s approach is that it was not easily scalable. At the time of creation of the “flow production” the only product he had in production was his Model T, and integrating a smooth continuous flow of assembly was fairely simple. However, as industries grew larger, and the products grew more diverse, Ford and other manifacturors abandonned the original flow methodologies as they were no longer applicable. 

  

### [Toyota](https://www.lean.org/the-lean-post/articles/jim-womack-explains-the-origins-and-value-of-value-stream-mapping/) 
    

Despite being left out by ford and his contemporaries, the production flow principles were rediscovered by Taiichi Ohno*, the originator of  the Toyota production system* after the end of WW2. One this he always said is “I learned everything I know from Henry Ford, except I found a way, to do it with high variety and low volume. Ford can only do it with low variety and high volume”(LEO, n.d.) The main goal behind their innovation was to create a product journey centered around the customer and that focuses in efficient production while maintaining  high variety and low volume. 

The Toyota team then then came to create the concept of value stream mapping where for each product family* they detailed every step of the creation of either the entire product on its indivisual components. 

The mapping then goes as follows: we have the raw elements that will eventually make their way to the customer in a different form: final product. Identify the individual steps of that process in each one of them, and then start your classification: which of these steps are waste and which are value that the customer would be willing to finance. 

These constitute the physical steps, along sides of them we have the [information flow](https://www.lean.org/lexicon-terms/information-flow/)* that goes on the top of the map. In simple terms, information flow is how information moves within a company to ensure products are made efficiently and meet customer demands. In the Toyota system, a central scheduling point where production plans are made is scheduled,  that uses "pull loops" of information. They signal upstream to earlier production points about what is needed, and downstream to later points about what has been produced. These points helps synchronize production closely with customer demand, reducing waste and improving efficiency. This information flow contrast to traditional mass production information flow where forecasts, schedules, and shipping orders go back and forth between different parts of the company and its facilities creating a lot of chaos and disorganization. 

  

### Lean Thinking and global adoption 
    

In the 1990s James womack and Daniel Jones popularized “Lean thinking” setting the building blocks for the Lean Enterprise Institute. They highlighted VSM as a key technique for identifying value-added and non-value-added activities popularizing even more among diffirent businesses. Today, Organizations worldwide embraced lean principles, including VSM, to streamline processes and enhance efficiency.

  

TODO: gratical representation 

TODO: make a grafixal representation of the history

speak about the extension to other fields even (SAFe methodology) other desciplines 

  

## [VSM case study](https://www.sciencedirect.com/science/article/pii/S1877705815004269?ref=pdf_download&fr=RR-2&rr=8a53c8748c807781): manufacturing example
    

### Company background 
    

 The enterprise we will be looking at manufactures plastic products for the pharmacy and healthcare industry.

Strategic Goals (2014-2018): Goals are divided into three groups:

- Q-group: Quality goals related to manufacturing processes.
    
- L-group: Logistic goals related to logistics and storage processes.
    
- C-group: Cost goals focused on personnel costs.
    

Balanced Scorecard Method: Strategic goals are detailed into yearly, quarterly, and monthly plans with specific KPIs.

KPI Documentation: Simplified KPI documents are used to track performance and are presented to top management as primary information sources

Averaging KPIs Issue: when the company averages KPI (Key Performance Indicator) values across the entire organization, it can mask the differences in performance between various product groups and departments. This "arithmetic-average-trap" makes it difficult to pinpoint specific areas where waste and inefficiencies exist. As a result, the primary function of identifying problems within the value chain is compromised, as the averaging process blurs significant performance variations and hides specific issues that need addressing.

Thus, for the rest of the  case study we will be focusing only on L-group KPIs only. 

  

Before implementing any changes to the value stream, here’s how the current state map looked like: 

  

//TODO: insert before state

[Value Stream Mapping Demonstration on Real Case Study](https://www.sciencedirect.com/science/article/pii/S1877705815004269?ref=pdf_download&fr=RR-2&rr=8a53c8748c807781)

  

### Performance Evaluation

1. Logistic Conception and Storage:
    

- The VSM method shows the dependency on external storage, 27 km from production.
    
- VSM map reveals the current logistics demand high transportation between manufacturing and the warehouse.
    

3. Lead Time:
    

- The actual lead time is 296 days, much higher than the target of 96 days.
    
- The goal breakdown: RAW (77 days) + SEMI-FINISHED (12 days) + FINISHED (7 days) + VA time (79 sec) = 96 days.
    

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXdxCQwQMotoQNsNct5-nrO9jcVOvSrPMYgTLm-ILeP2pssXZJ1t8AuiI9nFnYu5Zx8b7kOHDOxjHbSSAk8Xjo2tEoDDnrXbwzc4lhgcNP_ZNTRhR_bBJRQF-gpEvDOUvLulsLGNVvnXTJucYoU8Uw95Uvb0?key=Nu8PMyX64obvw5Muh2vzug)

[Value Stream Mapping Demonstration on Real Case Study](https://www.sciencedirect.com/science/article/pii/S1877705815004269?ref=pdf_download&fr=RR-2&rr=8a53c8748c807781)

3. KPI Discrepancy:
    

- The VSM map indicates non-fulfillment of KPIs, contradicting the KPI documents claiming compliance.
    
- The arithmetic-average-trap is evident due to 15 other value chains in the company.
    

5. Financial Implications:
    

- About 276,000 EUR tied up in unnecessary inventories for the selected value chain.
    
- Unnecessary inventories require 100 pallets of extra capacity at external storage.
    
- Annual financial loss is 16,000 EUR due to wasted resources and storage costs.
    
- This figure applies to one product line, implying potential larger issues.
    

  

###  Analysis and Problem-Solving Procedures

1. Root Cause Identification:
    

- VSM analysis triggers identification of root causes using methods like 5 Whys, Ishikawa Chart, 5W2H, etc.
    

3. Analytical Nature of VSM:
    

- VSM is analytical and does not solve problems by itself.
    
- Problems identified by VSM need to be addressed using other methods, such as lean methods.
    

### Creation of the VSM Future Map and Identified Problems, Their Causes, and Proposals for Potential Improvements

  

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXf1RwLHDA3rn_-7VhKWtEcvwxsjk_VTzayeOHNKPuS9tD8am4yrvUYKJsi5O2gRw0bU5KEmKTnBVcxrZQJg2QFAHTqEPzlEb7L8usclVJdEkIDufCTJi3OaZSv8ugSpq1wZlaS0xo5fH8uPW0sQV2-WWtMz?key=Nu8PMyX64obvw5Muh2vzug)

[Value Stream Mapping Demonstration on Real Case Study](https://www.sciencedirect.com/science/article/pii/S1877705815004269?ref=pdf_download&fr=RR-2&rr=8a53c8748c807781)

  
  

1. Current Logistic Conception Issues:
    

- The existing logistic system is complex, administratively and logistically difficult, with many human interactions leading to errors and waste.
    
- Solution: Reduce human factor involvement in purchase, quality, and storage processes.
    

3. Problem Identification and Solutions:
    

- Problems and causes were identified using the 5 Whys method.
    
- Possible solutions were proposed through brainstorming with company workers.
    
- Proposed improvements are categorized into:
    

- Simple incremental improvements with small investment costs.
    
- More difficult improvements within the current logistic system.
    
- Radical process reengineering improvements.
    

5. Impact on KPIs:
    

- Each proposed improvement aims to meet L-category KPIs (logistics goals).
    
- Special VSM reports can prevent the arithmetic-average-trap and provide more accurate inventory management.
    

7. Cost and Benefit Analysis:
    

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXe9WIWAaTUNIsjrmzuAYZfBg6IwJrZO3rrd3-6xU-YxVaqbqHLW0a7i1tLi9i4ARpWypNxCuo_YvWO0R4KL_fuiDuLbO1GQzrXGXpLTwrjzAHLGoKaaCGuu0UTWdGFRs7r6RvOcwSoHlZ18QlmmHE-YpSSc?key=Nu8PMyX64obvw5Muh2vzug)

[Value Stream Mapping Demonstration on Real Case Study](https://www.sciencedirect.com/science/article/pii/S1877705815004269?ref=pdf_download&fr=RR-2&rr=8a53c8748c807781)

- Rising production (59%) and transport/storage costs (163%) from 2014-2018 necessitate improvement.
    
- Discussion on building an own logistics center to save about 1 million EUR annually.
    
- Simple projects use a simple term of recoverability (SToR).
    
- Larger projects require sophisticated economic methods like NPV, IRR, EVA, CFROI, and risk management.
    

5. Project Evaluation:
    

- Portfolio attitude and mathematical optimization recommended for decision-making on projects with limited financial resources.
    
- Simpler projects may be better decided by practical manager intellect due to difficulty in accurate cost estimation.
    

7. Large Investment Project:
    

- Example: Constructing a logistics center with 45 million EUR investment, expected to be profitable within eight years.
    
- Positive evaluation using NPV and IRR (own capital costs = 7.71%).
    

9. Implementation and Outcomes:
    

- Three simple incremental improvements already implemented: assessment of employee competencies, strict time deadlines for quality acceptance processes, and preparation of special VSM reports.
    
- Improvements show potential to fulfill approved KPIs and demonstrate three times higher efficiency compared to the current state.
    
- VSM improves process functionality, leading to better cash flow and financial health of the company.
    

  

##   Vsm projection on other fields: [health industry example](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3259414/) 
    

When switching sectors, perspectives differ in terms of how wastes manifest and are managed, highlighting the need for tailored solutions. For instance, if we were to observe how the seven types of waste manifest we will find the following distribution: 

- Waste of overproducing: Not applicable to stents, but overordering can lead to waste of inventory.
    
- Waste of waiting: Addressed by improving information flow and scheduling to reduce delays in stent orders and patient treatments.
    
- Waste of transport: Minimized by optimizing logistics and direct delivery of stents to the angio suite to reduce handling and inspections.
    
- Waste of processing: Managed by ensuring interventions are comprehensive initially, reducing the need for additional procedures.
    
- Waste of inventory: Reduced by implementing a kanban system in the angio suite for demand-driven stent orders, eliminating excess stock.
    
- Waste of motion: Addressed through standard operating procedures (SOPs) and visual labeling to minimize unnecessary movements during procedures.
    
- Waste of defects and spoilage: Mitigated by improving staff expertise and supervision to prevent errors and reworks.
    

Thus, the proposed solutions must include digital ordering systems, SOPs, kanban systems, and improved logistics coordination. The original article also suggests an interdisciplinary approach which involves referrers, conductors (interventional radiologists), and specialists to streamline the entire process from order to treatment. It also emphasizes collaboration and process understanding across different departments and roles.

The paper concludes by praising the efficiency of the the adaptation of VSM as it presented itself as a crucial tool in not only visualizing process flows comprehensively but also in strategizing to reduce waste effectively across complex systems like healthcare. By following the lean guidelines, the organization was able to identify inefficiencies streamline processes, and enhance overall operational efficiency.

  

//TODO: link to IT + example : devops and widely adopted 

Is it still approved for orgs aimed at digital transformation + digital transformation + benefits for orgs seeking that 

  

//TODO: change this into into a big title of best practices and add maturity levels 

## [The Value Stream Management Maturity Model](https://www.software.broadcom.com/hubfs/ValueOps%20Maturity/vsm-maturity-model-WP_BC-VO-2023_CE-3887_v16.pdf)

Broadcom has developed a VSM maturity model based on their experience and a global survey conducted by Dimensional Research. This model aims to assist organizations at various stages of VSM adoption. The outcome of the survey indicate that despite the fact that many organizations have started their VSM journey, only a small percentage (about 2%) have reached advanced stages of maturity.  
This maturity level aims at helping more teams navigate their value stream journeys and achieve full maturity. 

They have split the process into five stages: 

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXdeHBadyZfDQ2JdL303GfLXEJ1rEldEsYMb_l-H9Km9ElqKwlY1xuaI8cnV84ftt4N39jINFWKW6MJ3ZTNLbPYRK2iIsVuEryP_y-ugUipdfCcn-9LGDBtr04O_jiDXh1QdiN1X6Y0lQBGYDAi22d5oSIY?key=Nu8PMyX64obvw5Muh2vzug)

#### Level 1 foundational 

Basic Understanding: Organizations at Level 1 of VSM have a basic understanding of their product or service delivery but lack a comprehensive view of end-to-end processes.

Desire for Improvement: There's a clear desire to modernize and improve, often through digital transformation, but efforts are disjointed and not coordinated across teams.

Operational Silos: Teams work in isolation with little collaboration, and leadership lacks alignment, often working with conflicting incentives.

Limited Data Use: Insights from data are minimal, with decisions often based on anecdotal information rather than data-driven analysis.

Risk of Inefficiencies: Anecdotal decision-making increases risks, dependencies, and inefficiencies within the organization.

  

#### Level 2: value stream aware 

Growing Understanding: Organizations at Level 2 of VSM have a developing grasp of their value streams and recognize the importance of continuous improvement.

Early VSM Adoption: Teams are beginning to implement Value Stream Mapping (VSM) concepts, identifying and mapping their value streams.

Pilot Initiatives: Initial pilot projects are underway to test new processes and feedback loops.

Metrics Collection: Metrics are being collected, but they are not yet fully utilized to drive process improvements effectively.

Mitigating Inefficiencies: Efforts are focused on implementing plans to reduce inefficiencies, address dependencies, and mitigate risks.

Focus on Infrastructure: There's an emphasis on building the necessary infrastructure to support ongoing improvement efforts and align with top-level strategies.

  

#### Level 3: collaborative 

Alignment and Collaboration: Level 3 in VSM emphasizes strong alignment and collaboration across entire value streams.

Focus on Efficiency: Teams prioritize reducing inefficiencies and improving overall performance, reflecting a shift towards more streamlined operations.

Established Practices: Consistent practices and organizational guardrails are implemented to mitigate risks, dependencies, and inefficiencies.

Breaking Down Silos: Silos between business and technology teams are dissolved, fostering increased collaboration and alignment.

Active Participation: Technology teams are actively involved in infrastructure updates and understand the rationale behind organizational guardrails, demonstrating ownership and collaboration.

  

#### Level 4: Data-driven

Data-Driven Decision Making: Level 4 in VSM emphasizes robust data-driven decision making across all value streams.

High Data Maturity: There is a high level of data maturity with consistent use of data and dashboards by both business and technology teams.

Integrated Data Flow: Data flows seamlessly between tools, enhancing process efficiency and collaboration.

Real-Time Dashboards: Teams utilize real-time dashboards instead of relying on quarterly reports, providing stakeholders with up-to-date insights.

Strategic Insights: Data is used to define top-level strategies, enabling business leadership to make informed decisions based on real-time execution data.

Automated Reporting: Status reporting is automated using workflow-derived data, reducing inaccuracies and administrative overhead associated with manual reporting methods.

  

#### Level 5: Full Transparency and Flow

Excellence in VSM and Beyond: Level 5 organizations excel not only in Value Stream Management (VSM) but also in innovation, collaboration, and transparency across the board.

Culture of Continuous Improvement: A strong culture of continuous improvement is present, where experimentation and innovation are naturally integrated into workflows.

Challenging Assumptions: Teams are proactive in challenging existing assumptions and are open to experimenting with new methods and approaches.

Full Operational Visibility: There is complete visibility and transparency in operations, from the initial ideation phase to post-release customer feedback.

Proactive Bottleneck Identification: Teams can identify and address potential bottlenecks early, preventing them from becoming significant issues.

Distributed Decision Making: Decision making is distributed, empowering teams to act on insights and be more informed.

Limited Team-Level Decision Making: Despite these advances, only 6% of respondents report that decisions are consistently made and implemented at the team level.

  
  
  

## How o[rganizations fail when using VSM](https://www.linkedin.com/pulse/important-ways-we-fail-learn-from-toyota-david-verble/)
    

  

// TODO: change the title and make it clearer 

When observing how some companies try to adopt lean practices and specifically VSM, one can easily identify the reasons why tehy are struggling to make their experiences successful. Among these points of failure we can name: 

- Misconceptions about VSM: a lot of companies treat VSM as a mere visual artifcat rather than utilising for its initial purpose which is performance improvement. Consequently a lot of them fall into the trap of simply making the “current state map” and fail to update or integrate them with Future State designs, missing the point of continuous improvement. 
    
- Focusing solely on risk reduction: focusing solely on reducing waste without addressing underlying workflow issues (instability, variation, overburden) can worsen customer delivery and cause waste to reappear elsewhere. One must acknowledge the fact that barriers to smooth flow (e.g., scheduling, information flow) are often more critical than isolated instances of waste.
    
-  Not following Toyota’s management approach for VSM: managers aught to use VSM to identify barriers to flow and quality, then create annual plans aligned with strategic priorities (hoshin). Teams systematically address these barriers through continuous problem solving. For more concrete examples of how this can be done,  Weekly activities like Jushiken bring together teams to map flows, balance operations, conduct experiments, and redesign processes to tackle significant workflow issues.
    
- Lean Thinking vs. Doing Lean: implementing the lean tools (like VSM for instance)  true lean transformation requires adopting lean thinking. This means that a change of mentality is crucial to radically solve the problems that VSM tries to touch. 
    

  
  

//TOASK: is this where we should start talking about global banking 

//TOAS.he last one 

  
  

# The historical development of banking channels toward omnichannels
    

//TODO: add graphics + elaborate 

## Transactional era 
    

Historically, banks revolved mainly around transactions. Customers visited physical branches for routine tasks like deposits and withdrawals. Operations were fairely simple as a bank had to only manage its internal affairs withing the one or multiple branches they had. All documentation and processes were handled manually. 

  

// TODO: monoagence in B

## Multichannel Approach
    

As technology advanced, and specifically during the technological boom,banks introduced additional channels: ATMs, call centers, and online banking. However important these advances might’ve been, they were still not enough. The channels operated independently making the user experience very inconsistent as history did not follow across channels due to a lack of integration between them. 

  

## Bidirectional Omnichannel 
    

//TODO: add bidirectional 

  

In the 2010s, there was a common consensus for the need to unify the fronts of banks. In other words we marked the emergence of omnichannel banking to integrated a seemless user experience. This new approach focuses on four key concepts: 

- Integration: Channels connected to provide a unified view of customer data.
    
- Consistency: Customers received uniform service across touchpoints.(TODO: kept history among different channels)
    
- Personalization: Data-driven insights enabled tailored interactions.
    
- Contextual Journeys: Understanding customer context allowed proactive engagement.( TODO: digital engagelt platform)
    

  

### Focus on the customer(TODO customer crntricity) 
    

Adapting an omnichannel approach meant an inevitable switch towayrds customer focused banking. And slowly we witnessed the immergence of customer journeys. This manifests in the following aspects: 

- Customer-Centric Approach:
    

- Understanding needs, preferences, and pain points.
    
- Mapping end-to-end journeys (e.g., account opening, loan application).
    
- Identifying touchpoints and addressing friction.
    

  

- Seamless Experiences:
    

- Customers seamlessly switch channels.
    
- Contextual information transfers.
    
- Personalized recommendations based on behavior.
    

- Implementing technology enablers(TODO: to satisfy internal and external customer): 
    

- APIs: Enable integration between channels.
    
- Mobile Apps: Central hub for banking activities.
    
- Data Analytics: Insights drive personalized offers. (TODO: big data?)
    
- Chatbots and AI: Assist across channels. (TODO: customer churn? How to use these tools use case ENGAGEMENT)
    

  

### Potential challenges
    

// to do keep at the end 

  

- Data Privacy: Balancing personalization with privacy.
    
- Channel Proliferation: Managing new channels (e.g., social media, voice assistants).
    
- Hyper-Personalization: AI-driven recommendations.
    
- Physical-Digital Blend: Branches as advisory centers. (TODO:Figital)
    
- TODO: the inevitable banking crisis + budget cuts
    
- TODO: scalability due to big data and real time and availability
    

  
  
  

// TODO how boderectional focuses on the enterbal customer 

However they still facing these challenges and supported by enable ETD 

  
  
  
  
  

# Value streams VS customer journey 
    

## What is customer journey 
    

The customer journey is the serious of steps starting with awareness and dating ack to before becoming a customer and leads to a purchase and eventual customer loyalty. Customer journeys need to and aim at [understanding their customers’ experiences and optaizing them at any touchpoint](https://business.adobe.com/blog/basics/customer-journey). 

  

Stages of Customer journey

- Awareness: how does the customer gets to make the first contact with the brand. Information is usually broadcasted via social media search engines, and other channels including banners and TV advertisement. 
    
- Consideration: Customers start considering your brand as a solution to their problem.
    
- Decision: The moment of purchase or commitment.
    
- Adoption: After the purchase, customers interact with your product or service.
    
- Advocacy: Satisfied customers become advocates, sharing their positive experiences with others.
    

  

Benefits of knowing the customer journey

Being fully aware of the customer journey will inevitably lead to lot of added value to the company mainly: 

- Enhanced Customer Experience: By optimizing each stage of the journey, businesses can create positive interactions, leading to increased customer satisfaction and loyalty.
    
- Improved Marketing Strategies: Knowing the journey helps tailor marketing efforts to meet customers’ needs at each stage, making campaigns more effective.
    
- Increased Retention: Focusing on the post-purchase stages helps retain customers, which is often more cost-effective than acquiring new ones.
    
- Better Customer Insights: Mapping the journey provides valuable insights into customer behavior, preferences, and pain points, enabling more informed business decisions.
    

//TOASK: should we elaborate more on customer journeys? 

  

## Value streams Vs customer journeys, are they the same
    

As explained above, a value stream is the series of steps of the creation of a production from its ideation to the end of its production. [The VSM consortium illustrated it as follows](https://www.vsmconsortium.org/blog/is-a-customer-journey-a-value-stream): 

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXemng7_DzUnUaOhqfjwgSlSzDbMaEQ5ya_3EDKgJfehnR51Usv890eJIEMFk1MadtoGCVoJqlVSbby7EoJevVys173lzP0oUjMW-11tM7gChmjMsZ6Mr4QmJpNt65peLnPPJIyHj1ZqUHll2-NUfvKYbP_r?key=Nu8PMyX64obvw5Muh2vzug)

On the other hand a customer journey is how the customer gets in contact with the product and buys it. 

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXdYCt0S6dSwo9m_IZeotiAK7VOfiogbqJtuUDSavJlxJp5xehBBcT3kfb8DiSFE2kVYcznesHLzFq7qkHxY7tdAzt6OiojPsxhloshp8bRUM5Q6aynQpwWmyiSXa2T0Be449in3PqAkz1FVDpzn3ms3gQQX?key=Nu8PMyX64obvw5Muh2vzug)

1. Data collection
    

With a focus on the customer rather then the product, we can see that VSM focuses how long the product will take to reach the customer after a change and how the customer will react to it (ignoring the benefits it might have on the business itself). Customer journey data collection however, focuses on how fast and how much of your product will the customer by and how enjoyable the buyign experience will be for them. 

  

2. Internal vs external
    

Value streams are internal processes within a business, whereas customer journeys are external experiences from the customer’s perspective.

  

3. Interconnectedness
    

While being seperated in principle, the two concepts are still fairly connected in their end goal. 

Let’s take an example of taking out a loan: 

Mapping and Connecting:

  

By understanding and mapping out both customer journeys and the value streams that enable them, businesses can see how each part of their operation contributes to the overall customer experience.

This holistic view allows for identifying areas of improvement across the entire system, enhancing both customer satisfaction and business outcomes.

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXf0N9s0avrQDNPHQMglRp3SSlAshodaApg3WcwdUagL0iHLt6rQKcCQb--2as4Ja2BsK1woKV9EhkTAd7fekmQ7lfTnZc04gZ-6QRlUCw-ttzyYm52XrH1F1pGDYfhCtAqX3rgDdx_6JdrMUlM_FqDBkZKj?key=Nu8PMyX64obvw5Muh2vzug)

[A customer journey enabled by value streams](https://www.vsmconsortium.org/blog/is-a-customer-journey-a-value-stream)

Improvement:

  

Once you have mapped the customer journeys and the corresponding value streams, you can start optimizing each touchpoint and process. For example, if the qualification process is slow, the Qualification Stream can be examined and refined.

Enhancing one part of the value stream can have a positive ripple effect on the entire customer journey, leading to better service delivery and increased customer satisfaction.

  

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXfhC5EKFAwjzeuMxrHKA7D1LmWismsEvlCRHr0isgFKpxG-9nH3q2zV6JgDig5G26i9z4uTUJWbYMQbyMfS2a_P8EnIvrTeRrRftELxHdHHqW3epoIAXURhpnZhXYbn4QERTBr1M4YLvHOyJSAjuBSkuIQ?key=Nu8PMyX64obvw5Muh2vzug)

 A customer journey enabled by a single stream, supported by enabling value streams and platform capabilities

  

At this point it is fairly straightforward to assume that value stream is the backbone delivering the experiences that make up customer journeys. Understanding the interconnectedness of these elements allows businesses to create seamless, efficient, and satisfying customer experiences.

#  Roadmap for the integration of value streams in digital banking
    

Taking customer value beyond cutomer journey 

Give hints 

Projection of maturity levels for banking 

Project management office PMO we should care abo r the renovation of the product not the building (E Branch)

Focus on the digital product 

Moyen - how to develop and techno - defective lmk channel and customer oriented 

Look at it from ppt

  

## [Value stream for banking](https://www.atlassian.com/blog/enterprise/accenture-vsm-banking#:~:text=Value%20stream%20management%20optimizes%20customer%20experience%20and%20digital%20innovation)

In modern omnichannel banking, focus on the customer journey is not the issue since many already either did or are on their way to applying it to their culture. The actual challenge however is how to embed it  it into the operating structure of the organization. In today’s competitive banking environment. This comes to say that focusing solely on the customer journey with no regards to the infrastructure that makes it as well as digitilization possibl can lead to fewer customers and lower profits. 

It is in this context that  banks can stay ahead of competitors by accelerating their enterprise agility journey and adopting value stream management (VSM) practices.

  

### History of customer value in banking 

To understand the necessity of VSM one must look at its history in the banking system.

  

Relationships between customers and banks was face to face:  In the past, customers would walk into a local branch and friendly employees would help them with current needs and future plans making customer satisfaction seen hands on through the customers. 

  

However, after the digital revolution,  those relationships have been replaced by automated processes creating a lack in the evaluation metrics pushing banks to often fall short when it comes to meeting customer expectations. 

  

This happens for three main reasons: 

- Scale and reach have increased, but achieving the goals of customer personalization and impact is infrequent and distributed.
    
- Competing priorities and numerous tasks hinder banks from delivering customer value, including:
    

- Economic uncertainty
    
- Changing interest rates
    
- Regulatory risk management
    
- Siloed product lines
    
- Technical debt from legacy systems
    

- Legacy systems pose significant challenges.
    

- Existing systems and infrastructures are outdated and lag behind the speed of innovation.
    
- Legacy systems are inadequate for current app, API, and security features, and for processing data for cross-selling.
    
- Successful digital transformation requires addressing technical debt to avoid system instability and enable rapid change.
    

  

Thus banks should prioritize customer value in their software planning and development, while being innovative and responsive to surpass customer expectations. They also need to identify end-to-end value streams for software development. In this sense, digital and agile transformations offer a competitive edge for banks in achieving this.

  

Today, according to a [Broadcam’s global report](https://www.software.broadcom.com/hubfs/ValueOps%20Maturity/Global-Report-on-VSM-Maturity-WP_BC-VO-2023_CE-3936_v16.pdf)  conducted over 500 professionals and executives who have responsibilities related to Value Stream Management (VSM) and digital transformation in their organizations, we can see that many are still in the early stages. More than half (60%) of respondents are still in the early phases of adoption, with 13% in planning, 25% with a pilot project, and 23% running VSM on a single product. Only about 2% use VSM on all products, representing the top tiers of VSM maturity.

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXd_dNQbPGuGD_LT-D5oMkL1SR0PYEPC2b-n5VZFU1zcYLCEIR-rCEEMBz5WCU0ik_8lr5v4-XRwS6b-N4BmyXS69ffAuTWIpR7wZ8SkfEx9-xEuXRiAnFGUVh-xwaw2MG2Zwm7YHrfPZQW5WRMKSur7fXGD?key=Nu8PMyX64obvw5Muh2vzug)

The survery also indicates a lack of visibility, as more than two-thirds say their visibility isn’t what it could or should be. 42% indicate their visibility is “OK,” and 21% characterize it as either poor or a complete “black hole.” Accordingly, insights are not being provided in real time. Currently, more than two-thirds (69%) of respondents share VSM metrics quarterly or monthly with only 9% indicating this data is being made available continuously. Tooling is also an issue. When surveyed on tools employed, Excel spreadsheets were the most common answer, with 50% of respondents continually relying upon them. And despite their effectiveness, other more specialized tools are required when aiming for a higher maturity level.

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXfUQXmQ8VwW0A2dWGUIC14O9X3ISnrW932JKpLTRSLPDPu2fjyb1hrIYegBchioDhXZSLzTajP-QWUYwaNxkqYcf9xPqOu8vnhCbtcAwfWHId81ozqHSKoWZZdbNsiNmBwO8ytI08jevoaajURMprxk4-cJ?key=Nu8PMyX64obvw5Muh2vzug)

  
Evaluation is also not being properly handled. 11% of companies don’t give employees business metrics to achieve or measure products by. 63% indicated they have metrics but that those are not mapped to individual product performance. Thus, the findings suggest that almost three-quarters of companies are missing the opportunity to have everyone aligned and focused on key objectives. 

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXfvYXh-r8-E6I0ibPL9IzGBmNltsHA7JG7iJJQRS9d3alTYFlIbqpvkTqJkpaMpCao3LCTMJVsQ7NNVwzPz438AQOsmOI35ifmELzplLU9SdtzFL5SnG6BE3mlC8IDbDI0ED_y_wvepLBKOgMJkhWNsL-hK?key=Nu8PMyX64obvw5Muh2vzug)

With all of this in mind, it would not come as a surprise that decision-making remains centralized. For most respondents, 85%, decisions are either made at the leadership level or teams need leadership approval before implementing their decisions. Currently, only 6% say decisions are made and implemented at the team level, which is a hallmark of many of the most advanced VSM implementations.

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXfN5oq4xg4toq3r2ZCCtB9mGwYM8YcAFWzyZMs8hMTis4MTjPnFyjGeIucqZmJoOajlawROq5mvkVhm9zK7WZIXLCbexlwN6LkmES505nTxXBWBq8C5G5xXcbh8_JBCuvYrR6X1DCLS40EvsY_lza0xXX7D?key=Nu8PMyX64obvw5Muh2vzug)

  

## How can banks ascend through the maturity levels of VSM

### Level 1: Foundational

Objective: Establish a basic understanding and initiate digital transformation efforts.

  

Understanding Current State:

  

Conduct workshops and training sessions to educate teams on value stream concepts.

Map out existing product/service delivery processes to identify gaps and inefficiencies.

Desire for Improvement:

  

Formulate a digital transformation strategy aligning with organizational goals.

Identify and prioritize key areas for improvement.

Operational Silos:

  

Implement regular cross-functional meetings to encourage communication.

Use collaboration tools like Slack or Microsoft Teams to facilitate team interactions.

Limited Data Use:

  

Start collecting basic metrics and KPIs related to product/service delivery.

Use simple analytics tools (e.g., Google Analytics, basic Excel dashboards) for initial data insights.

Risk of Inefficiencies:

  

Document current decision-making processes to highlight inefficiencies.

Introduce basic project management tools like Trello or Asana to improve task tracking and accountability.

  

Customer-Centric Approach: Focus on understanding customer journeys and organizing around them.

Digital Adoption: Emphasize the need for digital channels to meet modern customer expectations.

  

### Level 2: Value Stream Aware

Objective: Develop a deeper understanding and begin implementing VSM concepts.

  

Growing Understanding:

  

Conduct detailed value stream mapping workshops.

Create value stream maps for critical processes to visualize workflows.

Early VSM Adoption:

  

Identify pilot projects to test value stream mapping and continuous improvement concepts.

Establish a VSM team or task force to oversee these initiatives.

Pilot Initiatives:

  

Implement pilot projects focusing on specific areas such as customer onboarding or loan processing.

Gather feedback from pilot projects to refine processes.

Metrics Collection:

  

Start collecting detailed metrics (cycle time, lead time, process efficiency).

Implement more advanced analytics tools like Tableau or Power BI.

Mitigating Inefficiencies:

  

Develop and execute plans to address identified inefficiencies from pilot projects.

Focus on building a solid technological infrastructure (cloud services, integrated CRMs).

Focus on Infrastructure:

  

Invest in scalable technology infrastructure (e.g., cloud platforms like AWS, Azure).

Align IT and business strategies to ensure infrastructure supports improvement efforts.

  

Customer Insights: Use initial data to gather insights into customer behavior and preferences.

Agile Methodologies: Start incorporating agile methodologies for quicker iterations and feedback.

  

### Level 3: Collaborative

Objective: Enhance alignment, collaboration, and established practices.

  

Alignment and Collaboration:

  

Foster a culture of continuous improvement through regular training and communication.

Implement collaboration platforms that integrate with existing tools (e.g., Jira, Confluence).

Focus on Efficiency:

  

Streamline operations by refining and optimizing value stream maps.

Use process automation tools (e.g., RPA) to reduce manual tasks.

Established Practices:

  

Develop organizational standards and best practices for value stream management.

Implement governance frameworks to ensure consistent application of VSM practices.

Breaking Down Silos:

  

Create cross-functional teams for key projects to promote collaboration.

Implement shared goals and KPIs to align incentives across teams.

Active Participation:

  

Ensure technology teams are integral to infrastructure and process updates.

Promote ownership and accountability through transparent communication and shared responsibilities.

  

End-to-End Redesign: Prioritize end-to-end process redesigns to improve customer experience.

Cross-Functional Teams: Form cross-functional teams to focus on customer journey enhancements.

  

### Level 4: Data-Driven

Objective: Achieve robust data-driven decision-making and high data maturity.

  

Data-Driven Decision Making:

  

Develop a data strategy that aligns with business objectives.

Train teams on the importance and use of data in decision-making.

High Data Maturity:

  

Implement advanced data analytics and machine learning tools (e.g., Python, R, AWS ML services).

Foster a data-centric culture through regular training and workshops.

Integrated Data Flow:

  

Ensure seamless data integration across tools and platforms (e.g., using ETL tools like Talend, Informatica).

Develop APIs for real-time data exchange between systems.

Real-Time Dashboards:

  

Implement real-time monitoring and dashboards (e.g., using Power BI, Tableau, Grafana).

Provide stakeholders with real-time insights to enable quick decision-making.

Strategic Insights:

  

Use data analytics to inform strategic decisions and identify new opportunities.

Regularly review and update strategies based on data insights.

Automated Reporting:

  

Implement automated reporting tools (e.g., Power Automate, Alteryx).

Reduce manual reporting by leveraging workflow-derived data.

Advanced Analytics: Leverage advanced analytics to derive actionable insights from customer data.

Real-Time Data: Utilize real-time data to personalize and improve customer interactions.

  

### Level 5: Full Transparency and Flow

Objective: Achieve full transparency and seamless flow across all value streams.

  

Full Transparency:

  

Develop comprehensive dashboards that provide visibility into all value streams.

Ensure transparency in processes, decisions, and performance metrics.

Seamless Flow:

  

Optimize processes to achieve seamless flow and minimal bottlenecks.

Implement continuous improvement methodologies (e.g., Lean, Six Sigma).

Continuous Feedback Loops:

  

Establish continuous feedback mechanisms to gather insights from all stakeholders.

Use feedback to drive iterative improvements.

Integrated Ecosystem:

  

Develop an integrated ecosystem of tools and platforms that support end-to-end value streams.

Ensure interoperability and seamless data flow across the ecosystem.

Sustainable Practices:

  

Implement sustainable practices to ensure long-term value stream efficiency.

Regularly review and update practices to adapt to changing business environments.

  

Seamless Experience: Ensure a seamless and consistent experience across all digital and physical channels.

Continuous Innovation: Foster a culture of continuous innovation and improvement focused on customer value.

  

# Example for the value stream roadmap application 
    


A catalogue of main customer value stream in banks (internal and external) 

Whenever there es a prosecutorial there’s a value stream quote 

Loan

Onboarding 

Billpayement / card management 


### [List Possible Banking Value Streams](https://www.capstera.com/product/bank-value-streams/)

1. Account Opening
2. Account Closure
3. Loan Underwriting and Risk Assessment
4. Mortgage Foreclosure
5. Loan Origination
6. Loan Term Modification
7. Loan Payment Processing
8. Check Processing
9. Customer Service
10. Fraud Detection and Prevention
11. ATM Management
12. Credit Card Processing
13. Wire Transfers
14. Savings and Investment Products
15. Online and Mobile Banking
16. Wealth Management
17. Anti-Money Laundering (AML) Compliance
18. Risk Management
19. Treasury and Cash Management
20. Merchant Services
21. Corporate Banking
22. Intemational Banking
23. Regulatory Compliance
24. Collections and Recovery
25. Data Analytics and Business Intelligence
26. Vendor Management
27. Financial Reporting and Accounting
28. Branch Operations
29. Document and Content Management
30. Product Development and Innovation

### [Value Stream Mapping for a Bank Loan Process](https://www.hcltech.com/blogs/value-stream-management-in-action-banking-on-transformation)

Before VSM Implementation:

Value can be seen in terms of ease of obtaining a loan, customer satisfaction, process duration, simplicity, and overall ease of the process.

1. Customer Application:
    

- Customers submit loan applications through various channels (branch, online, phone).
    
- Manual data entry into different systems.
    

3. Initial Review:
    

- Loan officers manually review applications.
    
- Communication between departments (e.g., risk, underwriting) is siloed.
    
- Delays due to manual handoffs.
    

5. Credit Check:
    

- Separate systems for credit checks.
    
- Manual entry and retrieval of credit reports.
    

7. Loan Underwriting:
    

- Underwriters manually assess applications using different criteria.
    
- Lack of standardized decision-making tools.
    

9. Approval/Rejection:
    

- Manual approval processes with limited automation.
    
- Customers notified via separate channels (mail, email, phone).
    

11. Disbursement:
    

- Manual fund transfer processes.
    
- Inconsistent communication with customers.
    





Components of value stream 

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXfRo3RDMjM4ktZGGmeMPFvEjc1uzNSHn4irvp0SfmibyRCQVR8hA_IuQBK19QGaWc11RB8pbOPj1__4WPq__rwOUq5NBIWvCiGMLmgEzTAECjci0kmwqg_4HWU_SH_hXKDKW_RuhjdwFViFkzvs82S03DH4?key=Nu8PMyX64obvw5Muh2vzug)

Analysis phase

1- Issue Identification: The bank notices its customer satisfaction (CSAT) scores for loan processing are below the industry average.

2- Value Stream Management (VSM)

- The bank must identify the possible value streams that they aim to target 
    
- Value Stream Mapping: A visual representation of systems, processes, and people involved is created.
    
- Identify Areas of Improvement: Issues are identified, such as lengthy application forms, outdated data processing tools, and cumbersome data points for loan authorization.
    

  

After VSM Implementation:

1. Customer Application:
    

- Unified digital platform for loan applications.
    
- Automated data entry and integration with CRM.
    

3. Initial Review:
    

- Automated pre-screening of applications.
    
- Integrated communication platform for real-time collaboration.
    

5. Credit Check:
    

- Automated credit checks with integrated credit bureau APIs.
    
- Real-time retrieval and analysis of credit reports.
    

7. Loan Underwriting:
    

- Standardized underwriting criteria using automated decision tools.
    
- Integration with risk assessment models.
    

9. Approval/Rejection:
    

- Automated approval processes with predefined criteria.
    
- Instant notifications to customers via their preferred channels.
    

11. Disbursement:
    

- Automated fund transfer with integrated banking systems.
    
- Consistent and automated communication with customers.
    

Continuous monitoring 

- Once implemented, the bank must monitor the changes and actively assess their effectiveness on customer satisfaction 
    

#### Analysis

Efficiency Improvements:

6. Time Reduction: Automated data entry, credit checks, and underwriting significantly reduce processing times.
    
7. Error Reduction: Automation minimizes manual errors, leading to more accurate data handling.
    
8. Customer Experience: Unified platforms and instant notifications enhance customer satisfaction and transparency.
    
9. Collaboration: Integrated communication tools break down silos, fostering better collaboration across departments.
    
10. Scalability: Standardized and automated processes enable the bank to handle increased volumes efficiently.
    

  

”In this example, a bank could improve efficiency, reduce costs, and provide a better customer experience by applying value stream management approach to its loan process. Ultimately, this could help the bank to remain competitive and attract more customers.”

  

### [Value stream mapping for customer onboarding](https://www.vsmconsortium.org/blog/is-onboarding-a-value-stream) 

The onboarding process encompasses the process of closing in new customers with the ultimate goal being to do it as quickly, efficiently and most importantly consistently as possible. 

VSM is important in this case for four main reasons:

- The customer is straightforward: whether it being a bank customer (external) or an employee (internal), the bank has a clear direction of who will be most impacted by the changes. 
    
- Importance of costs: since acquisition costs include onboarding costs, minimizing them is bound to improve margins. 
    
- Criticality of time and flow: the time it takes to onboard a customer is crucial in achieving customer satisfaction.
    
- Risk and service quality; making sure that the onboarding process is optimal is very important when investing in an acquisition. 
    

#### VSM for employee onboarding

Talking about the employee as a value stream is also quite crucial, as tehy can be seen as the internal customer of the bank. In fact, [“seeing them as a value stream provides end-to-end visibility of this flow of activities, from the arrival of the new hire to a successful integration after a few weeks or months.”](https://www.vsmconsortium.org/blog/is-onboarding-a-value-stream)

VSM consortium visualized the employee onboarding value stream map as follows: 

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXePrroLLVTSO3TwH6IfVdFIlQaylzqMZg95qXVTD26zKusaUQSJN8Zqkw_r5QA-oMnb60Z-rAc6R9rCnDL8zpZ0IdZ33iNLCsbJDr5NWq5nQyzCZIeqdOy_pW7eXNB8ENJ4L61sAvOE_Mc11m7_-EDGxbig?key=Nu8PMyX64obvw5Muh2vzug)

In today's industry, where knowledge workers operate in loosely coupled teams with autonomy, value streams can be applied at any level—from strategic visions to operational tasks. They help communicate how outcomes are achieved and identify the teams and actions involved.

  

#### VSM for external customer onboarding 

### Before VSM Implementation

#### 1. Customer Application:

- Channels: Customers apply for loans through multiple channels (in-person, online, phone).
    
- Data Entry: Information is manually entered into different systems.
    
- Delays: Manual data entry and siloed systems lead to delays.
    

#### 2. Initial Review:

- Manual Review: Loan officers manually review applications.
    
- Siloed Communication: Different departments (risk, underwriting) work in isolation, causing delays.
    

#### 3. Credit Check:

- Separate Systems: Credit checks are done using separate, non-integrated systems.
    
- Manual Processes: Credit reports are manually retrieved and entered into the system.
    

#### 4. Loan Underwriting:

- Manual Assessment: Underwriters use varied criteria without standardized tools.
    
- Inconsistencies: Lack of standardized decision-making leads to inconsistencies.
    

#### 5. Approval/Rejection:

- Manual Approval: The approval process is manual with little automation.
    
- Delayed Notifications: Customers are notified via mail, email, or phone, causing delays.
    

#### 6. Disbursement:

- Manual Fund Transfer: The process for transferring funds is manual.
    
- Inconsistent Communication: Communication with customers about disbursement is inconsistent.
    

### After VSM Implementation

#### 1. Customer Application:

- Unified Platform: A single digital platform is used for all loan applications.
    
- Automated Entry: Data entry is automated and integrated with the Customer Relationship Management (CRM) system.
    

#### 2. Initial Review:

- Automated Pre-Screening: Applications are pre-screened automatically.
    
- Integrated Communication: Real-time collaboration is enabled through an integrated platform.
    

#### 3. Credit Check:

- Automated Process: Credit checks are automated with integrated APIs from credit bureaus.
    
- Real-Time Analysis: Credit reports are retrieved and analyzed in real-time.
    

#### 4. Loan Underwriting:

- Standardized Tools: Underwriting uses standardized criteria with automated decision tools.
    
- Risk Integration: Integration with risk assessment models ensures consistency.
    

#### 5. Approval/Rejection:

- Automated Approval: Approval processes are automated with predefined criteria.
    
- Instant Notifications: Customers receive instant notifications through their preferred channels (SMS, email, app).
    

#### 6. Disbursement:

- Automated Transfers: Funds are transferred automatically with integrated banking systems.
    
- Consistent Communication: Customers receive consistent, automated updates throughout the process.
    

### Continuous Monitoring and Analysis

- Efficiency Improvements:
    

- Time Reduction: Automation of data entry, credit checks, and underwriting reduces processing times.
    
- Error Reduction: Automation decreases manual errors, improving accuracy.
    

- Customer Experience:
    

- Enhanced Satisfaction: Unified platforms and instant notifications improve customer satisfaction and transparency.
    

- Collaboration:
    

- Breaking Silos: Integrated tools enhance communication and collaboration across departments.
    

- Scalability:
    

- Increased Capacity: Standardized and automated processes allow the bank to handle higher volumes efficiently.
    

Monitoring: The bank should continuously monitor the new system, assessing its impact on customer satisfaction (CSAT) and making iterative improvements as necessary.

  
  
  

11. # Annex 
    

- Assembly line
    
- Flow 
    
- Henry Ford
    
- Model T 
    
- Taiichi Ohno
    
- Toyota production system
    
- product family
    

**