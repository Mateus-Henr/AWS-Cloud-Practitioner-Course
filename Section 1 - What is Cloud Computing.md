# 1. What is Cloud Computing Section

 

## 7\. Traditional IT Overview

-   IP addresses are how servers and clients make connections.

-   Routers have the job of fowarding data packets to specific addresses.

-   Switch is a device that takes a packet and sends it to the correct server/client (on the same network).

>  
>
> **IT approach** - Scale things up as required (physical scale)
>
> Some problems are:

-   Rent

-   Energy (Cooling, supply)

-   Hardware

-   Employees

-   Scaling

 
 

## 8\. What is Cloud Computing?

-   It consists of an on-demand delivery (you get resources as you need them), such as computer power, database storage and so on.

-   Cloud services offer a pay-as-you-go-pricing.

-   You can get exactly what you need when it comes to size of resources, etctera.

-   Resources are reachable instantly.

-   Simple UI.

-   Gmail is an example of cloud service.

 

**Cloud Models**

-   Private Cloud - Single organization, not exposed. More secure, and meet specific business needs.

-   Public Cloud - Azure, Google Cloud, AWS are examples. They are delivered over the internet.

-   Hybrid Cloud - Keep some servers on premises but others are exposed. AWS and private cloud for intance.

 

**Characteristics of Cloud Computing**

-   On-demand self service: you can just "shop" want you want when you want it.

-   Broad network access: resources availability over the network by diverse client platforms.

-   Multi-tenancy and resource pooling: Sharing apps with security and privacy.

-   Rapid elasticity and scalability - Scalability on-demand and quickly.

-   Measured service: Pay for what you use.

 

**Six advantagens of Cloud Computing**

-   Trade CAPEX (capital expense) for OPEX (operational experience): Pay on-demand and cost reduce.

-   Massive economies of scale: Bigger scale less price.

-   Stop guessing capacity: Scale automatically.

-   Increase speed and agility.

-   No more data center expenses.

 

**Problems solved by the Cloud**

-   Flexibility

-   Cost-Effectiveness

-   Scalability

-   Elasticity

-   High-availability and faul-tolerance.

-   Agility

 
 

## 9\. The Different Types of Cloud Computing

 

**Infrastructure as a Service (IaaS)** - AWS (EC2), Azure, Linode

-   Provides the building blocks, networking, computers, data storage space etc.

-   Highest level of flexibility.

-   Migrating from on-premises to the cloud (EC2).

 

**Platform as a Service (PaaS)** - AWS (Elastic Beanstalk), Heroku, Google App Engine, Windows Azure

-   It doesn't manage infrastructure.

-   Focus on the deployment and managements of apps.

 

**Software as a Service (SaaS)** - AWS (Rekognition is one of many examples), Google Apps, Zoom

-   Completed product that is run and managed by the service provider.

 

**Comparison:**

<img src="https://drive.google.com/uc?export=view&id=1C-CSh1X1cACYdt_DXUguMlYGo7sIstdr" style="width:7.125in;height:4.24167in" />

 

**Pricing**

-   For computing and storing we pay the exact used price.

-   Relating data transfer we only pat we data LEAVES the cloud.

 
 

## 10\. AWS Cloud Overview

 

**AWS Cloud History**

> 2002 - Internally launched.
>
> 2003 - Realized that they had a good infraestructure.
>
> 2004 - Launched publicly with SQS.
>
> 2006 - RE-launched with more services.
>
> 2007 - Launched in Europe.

**Curiosities**

It's has the biggest cloud infrastructure.

 

**AWS Global Infrastructure**

-   *AWS Regions* - It's a cluster of data centers (ex: 'us-west-3'). Most AWS services are region-scoped.

    -   How to choose an AWS region?

        -   Compliance - Data never leaves a region without your explicit permission.

        -   Proximity - Reduced latency.

        -   Available services within a Region - Some services aren't available in every region.

        -   Pricing - Price varies from region to region.

 

-   *AWS Availability Zones* - Each region has many availability zones (usually 3, min is 3, max is 6).

    -   What are they?

        -   Each one is one or more discrete data centers with redundant power, networking, and connectivity.

        -   They are defined by letters.

        -   The fact for them to be separated is to be isolated from disasters.

        -   They're connected with high bandwidth ultra-low latency networking.

        -   They made up a region.

 

-   *AWS Data Centers* - One of its several cores.

 

-   *AWS Edge Locations / Points of Presence* - AWS has 216 points of presence around the world. Meaning that low latency is easy.

 

**Others**

-   AWS has some Global services but most of its services are Region-scoped.

 
 

## 12 - Shared Responsibility Model & AWS Acceptable Policy

 

**Shared Responsability Model diagram** - This is basically what is your responsabilities and what is AWS' responsabilities.

> Customer - Responsability for the security in the cloud.

> AWS - Responsability for the security on the cloud (their hardware and software).