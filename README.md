## Project Name

Helixsense - Multiscreens

## Description

Multiscreens is about, Digital transformation of facilities and property management, end users can see the data in visualized format.

## Table of Contents

- [Installation](#installation)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [About Techstack](#about-techstack)
- [Style Guide](#style-guide)
- [Naming Conventions](#naming-conventions)
- [Folder Structure](#folder-structure)
- [State Management](#state-management)
- [Architecture](#architecture)

## Installation

1. Clone the repository: `git clone https://github.com/saikumartyny/multiscreens.git`
2. Navigate to the project directory: `cd Mulltiscreens`
3. Install dependencies: `npm install`
4. Start project: `npm run dev`

## Technologies Used

- React
- NodeJS
- Typescript
- Material UI, CSS

## About Techstack
Need to known
- HTML
- CSS
- Javascript
- React JS
- Node JS
- Typescript
- Meterial UI

## Naming Conventions
- camelCase

## Style Guide
- primary color: #083890;

- primary-font: 'Mulish';
- secondary-font: 'Roboto';

- icons : https://react-icons.github.io/react-icons/

## Folder Structure

src/
|-- components/
|-- appData/
|-- pages/
|-- hooks/
|-- utils/
|-- assets/
|-- App.tsx
|-- index.css

- components: UI componens (Ex: buttons,forms, cards, loaders)
- appData: Application's data
- pages: Routing pages - main page, operations page, cards page
- hooks: API hook
- utils: Reusable function logics
- assets: fonts, icons
- App: root file
- index.css: styles

## State Management
- useState hook

## Architecture
Designing a robust architecture for your React app is crucial for scalability, maintainability, and code organization. Here's a more detailed breakdown of the different layers and components you might consider in your React app architecture:

1. **Folder Structure:**

   - **components/**: Reusable UI components that can be used across the app
   - **pages/**: Top-level components that define different routes or views of your app.
   - **utils/**: Helper functions, utility modules, and constants.
   - **assets/**: Static assets like images, fonts, and other media files.
   - **styles/**: Global and component-specific styles.

2. **State Management:**

   - **Local State**: For simpler apps, React's built-in state management using `useState` and `useReducer` might suffice.
   
3. **Routing:**

   - **react-router**: A widely used library for handling navigation and routing in React apps.

4. **API Communication:**

   - **Axios**: A popular library for making HTTP requests.
   - **Fetch API**: JavaScript's built-in mechanism for making network requests.

5. **Authentication and Authorization:**

   - **OAuth**: A protocol for authorization; useful for integrating third-party services.


6. **Error Handling:**

   - **Error Boundaries**: Use React's error boundaries to catch and handle errors within components.
  
7. **Deployment:**

   - **CI/CD**: Set up Continuous Integration and Continuous Deployment pipelines for automated testing and deployment.

8. **Code Quality:**

    - **ESLint**: A linter for code quality and style consistency.
    - **Prettier**: A code formatter to maintain consistent code style.


## Contributing

saikumartyny

## Contact

Saikumar Vasamsetti
email: saikumar.vasamsetti@tynybay.com
