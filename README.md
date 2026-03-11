# tailspend

&gt; Autonomous AI agents for the 80% of procurement chaos that nobody wants to touch.

---

## The Problem

**Tail spend**—the 80% of transactions that make up only 20% of your spend—is procurement's neglected stepchild. High volume, low value, decentralized, and often completely unmanaged. It slips through ERP cracks, breeds maverick buying, and quietly erodes 5-10% of potential savings.

Most procurement teams ignore it because fighting a thousand $500 battles feels impossible. Consultants sell you visibility dashboards. We give you autonomous execution.

---

## What This Is

An open-source framework of AI agents that handle tail spend workflows end-to-end:

| Agent | What It Does | Status |
|-------|-----------|--------|
| **Supplier Intelligence** | Builds negotiation dossiers from public data, earnings calls, market signals | 🚧 In Progress |
| **Spot Buy Executor** | Autonomously executes low-value purchases within guardrails (spend limits, approved vendors, compliance) | 📋 Planned |
| **Contract Auditor** | Matches invoices to contracts, flags discrepancies, learns your risk patterns | 📋 Planned |

---

## Why Open Source?

Procurement is too relationship-heavy and compliance-obsessed for black-box AI. This is a transparent, extensible framework for teams who want to automate the tactical without losing control of the strategic.

Every decision is logged. Every guardrail is inspectable. Every agent action can be overridden.

---

## Quick Start

```bash
# Clone
git clone https://github.com/yourusername/tailspend.git
cd tailspend

# Install (uv recommended)
uv venv
source .venv/bin/activate
uv pip install -e .

# Configure
cp .env.example .env
# Add your OPENAI_API_KEY or ANTHROPIC_API_KEY

# Run
python -m tailspend demo "Acme Semiconductor GmbH"
