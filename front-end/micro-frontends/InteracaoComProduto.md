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
Interação com Produto
## Context and Responsibility
This microfrontend consolidates all functionalities related to user feedback. This encompasses tasks such as adding items to favorites, rating them on a scale of 0 to 5 stars, and displaying reviews from other clients.
## Decisions
We decided to follow this route because all features are interlined. Our biggest motivation was that in this app the users are advised to save the products to their favorites to then later contribute with a rating. This correlation helps the team to focus on all interlined aspects of a problem such as this one. This promotes Independent deployment, Autonomous teams work and flexibility in the development process.
## Consequences
* Good:
1. Organizing feedback-related functionalities within a dedicated microfrontend enhances flexibility, enabling easier modification, extension, and maintenance of these features in isolation.
2. Feedback components can potentially be reused in different projects, enhancing development efficiency and consistency.
* Bad:
1. In terms of simplicity, this microfrontend may pose challenges as it integrates various features scattered across different sections of the app. Additionally, ensuring a seamless user experience across these interconnected features requires careful coordination and testing. 