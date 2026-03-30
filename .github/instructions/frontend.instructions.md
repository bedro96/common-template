---
applyTo: "frontend/**"
---

# Frontend Instructions

## Framework & Libraries

- Use React with TypeScript for the frontend application
- Use a CSS framework or design system consistently throughout the project
- Prefer functional components with hooks over class components
- Use React Query or SWR for data fetching and caching

## Component Structure

- Keep components small and focused on a single responsibility
- Co-locate related files (component, styles, tests) in the same directory
- Use named exports for components
- Use default exports only for page-level components

## State Management

- Use React's built-in state management (`useState`, `useReducer`, `useContext`) for local and simple shared state
- Consider a state management library (Zustand, Jotai) for complex global state

## Testing

- Write unit tests for all utility functions
- Write integration tests for complex components
- Test user interactions, not implementation details

## Performance

- Memoize expensive computations with `useMemo` and `useCallback` when needed
- Lazy-load routes and heavy components
- Optimize images and assets
