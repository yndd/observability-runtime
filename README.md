# observability runtime

The major differences with the config runtime

- no validation, other than ygot
- connector only implements (observe, create, delete, close)
    - updates are handled by subscribing again to the system (start/stop the subscription)
- No system cache


