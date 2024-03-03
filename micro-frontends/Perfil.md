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
Perfil
## Context and Responsibility
Enables users to access and manage their personal information (such as profile photo, username, email,...); Provides access to app settings for customization and configuration ; Also includes a company contact form for users to reach out. 
## Decisions
We chose to consolidate these slightly varied features due to their shared emphasis on user preferences and needs that diverge from the app's primary focus. Users can tailor certain aspects to their liking within both app settings and profile information. Moreover, the contact form serves as a direct channel for users to communicate with the app's business, enabling them to report complaints and provide recommendations aimed at enhancing the overall user experience.
Another reason that led to this choice is due to the lack of information displayed in the prototype. We are not sure what's the content presented in the pages that the buttons would lead us to.
## Consequences
* Good:
 1. This aggregation choice promotes simplicity due to the aggeragation that was created. If there were three distinct microfrontends instead, it    would entail minimal effort for those teams.
 2. As this microfrontend is focused on dealing with features unrelated to the app's primarly focus, it's an isolated matter. Therefore allows autonomous teams that focus on independent features.

* Bad:
 1. This frontend doesnt promote reusability due to the fact that is a really specific part of the app.