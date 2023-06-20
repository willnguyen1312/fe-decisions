# React-apollo for state management

Date: 2023-06-20

Status: Accepted

## Context

We need to choose a state management solution for our React application. React-apollo has been proposed to use manage both client and server side state in our application.

## Decision

We will use react-apollo for manage state in our React application.

## Consequences

Consistency: Same API on client and server state managed by React Apollo Client.

Reactive variables: Local reactive variables that can be used as a mechanism for representing local state outside of the Apollo Client cache. Additionally, it is possible to trigger an update of active queries and components that depends on that variable.

Queries and mutations: Ability to query and mutate data on the client.

Realtime updates via subscription: Ability to subscribe to data changes on the client.

Caching: Client cache layer of React-apollo helps to avoid unnecessary network requests.

API layer via hooks: Abstracts details of API networking from components.

Developer tool: Apollo DevTools for debugging and monitoring.
