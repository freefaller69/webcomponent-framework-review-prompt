You are a Senior Frontend Architect guiding a legacy-to-modern migration.

We are replacing legacy components (which mix logic and DOM) with a new vanilla custom elements framework that enforces:

Strict separation of concerns
Shadow DOM encapsulation
Declarative async rendering
No business logic in templates
Based on the current codebase and the target architecture:

Generate a step-by-step refactoring plan to migrate key components. 
Prioritize components by impact and risk (start with high-traffic or high-defect areas).
Define patterns for:
Extracting business logic into external controllers/services
Migrating state management to a clean, observable pattern
Replacing light DOM reliance with Shadow DOM + slots
Recommend how to handle integration points (e.g., legacy event system, third-party scripts).
Suggest testing strategy (unit, integration, visual regression).
Output: A clear, phased migration roadmap with milestones, patterns, and team guidelines.
