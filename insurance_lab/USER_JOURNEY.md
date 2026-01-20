# 🚗 Auto Insurance Claim Automation - User Journey

## Overview

This document illustrates the transformation from traditional, manual insurance claim processing to an AI-powered, automated experience using watsonx Orchestrate.

---

## **Meet Sarah - The Frustrated Customer**

Sarah was rear-ended at a traffic light. Her car has significant damage, and she needs to file an insurance claim with ABC Insurance.

### **The Old Way (Before Agentic AI)** 😫

```mermaid
journey
    title Sarah's Frustrating Insurance Claim Journey (Legacy System)
    section Incident Occurs
      Car accident happens: 1: Sarah
      Takes photos with phone: 3: Sarah
    section Filing Claim
      Calls insurance hotline: 2: Sarah
      Waits on hold 45 minutes: 1: Sarah
      Explains incident verbally: 2: Sarah
      Told to mail documents: 1: Sarah
    section Paperwork Hell
      Prints claim forms: 2: Sarah
      Fills out 12-page form: 1: Sarah
      Scans documents: 2: Sarah
      Emails everything: 3: Sarah
      Realizes missing info: 1: Sarah
      Repeats process: 1: Sarah
    section Waiting Game
      No status updates: 1: Sarah
      Calls for updates: 2: Sarah
      Transferred 3 times: 1: Sarah
      Still no clear answer: 1: Sarah
    section Resolution
      Claim approved after 3 weeks: 4: Sarah
```

**Sarah's Pain Points:**
- ⏰ **45-minute hold times** just to speak to someone
- 📄 **12 pages of confusing paperwork** with insurance jargon
- ❓ **Zero visibility** into claim status
- 📞 **Multiple follow-up calls** with no clear answers
- ⏳ **3+ weeks** to get claim approved

---

### **The New Way (With Agentic AI)** 🎉

```mermaid
journey
    title Sarah's Seamless Insurance Claim Journey (AI-Powered)
    section Incident Occurs
      Car accident happens: 1: Sarah
      Opens insurance app: 5: Sarah
    section AI-Guided Submission
      AI asks simple questions: 5: Sarah
      Uploads photos from phone: 5: Sarah
      AI extracts all details: 5: Sarah
      Reviews pre-filled form: 5: Sarah
      Submits in 5 minutes: 5: Sarah
    section Automated Processing
      AI validates policy: 5: Sarah
      AI checks claim history: 5: Sarah
      AI detects no fraud flags: 5: Sarah
      AI generates settlement: 5: Sarah
    section Real-Time Updates
      Gets instant confirmation: 5: Sarah
      Receives status updates: 5: Sarah
      Asks AI about coverage: 5: Sarah
      Gets clear explanations: 5: Sarah
    section Quick Resolution
      Claim approved in 2 days: 5: Sarah
      Payment processed: 5: Sarah
```

**Sarah's New Experience:**
- ⚡ **5 minutes** to submit claim via guided digital interface
- 🤖 **AI extracts** all information from photos automatically
- 📱 **Real-time updates** via app notifications
- 💬 **Instant answers** to policy questions via conversational AI
- ✅ **2 days** to claim approval (vs. 3 weeks)

---

## **Meet David - The Overwhelmed Claim Processor**

David processes 50+ claims per week at ABC Insurance. He's drowning in manual work.

### **The Old Way (Before Agentic AI)** 😓

```mermaid
journey
    title David's Overwhelming Workday (Legacy System)
    section Morning Rush
      Opens 30 new claims: 2: David
      Manually enters data: 1: David
      Switches between 5 systems: 1: David
    section Data Validation
      Checks policy details: 2: David
      Looks up claim history: 2: David
      Calls customer for missing info: 1: David
      Waits for callback: 1: David
    section Fraud Detection
      Reviews photos manually: 2: David
      Compares to similar claims: 2: David
      Flags suspicious patterns: 3: David
      Escalates to supervisor: 2: David
    section Settlement Decision
      Calculates settlement: 2: David
      Reviews policy conditions: 2: David
      Writes justification: 2: David
      Gets manager approval: 2: David
    section End of Day
      Processed only 8 claims: 1: David
      42 claims still pending: 1: David
      Works overtime: 1: David
```

**David's Pain Points:**
- 🔄 **Manual data entry** across 5 different systems
- 📞 **Constant phone calls** for missing information
- 🕵️ **Manual fraud detection** - time-consuming and error-prone
- 📊 **Complex calculations** for settlement amounts
- ⏰ **Only 8 claims/day** processed - backlog keeps growing

---

### **The New Way (With Agentic AI)** 🚀

```mermaid
journey
    title David's Efficient Workday (AI-Powered)
    section Morning Review
      AI pre-processed 30 claims: 5: David
      Reviews AI summaries: 5: David
      Focuses on complex cases: 5: David
    section Automated Validation
      AI validated all policies: 5: David
      AI cross-checked history: 5: David
      AI flagged 2 for review: 5: David
    section Smart Fraud Detection
      AI detected anomalies: 5: David
      Reviews AI recommendations: 5: David
      Approves AI findings: 5: David
    section AI-Assisted Decisions
      AI calculated settlements: 5: David
      Reviews AI reasoning: 5: David
      Approves recommendations: 5: David
    section End of Day
      Processed 45 claims: 5: David
      High-quality decisions: 5: David
      Leaves on time: 5: David
```

**David's New Experience:**
- 🤖 **AI handles** 90% of routine data entry and validation
- 🎯 **AI prioritizes** claims needing human attention
- 🔍 **AI detects** fraud patterns automatically
- 💡 **AI recommends** settlement amounts with reasoning
- ✅ **45 claims/day** processed (5.6x improvement)

---

## **Business Impact Summary**
Numbers are assumed.

| Metric | Before AI | With AI | Improvement |
|--------|-----------|---------|-------------|
| **Claim Submission Time** | 45+ minutes | 5 minutes | **9x faster** |
| **Claim Processing Time** | 3+ weeks | 2 days | **10x faster** |
| **Claims per Processor/Day** | 8 claims | 45 claims | **5.6x more** |
| **Customer Satisfaction** | 2.5/5 ⭐ | 4.8/5 ⭐ | **92% increase** |
| **Fraud Detection Rate** | 65% | 94% | **45% improvement** |
| **Operational Cost** | High | 40% lower | **40% savings** |

---

## **Key Takeaway**

**Goal:** Transform frustrating, slow insurance claims into seamless, fast experiences for both customers and processors through AI automation.

**Value:** 
- Customers get claims resolved in **days** (not weeks)
- Processors handle **5x more claims** with better accuracy
- Company reduces operational costs by **40%**
- Fraud detection improves by **45%**

---

## Learn More

See the [main README](./README.md) for technical details and the [hands-on lab](./assets/hands_on_lab_autoclaim_insurance.md) to build this solution yourself.