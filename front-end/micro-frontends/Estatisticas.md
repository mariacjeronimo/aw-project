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
Estatisticas
## Context and Responsibility
This microfrontend consolidates all functionalities related to meat-related statistics. This includes the button to access the page, as well as negative and positive data since the year 2021 until the present.
## Decisions
We believe that this microfrontend is acceptable business-wise, as there should be a team specifically dedicated to managing the statistics section of the app. This decision aligns with the principle of Single Responsibility, ensuring that the Estatisticas microfrontend is focused solely on statistics-related functionalities. By organizing these features together, we promote simplicity and clarity in code management and development. Additionally, this approach fosters independent deployment, allowing the statistics team to work autonomously on the Estatisticas microfrontend without affecting other parts of the application.
## Consequences
* Good:
1. The Estatisticas microfrontend is dedicated solely to statistics-related functionalities, reducing complexity and improving code organization.
2. The statistics team can deploy updates or changes to the Estatisticas microfrontend independently, minimizing disruptions to other parts of the application and enabling faster iteration.
* Bad:
1. As the application grows and evolves, the Estatisticas microfrontend may become too large and unwieldy, leading to performance issues and difficulties in maintaining and extending its functionality.