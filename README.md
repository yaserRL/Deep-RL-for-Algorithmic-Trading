Deep RL for Algorithmic Trading

Overview

This project explores the vulnerability of Deep Reinforcement Learning (DRL) agents in algorithmic trading to adversarial attacks. The study highlights how such attacks can manipulate trading policies, leading to suboptimal or harmful decisions. It also provides insights into threat modeling, attack techniques, and experimental results demonstrating the feasibility and severity of these attacks.

Key Features

Threat Model for DRL Trading Agents:
Identifies potential attack surfaces, including observation and reward channels.
Describes attack vectors such as Man-In-The-Middle (MITM) and Denial of Service (DoS).
Adversarial Attack Techniques:
Non-targeted attacks (e.g., delays, random perturbations).
Targeted attacks that influence agents to perform specific, suboptimal actions.
Experimental Setup:
Includes environments based on OpenAI Gym and TensorTrade frameworks.
Demonstrates attacks in both simplified and realistic trading scenarios.
Findings:
Adversarial examples (e.g., FGSM and C&W attacks) negatively impact DRL agents’ performance.
Observational delays (e.g., via DoS) significantly reduce agent rewards.
Highlighted risks to portfolios tied to trading agents due to test-time attacks.
Contents

TensorTradeDQN_Attack.ipynb: Jupyter Notebook implementing DRL trading attacks.
Deep RL .pdf: Research paper providing in-depth technical details.
README.md: This document.
Key Insights

DRL Vulnerabilities:
DRL trading agents are highly susceptible to adversarial manipulations, affecting both performance and external portfolios.
Even minor perturbations can lead to drastic financial impacts.
Experimental Results:
Non-targeted attacks reduced total rewards and altered agent behavior.
Targeted attacks manipulated agents to take predefined suboptimal actions, impacting net worth.
Future Directions:
Development of resilience metrics and robust defenses against adversarial attacks.
Improved risk management strategies for DRL-based trading agents.
Tools and Frameworks

Deep Reinforcement Learning: Focus on Deep Q-Networks (DQN).
OpenAI Gym: Simplified trading environment.
TensorTrade: Advanced framework for realistic trading simulations.
Authors

Yaser Faghan, Nancirose Piazza, Vahid Behzadan, and Ali Fathi
Institutions include: University of Lisbon, University of New Haven, and Royal Bank of Canada.
