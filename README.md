# Conversational Agentic Checkout

A complete, interactive single-page web app demo built for the **AI Growth & Agentic Commerce** track. 
This demo showcases an end-to-end AI agent checkout flow that grows a merchant's revenue while making them fully transactable by AI buyers.

## 🚀 Live Demo
Simply download and open `checkout_demo.html` in any modern web browser to experience the demo. 
*No backend, databases, or build steps required.*

## 🏆 Hackathon Track Alignment (Track 01)
This project hits all mandatory requirements (**The Bar**) and covers 3 out of 4 **Example Directions**.

### The Bar (Met)
* **Explainable:** Persistent, live-updating 31-entry System Audit panel tracks every single API interaction (UAP, AP2, ACP).
* **Bounded:** Users must explicitly sign a Cryptographic Intent Mandate strictly limiting the AI to a ₹5,000 max spend and a 24-hour expiry.
* **Gated:** The agent cannot proceed without AP2 Authorization Service issuing a Verifiable Credential (VC).
* **Graceful Failure:** A built-in toggle simulates a Razorpay API failure. The agent cleanly handles the timeout, preserves the cart state, and logs a rollback.

### Example Directions Implemented
1. **Conversational in-app checkout:** A fully scripted 12-state conversational UI (Agent 1: Negotiator) guides the user from intent to payment.
2. **Agent-readable catalog:** Includes a dedicated Catalog dashboard exposing the simulated `ACP Catalog API`, complete with machine-readable tags and an `agent_score` for SKUs.
3. **Upsell & cross-sell agent:** Dynamically queries the catalog's upsell graph to recommend complementary add-ons that fit within the remaining mandate limit, actively **growing merchant revenue** by tracking the specific `+₹X` uplift.

## 💻 Tech Stack
* **Frontend UI:** Pure HTML, CSS (Vanilla), and JavaScript.
* **Aesthetics:** "Nexus Terminal" design system featuring dark glassmorphism, dynamic data visualizations, SVG network animations, and a rich color palette (Indigo/Violet/Emerald/Amber).

## 🛠️ Features
* **Multi-Dashboard Architecture:** 
  * **Dashboard:** Live KPI tracking, spending charts, and system health status.
  * **Mandates:** Table view of all active cryptographic intents with detailed inspection.
  * **Agents:** The core 3-panel chat interface (Mandate Context / Live Chat / Audit Trail).
  * **Security:** AP2 Authorization visualizations, verifiable credentials, and compliance policy checks.
