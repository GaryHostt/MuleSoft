<p align="center">
  <img src="https://www.mulesoft.com/sites/default/files/MuleSoft_logo_299C_stacked_3.png?raw=true" width = 510 height = 360 alt="Mule"/>
</p>

**by [Alex MacDonald](https://intro.alexmacdonald.solutions)**

## Introduction 

[What is MuleSoft?](https://www.salesforce.com/blog/what-is-mulesoft/)

- Try MuleSoft with a 30 day trial [here](https://www.mulesoft.com/legal/terms/trial). You can keep AnypointStudio on your laptop past that (which is plenty to learn how to develop with Mulesoft), but after you will lose access to cloud deployments.

[MuleSoft](https://status.mulesoft.com/) status & [salesforce](https://trust.salesforce.com/en/) Trust

## Outline

- Getting started
- Anypoint
- Training
- How to integrate with X, Y, Z
- Administering MuleSoft
- Certifications
- Misc

**Tips on using this repo:**
1. If you search for 'Youtube' that will take you to all of the video resources here.
2. You can also search for the app name you are trying to integrate (such as 'salesforce'), or 'template' for potential pre-built solutions
3. If I have not given enough context with the terms I have used, see the [Mulesoft glossary](https://docs.mulesoft.com/general/glossary).

## Getting started

[Mulesoft.com](https://www.mulesoft.com)

- ~50% of this repo can be found somewhere there.

[Official MuleSoft documentation](https://docs.mulesoft.com/general/)

[Login to Anypoint Platform](https://anypoint.mulesoft.com/login/) ++ [additional useful tools to enhance development](https://blogs.mulesoft.com/dev-guides/api-design/enhance-developers-anypoint-studio-experiences/)

- This is where I spend most of my time these days.

[Radio MuleSoft, a podcast](https://podcasts.apple.com/be/podcast/radio-mulesoft/id1498103178)

- [Season 2 episode 1](https://podcasts.apple.com/be/podcast/apis-unplugged-season-2-episode-1-api-questions-for/id1498103178?i=1000506223990) started off with a very interesting story on how [this happened](https://cybernews.com/news/70tb-of-parler-users-messages-videos-and-posts-leaked-by-security-researchers/) (**hint: bad API design!**).

[White papers](https://www.mulesoft.com/integration-resources?type[0]=Whitepaper) & [Articles](https://www.mulesoft.com/resources/articles)

- Find the best practices, example: [HCM](https://www.mulesoft.com/lp/whitepaper/api/hcm-integration-best-practices)

[Vertical/Industry specific solutions](https://www.mulesoft.com/integration-solutions)

### Youtube

[MuleSoft channel](https://www.youtube.com/user/mulesoftvids)

[What is API-led Connectivity?](https://www.youtube.com/watch?v=WYociWuCInE)

- It is the approach you use when developing with Mulesoft. It packages underlying connectivity and orchestration services as easily discoverable and reusable building blocks, exposed by APIs.

[What is Mulesoft? Tutorial playlist](https://www.youtube.com/watch?v=lRpJtMfa4zs&list=PLfEAetjBY9s5gywT2hC95rnZaW5CEZis-)

### You & MuleSoft

[Work at MuleSoft!](https://www.mulesoft.com/careers)

[MuleSoft meetups](https://meetups.mulesoft.com)

[Customer case studies](https://www.mulesoft.com/case-studies)

[Build a connector](https://www.mulesoft.com/webinars/saas/building-powerful-connector-scratch) for your app! And get it [certified by Mulesoft](https://www.mulesoft.com/platform/cloud-connectors/certified)

## Anypoint

Menu                           |  Architecture
:-----------------------------:|:-------------------------:
![](components.png)            |  ![](architecture.png)

[API Manager](https://docs.mulesoft.com/api-manager/2.x/)

[Exchange](https://www.mulesoft.com/exchange/)

- The above link will take you to assets provided by Mulesoft. Exchange offers hundreds, if not thousands, of [prebuilt templates](https://www.mulesoft.com/exchange/?type=template). Your use case may already be built and available for download!

[Mulesoft Composer](https://www.mulesoft.com/platform/api/no-code-integration-tool)

- COMING SOON! This will be awesome.

[Object Storage](https://anypoint.mulesoft.com/exchange/org.mule.modules/mule-module-objectstore/)

[MQ](https://anypoint.mulesoft.com/exchange/org.mule.tooling.messaging/mule-module-anypoint-mq-ee-studio/)

## Training

### Official

[API-led Connectivity](http://workshop.tools.mulesoft.com/modules/module0)

- This is the **first place** I would tell you to start in order to learn Mulesoft. 

[MuleSoft tutorials](https://developer.mulesoft.com/tutorials-and-howtos)

[Top tutorials for new developers](https://blogs.mulesoft.com/dev-guides/how-to-tutorials/getting-started-with-mulesoft/)

[Trailhead for integration](https://trailhead.salesforce.com/en/content/learn/trails/mulesoft-integration-trailblazer)

### Third party

[Free MuleSoft self-paced training](https://training.mulesoft.com/course-catalog?results=true&courseFormat=Self-paced)

[TutorialsPoint](https://www.tutorialspoint.com/mulesoft/index.htm)

[Vanchiv tutorials](https://vanchiv.com/category/integration/mulesoft-tutorial-and-guide/)

# How to integrate with X

## General

[MuleSoft connector documentation - yes, all of them](https://docs.mulesoft.com/connectors/)

[Top 10 MuleSoft connectors](https://blogs.mulesoft.com/dev-guides/how-to-tutorials/top-download-connectors-anypoint-platform/)

- All of these are discussed in this repo.

[MuleSoft Anypoint Examples on Github](https://github.com/mulesoft/anypoint-examples)

[Batch jobs & Docker with MuleSoft](https://github.com/manikmagar/mule4-examples) 

[Mulesy - sample POCs](https://mulesy.com/mulesoft-pocs/)

## salesforce

<p align="center">
  <img src="http://pluspng.com/img-png/salesforce-logo-vector-png-salesforce-logo-png-2300.png?raw=true" width = 400 height = 300 alt="sfdc"/>
</p>

[SFDC General practices](https://www.mulesoft.com/resources/salesforce)

[Connector documentation](https://docs.mulesoft.com/salesforce-connector/0.3.9/)

[All MuleSoft salesforce integration templates](https://www.mulesoft.com/exchange/?type=template&search=salesforce)

- you can search for any application for Mulesoft supported templates

### Youtube

[Querying salesforce with MuleSoft](https://www.youtube.com/watch?v=TeAHUjILPJA)

- [Official salesforce SOQL guide](https://developer.salesforce.com/docs/atlas.en-us.soql_sosl.meta/soql_sosl/sforce_api_calls_soql.htm)

[salesforce & MuleSoft workshop](https://www.youtube.com/watch?v=NplNJIdT1y4&list=PL5jx2tzaZzrACn0PHDslh_S7cMO4FIk86)

[batch request](https://www.youtube.com/watch?v=6AYGCfQCOCQ)

[syncing data to AWS S3](https://www.youtube.com/watch?v=b3Z9pWi2lkk)

## Oracle

<p align="center">
  <img src="http://logos-download.com/wp-content/uploads/2016/03/Oracle_logo_logotype_wordmark.png?raw=true" width = 550 height = 160 alt="oci"/>
</p>

### Applications

[Peoplesoft](https://www.mulesoft.com/resources/api/oracle-peoplesoft-integration)

[Eloqua](http://cdn.cdata.com/help/DUF/mule/)

[Fusion/Cloud ERP](https://www.astcorporation.com/mulesoft-oracle-connector/)

[Sales Cloud](https://www.youtube.com/watch?v=Fd-XHKQCJPA)

[Netsuite](https://www.youtube.com/watch?v=venI2PBqgEY)

[All MuleSoft Oracle templates](https://www.mulesoft.com/exchange/?type=template&search=oracle)

[EBS connector documentation](https://docs.mulesoft.com/oracle-ebs-122-connector/2.1/) and on [exchange](https://www.mulesoft.com/exchange/com.mulesoft.connectors/mule-oracle-ebs-122-connector/)

- The EBS connector is one of many supported directly by Mulesoft, and can be used to capture business events and more.

<p align="center">
  <img src="https://docs.mulesoft.com/oracle-e-business-suite-connector/0.3.6/_images/connector-architecture.jpg?raw=true" width = 500 height = 160 alt="ebs"/>
</p>

### Youtube

[EBS connector](https://www.youtube.com/watch?v=aO48A17RQqg)

[Oracle Database Connector](https://www.youtube.com/watch?v=EEDl0Sn8N5I)

[Query Oracle Database](https://www.youtube.com/watch?v=AW6_unMvxYY)

[Insert to Oracle Database](https://www.youtube.com/watch?v=Rxz6CnC0L1o)

## Microsoft

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a8/Microsoft_Azure_Logo.svg/1280px-Microsoft_Azure_Logo.svg.png?raw=true" width = 480 height = 180 alt="Microsoft"/>
</p>

[SQL Server - 1](https://mulesy.com/microsoft-sql-server-with-mule/) & [SQL Server - 2](https://dzone.com/articles/connecting-to-ms-sql-server-with-mulesoft)

[Azure storage](https://mulesy.com/integrating-azure-storage-with-mulesoft/)

[Azure Service Bus connector documentation](https://docs.mulesoft.com/microsoft-azure-sb-connector/3.1/) + [how to-1](https://www.whishworks.com/blog/mulesoft/integration-of-mule-esb-with-microsoft-azure/) & [how to-2](https://www.ricston.com/blog/mulesoft-connectivity-with-microsoft-azure-service-bus/)

[Azure data lake](https://blogs.mulesoft.com/dev-guides/how-to-tutorials/create-customer-360-mulesoft-azure-data-lake-store/)

[Step by step instructions on configuring Sharepoint](https://mulesy.com/create-trail-account-on-sharepoint/) and using [the connector](https://mulesy.com/file-operations-using-sharepoint-connector-in-mule-4/)

[Dynamics-1](https://anypoint.mulesoft.com/exchange/org.mule.modules/mule-module-ms-dynamics-crm/) & [Dynamics-2](https://docs.mulesoft.com/microsoft-dynamics-crm-connector/0.3.8/)

## GCP

<p align="center">
  <img src="https://avatars1.githubusercontent.com/u/2810941?s=280&v=4?raw=true" width = 280 height = 280 alt="GCP"/>
</p>

[BigQuery](https://www.apisero.com/mulesoft-bigquery-series-2/)

[Setup VPN from Mulesoft to Google Cloud](https://blogs.mulesoft.com/api-integration/security/setting-up-vpn-with-google-cloud/)

[Pub/Sub - Youtube](https://www.youtube.com/watch?v=74Rb1to0vNc)

## SAP

<p align="center">
  <img src="https://www.appythings.nl/wp-content/uploads/2018/06/SAP-logo-icon-PNG-Transparent-Background.png?raw=true" width = 280 height = 280 alt="SAP"/>
</p>

[salesforce to SAP Exchange template](https://www.mulesoft.com/exchange/org.mule.templates/template-sfdc2s4hana-order-migration/)

### Youtube

[SAP Connector demo](https://www.youtube.com/watch?v=1xenBmdVNSo)

[SAP configuration](https://www.youtube.com/watch?v=tf_qS-VSMHw)

[Send iDoc with SAP](https://www.youtube.com/watch?v=hM98SZXQorU)

[Integration made Easy](https://www.youtube.com/watch?v=xNgL2vVLsZw)

[Detailed explanation](https://www.youtube.com/watch?v=nrfKgiJvVuw)

## AWS

<p align="center">
  <img src="http://logos-download.com/wp-content/uploads/2016/12/Amazon_Web_Services_logo_AWS.png?raw=true" width = 550 height = 200 alt="AWS"/>
</p>

[General resources](https://blogs.mulesoft.com/tag/aws-integration/)

[Extending AWS with MuleSoft - white paper](https://www.mulesoft.com/webinars/api/aws-integration-developer)

### Youtube

[AWS S3 with MuleSoft](https://www.youtube.com/watch?v=VlPmg2lVvzM)

[Redshift](https://www.youtube.com/watch?v=uAfEg80SqOA&t=9s)

[lambda](https://www.youtube.com/watch?v=Fad_shR9hMw)

## ServiceNow

<p align="center">
  <img src="https://www.tenable.com/sites/drupal.dmz.tenablesecurity.com/files/images/technology-partners/transparent-sn-logo%20%281%29.png" width = 600 height = 240 alt="Microsoft"/>
</p>

[Example-1](https://www.apisero.com/integration-between-servicenow-and-mulesoft/) & [Example-2](https://dzone.com/articles/mulesoft-integration-with-servicenow)

[JIRA + ServiceNow](https://www.mulesoft.com/resources/jira-servicenow)

[ServiceNow - official documentation](https://docs.mulesoft.com/servicenow-connector/6.8/)

[ServiceNow templates on Exchange](https://www.mulesoft.com/exchange/?type=template&search=servicenow)

## Twilio

<p align="center">
  <img src="https://cdn.freebiesupply.com/logos/thumbs/2x/twilio-logo.png?raw=true" width = 285 height = 260 alt="Twilio"/>
</p>

[Twilio connector documentation](https://docs.mulesoft.com/twilio-connector/3.0/)

[Twilio dev-guide](https://blogs.mulesoft.com/dev-guides/how-to-tutorials/twilio-cloud-connector-2/)

## Other SaaS

[Docusign](https://www.whishworks.com/blog/mulesoft/integrating-docusign-with-mulesoft/)

[Marketo](https://launchpoint.marketo.com/mulesoft-inc/mulesofts-anypoint-connector-for-marketo/)

[Work.com](https://www.mulesoft.com/exchange/org.mule.examples/mulesoft-accelerator-for-workcom/)

[Workday & ServiceNow Employee Aggregation template](https://www.mulesoft.com/exchange/org.mule.templates/template-wday2snow-employee-aggregation/)

### Sign up for your very own SaaS to play with

[salesforce](https://developer.salesforce.com/signup)

[ServiceNow](https://developer.servicenow.com/dev.do)

[okta](https://developer.okta.com/signup)

## Open Source/technology/generic

[File based integrations](https://blogs.mulesoft.com/dev-guides/how-to-tutorials/howto-file-based-integrations-and-transfer/)

[kafka](https://www.royalcyber.com/blog/apache-kafka/apache-kafka-integration-with-mulesoft/)

[LDAP-1](https://anypoint.mulesoft.com/exchange/org.mule.modules/mule-module-ldap/) & [LDAP-2](https://docs.mulesoft.com/ldap-connector/0.3.8/)

### General REST APIs

<p align="center">
  <img src="https://d12m9erqbesehq.cloudfront.net/wp-content/uploads/2016/04/30152042/event-smart-rest-api.png?raw=true" alt="general"/>
</p>

[Consuming REST in Mulesoft - Youtube](https://www.youtube.com/watch?v=fLJnezzVU4s)

### APIs to play with

[Countries](http://restcountries.eu)

[Star Wars API](https://swapi.dev)

- If you want to learn GraphQL, this is a great API to do it with, shown [here](https://github.com/graphql/swapi-graphql), [here](https://openbase.com/js/swapi-graphql/documentation), [here](https://www.youtube.com/watch?v=RDQyAcvmbpM). Then you can use [Mulesoft with GraphQL](https://dzone.com/articles/implementing-graphql-with-mulesoft)! A GraphQL integration can be a great [process API used with API-led connectivity](https://blogs.mulesoft.com/dev-guides/how-to-tutorials/graphql-api-gateway/).

[News API](https://newsapi.org)

- [Here's an example](https://github.com/GaryHostt/DailyNewsText) of a custom code application I wrote that calls this API.

[Census](https://www.census.gov/data/developers/data-sets.html)

[The Department of Justice](https://www.justice.gov/developer/api-documentation/api_v1)

[COVID-19 Data Tracking](https://www.mulesoft.com/exchange/68ef9520-24e9-4cf2-b2f5-620025690913/covid19-data-tracking-api/)

# Administering Mulesoft

[Mule Deployments as Code](https://github.com/mulesoft-consulting/MuleSoft_DeploymentAsCode)

[Using your own Identity Provider with Mulesoft](https://docs.mulesoft.com/access-management/managing-users)

[CloudHub connector](https://anypoint.mulesoft.com/exchange/org.mule.modules/mule-module-cloudhub/)

- This provides the ability to interact with CloudHub from within a Mule application. The operations allow you to deploy, start, stop, and update applications as well as send notifications from your Mule application to CloudHub.

[Pricing](https://www.mulesoft.com/anypoint-pricing), [licensing, & sizing](https://www.infomentum.com/mulesoft-pricing-licence-cost)

- [additional info](https://www.whishworks.com/blog/mulesoft/mulesoft-anypoint-platform-licence-cost/)

[Deployment options](https://docs.mulesoft.com/runtime-manager/deployment-strategies#cloudhub-deployments)

[Increasing JVM memory](https://help.mulesoft.com/s/article/Increasing-JVM-memory-heap-in-Anypoint-Studio-to-avoid-OutOfMemory-issues)

- This can be useful when doing local development on your laptop.

## Youtube

[Object store on MuleSoft](https://www.youtube.com/watch?v=gXZMxTZoXCQ)

[CI/CD - high level](https://www.youtube.com/watch?v=c_Mlifcikj8)

[Setting up Anypoint studio for the first time](https://www.youtube.com/watch?v=cZUw2T0D7PU)

[Using Github with Anypoint studio](https://www.youtube.com/watch?v=35fHx23zjP0)

## Mulesoft on other clouds

[Runtime Fabric on AWS](https://stackoverflow.com/questions/57526007/deploying-mulesoft-application-using-azure-devops)

[Running Mulesoft on Google Kubernetes Engine](https://www.youtube.com/watch?v=tJDSQ1EUKUI)

[Running Mulesoft on Azure](https://docs.mulesoft.com/runtime-fabric/1.8/install-azure)

[Deploy Mulesoft with Azure DevOps](https://dzone.com/articles/deploying-mulesoft-using-azure-devops) + [details](https://stackoverflow.com/questions/57526007/deploying-mulesoft-application-using-azure-devops)

# Certifications

## Offical

[Preparing - what you need to know, by Mulesoft](https://www.mulesoft.com/webinars/api/preparing-for-mulesoft-certifications)

[Exam details](https://help.learn.mulesoft.com/hc/en-us/categories/115001475248-Certification)

[Level 1 exam summary](https://training.mulesoft.com/certification/developer-mule4-level1)

[5 things to know about getting certified](https://blogs.mulesoft.com/learn-apis/integration-training/learn-about-mulesoft-training-and-certification/)

[All Mulesoft Certifications](https://training.mulesoft.com/certification)

## Third party

[Mulesy - general guide](https://mulesy.com/0-mulesoft-certifications/)

[Udemy - Mulesoft level 4](https://www.udemy.com/course/mulesoft-certified-developer-mule-4/)

[Udemy - Mulesoft Platform Architect](https://www.udemy.com/course/ultimate-mulesoft-certified-platform-architect-course/)

## Study links

- some of my bookmarks for [MCD](https://training.mulesoft.com/certification/developer-mule4-level1) studying

### Flows

[Mule Flows 101](https://blogs.mulesoft.com/dev-guides/api-design/mule-flows-101-types-attributes-variables/)

[Youtube - subflows, attribues, variables, VM connector, and flow reference](https://www.youtube.com/watch?v=X2luxC5cxw8)

[Scatter-gather](https://docs.mulesoft.com/mule-runtime/4.3/scatter-gather-concept)

[Youtube - scatter-gather](https://www.youtube.com/watch?v=mTspKZhpyck)

[Youtube - choice router](https://www.youtube.com/watch?v=R_br2QDqsHI)

[Error Handling](https://blogs.mulesoft.com/dev-guides/how-to-tutorials/mule4-error-handling/)

[Youtube - error handling](https://www.youtube.com/watch?v=a86tdUBu9lQ)

...........

### Connectors

[List Files w/ file connector](https://docs.mulesoft.com/file-connector/1.3/file-list)

[Youtube - file connector](https://www.youtube.com/watch?v=eUUIGer0XKM)

[Youtube - database adapter](https://www.youtube.com/watch?v=n1CD6iXNmm8)

[Consume JMS messages](https://docs.mulesoft.com/jms-connector/1.7/jms-consume)

[VM Connector](https://docs.mulesoft.com/vm-connector/2.0/)

[Web Service/SOAP tutorial](https://tutorialspedia.com/mulesoft-step-by-step-tutorial-consume-soap-web-service-using-mule4/)

...........

### Misc

[Class-loading isolation](https://docs.mulesoft.com/mule-runtime/4.3/about-classloading-isolation)

[Add SLA tiers to API Groups](https://docs.mulesoft.com/api-manager/2.x/api-groups-add-sla-tiers)

[API Autodiscovery](https://docs.mulesoft.com/api-manager/2.x/api-auto-discovery-new-concept)

[Defining examples in RAML](https://docs.mulesoft.com/design-center/design-named-examples)

[RAML Tutorial](https://raml.org/developers/raml-200-tutorial)

[Watermarks + object store](https://docs.mulesoft.com/object-store-connector/1.1/object-store-to-watermark)

[HTTPS service](https://docs.mulesoft.com/mule-runtime/4.3/build-an-https-service)

...........

### DataWeave

[DataWeave reference](https://docs.mulesoft.com/mule-runtime/4.3/dw-functions)

[DataWeave JSON to XML](https://www.jitendrazaa.com/blog/integration/mulesoft/mulesoft-4-transformation-convert-json-to-xml/)

[DataWeave Playground](https://dwlang.fun/)

- easiest way to practice your DataWeave skills

[Youtube - Map & mapObject in DW](https://www.youtube.com/watch?v=YDb4hY9zbcw)

...........

### Batch & For each scopes

[Youtube - batch processing](https://www.youtube.com/watch?v=sxtbeiRkZWQ&list=PL5GwZHHgKcuCc9bWcBy73yjtEOZ5pcJW6)

[Mule batch jobs](https://dzone.com/articles/mule-batch-jobs-and-its-variables)

[Youtube - batch aggregator/step/accept expressions](https://www.youtube.com/watch?v=ruCWz2yPCvk)

[Youtube - batch processing + salesforce](https://www.youtube.com/watch?v=sxtbeiRkZWQ)

[Youtube - for each scope](https://www.youtube.com/watch?v=ccE9hs1tY6c)

# Misc

[Ross Mason, the founder of Mulesoft](https://www.forbes.com/sites/stuartanderson/2016/06/04/ross-mason-immigrant-founder-of-1-5-billion-mulesoft-on-job-market-and-managing-a-global-company/?sh=608acfc547e3)

[Workshop presentations](https://martinhumpolec.cz/mulesoft-workshop/)

[API-led Connectivity slides](https://www.slideshare.net/mulesoft/transform-your-business-with-apiled-connectivity)


