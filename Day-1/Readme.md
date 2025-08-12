# Day-01: Introduction to Cloud and GCP

---

## What You Will Learn Today

- What is Cloud Computing?
- Difference between Cloud and Traditional IT
- Why choose Google Cloud (GCP) over AWS or Azure?
- Create your Free GCP Account
- Quick Tour: GCP Console and Cloud Shell

---

## Concepts Simplified

### What is Cloud Computing?

Cloud computing means renting servers, databases, storage, and other services over the internet instead of owning them.

In simple words:  
> "You pay only for what you use. No upfront investment, no maintenance headache."

**Cloud providers**: Google Cloud (GCP), Amazon Web Services (AWS), Microsoft Azure

---

### Traditional IT vs Cloud

| Traditional IT                | Cloud (GCP)                       |
|------------------------------|-----------------------------------|
| Buy servers upfront           | Rent what you need                |
| Pay for peak capacity         | Auto-scale as needed              |
| Manual setup                  | Automated provisioning            |
| High maintenance              | Managed by Google                 |

---

### Why GCP?

- Google-level infrastructure (same as YouTube, Gmail)
- Powerful networking and AI services
- Easy to use UI + powerful CLI
- Cost-effective and beginner-friendly
- Used by gaints like META

---

## Task: Create Your Free GCP Account

1. Go to: https://cloud.google.com/free
2. Sign in with your Gmail
3. Provide PAN and card details or UPI

✅ No charges unless you upgrade manually.

---

## Task: Explore GCP Console and Cloud Shell.

### GCP Console

- URL: [https://console.cloud.google.com](https://console.cloud.google.com)
- Everything you need is here: compute, storage, billing, IAM, etc.

### Cloud Shell

- Built-in terminal in your browser
- Free VM with 5GB storage
- Comes pre-installed with `gcloud` CLI

🔍 Try this:
```bash
gcloud auth list
gcloud config list
```

---


# Basics of Cloud Computing

## What is Cloud ?

In simpler terms, imagine the cloud as a vast, virtual space where you can store files, run software, and access various services over the internet. 

It's like having a powerful computer somewhere out there on the web that you can use for tasks without needing to own or physically manage the hardware. This allows users to access data and applications from anywhere with an internet connection.

## What is Cloud Computing ?

Cloud computing is a technology model that involves the delivery of computing services over the internet. Instead of owning and maintaining physical servers and infrastructure, users can access and use computing resources, applications, and storage provided by either third-party service providers (public cloud) or their own organization (private cloud) through the internet. These services are hosted in data centers located around the world.

In essence, cloud computing can involve both third-party providers (public cloud) and an organization's internal resources (private cloud). The distinction lies in whether the computing resources are shared among multiple customers (public cloud) or dedicated to a single organization (private cloud). The flexibility of cloud computing allows organizations to choose the deployment model that best aligns with their needs and requirements.

## Public Cloud:

**Who Uses It:** Everyone, like individuals, businesses, and organizations.

**What It's Like:** Imagine a giant, shared computer space on the internet. It's like using apps, storing files, or doing tasks on the internet that anyone can access.

**Example:** Think of Google Drive or Amazon Web Services (AWS).

## Private Cloud:

**Who Uses It:** One specific organization or business.

**What It's Like:** Picture having your own personal, private computer space. It's like a digital clubhouse where only you and your team have access. Others can't just drop in.

**Example:** A company using its own server for all its digital needs.

## Hybrid Cloud:

**Who Uses It:** A mix of everyone, depending on needs.

**What It's Like:** It's like having your private computer space, but sometimes you use the shared internet space too. 

**Example:** A business storing sensitive data in its private space but using the public cloud for extra storage or specific tasks.

### In a Nutshell:

**Public Cloud:** Shared digital space for everyone.

**Private Cloud:** Your own exclusive digital space.

**Hybrid Cloud:** Using both your private space and the shared online space when needed.

# Vocabulary in Cloud Computing

## Virtualization

Virtualization is the process of creating a virtual version of something, such as an operating system, server, storage, or network resources.

## Virtual Machine

A Virtual Machine (VM) is a software-based emulation of a physical computer. It allows running multiple operating systems on a single physical machine.

## API (Application Programming Interface)

API is a set of rules and protocols that allows different software applications to communicate with each other. It defines how software components should interact.

## Regions

Regions in cloud computing refer to geographic locations where cloud providers have data centers. Each region contains multiple data centers.

## Availability Zones

Availability Zones are isolated locations within a region that have their own power, cooling, and networking. They are designed to provide high availability and fault tolerance.

## Scalability

Scalability is the ability of a system to handle an increasing amount of work or its potential to be enlarged to accommodate that growth.

## Elasticity

Elasticity in cloud computing refers to the ability to dynamically scale resources up or down based on demand.

## Agility

Agility is the capability of quickly and easily adapting to changes. In the context of cloud computing, it involves the rapid deployment of resources and applications.

## High Availability

High Availability (HA) ensures that a system or application is operational and accessible for a high percentage of time, typically 99.9% or higher.

## Fault Tolerance

Fault Tolerance is the ability of a system to continue operating without interruption in the presence of hardware or software failures.

## Disaster Recovery

Disaster Recovery involves the planning and processes for restoring and recovering data and systems after a natural or human-induced disaster.

## Load Balancing

Load Balancing is the distribution of network traffic or computing workload across multiple servers to ensure no single server is overwhelmed.
