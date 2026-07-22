---
title: "Event 2"
date: 2026-06-27
weight: 1
chapter: false
pre: " <b> 4.2. </b> "
---

# Reflection 2: "FCAJ Community Day: Data Driven, AI Risen"

### Event Information
**Event Name:** FCAJ Community Day: Data Driven, AI Risen
**Date & Time:** June 27, 2026
**Location:** AWS Vietnam Office, 36th Floor
**Role:** Attendee

### Event Objectives
- Update on the most advanced technology trends regarding AI Agents, Voice AI, and AWS DevOps automation from industry leaders and experts.
- Provide practical knowledge and in-depth perspectives to help attendees learn how to build, architect, and operate modern AI/DevOps systems in real-world projects.

### List of Speakers
- **Steve Tran** - CTO/Founder  CloudThinker
- **Truong Tran** - AI Solution Sales Noventiq
- **Trung Vu** - CEO Revve AI
- **Anh Dang** - Solution Sales Noventiq
- **Nghi Danh** - AI Engineer Renova Cloud
- **Kiet Tran** - AI Engineer AWS Student Builder Group
- **Bao Han** - Cloud Engineer Cloud Kinetics
- **Nguyen Nguyen** - Cloud Engineer Cloud Kinetics
- **Toan Nguyen** - AWS Security Builder

### Key Highlights
**Topic 1: Agentic Ops for your Cloud**<br>
**Speaker**: **Steve Tran**
- Steve Tran's journey starting from zero with Cloud technology with no prior experience, how he self-built his expertise, and successfully founded the consulting company CloudThinker.io. His personal lessons learned.
- **AI architecture decision framework (Single Agent vs. Multi-Agent):**
  - **Single Agent:** For simple, focused tasks, limited to a specific domain, and requiring low complexity.
  - **Multi-Agent:** A mandatory solution for complex problems requiring parallel processing, decision-making collaboration among multiple specialized Agents, and demanding high scalability/fault tolerance.<br>

**Topic 2: Building Voice Agent at Scale** <br>
**Speakers**: **Nghi Danh**, **Kiet Tran**, **Trung Vu** <br>
- **Optimized Architecture specifically for Vietnamese**:<br>
A bright spot of the presentation was the core architecture analysis. While the Sound-to-Sound model has an advantage for English, the SCT-LLM-TTS (Speech-to-Text, through Large Language Model, then back to Text-to-Speech) architecture proved its superior optimization for Vietnamese. This architecture thoroughly resolves complex linguistic nuances, allows the establishment of effective safety guardrails, and has been successfully applied in reality at VPBank and VIB.

- **Live Demo and Technical Deployment**:<br>
The speakers demonstrated a real Voice Agent system with real-time interaction capabilities, deep context awareness, and multi-language support. The entire system operated smoothly through a standard technical pipeline including: Speech Recognition, Natural Language Processing, Response Generation, and Speech Synthesis.

**Topic 3: AWS DevOps AI Agent**<br>
**Speakers**: **Bao Han**, **Nguyen Nguyen**<br>

- **Solving the problem of monitoring and troubleshooting**:<br>
 AWS DevOps Agent was introduced as a solution to completely overcome the issue of scattered monitoring data. Through the ability to automatically build system topology diagrams, the AI Agent can deeply understand the system's context. An extremely impressive real-world example shared was a case study at WGU University, where this solution helped reduce the Mean Time To Recovery (MTTR) by up to 77%.

**Topic 4: AI-Powered Productivity**<br>
**Speakers**: **Truong Tran**, **Anh Dang**<br>
- The fact that HR does not use AI to filter personnel and candidates poses many major challenges such as: manual CV reading easily missing potential candidates, difficulty in clearly defining the required talent due to relying too much on intuition...
- Amazon Q can address this: Automating HR workflows, handling employee questions, processing and managing documents, automating onboarding, and supporting performance reviews.

**Topic 5: Building Secure Private MCP for Amazon Q**
**Speakers**: **Toan Nguyen**, **Nghi Danh**
- **The Model Context Protocol (MCP)** helps standardize and securely connect AI models with the enterprise's internal data sources. The highlight of the solution is the use of a Private Connection (including VPC Connection, Interface Endpoint, Route 53 Resolver, ALB) to connect with the MCP Server. This architecture thoroughly prevents DoS and Man-in-the-middle attacks, ensuring sensitive data only circulates internally and is absolutely not exposed to the Internet.

- Through this private network architecture, Amazon Q can securely query context in real-time while meeting strict compliance standards thanks to end-to-end encryption, detailed IAM authorization control, and comprehensive Audit Logging.

### Lessons Learned
- Understood that to successfully apply AI in enterprises, besides performance, localization (specialized Voice AI architecture for Vietnamese) and absolute data security (Private MCP) are decisive factors.
- Clearly realized the strong shift of AI from isolated support tools to comprehensive automation systems (Multi-Agent, Voice AI, DevOps Agent) that help completely solve complex operational problems.

### Application to Work
- **Building Cloud and AI foundations:** Focus on solidifying fundamental knowledge of Cloud systems (especially the AWS ecosystem) and core AI operational principles as a premise to gradually approach complex system architectures.
- **Applying the "Single Agent" model to daily tasks:** Start experimenting with AI on a small scale by setting up in-depth prompts, turning the AI into independent "Agents" to support specific tasks like code review and debugging.
- **Complying with Data Security principles:** Apply the security mindset from the Private MCP architecture into actual work. Absolutely do not input sensitive data, internal corporate information, or project source code into public AI platforms (like ChatGPT or Claude) to prevent data leakage risks.

### Event Photos 

<p align="center">
  <img src="/images/anh1.png" alt="Event photo 1" width="48%">
  <img src="/images/anh2.png" alt="Event photo 2" width="48%">
</p>