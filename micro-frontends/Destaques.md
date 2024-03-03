<!-- 
Justify using arguments related to
- Simplicity
- Single responsibility
- Reusability
- Independent deployment
- Autonomous teams
- Vertical services
- Flexibility
- Define the responsibility of each
micro-frontend 
-->

## Title
Destaques
## Context and Responsibility
This microfrontend contains the Highlights inside a specific category with the message regarding the reason why it is highlighted.
## Decisions
Our biggest motivation to consider this as a microfrontend was an example shown in class, to which we agreed that there should be a team that could manage the highlighted products as well as the reason as to why they are highlighted. This decision aligns with the principle of Single Responsibility, ensuring that the Destaques microfrontend is focused solely on managing and updating the highlighted products within a specific category.
## Consequences
* Good:
1. Grouping highlighted product-related functionalities within a single microfrontend promotes a simpler and more cohesive codebase.
2. By isolating highlighted product-related functionalities, teams can work autonomously on the Destaques microfrontend, fostering ownership and accountability.
* Bad:
1. We were apprehensive about this microfrontend being too simple for one whole team.