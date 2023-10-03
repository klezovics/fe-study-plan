# Summary
This is the summary of all key and critical aspects of FE dev

## HTML breakdown
HTML = Collection of nested tags with attributes ~ 20% of tags are used 80% of the time

## JS breakdown
JS = Core JS(X) + Libs
JS = Core JS + React JSX
Key libs = CSS-IN-JS + Hooks + State management + HTTP
Automated tests

## CSS breakdown
CSS = Base(Static) + Responsive + Advanced(Dynamic)
Base = Layouts + Colors + Typography + Spacing
Advanced = Transitions + Animations
Design system

## Key concerns
### Developer experience
- Which tools to you ? How to use them best ?

### Dependencies
- Choosing and importing the right dependencies
- Updating dependencies -> vulnerabilities, bug fixes and improvements
- Preventing dependency conflicts

### Layouts
- Getting the layouts right and making them consistent
- Making the layouts responsive

### Styling
#### Consistency
- Across browsers -> normalize.css
- Colors
- Typography
- Layouts and spacing

### Business logic
- How to structure the code ?
- What should the folder structure be in the project ?

### API interactions
- How to keep the code clean
- How to keep the code performant

### Build and deploy
- Choosing a rendering strategy: SSG vs SSR vs CSR
- Creating and deploying a production build

### Etc
- Storybook -> design system
- SEO

# Learning Process
## Questions

### Consistency/Reusability
- How to ensure consistent gaps everywhere?
- How do I design reusable components ? Think buttons with rounded corners ? How to avoid prop overload ?

### Features
- What are the key aspects/features of next.js ?
- How can I leverage bootstrap and other UI libs as much as possible ? How do I make them customizable ?

### Layouts 
- How create high quality and clean high level layouts ?
- How do I master creating layouts 
- What are common layout pattrens ? How can I easily implement them ?

### Clean code & clean architecture
- Which patterns and best practices can I use ?
- How can I structure my app in layers ? Do I use classes or functions ?
- How can I structure my FE into modules ?
- Best practice around next.js 13 project structure ?

## Drills
- D1 -> Making layouts -> Get a list of layout patterns from ChatGPT and implement them using grid/flexbox
- D2 -> Absolute positioning -> Grab a bunch of elements and position them in crazy places
- D3 -> Hooks + custom hooks. Come up with ways to use hooks in all ways and then extract this logic into custom hooks
- D4 -> Context. Learn to implement contexts and pass data around using them
- D4 -> Redux -> Practice using redux and mapping state and dispatch to props
- D5 -> Layering -> Read a few articles/projects about layering and do 3 projects with layers
- D6 -> Animations -> Start with basic and move on to more advanced animations
- D7 -> Project generators -> Try out a few and check that you get a project with all dependencies configured
- D8 -> Responsive design -> Create a few designs which are effortlessly responsive
- D9 -> Using libraries. Integrate about 20 different libraries and try to use them
- D10 -> Component communications practice. Prop drilling, context, zustand

# Languages
- JS
- Typescript

# Next.js
- Next auth
- Next internationalization
- Next app router
- Alternative: after.js, refine.js

# Tools 🛠
## Figma
- Figma basics
- How to convert figma to code while preserving spacing
- Web design basics
- How to convert figma to code ?
- Design token export: https://www.figma.com/community/plugin/888356646278934516/design-tokens

### CLI utils
- Generator -> superplate, refine
- Package manager -> npm, yarn
- Linter -> eslint, prettier (Something to create a fixed order of CSS properties?)
- CLI node utilities -> nvm, npx -> what else ?

### Browser dev tools
- Chrome Dev Tools, Firefox for developers
- Lib inspector tools -> react, redux, react-query

### Other
- Generators -> gradient, shadow, text shadow, animation, transformation

# React
## Hooks
- useState
- useEffect
- useRef
- useContext
- useReducer

## Libs
- React Query & 1 alternative
- Client state; Zustand, Redux, Redux toolkit

## Patterns
- React component patterns
- React component interaction patterns

# CSS
## Core CSS
### Basic concepts
- Excellent intro: https://cssdemystified.com/
- Fundamentals: box-model, inheritance, cascading
- Reset -> box-sizing: border-box, normalize.css, 10px per rem

### Layouts
- Normal flow
- Display
- Position
- Flexbox
- Grid
- Responsive design https://courses.kevinpowell.co/conquering-responsive-layouts https://scrimba.com/learn/responsive

### Coloring
- Coloring -> shadows, gradients
- Typography -> font-* properties, inhertiance of font-* properties, typography theory basics

### Etc
- Transformations -> translate, rotate, scale
- Animations -> transition, @keyframes

- Pseudo elements -> :hover, :active, :focus, :visited, :nth-child, ::before-after
- Pseudo classes -> :hover, :active, :focus, :visited
- Pseudo selectors -> :nth-child
- Media queries

- CSS modules
- Beyound CSS -> https://www.beyondcss.dev/

## CSS in JS
- Libs -> Styled components, styled-jsx, emotion
- Styled System (!!!)

# Libs
## Starter lib pack
### Main
- JS: typescript support
- CSS: styled-components, styled-system
- API: axios, react-query(prevents too much hits of the API(!!))
- Forms: react-hook-form
- Validation: Zod
- State management: zustand, immer

### Support
- Linting: eslint, prettier
- Unit Testing: jest, react-testing-library -> ???
- E2E Testing: ???

## Component libs
### Tailwind
- m, p, text and breakpoint(responsive!!) classes for consistent sizing
- flex-row, flex-col

### Bootstrap
- Bootstrap Grid
- Bootstrap components

### Other
- Material UI
- Chakra UI
- 2 headless UI libs
- Figure out how to customize lib components

### Headless component libs
These libs only provide hooks and let you style components how you want
- React Select
- React Table

### Table libs
- TanStackTable, AntDesign table

## Animation Libs
- @keyframes
- React Spring, Framer Motion

## Form Libs
- React hook form

## Validation Libs
- Yup, Joi

## HTTP Libs
- React Query, RTK Query
- fetch API, axios

## Data visualisation Libs  
- ChartJS, VictoryChart

## Component Design System Libs
- Storybook

## Authentication Libs/Providers
- Firebase auth
- Auth0
- 1 more auth provider

## I18n Libs
- react-i18next
- 1 more libs

## Testing libs
- Jest
- React Testing Library
- Playwright

## Reactive libs
- RxJS -> NgRx
- Some 3D libs

## Typography libs
- Typographer lib -> add link

# Clen code & clean architecture
- Clean code React
- Clean architecture React
- React patterns
- Redux patterns

# SVG
- SVG basics
- SVG animations
- SVGR

# Cloud services
- Vercel -> quick deployment
- Firebase -> auth, db, backend as a service

# Web Design
- Site navigation
- Design tokens: colors, typography, spacing
- Layout

# Projects
- Do 5 projects based on Youtube tutorials based on react/next.js