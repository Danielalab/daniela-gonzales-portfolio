---
title: "Rimac Insurance Quote Generator"
description: "This project is a single-page web application developed for the Hacking Challenge Rimac. It serves as a comprehensive tool enabling customers to easily quote and customize their vehicle insurance plan 🚗."
image: "../../assets/insurance.png"
startDate: "2024-12-07"
skills: ["React", "React Router", "Sass (SCSS)", "Bootstrap", "Eslint", "Git & GitHub", "Firebase Hosting"]
sourceLink: "https://github.com/Danielalab/hacking-challenge-rimac"
demoLink: "https://hacking-challenge-rimac.web.app/"
---

## Project Overview

This project is a single-page web application developed for the "Hacking Challenge Rimac." It serves as a comprehensive tool enabling customers to easily quote and customize their vehicle insurance plan 🚗.

### Core Features & Functionality
- Custom Quotation: Users can enter their personal and vehicle details to generate an initial insurance quote.
- Custom Coverage Selection: Users have the flexibility to adjust the insured amount and dynamically add or remove extra coverage options (e.g., roadside assistance, deductible adjustment) to tailor the plan to their needs.

### Technology Stack
Technology	Role & Key Implementation Details
- React	Core library: for building a Single Page Application (SPA), ensuring fast load times and a responsive UI. Utilized React Hooks for application state management: <ul><li>useState: For component-level internal state.</li><li>useContext: For global state management (e.g., customer name, license plate) across different components.</li></ul>
- React Router:	Used for client-side routing, enabling smooth navigation between different views without full page reloads. Hooks used: useLocation, useHistory.
- PropTypes	Implemented for type checking and validation of properties passed into React components, improving code robustness and catching bugs early.
- Sass (SCSS):	Preprocessor used for writing maintainable and reusable styles through features like nesting, variables, and mixins.
- Bootstrap:	CSS framework used for rapid UI development by leveraging pre-built components and utility classes.
- Eslint:	Development tool used to enforce code quality and maintain a consistent, readable style throughout the project, specifically utilizing the Airbnb Style Guide.
- Git & GitHub:	Used Git for local version control and GitHub for remote repository hosting, managing releases, project planning boards, and tracking issues.
- Firebase Hosting:	Platform as a Service (PaaS) used for fast and reliable deployment of the final application.

### 🚀 Project Planning & Management

This project followed an agile methodology, structured around user stories and a Kanban board.

- Methodology: The project utilized 4 core User Stories, each complete with acceptance criteria and a Definition of Done.
- Kanban Board: Planning and task tracking were managed using a GitHub Project Board View Kanban Board.
- Component First: Before writing the user stories, potential components were identified based on the design mockups View Component List (Figma).

### User Stories

Detailed tasks and development items for each story were tracked as GitHub Issues View Task List.

- [1: User Login: As a Rimac customer, I must be able to log in simply to start quoting my vehicle insurance.](https://github.com/Danielalab/hacking-challenge-rimac/issues/3)
- [2: Vehicle Details & Quote: As a Rimac customer, I must be able to provide my vehicle details and the desired insured amount.](https://github.com/Danielalab/hacking-challenge-rimac/issues/16)
- [3: Coverage Customization: As a Rimac customer, I must be able to add and remove coverages from my vehicle insurance plan.](https://github.com/Danielalab/hacking-challenge-rimac/issues/26)
- [4: Confirmation & Thank You: As a Rimac customer, I must be able to view a thank you page with final instructions.](https://github.com/Danielalab/hacking-challenge-rimac/issues/37)

### Releases

The project was managed and deployed in three main releases:

- [v0.2.0: Boy With Luv](https://github.com/Danielalab/hacking-challenge-rimac/releases/tag/v0.2.0)
- [v0.3.0: ON Kinetic Manifesto Film](https://github.com/Danielalab/hacking-challenge-rimac/releases/tag/v0.3.0)
- [v0.4.0: Fake Love](https://github.com/Danielalab/hacking-challenge-rimac/releases/tag/v0.4.0)
