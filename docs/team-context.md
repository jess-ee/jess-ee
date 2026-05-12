# Sales Agent Team — Context

Captured 2026-05-12. Use this as durable context for future visualizations, planning, and onboarding conversations.

## What the team owns

The Sales Agent team is responsible for **two product surfaces** that together form the conversational shopping layer:

1. **Cues** — inline conversational elements embedded across the website. Smaller, page-scoped widgets that answer focused questions in-page (product pages, filter pages, advice pages, etc.).
2. **Sales Agent** — the full-screen, full-journey conversational interface. A deep agent that needs all capabilities required to convert a visitor all the way to the `/basket` page.

The team's job is to **build and combine** these elements and **create new journeys** with them.

## What "building the Sales Agent" entails

The Sales Agent is itself a thing to be built. It consists of:

- The **harness** (runtime, orchestration)
- **Commerce capabilities** (cart, pricing, availability, checkout-relevant actions)
- **UI** (chat surface, components, transitions)
- **Skills** — built in close collaboration with the **Product Advice Journey (PAJ) team**, per product cluster

## Two directions of collaboration

The team sits between two flows of work:

### A. "Integration In" — domains wanting their thing represented in the agentic journey

These teams approach Sales Agent to **integrate their capability or content into the agent / cues**:

- **Pre-cart teams** — page integrations for specialised cues on their pages (Sales Agent connects cues, links them to the Sales Agent itself)
- **Stores** — store agent
- **Insurances**
- **Installation services**
- **Energy contracts**
- **B2B**
- **Product support**
- **Cross-sell**

### B. "Feedback Out" — domains wanting data/insights from the agent

These teams want signal flowing back **out** of the agent (conversation insights, behaviour, feedback loops):

- **Category teams** — read conversations for assortment decisions, agent improvement, content
- **Pre-cart** — insights to inform website organisation and new UI / visualisations
- **Product Advice Journey team** — improve ground truth
- **Marketing** — retargeting, personas, messaging
- **Sales Agent team itself** — new capabilities and UI driven by real interactions

## The special triangle: PAJ ↔ Category teams ↔ Sales Agent

- **Skills per product cluster** are built in collaboration with PAJ.
- **Category teams** are responsible (via PAJ) for the skills given to the agents for their cluster.
- They want **insights** and they want **knobs** to influence the experience of *their* agent.
- **Today** they can influence: instructions, the questions, and the filters selected.
- **Future** knobs could include: UI elements, special features per important cluster.

## Why this matters

The team is structurally a **hub**: many teams push *into* the agent, many teams pull insight *out*. The PAJ + Category relationship is the load-bearing collaboration for product-specific quality. Visualisations should make the hub-and-spoke nature clear and separate the two directions of value flow.
