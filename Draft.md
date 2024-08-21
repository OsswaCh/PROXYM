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
    

 



#### [Added Value of VSM](https://www.dozuki.com/blog/why-do-value-stream-mapping-benefits-examples#:~:text=Value%20stream%20mapping%2C%20or%20VSM,process%20for%20the%20customer's%20benefit.)

Adopting value stream oriented practices is bound to have a lot of benefits on both the company and the customer: 
[**Added value for the customer**:]([www.atlassian.com](https://www.atlassian.com/agile/value-stream-management))
* **Increased customer satisfaction**: by enhancing the value stream, companies become more capable of quickly responding to customer requests and allows for more improvements of the customer experience 
* **Higher quality products and services**: eliminating waste and inefficiencies leads to higher quality outputs  
* **Faster delivery**: Streamlining processes reduces delays and bottlenecks, ensuring that products and services are delivered to customers more quickly 
* **Better predictability**:  With a clear understanding of the value stream, organizations can reduce uncertainties and surprises, leading to more reliable delivery timelines
* **Enhanced visibility**: Value stream management provides end-to-end visibility of processes, making it easier to track progress and address issues promptly.
* **Cost reduction**: By eliminating waste and improving efficiency, organizations can reduce costs, which can be passed on to customers in the form of lower prices or better value. 
* Continuous improvement: Engaging all stakeholders in collaborative improvement efforts ensures that the organization continuously evolves to meet customer needs more effectively.




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

The Toyota team then  came to create the concept of value stream mapping where for each product family* they detailed every step of the creation of either the entire product on its indivisual components. 

The mapping then goes as follows: we have the raw elements that will eventually make their way to the customer in a different form: final product. Identify the individual steps of that process in each one of them, and then start your classification: which of these steps are waste and which are value that the customer would be willing to finance. 

These constitute the physical steps, along sides of them we have the [information flow](https://www.lean.org/lexicon-terms/information-flow/)* that goes on the top of the map. In simple terms, information flow is how information moves within a company to ensure products are made efficiently and meet customer demands. In the Toyota system, a central scheduling point where production plans are made is scheduled,  that uses "pull loops" of information. They signal upstream to earlier production points about what is needed, and downstream to later points about what has been produced. These points helps synchronize production closely with customer demand, reducing waste and improving efficiency. This information flow contrast to traditional mass production information flow where forecasts, schedules, and shipping orders go back and forth between different parts of the company and its facilities creating a lot of chaos and disorganization. 

  

### Lean Thinking and global adoption 
    

In the 1990s James Womack and Daniel Jones popularized “Lean thinking” setting the building blocks for the Lean Enterprise Institute. They highlighted VSM as a key technique for identifying value-added and non-value-added activities popularizing even more among diffirent businesses. Today, Organizations worldwide embraced lean principles, including VSM, to streamline processes and enhance efficiency.


### Today


- **Lean and Agile Integration**: Value Stream Mapping has increasingly been integrated into Agile frameworks, especially with the rise of the Scaled Agile Framework (SAFe). In SAFe, VSM is crucial for identifying and optimizing value streams, which are central to delivering continuous value to customers. SAFe defines both _operational_ and _development_ value streams, and VSM helps organizations map these streams to reduce bottlenecks, improve flow, and align organizational strategies with customer needs.
    
- **Digital Transformation**: VSM has also been adapted for software and IT environments, moving beyond its manufacturing roots. In DevOps, for example, VSM helps teams visualize and optimize the flow of code from development to deployment, ensuring faster and more reliable delivery. Tools like Tasktop, Plutora, and ServiceNow have incorporated VSM to support continuous delivery and enterprise agility.
    
- **Healthcare**: The adoption of VSM in healthcare has grown, focusing on improving patient care processes and reducing waste in hospitals and clinics. VSM is applied in areas like patient flow, supply chain management, and administrative processes, leading to more efficient and patient-centered care.
    
- **Hybrid and Remote Workflows**: As organizations shift to hybrid and remote work models, digital VSM tools like Lucidchart, Miro, and LeanIX have gained popularity. These tools facilitate virtual collaboration, enabling distributed teams to create, share, and analyze value streams in real-time.
  ![[Timeline Infographic.jpg]]



  

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

## Value stream vs internal value chain
    

Value streams are usually visualized from the stakeholder’s viewpoint. And at this point we come the make the distinction between value streams and internal value chains. While value streams focus on how the value is achieved for the end customer, internal value chain describes the series of activities within an organization that add value to a product or service. In other terms  The value chain focuses on identifying the specific activities that add value to the organization’s products or services and seeks to optimize these activities to gain a competitive advantage. 

Thus, the main difference is that while the value chain focuses on internal processes and how they add value within the organization, while value streams encompass the entire flow of activities needed to deliver value to the customer, often crossing organizational boundaries. And in terms of objective, value chains are aimed at identifing and optimizing the internal activities for competitive advantage while value streams take a more holistic view aiming at improving the overall flow of value to the customer by eliminating waste and increasing efficiency.

## Best practices for value stream management 
### [The Value Stream Management Maturity Model](https://www.software.broadcom.com/hubfs/ValueOps%20Maturity/vsm-maturity-model-WP_BC-VO-2023_CE-3887_v16.pdf)

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

  
  
  

### [Bad practices when adopting VSM](https://www.linkedin.com/pulse/important-ways-we-fail-learn-from-toyota-david-verble/)
     

When observing how some companies try to adopt lean practices and specifically VSM, one can easily identify the reasons why they are struggling to make their experiences successful. Among these points of failure we can name: 

- Misconceptions about VSM: a lot of companies treat VSM as a mere visual artifcat rather than utilising for its initial purpose which is performance improvement. Consequently a lot of them fall into the trap of simply making the “current state map” and fail to update or integrate them with Future State designs, missing the point of continuous improvement. 
    
- Focusing solely on risk reduction: focusing solely on reducing waste without addressing underlying workflow issues (instability, variation, overburden) can worsen customer delivery and cause waste to reappear elsewhere. One must acknowledge the fact that barriers to smooth flow (e.g., scheduling, information flow) are often more critical than isolated instances of waste.
    
-  Not following Toyota’s management approach for VSM: managers aught to use VSM to identify barriers to flow and quality, then create annual plans aligned with strategic priorities (hoshin). Teams systematically address these barriers through continuous problem solving. For more concrete examples of how this can be done,  Weekly activities like Jushiken bring together teams to map flows, balance operations, conduct experiments, and redesign processes to tackle significant workflow issues.
    
- Lean Thinking vs. Doing Lean: implementing the lean tools (like VSM for instance)  true lean transformation requires adopting lean thinking. This means that a change of mentality is crucial to radically solve the problems that VSM tries to touch. 


## Conclusion 
Value streams are the new direction for businesses and manufactures that allows them to increase productivity, reduce waste and most importantly ensure customer satisfaction. 
This work methodology peaked especially during the technological boom of enterprises as it was recommended by entities such as SAFe and Lean Enterprise institute. This goes to say that value streams aim at ensuring a maximum customer satisfaction through an efficient integration of efficient analysis tools within the processes. 
This fluid nature allowed it to easily make its way to the a variety of different fields. We saw together how it started in car manufacturing companies, and made its way to the health as well as multiple B2B and B2C ones. But along side them, we particularly saw a major rise in its adaptation within the [tech industry and digital product delivery](https://www.vsmconsortium.org/blog/the-evolution-of-value-stream-management-and-the-digital-twin). It bridges the gap between management and production allowing for better execution and better integration of agile methodologies.    


# The historical development of banking channels toward omnichannel

![[white-background-designify.png]]
## Transactional era 
    

Historically, banks revolved mainly around transactions. Customers visited physical branches for routine tasks like deposits and withdrawals. Operations were fairely simple as a bank had to only manage its internal affairs withing the one or multiple branches they had. All documentation and processes were handled manually. 


## Multichannel Approach
    

As technology advanced, and specifically during the technological boom,banks introduced additional channels: ATMs, call centers, and online banking. However important these advances might’ve been, they were still not enough. The channels operated independently making the user experience very inconsistent as history did not follow across channels due to a lack of integration between them. 

  

## Bidirectional Omnichannel 

In the 2010s, there was a common consensus for the need to unify the fronts of banks. In other words we marked the emergence of omnichannel banking to integrated a seemless user experience.
### Unidirectional omnichannel banking 

Unidirectional omnichannel banking refers to a system where information flows in one direction—from the bank to the customer. This approach primarily focuses on providing consistent information and services across various channels (e.g., online banking, mobile apps, ATMs) without much interaction or feedback from the customer. 
Some of its characteristics include : 
- **consistent communication**: Ensuring that customers receive the same information regardless of the channel they use. 
- **Channel-Specific Services**: Each channel operates independently, offering specific services tailored to that medium.
- **Limited Interaction**: Minimal customer feedback or interaction is integrated into the system.
### Bidirectional omnichannel banking

Bidirectional omnichannel banking, on the other hand, involves a two-way flow of information between the bank and the customer. This approach emphasizes interaction, feedback, and a seamless experience across all channels. In other words, this new approach is meant to emphasize the importance of the internal customer of the bank, i.e. the employee. By recognizing that the experience of the internal employee is indispensable in ensure customer satisfaction, banks can achieve maximum efficiency. 
It focuses on the following characteristics: 
- **Integrated Channels**: All channels are interconnected, allowing customers to start a transaction on one channel and complete it on another.
- **Personalized Experience**: Customer data and feedback are used to tailor services and offers, enhancing the overall experience.
- **Real-Time Interaction**: Customers can interact with the bank in real-time, providing feedback and receiving immediate responses.
  

### Customer centricity 
    

Adapting an omnichannel approach meant an inevitable switch towards customer focused banking. And slowly we witnessed the immergence of customer journeys. This manifests in the following aspects: 

- **Customer-Centric Approach (internal and external):**
	    
	- Understanding needs, preferences, and pain points.
	- Mapping end-to-end journeys (e.g., account opening, loan application).
	- Identifying touchpoints and addressing friction

- **Seamless Experiences:**
	
	- Customers whether internal or external seamlessly switch channels.	    
	- Contextual information transfers.
	- Personalized recommendations based on behavior.
    

- **Implementing technology enablers: 

	- [**APIs**:]([Omnichannel Banking: How to Implement It Properly (techmagic.co)](https://www.techmagic.co/blog/omnichannel-banking/)) APIs allow seamless integration between various banking channels (e.g., online banking, mobile apps, ATMs), providing a consistent and smooth experience. *External customers* can access their accounts and perform transactions effortlessly across different platforms. For *internal customer* on the other hand, APIs facilitate better communication and data sharing between different departments and systems within the bank, improving operational efficiency and enabling staff to provide quicker and more accurate service to customers.

	- **[Mobile Apps]([Omnichannel Banking: How to Implement It Properly (techmagic.co)](https://www.techmagic.co/blog/omnichannel-banking/))**:  serve as a convenient, central hub for all banking activities, allowing customers to manage their accounts, make payments, and access services anytime, anywhere. This enhances customer satisfaction by providing flexibility and ease of use. Employee oriented mobile apps can also be use to perform tasks on the go like scheduling meetings, internal communications and special inquiries.  

	- **Data Analytics**: by making use of big data, banks will be able to oversee and even predict customer behavior and preferences enabling them to make more personalized adds or helping them in the choice of creating, continuing or discontinuing a product.[ This approach can increase customer satisfaction and loyalty on the shirt and log run.]([Omnichannel Banking: How to Implement It Properly (techmagic.co)](https://www.techmagic.co/blog/omnichannel-banking/))This being said we can see that using big data will also allow employees to make tailored decisions to optimize the marketing strategy  and identify opportunities for cross-selling and upselling, ultimately driving business growth.   	    

	- **Chatbots and AI**:  Chatbots will allow customers to have 24/7 customer support across different channels reducing wait times and improving the overall customer experience. [They can also help reduce customer churn by proactively addressing issues and providing personalized recommendations.  ]([Unlocking the power of chatbots: Key benefits for businesses and customers - IBM Blog](https://www.ibm.com/blog/unlocking-the-power-of-chatbots-key-benefits-for-businesses-and-customers/))These Tools can also help employees whether it being by pattern recognition alert, or by handling routine inquiries and tasks, allowing employees [to be redirected towards solving more complex issues.]([Unlocking the power of chatbots: Key benefits for businesses and customers - IBM Blog](https://www.ibm.com/blog/unlocking-the-power-of-chatbots-key-benefits-for-businesses-and-customers/))
  

### Potential challenges

- **Data integration**: integrating data from various channels is starting to inevitably present itself as a big issue for banks aiming at becoming omnichanneled

- **Resource constraints**:  A technological shift of this level is very resource demanding. And in the light of lack of resources and investment can hinder the successful implementation of an omnichannel strategy.

* **Siloed Organizational Structure**: The current structure of many banks consists of having many departments working in silos which can lead to poor communication and coordination, affecting the customer experience.

* Legacy systems: Outdated legacy systems can be difficult to integrate with new digital platforms.

* **Customer data security**:  Ensuring the security of customer data across multiple channels is a significant challenge.

- **Regulatory Compliance**: Navigating complex regulatory banking requirements across different channels can be challenging.

-  **Inconsistent Customer Experience**: synchronizing multiple channels and maintaining a consistent and secure data flow between them is difficult. 

  
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

### [Customer journey maps ](https://www.salesforce.com/products/marketing-cloud/best-practices/customer-journeys/)

A customer journey map is a diagram that tracks all the interaction point between the customer and the product during the six stages of customer engagement. The map should be tailored to the business need as the different types of channels and target costumers affects the number of journey maps needed. This all aimed at ensuring maximum customization utilizing the collected customer data.  

**Identify your audience**
In order to create a meaningful journey we must first know who we are targeting and what their pain points are in order to put yourself in their shoes and actually understand their behaviors and needs. 
some of the questions that we need to ask include but are not limited to: 
- what demographic specifications unite our customers
- what do they want
- how they expect to receive it
- what disappoints them the most
- how are their choices about the purchase are being made


**Define the steps**

This step defines the usual development of a customer interaction with your company. 
[SalesForce](https://www.salesforce.com/products/marketing-cloud/best-practices/customer-journeys/)gives an example of how a typical customer progression looks like: 

>- Defining a need  
>- Searching for information online
>- Visiting a brand website
>- Exploring features and benefit
>- Comparing brands and prices
>- Making a purchase
>- Setting up/unboxing
>- Initial usage
>- Continuing usage
>- Troubleshooting
>- Needing to upgrade
>- Researching options for upgrade
>- Comparing brands and prices
>- Making a decision to stay or leave

**List your brand’s touchpoints** : This refers to the physical or digital locations where the customer interacts with your brand or product. This includes adds, stores, applications, platforms etc. 

**Identify the data you want to track** :specify what you want to know and how you want to collect it. 

**Think about your content**: Providing relevant content to your customers is the foundations of building a good relationship with them. We must look at the content we are currently providing analyze how well the customers consume it as well as how effective it is to keep the customers.  

**Choose your channels**: Based on the chosen analytics, choosing the appropriate platform for establishing touchpoints is fairly straightforward. This platform should be able to make "meaningful moments" with the customer as well have a great impact on their decisions. 


## Value streams Vs customer journeys, are they the same
    

As explained above, a value stream is the series of steps of the creation of a production from its ideation to the end of its production. [The VSM consortium illustrated it as follows](https://www.vsmconsortium.org/blog/is-a-customer-journey-a-value-stream): 

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXemng7_DzUnUaOhqfjwgSlSzDbMaEQ5ya_3EDKgJfehnR51Usv890eJIEMFk1MadtoGCVoJqlVSbby7EoJevVys173lzP0oUjMW-11tM7gChmjMsZ6Mr4QmJpNt65peLnPPJIyHj1ZqUHll2-NUfvKYbP_r?key=Nu8PMyX64obvw5Muh2vzug)

On the other hand a customer journey is how the customer gets in contact with the product and buys it. 

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXdYCt0S6dSwo9m_IZeotiAK7VOfiogbqJtuUDSavJlxJp5xehBBcT3kfb8DiSFE2kVYcznesHLzFq7qkHxY7tdAzt6OiojPsxhloshp8bRUM5Q6aynQpwWmyiSXa2T0Be449in3PqAkz1FVDpzn3ms3gQQX?key=Nu8PMyX64obvw5Muh2vzug)

1. Data collection
    

With a focus on the customer rather then the product, we can see that VSM focuses how long the product will take to reach the customer after a change and how the customer will react to it (ignoring the benefits it might have on the business itself). Customer journey data collection however, focuses on how fast and how much of your product will the customer by and how enjoyable the buying experience will be for them. 

  

2. Internal vs external
    

Value streams are internal processes within a business, whereas customer journeys are external experiences from the customer’s perspective.

  

3. Interconnectedness
    

While being separated in principle, the two concepts are still fairly connected in their end goal. 

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

>   
     “ Whenever there is a product for a customer, there is a value stream. The challenge lies in seeing it.” – Mike Rother and John Shook in ‘Learning to See: Value stream mapping to create value and eliminate muda’ (The Lean Enterprise Institute, 1999)


In modern omnichannel banking, focus on the customer journey is not the issue since many already either did or are on their way to applying it to their culture. The actual challenge however is how to embed it  it into the operating structure of the organization. In today’s competitive banking environment. This comes to say that focusing solely on the customer journey with no regards to the infrastructure that makes it as well as digitalization possible can lead to fewer customers and lower profits. 

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

  

# Examples for the value stream roadmap application 
    


A catalogue of main customer value stream in banks (internal and external) 

Whenever there es a prosecutorial there’s a value stream quote 

Loan

Onboarding 

Billpayement / card management 


### [List of Possible Banking Value Streams](https://www.capstera.com/product/bank-value-streams/)

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

Let's consider a value stream mapping (VSM) for a bank's loan processing system, focusing on the journey from when a customer applies for a loan to when the loan is approved and disbursed.

#### **Step 1: Define the Current State (Before)**

In the current state, the loan processing system may be inefficient, with delays and bottlenecks.

##### **Current State Value Stream Mapping**

1. **Loan Application Submission**:
    
    - **Trigger**: Customer submits a loan application online or in-branch.
    - **Process Time (PT)**: 30 minutes (filling out the application form).
    - **Lead Time (LT)**: 1 day (waiting for the application to be reviewed).
    - **Waste**: Manual data entry errors, incomplete applications requiring resubmission.
2. **Initial Review & Credit Check**:
    
    - **Trigger**: The loan officer receives the application and performs an initial review, including a credit check.
    - **PT**: 1 hour (reviewing the application, running a credit check).
    - **LT**: 2 days (waiting for the credit report).
    - **Waste**: Delays in receiving the credit report, redundant manual checks.
3. **Document Collection & Verification**:
    
    - **Trigger**: Customer submits supporting documents (e.g., income proof, ID).
    - **PT**: 2 hours (customer gathers and submits documents).
    - **LT**: 3 days (waiting for the document verification process).
    - **Waste**: Manual document checks, errors, and missing documents.
4. **Loan Underwriting**:
    
    - **Trigger**: The underwriter evaluates the application and supporting documents to assess risk.
    - **PT**: 3 hours (risk assessment and decision-making).
    - **LT**: 4 days (waiting for internal reviews and approvals).
    - **Waste**: Delays in communication between departments, manual risk assessment processes.
5. **Loan Approval & Documentation**:
    
    - **Trigger**: The loan is approved, and the customer is informed to sign the agreement.
    - **PT**: 1 hour (preparing and sending the loan agreement).
    - **LT**: 2 days (waiting for the customer to sign and return the agreement).
    - **Waste**: Delays in signing, manual processing of agreement documents.
6. **Loan Disbursement**:
    
    - **Trigger**: Upon receiving the signed agreement, the loan amount is disbursed.
    - **PT**: 30 minutes (processing the disbursement).
    - **LT**: 1 day (waiting for funds to be released).
    - **Waste**: Processing delays, potential errors in disbursement.

**Total Lead Time**: 13 days  
**Total Process Time**: 8 hours  
**Key Issues**: Delays due to manual processes, waiting times between steps, errors, and customer dissatisfaction.

![[loan1.png]]


####  **Step 2: Analyze and Identify Waste**

The current process has the following forms of waste:

- **Waiting**: Significant delays between each step, especially during credit checks, document verification, and underwriting.
- **Defects**: Errors in application submission and document verification leading to rework.
- **Overprocessing**: Manual reviews and redundant checks that could be automated.
- **Motion**: Excessive handling of documents and manual data entry.

![[Loan2.png]]


![[loan3.png]]
*example of problem solving depending on the identified issue*
#### **Step 3: Define the Future State (After)**

The future state aims to reduce lead time and process time by automating key steps, improving communication, and eliminating waste.

##### **Future State Value Stream Mapping**

1. **Loan Application Submission**:
    
    - **Trigger**: Customer submits a loan application through an optimized digital platform.
    - **PT**: 15 minutes (guided form with real-time validation).
    - **LT**: Immediate.
    - **Improvement**: Reduced errors, instant submission, and automated initial checks.
2. **Initial Review & Credit Check**:
    
    - **Trigger**: The system automatically performs an initial review and credit check.
    - **PT**: 10 minutes (automated credit check and application review).
    - **LT**: Immediate.
    - **Improvement**: Automated credit checks, real-time results, and faster initial review.
3. **Document Collection & Verification**:
    
    - **Trigger**: Customer uploads documents via a secure online portal with automated verification.
    - **PT**: 30 minutes (guided document upload with instant verification).
    - **LT**: 1 hour (automated document verification).
    - **Improvement**: Instant validation, reduced manual work, and faster processing.
4. **Loan Underwriting**:
    
    - **Trigger**: The underwriting process is initiated immediately after document verification.
    - **PT**: 1 hour (automated risk assessment using AI/ML models).
    - **LT**: 1 day (automated approvals with minimal manual intervention).
    - **Improvement**: Faster and more accurate risk assessment, reduced manual checks, and streamlined approval.
5. **Loan Approval & Documentation**:
    
    - **Trigger**: The loan is approved, and the customer signs the agreement digitally.
    - **PT**: 15 minutes (digital signing and immediate processing).
    - **LT**: Immediate.
    - **Improvement**: Instant digital signing, automated document processing, no delays in communication.
6. **Loan Disbursement**:
    
    - **Trigger**: The loan is disbursed automatically upon receiving the signed agreement.
    - **PT**: 15 minutes (automated disbursement process).
    - **LT**: Immediate.
    - **Improvement**: Instant disbursement, no waiting for fund release, reduced errors.

**Total Lead Time**: 1 day  
**Total Process Time**: 2 hours 25 minutes  
**Key Improvements**:

- **Reduction in lead time** from 13 days to 1 day.
- **Streamlined processes**: Automation reduces manual work, errors, and waiting times.
- **Customer experience**: Faster loan approval and disbursement, leading to higher satisfaction.  

”In this example, a bank could improve efficiency, reduce costs, and provide a better customer experience by applying value stream management approach to its loan process. Ultimately, this could help the bank to remain competitive and attract more customers.”

  ![[loan4.png]]

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

##### **Step 1: Define the Current State (Before)**

In the current state, the employee onboarding process may suffer from delays, inefficiencies, and miscommunication.

**Current State Value Stream Mapping**

1. **Job Offer Acceptance**:
    
    - **Trigger**: Candidate accepts the job offer.
    - **Process Time (PT)**: 20 minutes (offer letter signed and returned).
    - **Lead Time (LT)**: 1 day (HR processes acceptance).
    - **Waste**: Delays in HR communication and confirmation.
2. **Document Submission & Verification**:
    
    - **Trigger**: New hire submits required documents (e.g., ID, certifications).
    - **PT**: 30 minutes (employee gathers and submits documents).
    - **LT**: 2 days (waiting for HR to verify documents).
    - **Waste**: Delays due to manual verification, incomplete submissions.
3. **Background Check**:
    
    - **Trigger**: Initiation of background checks by HR.
    - **PT**: 1 hour (submitting information to the background check provider).
    - **LT**: 5 days (waiting for results).
    - **Waste**: Waiting time for third-party service.
4. **System Access Provisioning**:
    
    - **Trigger**: IT receives a request to set up system access for the new employee.
    - **PT**: 2 hours (setting up accounts, email, and access to necessary systems).
    - **LT**: 3 days (waiting for IT to process request and handle dependencies).
    - **Waste**: Delays in coordination between HR and IT, rework due to missing information.
5. **Workspace Setup**:
    
    - **Trigger**: Facilities are notified to prepare a workspace for the new employee.
    - **PT**: 1 hour (setting up desk, phone, and other equipment).
    - **LT**: 2 days (waiting for availability of resources).
    - **Waste**: Delays in resource allocation, potential double handling of equipment.
6. **Orientation & Training**:
    
    - **Trigger**: New employee attends orientation and initial training.
    - **PT**: 8 hours (full-day orientation session).
    - **LT**: 3 days (scheduling conflicts and coordination delays).
    - **Waste**: Inefficient scheduling, repetitive content, and waiting for trainers.
7. **Compliance & Policy Acknowledgment**:
    
    - **Trigger**: New employee reviews and acknowledges company policies and compliance documents.
    - **PT**: 1 hour (reading and signing documents).
    - **LT**: 1 day (waiting for all forms to be submitted and approved).
    - **Waste**: Manual tracking of acknowledgments, delays in submission.

**Total Lead Time**: 17 days  
**Total Process Time**: 13 hours 50 minutes  
**Key Issues**: Coordination delays, redundant processes, manual work, and a poor experience for new employees.

##### **Step 2: Analyze and Identify Waste**

The current process has several forms of waste:

- **Waiting**: Significant delays at each step, particularly in document verification, background checks, and IT provisioning.
- **Defects**: Errors in document submission and incomplete setup leading to rework.
- **Overprocessing**: Manual processes that could be automated.
- **Motion**: Excessive communication and coordination between departments.

##### **Step 3: Define the Future State (After)**

The future state aims to streamline the process through automation, better communication, and more efficient resource allocation.

##### **Future State Value Stream Mapping**

1. **Job Offer Acceptance**:
    
    - **Trigger**: Candidate accepts the job offer through an integrated HR platform.
    - **PT**: 10 minutes (digital signature and immediate processing).
    - **LT**: Immediate.
    - **Improvement**: Instantaneous confirmation, automated notifications to relevant departments.
2. **Document Submission & Verification**:
    
    - **Trigger**: New hire submits documents via an online portal with real-time validation.
    - **PT**: 15 minutes (guided submission with automated checks).
    - **LT**: 30 minutes (instant verification using automated tools).
    - **Improvement**: Eliminated errors and delays, faster document processing.
3. **Background Check**:
    
    - **Trigger**: Background check is initiated automatically upon document submission.
    - **PT**: 10 minutes (automated submission to third-party services).
    - **LT**: 2 days (expedited processing with selected vendors).
    - **Improvement**: Faster processing through preferred partnerships, reduced wait times.
4. **System Access Provisioning**:
    
    - **Trigger**: IT receives an automated request to set up access immediately after background check initiation.
    - **PT**: 30 minutes (automated account creation and access provisioning).
    - **LT**: 1 day (provisioning completed in parallel with other tasks).
    - **Improvement**: Automated access setup, simultaneous task processing, reduced lead time.
5. **Workspace Setup**:
    
    - **Trigger**: Workspace setup request is generated automatically upon job acceptance.
    - **PT**: 30 minutes (standardized setup process).
    - **LT**: 1 day (workspace ready before the employee's start date).
    - **Improvement**: Pre-arranged resources, efficient setup without delays.
6. **Orientation & Training**:
    
    - **Trigger**: Employee receives digital access to orientation materials and training schedule.
    - **PT**: 4 hours (blended learning with self-paced modules and live sessions).
    - **LT**: 1 day (flexible scheduling with immediate access).
    - **Improvement**: Streamlined, flexible orientation, reduced scheduling conflicts.
7. **Compliance & Policy Acknowledgment**:
    
    - **Trigger**: Automated prompts for policy review and acknowledgment via the HR platform.
    - **PT**: 30 minutes (digital review and acknowledgment).
    - **LT**: Immediate.
    - **Improvement**: Automated tracking and reminders, instant submission.

**Total Lead Time**: 5 days  
**Total Process Time**: 7 hours 55 minutes  
**Key Improvements**:

- **Reduction in lead time** from 17 days to 5 days.
- **Streamlined processes**: Automation reduces manual work, errors, and waiting times.
- **Employee experience**: Faster onboarding, better communication, and a smoother start.

#### VSM for external customer onboarding
This process starts from the moment a customer shows interest in the bank up until his full onboarding and beyond to ensure fidelity. 
##### **Step 1: Define the Current State (Before)**

In the current state, the customer onboarding process may be lengthy, with various bottlenecks and inefficiencies.

###### **Current State Value Stream Mapping**

1. **Customer Inquiry**:
    
    - **Trigger**: A potential customer expresses interest in opening an account (via online form, phone call, or in-branch visit).
    - **Process Time (PT)**: 10 minutes (initial inquiry handled by customer service).
    - **Lead Time (LT)**: 1 day (waiting for follow-up).
    - **Waste**: Potential customers often drop off due to delayed follow-up.
2. **Application Submission**:
    
    - **Trigger**: Customer submits the necessary forms and documents.
    - **PT**: 20 minutes (customer fills out forms, gathers documents).
    - **LT**: 2 days (waiting for document review).
    - **Waste**: Manual data entry, incorrect or missing information, and resubmission.
3. **Document Review & Identity Verification**:
    
    - **Trigger**: Bank staff reviews submitted documents and verifies identity.
    - **PT**: 1 hour (manual verification process).
    - **LT**: 3 days (waiting for verification completion).
    - **Waste**: Delays due to manual checks, errors, and the need for additional information.
4. **Account Setup**:
    
    - **Trigger**: Upon successful verification, the account is created in the system.
    - **PT**: 30 minutes (account setup and system entry).
    - **LT**: 1 day (waiting for system updates and approvals).
    - **Waste**: Waiting for approvals, system delays.
5. **Customer Notification**:
    
    - **Trigger**: Customer is notified that the account is active.
    - **PT**: 10 minutes (preparing and sending notification).
    - **LT**: 1 day (delayed due to manual processes).
    - **Waste**: Delays in communication.
6. **Customer Education**:
    
    - **Trigger**: Onboarding session or materials are provided to the customer.
    - **PT**: 1 hour (personal session, webinar, or material distribution).
    - **LT**: 3 days (waiting for the customer to schedule and attend the session).
    - **Waste**: Inefficient scheduling, delays in receiving materials.

**Total Lead Time**: 11 days  
**Total Process Time**: 3 hours 10 minutes  
**Key Issues**: High dropout rate, errors due to manual processes, long waiting times, and customer frustration.

##### **Step 2: Analyze and Identify Waste**

The current process includes several forms of waste:

- **Waiting**: Significant delays between each step, especially during document review and verification.
- **Defects**: Errors in application submission and document processing leading to rework.
- **Overprocessing**: Manual verification processes that could be automated.
- **Motion**: Excessive handling and movement of physical documents.

##### **Step 3: Define the Future State (After)**

The future state involves automating processes, improving customer communication, and reducing waste to streamline onboarding.

#### **Future State Value Stream Mapping**

1. **Customer Inquiry**:
    
    - **Trigger**: Customer expresses interest via an optimized digital platform with live chat support.
    - **PT**: 5 minutes (instant responses and guidance).
    - **LT**: Immediate.
    - **Improvement**: Reduced drop-off with immediate follow-up and engagement.
2. **Application Submission**:
    
    - **Trigger**: The customer completes the application on a user-friendly online platform with real-time validation.
    - **PT**: 10 minutes (guided form with auto-fill and validation).
    - **LT**: Immediate submission.
    - **Improvement**: Eliminated errors, instant document upload, and validation.
3. **Document Review & Identity Verification**:
    
    - **Trigger**: Automated document verification using AI and KYC tools.
    - **PT**: 15 minutes (automated checks and verification).
    - **LT**: 15 minutes.
    - **Improvement**: Real-time verification, reduced need for manual intervention, and faster processing.
4. **Account Setup**:
    
    - **Trigger**: Account creation is automated upon successful verification.
    - **PT**: 10 minutes (instant setup).
    - **LT**: Immediate.
    - **Improvement**: Instant account setup, no delays waiting for system updates.
5. **Customer Notification**:
    
    - **Trigger**: Automated notification sent immediately after account activation.
    - **PT**: Instant.
    - **LT**: Immediate.
    - **Improvement**: Instant communication, customer receives immediate confirmation.
6. **Customer Education**:
    
    - **Trigger**: Automated onboarding materials are provided via email or an interactive app, with an option for a quick online tutorial.
    - **PT**: 30 minutes (automated tutorial).
    - **LT**: 1 day (if a customer schedules a session, otherwise immediate).
    - **Improvement**: Self-paced learning, reduced delays, and increased customer understanding.

**Total Lead Time**: 1 day  
**Total Process Time**: 1 hour 10 minutes  
**Key Improvements**:

- **Reduction in lead time** from 11 days to 1 day.
- **Streamlined process**: Automation reduces manual work, errors, and waiting times.
- **Customer experience**: Improved engagement, faster onboarding, and better access to resources.



### Value stream mapping for a card management system of a bank 

we will consider a bank with issues in their card management system. 
The initial VSM would look like the following: 
#### **Step 1: Define the Current State (Before)**

In the current state, the card management process is inefficient, with several pain points, delays, and waste.

##### **Current State Value Stream Mapping**

1. **Customer Request**:
    
    - **Trigger**: A customer submits a request for a new card (e.g., online, via phone, or at a branch).
    - **Process Time (PT)**: 15 minutes (filling out forms, verification).
    - **Lead Time (LT)**: 1 day (until the request is processed).
    - **Waste**: Customers often need to resubmit information due to errors or missing details.
2. **Request Processing**:
    
    - **Trigger**: The request is forwarded to the card management team.
    - **PT**: 1 hour (verification, data entry, and approval).
    - **LT**: 2 days (waiting for a batch process to run).
    - **Waste**: Redundant manual checks, delayed processing due to batch runs.
3. **Card Production**:
    
    - **Trigger**: Approved requests are sent to the card production unit.
    - **PT**: 2 hours (printing, encoding, and quality check).
    - **LT**: 3 days (waiting for production slot).
    - **Waste**: Delays due to machine downtime or rework for defective cards.
4. **Card Delivery**:
    
    - **Trigger**: Completed cards are handed over to a courier service.
    - **PT**: 30 minutes (packaging, labeling).
    - **LT**: 5 days (shipping to customer).
    - **Waste**: Shipping delays, lost cards.
5. **Card Activation**:
    
    - **Trigger**: Customer receives the card and activates it via phone or online.
    - **PT**: 10 minutes (activation process).
    - **LT**: 1 day (system updates and customer notification).
    - **Waste**: Manual intervention required for failed activations.
6. **Customer Notification**:
    
    - **Trigger**: Confirmation sent to the customer about card activation.
    - **PT**: 5 minutes.
    - **LT**: Immediate.

**Total Lead Time**: 12 days  
**Total Process Time**: 3 hours 50 minutes  
**Key Issues**: Long wait times, redundant processes, manual errors, frequent rework, and customer dissatisfaction.

#### **Step 2: Analyze and Identify Waste**

In the current process, the following types of waste are present:

- **Overproduction**: Producing cards in large batches leading to delays.
- **Waiting**: Significant delays between steps, especially during batch processing.
- **Transportation**: Delays during card shipping.
- **Motion**: Excessive movement of physical forms and documents.
- **Defects**: Rework due to errors in production or customer information.

#### **Step 3: Define the Future State (After)**

To improve the process, automation, digitization, and lean practices will be implemented.

##### **Future State Value Stream Mapping**

1. **Customer Request**:
    
    - **Trigger**: A customer submits a request for a new card via a streamlined digital platform.
    - **PT**: 10 minutes (automatic data capture and verification).
    - **LT**: Immediate processing.
    - **Improvement**: Eliminated manual data entry errors, instant verification.
2. **Request Processing**:
    
    - **Trigger**: Automatically forwarded to the card management system.
    - **PT**: 15 minutes (automated verification and approval).
    - **LT**: 15 minutes.
    - **Improvement**: Real-time processing, eliminated redundant checks.
3. **Card Production**:
    
    - **Trigger**: Real-time order sent to the production unit.
    - **PT**: 1 hour (automated and efficient production).
    - **LT**: 1 day (scheduling optimized for daily production).
    - **Improvement**: Continuous production, reduced machine downtime, and minimized rework.
4. **Card Delivery**:
    
    - **Trigger**: Cards are immediately dispatched using same-day delivery services.
    - **PT**: 15 minutes (packaging and labeling).
    - **LT**: 1 day (expedited shipping).
    - **Improvement**: Partnered with reliable couriers for faster delivery, tracking system implemented.
5. **Card Activation**:
    
    - **Trigger**: Customer receives the card and activates it via a mobile app.
    - **PT**: 2 minutes (instant activation).
    - **LT**: Immediate.
    - **Improvement**: Instantaneous system updates, reduced customer effort.
6. **Customer Notification**:
    
    - **Trigger**: Automated notification sent to the customer.
    - **PT**: Instant.
    - **LT**: Immediate.

**Total Lead Time**: 2 days  
**Total Process Time**: 1 hour 52 minutes  
**Key Improvements**:

- **Reduction in lead time** from 12 days to 2 days.
- **Streamlined process**: Automation reduced manual errors, improved accuracy, and sped up processing.
- **Customer satisfaction**: Faster service, less hassle, and better communication.

### Value Stream mapping for an account creation 
#### Step 1: Define the Current State (Before)

In the current state, the account opening process may involve several manual steps, leading to delays and inefficiencies.

##### Current State Value Stream Mapping

1. **Customer Inquiry**:
    
    - **Trigger**: A potential customer inquires about opening an account (online, via phone, or at a branch).
    - **Process Time (PT)**: 15 minutes (customer service explains the process and requirements).
    - **Lead Time (LT)**: 1 day (waiting for customer to decide and gather documents).
    - **Waste**: Delays in providing information, potential customer drop-off due to complexity.
2. **Application Submission**:
    
    - **Trigger**: Customer submits the account opening application along with required documents.
    - **PT**: 20 minutes (filling out the application form).
    - **LT**: 2 days (waiting for the application to be reviewed by bank staff).
    - **Waste**: Errors in manual data entry, incomplete applications requiring follow-up.
3. **Document Verification**:
    
    - **Trigger**: The bank’s operations team verifies the submitted documents (e.g., ID, proof of address).
    - **PT**: 1 hour (manual document review and verification).
    - **LT**: 3 days (waiting for the verification process to complete).
    - **Waste**: Manual checks, rework due to incomplete or incorrect documents.
4. **Compliance & Risk Assessment**:
    
    - **Trigger**: Compliance team performs KYC (Know Your Customer) checks and assesses the risk of the new account.
    - **PT**: 2 hours (manual risk assessment and approval process).
    - **LT**: 4 days (waiting for all checks to be completed).
    - **Waste**: Delays due to manual processes and coordination between departments.
5. **Account Setup**:
    
    - **Trigger**: Upon approval, the account is set up in the bank’s system.
    - **PT**: 30 minutes (account creation and system updates).
    - **LT**: 1 day (waiting for system updates and notifications).
    - **Waste**: Delays in system processing and notification.
6. **Customer Notification & Activation**:
    
    - **Trigger**: Customer is notified that the account is active and provided with account details.
    - **PT**: 10 minutes (sending notification and instructions for account use).
    - **LT**: 1 day (delays in communication and activation).
    - **Waste**: Manual notification processes, delayed customer engagement.

**Total Lead Time**: 12 days  
**Total Process Time**: 4 hours 15 minutes  
**Key Issues**: Long waiting times, manual errors, inefficient communication, and customer dissatisfaction.

#### Step 2: Analyze and Identify Waste

The current process includes the following waste:

- **Waiting**: Significant delays between steps, particularly in document verification, compliance checks, and account setup.
- **Defects**: Errors in application and document submission leading to rework.
- **Overprocessing**: Manual verification and compliance checks that could be automated.
- **Motion**: Excessive movement of documents and manual data entry.

#### Step 3: Define the Future State (After)

The future state aims to streamline the account opening process by automating key steps, improving communication, and reducing waste.

##### Future State Value Stream Mapping

1. **Customer Inquiry**:
    
    - **Trigger**: Customer initiates the process through an optimized digital platform with live support.
    - **PT**: 5 minutes (instant access to information and guidance).
    - **LT**: Immediate.
    - **Improvement**: Immediate customer engagement, reduced drop-off rate.
2. **Application Submission**:
    
    - **Trigger**: Customer completes the application online using a guided form with real-time validation.
    - **PT**: 10 minutes (auto-fill and validation reduce errors).
    - **LT**: Immediate.
    - **Improvement**: Instant submission, automated data entry, and error reduction.
3. **Document Verification**:
    
    - **Trigger**: Documents are uploaded via a secure portal with automated verification tools.
    - **PT**: 15 minutes (automated document checks and validation).
    - **LT**: 1 hour (instant verification).
    - **Improvement**: Reduced manual work, faster document verification, and fewer errors.
4. **Compliance & Risk Assessment**:
    
    - **Trigger**: Automated KYC checks and risk assessment begin immediately after document verification.
    - **PT**: 30 minutes (automated checks using AI/ML models).
    - **LT**: 1 day (real-time risk assessment).
    - **Improvement**: Automated and quicker compliance checks, reducing the need for manual intervention.
5. **Account Setup**:
    
    - **Trigger**: The account is created automatically after compliance approval.
    - **PT**: 10 minutes (automated system setup).
    - **LT**: Immediate.
    - **Improvement**: Instant account creation, no waiting for system updates.
6. **Customer Notification & Activation**:
    
    - **Trigger**: Automated notification is sent to the customer with account details and activation instructions.
    - **PT**: 5 minutes (instant notification and instructions).
    - **LT**: Immediate.
    - **Improvement**: Instant communication, enabling the customer to start using the account immediately.

**Total Lead Time**: 1 day  
**Total Process Time**: 1 hour 15 minutes  
**Key Improvements**:

- **Reduction in lead time** from 12 days to 1 day.
- **Streamlined processes**: Automation reduces manual work, errors, and waiting times.
- **Customer experience**: Faster, more efficient account opening process, leading to higher satisfaction.

11. # Annex 
    

- Assembly line
    
- Flow 
    
- Henry Ford
    
- Model T 
    
- Taiichi Ohno
    
- Toyota production system
    
- product family
