# Use Vue 3

Date: 2023-06-19

Status: Accepted

## Context

We need to choose a JavaScript framework for the frontend of our application. Vue 3 has been proposed due to its small size, flexibility and performance improvements over Vue 2.

## Decision

We will use Vue 3 to build the frontend of our application.

## Consequences

Positives:

- Composition API: New, flexible way to compose components.
- Faster reactivity system: Up to 3x faster than Vue 2.
- Smaller bundle size: Optimized production bundle.
- Backward compatibility: Vue 3 supports most Vue 2 code.
- Typescript support: Improved Typescript support.

Negatives:

- Learning curve: Developers need to learn Vue's concepts.
- Migration effort: Potential work to migrate from Vue 2.

While there is a learning investment for Vue, the performance, composition API and bundle size improvements outweigh the migration complexity for our application.

Moving forward, all frontend development will be done in Vue 3. We will prioritize documentation, examples and codemod tools to help migrate existing Vue 2 code. Over time we may consider integrating additional libraries to further optimize our Vue components.

We will monitor the stability, performance and maintainability of our Vue 3 code as the application grows in order to determine if any additional optimizations are needed.
