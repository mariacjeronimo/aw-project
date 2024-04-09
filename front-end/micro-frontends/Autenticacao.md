
<!-- 
Justify using arguments related to
- Simplicity
- Single responsibility  /////
- Reusability
- Independent deployment /////
- Autonomous teams       /////
- Vertical services
- Flexibility
- Define the responsibility of each
micro-frontend 
-->

## Title
Autenticação
## Context and Responsibility
Allows the user to login and logout from the app taking into consideration security, privacy and data integrity.
## Decisions
We decided to aggregate both login page and the logout button (present on the profile page). This way all the authentication logic can be developed by the same team allowing an independent and cohesive approach to managing user authentication. This decision aligns with the principle of "Single responsibility", "Independent deployment" and "Autonomous teams" ensuring that each component is responsible for a specific task without causing unnecessary dependencies or conflicts with other parts of the system.
## Consequences
* Good: 
1. The Authentication micro-frontend maintains a clear and singular purpose, enhancing its simplicity and maintainability.
2. Single Responsibility allows for easier understanding and debugging of code within the micro-frontend.
* Bad:
1. It might result in larger initial development effort, as all authentication-related features are concentrated within one component.