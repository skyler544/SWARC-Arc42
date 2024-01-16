[<< Back](/README.md)

## Quality Attributes (ISO 9126)

- Portability
    - Replace-ability
        - Components are designed such that they can be replaced with new technologies if needed.
    - Installability
        - The services are constructed to be deployed quickly and simply whenever new features are completed.
- Maintainability
    - Stability
        - Normal use of the services does not cause crashes or loss of data.
    - Testability
        - Features have concrete interfaces which are thoroughly tested.
- Efficiency
    - Time behaviour
        - User-facing database transactions return within 500ms. 
    - Resource demand
        - Inactive instances do not consume machine resources, thereby saving on cloud infrastructure costs.
- Functionality
    - Security
    - Accuracy
- Reliability
    - Recoverability
        - The system is able to be restored to a recent state.
- Usability
    - Learnability
        - Tips are shown to the user
    - Understandability
        - Interfaces for users are easy to understand, precise and concise.

## Quality Scenarios

1. Driver accepts a contract. A canceled request is shown in a span of 2-3 seconds. 
2. User opens the application. All possible routes are shown in under 5 seconds.
3. The user makes a request that fails. The user is informed about the error and its reason. The error is shown in under 10 seconds.
