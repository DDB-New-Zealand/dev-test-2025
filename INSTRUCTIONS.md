# Frontend Developer Technical Test

This task is designed to evaluate your skills in **React**, **Next.js**, **Typescript**, **TailwindCSS**, and **animation libraries** such as **GSAP** or **Framer Motion**. You will build a small application that fetches data from a public API and presents it with engaging animations and a responsive UI.

## Project Requirements

### Tech Stack:

- **React with Next.js**
- **Typescript**
- **TailwindCSS** for styling
- **GSAP** or **Framer Motion** for animations

### Features to Implement:

1. Fetch data from a public API (e.g., [Free Test API](https://freetestapi.com/apis)).
2. Display a list of fetched data on the home page in an attractive and user-friendly way.
3. Provide a detail page for each item in the list (using Next.js dynamic routes). On this page, fetch and display some additional data related to the item.

### Extra Points (complete at least one of these, up to any number as time allows):

- Implement loading states for the API calls (e.g., spinners or skeleton loaders).
- Implement different types of interactions/animations using **GSAP** or **Framer Motion**.
  This can be one or more of the below:
  - Custom cursor: Implement custom cursor to override system cursors and to enhance the interactions with ui of the application (e.g. hover/loading/idle state triggers different animation on cursor).
  - Page transitions: Implement a page to page transition with seamless transition.
  - Scroll animation: Implement an animation based on movement of the scroll.
  - Theming: Implement components in such a way that it can transition from one particular theme to another (theme per page or dark mode toggle).
- Implement a WebGL effect.
  - This can be placing an interactable object using a library like [r3f (react-three-fiber)](https://github.com/pmndrs/react-three-fiber)
  - Or having a custom shader to give an interesting cool effect.
- Deploy the application (e.g., using **Vercel**) and provide a link.

## Getting Started

To get started, fork this repository and clone it to your local environment. Make sure you have **Node.js** installed, and then install the dependencies as you need.

Refer to the [Next.js documentation](https://nextjs.org/docs) for more information on how to work with Next.js or the README.md file for the project setup.
