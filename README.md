# Field notes: running AI agents on real customer service

Notes from building and operating AI agents that answer customer chat and email for an online brand selling in eight languages. Every note comes from production work: what the agent does, where it went wrong, and what we changed.

Maintained by [Dingbo AI](https://ai.dingboai.com/). We build and run AI agents for customer service, paid per completed task.

## Start here: the basics

- [What Is an AI Agent? A Plain Answer With a Real Example](https://ai.dingboai.com/en/what-is-an-ai-agent.html)  
  An AI agent is software that uses a language model to choose its own steps and tools to finish a task. The parts, the types, and one working example.
- [What Is Agentic AI? Definition, Examples, and Limits](https://ai.dingboai.com/en/what-is-agentic-ai.html)  
  Agentic AI is AI that works toward a goal over several steps, choosing actions and using tools while a person supervises. Definition, examples and limits.
- [Agentic AI vs Generative AI: The Difference at Work](https://ai.dingboai.com/en/agentic-ai-vs-generative-ai.html)  
  Generative AI writes when asked. Agentic AI uses the same models to look things up and finish a task. One customer email handled both ways, and what each needs.
- [AI Agent vs Chatbot: What Is the Difference?](https://ai.dingboai.com/en/ai-agent-vs-chatbot.html)  
  A chatbot is a conversation window. An AI agent looks things up and finishes tasks. How to tell them apart, with a real chat example and questions for vendors.
- [AI in Customer Service: What It Does Today, in Numbers](https://ai.dingboai.com/en/ai-in-customer-service.html)  
  What AI does in customer service today, from one live operation: 15,725 chats and 36,789 emails in 30 days, what AI handles alone and what people decide.
- [What Is BPO? And What Changes When AI Does the Work](https://ai.dingboai.com/en/what-is-bpo.html)  
  BPO means business process outsourcing: paying another company to run a process for you. The types, how it is priced, and what changes when AI does the work.
- [AI Automation Agency: What It Does and How to Pick One](https://ai.dingboai.com/en/ai-automation-agency.html)  
  An AI automation agency builds and runs AI systems that take over repetitive work for other businesses. The three kinds, what to ask, and warning signs.

## By platform and channel

- [Shopify AI Customer Service Agent: What to Connect](https://ai.dingboai.com/en/shopify-ai-customer-service-agent.html)  
  What a Shopify AI customer service agent needs beyond a chat widget: order lookups, carrier tracking, a knowledge base, ticket handoff and multi-store support.
- [Best AI Chatbot for Shopify: 9 Checks Before You Choose](https://ai.dingboai.com/en/best-ai-chatbot-for-shopify.html)  
  Nine checks to find the best AI chatbot for a Shopify store: real order lookup, failed lookups, refunds in chat, email, languages, and how you pay for it.
- [AI Customer Service for WooCommerce, Magento, Custom Stores](https://ai.dingboai.com/en/ai-customer-service-woocommerce-magento-custom-store.html)  
  What an AI customer service agent needs from a WooCommerce, Magento, BigCommerce or custom store: six read-only data points and how each platform exposes them.
- [Adding an AI Agent to Zendesk, Freshdesk or Gorgias](https://ai.dingboai.com/en/ai-agent-zendesk-freshdesk-gorgias.html)  
  Three ways to add an AI agent to a helpdesk such as Zendesk, Freshdesk or Gorgias: at the mailbox, through the ticket API, or with an approval workbench.
- [AI for a Shared Support Inbox: Gmail, Outlook, IMAP](https://ai.dingboai.com/en/ai-shared-inbox-support-email.html)  
  How an AI agent works a shared support inbox on Gmail, Outlook or any IMAP mailbox: threading, quoted text, automated mail, several mailboxes, thread replies.
- [AI Chat Support on Website and Mobile App: Real Split](https://ai.dingboai.com/en/ai-chat-website-mobile-app-support.html)  
  AI chat support across a website and iOS and Android apps: 15,725 conversations split by channel and country, what chat answers, and what becomes a ticket.
- [AI Email Reply Automation for Customer Support](https://ai.dingboai.com/en/ai-email-reply-automation-customer-support.html)  
  How to automate customer support email replies with AI: distil each email into facts, draft every reply, choose what sends itself, and measure what agents keep.
- [Multilingual AI Customer Service: 8 Languages, One Team](https://ai.dingboai.com/en/multilingual-ai-customer-service.html)  
  How one support team answers customers in eight languages with AI: one knowledge base, replies in the customer's language, and people reviewing in their own.
- [After-Hours Customer Service With AI: Real Numbers](https://ai.dingboai.com/en/after-hours-customer-service-ai.html)  
  How much customer service arrives after hours and at weekends, with real counts, and how an AI agent covers it: what it answers and what waits for a person.

## By support scenario

- [Pre-Sales AI Chat: Stock, Specs, Offers, Compatibility](https://ai.dingboai.com/en/ai-presales-chat-ecommerce.html)  
  What a pre-sales AI chat answers before the order: specifications by version and market, stock, published offers, compatibility, questions with no set answer.
- [WISMO: Automating Where-Is-My-Order Requests With AI](https://ai.dingboai.com/en/wismo-where-is-my-order-automation.html)  
  WISMO means where is my order. How an AI agent answers these requests in chat and email: order lookup, carrier status, failed lookups, when a person steps in.
- [AI Chatbot Order Tracking: Connecting Orders and Shipping](https://ai.dingboai.com/en/ai-chatbot-order-tracking.html)  
  How an AI chatbot answers where-is-my-order questions: reading the order number safely, read-only carrier lookups, and what it hands to the email team.
- [AI for Order Changes: Address Edits and Cancellations](https://ai.dingboai.com/en/ai-order-changes-address-cancellation.html)  
  How an AI agent handles address changes and cancellation requests: check whether the order has shipped, answer at once, and route the change to a person.
- [Delivered but Not Received: AI for Delivery Exceptions](https://ai.dingboai.com/en/ai-delivery-exception-handling.html)  
  How an AI agent handles delivery exceptions such as delivered but not received and returned to sender: what the reply says and who checks with the carrier.
- [AI Technical Support: Troubleshooting Hardware Products](https://ai.dingboai.com/en/ai-technical-support-troubleshooting.html)  
  How an AI agent does technical support for hardware: the fix in the first lines, steps and videos for the exact model, and what it asks the customer to do.
- [AI Warranty Claim Handling: From Photo to Spare Part](https://ai.dingboai.com/en/ai-warranty-claim-handling.html)  
  How an AI agent handles warranty claims for physical products: reading photos, checking coverage, troubleshooting first, and routing the spare part to approval.
- [AI Refund Request Handling: What the AI May Promise](https://ai.dingboai.com/en/ai-refund-request-handling.html)  
  How to let AI handle refund requests without paying out by mistake: who proposes, who approves, what chat must never promise, and which version gets recorded.
- [AI Ticket Triage: Sort Support Email by What Must Happen](https://ai.dingboai.com/en/ai-ticket-triage.html)  
  AI ticket triage that sorts support email by the action it needs, not by topic: pure replies, solutions that need approval, and work for the warehouse team.
- [AI Customer Service Escalation: When AI Hands Over](https://ai.dingboai.com/en/ai-customer-service-escalation.html)  
  An AI customer service escalation process that works: escalate by what the request needs, hand over the facts, and never let chat promise what a person must do.

## Running the operation

- [Role-Based AI Agents for Customer Service: Five Roles](https://ai.dingboai.com/en/role-based-ai-agents-customer-service.html)  
  How role-based AI agents split customer service into five jobs, what each role passes on, who owns each one, and what happens when that person is offline.
- [Human-in-the-Loop AI Agents: Who Approves What](https://ai.dingboai.com/en/human-in-the-loop-ai-agents.html)  
  Where the person sits in a human-in-the-loop AI agent: what the AI does alone, what a person approves and what a second person confirms, from live support work.
- [AI Replies to Customer Emails: 8 Best Practices](https://ai.dingboai.com/en/ai-reply-customer-emails-best-practices.html)  
  Eight best practices for AI replies to customer emails, from 204,910 drafts: answer first, give the fix, keep promises consistent, reply in the thread.
- [AI Customer Service Knowledge Base: What Goes In](https://ai.dingboai.com/en/ai-customer-service-knowledge-base.html)  
  What to put in a knowledge base for AI customer service, how to search it so the right answer comes first, and how to correct it without breaking the sync.
- [AI Customer Service Hallucination: Real Examples and Fixes](https://ai.dingboai.com/en/ai-customer-service-hallucination.html)  
  Six hallucinations we caught in a live AI customer service system, from invented shop names to wrong order numbers, and the fix that stopped each one.
- [How to Measure AI Customer Service Quality](https://ai.dingboai.com/en/measure-ai-customer-service-quality.html)  
  Measure AI customer service by what your team keeps: sent unchanged, edited, sent by the AI, and why agents edit. The metrics we track and what each told us.
- [CSAT for AI Customer Service: What Low Scores Meant](https://ai.dingboai.com/en/csat-ai-customer-service.html)  
  We read every low CSAT score over two days of AI and human support replies. Most were about when the survey was sent and real delays, not about AI wording.
- [What Is CSAT? Score, Formula and Survey Timing](https://ai.dingboai.com/en/what-is-csat.html)  
  CSAT is the customer satisfaction score: the share of customers who rate an interaction as satisfied. The formula, the question, and when to send the survey.
- [How an AI Support Agent Learns From Agent Edits](https://ai.dingboai.com/en/ai-learns-from-agent-edits.html)  
  How to make an AI support agent learn from the edits human agents make: compare draft and sent reply, find repeated changes, verify by replay, store only rules.
- [How to Write a Good Customer Service Email: 9 Rules](https://ai.dingboai.com/en/how-to-write-customer-service-email.html)  
  Nine rules for writing a good customer service email, drawn from what support agents changed in 400 drafts: answer first, give the fix, keep promises small.
- [Ticketing System for Customer Support: What It Must Do](https://ai.dingboai.com/en/customer-support-ticketing-system.html)  
  What a ticketing system does for customer support: one ticket per matter, statuses, owners and tasks. What changes when AI drafts and sends part of the replies.

## Buying, pricing and getting started

- [AI Customer Service Outsourcing: How It Works](https://ai.dingboai.com/en/ai-customer-service-outsourcing.html)  
  AI customer service outsourcing explained: what the provider runs, what your team keeps, where data stays, how a pilot starts, and paying per completed task.
- [AI Agent Pricing Models: Seat, Usage, Project, Outcome](https://ai.dingboai.com/en/ai-agent-pricing-models.html)  
  AI agent pricing models compared: per seat, per usage, fixed project and outcome-based. Who carries the risk in each, and what you must count to pay per result.
- [AI Agent ROI: How to Calculate It From Real Work](https://ai.dingboai.com/en/ai-agent-roi.html)  
  How to calculate AI agent ROI from production data: count output that was actually used, convert it to hours, and track three ratios. With real numbers.
- [AI Agent Pilot: Running a Proof of Concept on Real Work](https://ai.dingboai.com/en/ai-agent-pilot-proof-of-concept.html)  
  How to run an AI agent pilot that proves something: one job, a baseline, real historical cases, full human review, and three numbers that decide go or no-go.
- [AI Agent Use Cases: 9 Jobs Running in Production](https://ai.dingboai.com/en/ai-agent-use-cases.html)  
  Nine AI agent use cases running in production today, with volumes: chat answers, order lookups, email drafts, ticket handoff, triage, reports and documents.
- [Custom AI Agent Development Cost: Where the Money Goes](https://ai.dingboai.com/en/custom-ai-agent-development-cost.html)  
  Quotes for a custom AI agent range from a few hundred dollars to six figures because they build different things. What each tier gets you and what to ask first.
- [AI Customer Service System: Build, Open Source or Buy](https://ai.dingboai.com/en/ai-customer-service-system-build-vs-buy.html)  
  Buying AI customer service software, building on open source or hiring a custom team: the real cost of each, and the four things every option still needs.

## Engineering notes

- [How to Build an AI Agent That Survives Real Work](https://ai.dingboai.com/en/how-to-build-an-ai-agent.html)  
  Seven steps to build an AI agent for real work: pick the job, connect read-only tools, prepare facts, write rules once, set approval lines, replay, measure.
- [AI Agent vs Workflow: How to Choose for Real Work](https://ai.dingboai.com/en/ai-agent-vs-workflow.html)  
  One test decides it: if you can draw the next step in advance, build a workflow. Why we keep agents inside single steps, and the tool design that matters more.
- [Why AI Agents Fail in Production: 5 Causes and Fixes](https://ai.dingboai.com/en/why-ai-agents-fail-in-production.html)  
  Great in the demo, unreliable on real work. Five causes we hit running AI agents on live customer service, what each looked like, and the fix that worked.
- [RAG Not Finding Answers? Five Knowledge Base Problems](https://ai.dingboai.com/en/rag-not-finding-answers.html)  
  Documents uploaded, dashboard all green, yet the RAG chat cannot find the answer. Five causes we traced in production, and a fixed three-step acceptance check.
- [Private LLM Deployment: When On-Premise Is Worth It](https://ai.dingboai.com/en/private-llm-deployment.html)  
  Before a private LLM deployment, decide whether you need a private model or private data. Most businesses need the second, which costs far less.

## Checklists

- [Seven steps to build an AI agent that survives real work](checklists/build-an-ai-agent.md)
- [Questions to ask before buying an AI agent](checklists/vendor-questions.md)
- [How to review customer satisfaction ratings](checklists/csat-review.md)

## Contact

Questions or a job you want an agent to take over: yzh317179958@163.com, or the form at [ai.dingboai.com](https://ai.dingboai.com/). The notes are © Shenzhen Dingbo Intelligent Technology Co., Ltd. Link to them freely.
