# React-apollo for state management

Date: 2023-06-19

Status: Accepted

## Context

We need to choose a state management solution for our React application. React-apollo has been proposed to use manage both client and server side state in our application.

## Decision

We will use react-apollo for manage state in our React application.

## Consequences

Consistency: Same API on client and server state managed by React Apollo Client.

Reactive variables: Local reactive variables that can be used anywhere in your app and work with Apollo Client's reactive UI data.

Realtime updates: Ability to subscribe to data changes on the client.

Caching: Client cache avoids unnecessary network requests.

API layer: Abstracts details of API networking from components.

Developer tool: Apollo DevTools for debugging and monitoring.
