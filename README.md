# Collaborative Autonomy
Exploring the principles of autonomy through simple code &amp; simulations.

Concepts pulled from [Ten Challenges for Making Automation a “Team Player” in Joint Human-Agent Activity](https://ieeexplore.ieee.org/document/1363742).

10 elements necessary for an effective Human Machine Team, paraphrased by myself:

The Basic Compact - Each agent needs to recognize that they are part of a team, and will work as such. A group of agents that aren’t aware of each other and can not adapt to each other are not a team.
Adequate Models - All agents must be able to model the other agents’ intentions and actions regarding the joint activity.
Predictability - The human and machine components should be mutually predictable.
Directability - Agents must be dynamically directable.
Observability - Agents should make status and intentions obvious for their teammates. This isn’t full-blown explainability. Observability is focused on maintaining common ground during the current joint activity. Explainability is more for post activity understanding.
Interpreting Signals - The other side of observability. Agents should be able to interpret relevant signals produced by the other agents.
Goal Negotiation - An agent must be able to convey their current and potential goals, and there should be a way to update those goals. This can be seen as a subset of Directability.
Collaboration - A synthesis of many of the prior elements. The agents must be able to communicate. Planning, replanning, and retasking should take into account capabilities, states, and goals of the agents.
Attention Management - Common ground management is a vital function of the joint system. Agents need to be able to alert the other agents in the system to important changes in state, but can’t simply output every change, or they could overwhelm the other agents. Different agents will need different levels of communication.
Coordination Cost Control - A synthesis of Attention Management, the Basic Compact and other points. Coordination is costly, and it must be paid for by all the agents throughout the joint activity.

I believe these can be simply explored in code without machine learning. That's what I'm going to be doing in this repo.
