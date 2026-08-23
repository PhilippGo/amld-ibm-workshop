# The Agent Journey

**A Hands-On Path from Building and Integrating to Observability**

Workshop materials from [Applied Machine Learning Days (AMLD) 2026](https://2026.appliedmldays.org/) at EPFL Lausanne, 12 February 2026. Run by IBM Switzerland as a half-day hands-on session.

Participants build a multi-agent system end to end: designing the agents, connecting them to an existing backend through an OpenAPI specification, adding external tools, and then looking at how the whole thing behaves once it is running.

The workshop assumes no prior agent experience. It does assume you are comfortable reading an API spec and clicking through a browser-based tool.

---

## Prerequisites

- A laptop with a browser. No local installation required.
- An IBMid. See setup below.
- Access to the workshop environment on IBM watsonx Orchestrate, provisioned for registered participants.

---

## Setup

Run through these before the session starts. It takes about ten minutes and the first step occasionally needs a retry.

**1. Create your IBMid**

Use the same email address you registered with. If the addresses do not match, the environment invitation will not resolve to your account.

**2. Log in to watsonx Orchestrate**

You should have received two emails. The link in the first is sometimes blocked by corporate mail filters. If that happens, use the link in the second email instead:

```
https://eu-central-1.dl.watson-orchestrate.ibm.com/
```

If prompted for two-factor authentication, sending the code to your email is the quickest route. Keep the tab open once you are in.

**3. Open this repository in a second tab**

Instructions for the lab live in [`insurance_lab/`](insurance_lab/). Work through them in order.

**4. Use the provided test identity**

The lab uses a fictional customer, `Juan Andrade`. Enter the name exactly as written. No real personal data is used anywhere in this workshop, and the backend is a mock system.

---

## The lab: an insurance claims assistant

You build a small multi-agent system serving two different users, a customer and a claims processor, from one entry point. [`Get started`](insurance_lab/)

---

## Presenters

- **Mohamed Ali Dhraief**, AI Engineer, IBM
- **Dr. Naim Zierau**, AI Architect, IBM
- **Philipp Gordetzki**, AI Engineer, IBM

Questions about the material are welcome as issues on this repository.
