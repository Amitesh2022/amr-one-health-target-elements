# AMR One Health Target Elements

## One-sentence benefit
Helps health teams coordinate human, animal and environmental targets against antimicrobial resistance.

## Live demo
Run both layers locally, then follow [the verified application demo](docs/demo.webm).

## Screenshots
![AMR One Health target workspace](docs/screenshot.png)

## Main features
Search and sort AMR target cases, create a stewardship action, advance review and inspect priority gaps.

## Technology used
Lit, TypeScript, native Web Components, Vite, Spring Boot and Java.

## Installation instructions
Start `cd backend && mvn spring-boot:run`, then run `npm install && npm run dev` in another terminal.

## Commercial licensing/contact
Commercial licensing and implementation support are available through the repository owner.

## Business problem and users
Public-health, veterinary and environmental teams need shared ownership of consumption, infection and stewardship indicators.

## Key workflows
Filter target cases, create a hospital stewardship target and move a real backend record through review.

## Lit and Web Components highlights
A typed custom element, reactive state, keyed repeat rendering, a controller and reusable status cards are demonstrated.

## Java backend highlights
Spring Boot provides real list, search, create and update endpoints, validation, clear errors, health reporting and tests.

## Architecture and state flow
The custom element fetches authoritative Java records and re-renders when reactive state changes.

## Accessibility and responsive behaviour
Semantic headings, labelled search, visible status text, strong contrast and responsive layouts support varied devices.

## Verification commands
Use `npm test`, `npm run build`, and `cd backend && mvn test package`.

## Structure
`src` contains Lit components, `backend` contains Java, and `docs` contains verified media.

## Tradeoffs
The in-memory store keeps setup simple; production would add surveillance feeds, privacy controls and durable evidence.

## Roadmap
Add 2030 indicators, sector dashboards, laboratory feeds, trend alerts and multilingual awareness packs.
