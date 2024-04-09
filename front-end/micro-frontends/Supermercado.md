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
Supermercado
## Context and Responsibility
Allows the user to search for a specific supermarket and view it's location (in a map) and the diverse meat options.
## Decisions
We decided to aggregate similar and related information. The search bar enables the user to select their preferred store location which reveals a map displaying the store's exact position, the available meat categories available at the selected store and the highlights inside a specific category with the message regarding the reason why it is highlighted. 
These features are interdependent, highlighting the rationale behind their grouping, which promotes the principles of single responsibility and autonomous work. By organizing them together, we ensure each feature operates cohesively, facilitating independent development.
## Consequences
* Good:
1. Each feature within the micro-frontend serves a clear and distinct purpose, reducing complexity and improving maintainability.
2. Integration of related functionalities within a single micro-frontend supports a vertical service architecture, improving system coherence and reducing dependencies.
* Bad:
1. Combining features tightly may limit the flexibility to modify or extend individual functionalities without impacting others within the micro-frontend.