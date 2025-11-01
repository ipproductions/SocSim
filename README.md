# 🌐 SocSim: Agent-Based Model of Cooperation & Competition

## Overview

This project is an **Agent-Based Model (ABM)** simulation developed using vanilla JavaScript and HTML Canvas. It models a dynamic, complex society to investigate the stability, inequality, and resilience of different behavioral strategies (Cooperation, Competition, Defection, and Predation) under varying economic and political pressures.

The simulation currently runs a **High-Deterrence, High-Pressure Stress Test** designed to analyze the fundamental trade-off between **individual economic excellence** and **collective systemic security**.

## 🔬 Core Sociological Theories Modeled

The simulation mechanics are designed around several key concepts from behavioral economics and game theory:

* **Public Goods & Governance:** Agents are taxed to fund the Enforcer force, modeling the establishment and fiscal constraint of a minimal state.
* **Collective Action Dilemmas:** Cooperators invest in **Co-op Nodes (Club Goods)**, which provide exclusive resources and impose harsh punishments on free-riders (Defectors).
* **Reciprocity:** Cooperators practice a form of "tit-for-tat," permanently excluding Defectors from sharing after a low threshold of betrayal.
* **Economic Theory of Crime:** Predators balance the high rewards of theft (35% mass stolen) against the high costs of deterrence (long jail time, low bribe chance).
* **Bioeconomics:** A high base mass decay rate simulates a steep "cost of living," driving constant resource acquisition and competition.

## 👥 Agent Types & Behavioral Strategies

| Agent Type | Color | Primary Goal | Key Mechanics |
| :--- | :--- | :--- | :--- |
| **Cooperator** | Green/Cyan | Mutual gain, group stability. | Accepts a **50% base mass penalty** and invests **15%** of gains into Co-op Nodes. Trades individual wealth for systemic resilience. |
| **Defector** | Purple | Free-ride on Cooperation. | Attempts to exploit Cooperators' sharing and consume resources from Co-op Nodes, but faces a **30% mass punishment** upon discovery. |
| **Competitor** | Orange | Individual self-interest. | Maximizes resource efficiency (100% gain, no sharing/investment). Exhibits highest individual wealth accumulation but relies solely on Enforcers for protection. |
| **Predator** | Red | Exploitation through theft. | Steals **35%** of a victim's mass. Can build **Predator Nodes (Sanctuaries)** to evade the law, modeling illicit territories. |
| **Enforcer** | Blue | Deter crime, protect public mass. | Patrols autonomously, arresting high-crime Predators based on visibility (Vision: 150) and funding (Salary: 3.0). |

## 💡 Key Findings from Stress Test Configuration

The current configuration creates extreme incentives, leading to a profound observation on the cost of society:

| Observation | Implied Sociological Insight | Supporting Mechanic |
| :--- | :--- | :--- |
| **Competitors achieve the highest individual Mass/Capita.** | Individual rational self-interest is the most profitable short-term economic strategy in a tension-filled environment. | They pay no contribution/tax and claim 100% of their mass gain, free-riding on the security provided by the taxed populace. |
| **Cooperators have the lowest Mass/Capita.** | The creation and maintenance of a resilient society requires significant, ongoing individual economic sacrifice. | Cooperators face a cumulative 50% resource penalty, 15% node contribution, and 50% sharing cost. |
| **The Sacrifice is Systemic Insurance.** | The Cooperator's "loss" of wealth translates directly into a stable life with police protection, protected resources, and internal quality control, acting as systemic insurance against total economic collapse under high pressure. | Co-op Nodes and Enforcers stabilize the food supply and lower the threat level, preventing the group from being decimated by the high 0.04 decay rate. |

## 🚀 How to Run the Simulation

The simulation is built entirely in vanilla JS and HTML.

1.  Clone this repository or download `index.htm`, `style.css`, and `v03.js`.
2.  Open `index.htm` directly in any web browser.

The configuration panel will load with the parameters detailed above. Click **"Start Simulation"** to observe the dynamics.

## ⚙️ Configuration Details (Applied Defaults)

The simulation uses the following high-pressure default configuration:

| Category | Parameter | Value |
| :--- | :--- | :--- |
| **Governance** | Enforcer Salary (per frame) | 3.0 |
| | Enforcer Vision (pixels) | 150 |
| **Justice** | Jail Time (frames) | 2500 |
| | Bribe Chance (%) | 5 |
| **Predation** | Theft Rate (%) | 35 |
| **Cooperation** | Node Contribution Rate (%) | 15 |
| | Node Punishment Rate (%) | 30 |
| **Economy** | Resource Mass Gain | 75.0 |
| | Base Mass Decay | 0.04 |

## 📜 License

This project is licensed under the **MIT License**.