# Hydrate React Research

> React Design System and UI Builder Research for [Hydrate](https://www.hydrate.io).

## Companies

- [Compositor](https://compositor.io) - Modern tools for designers & developers.
- [Formidable](https://formidable.com) - A JavaScript Consultancy Built for the Modern Web.
- [Zeit](https://zeit.co) - These guys kick ass. Period.

## Projects

#### WYSIWYG UI Builders

- [Compositor Lab](https://compositor.io/lab) - Component-based design system manager for building production-ready UI.
  - Closed source product, but this blog [post](https://compositor.io/blog/open-formats) gives a solid idea of how they model things.

#### Component Library Style Guides

- [docz](https://github.com/pedronauck/docz) - It has never been so easy to document your things!
- [x0](https://github.com/c8r/x0) - Document & develop react components without breaking a sweat.
- [Styleguidist](https://github.com/styleguidist/react-styleguidist) - Isolated react component development environment with a living style guide.
- [Storybook](https://github.com/storybooks/storybook) - Interactive UI component dev & test.

#### Useful React Libraries

- [Kit](https://github.com/c8r/kit) - Tools for developing, documenting, and testing react component libraries.
  - Only 2 months old.
  - [Responsive](https://github.com/c8r/kit/blob/master/docs/Responsive.md) - Displays children in `<iframe>`s, using the `Frame` component, at multiple viewport sizes.
  - [XRay](https://github.com/c8r/kit/blob/master/docs/XRay.md) - Displays a grid and adds outlines to children.
  - [Frame](https://github.com/c8r/kit/blob/master/docs/Frame.md) - Renders children in an `<iframe>` – useful for testing responsive layouts and ensuring isolation from the parent document.
  - [Cartesian](https://github.com/c8r/kit/blob/master/docs/Cartesian.md) - Display the cartesian product of component props.
  - [Matrix](https://github.com/c8r/kit/blob/master/docs/Matrix.md) - Displays a matrix of component permutations.
  - [LiveEditor](https://github.com/c8r/kit/blob/master/docs/LiveEditor.md) - The LiveEditor component is a wrapper around [react-live][https://github.com/FormidableLabs/react-live], with basic UI and a [ThemeProvider][https://www.styled-components.com/docs/advanced#theming].
  - [PropsForm](https://github.com/c8r/kit/blob/master/docs/PropsForm.md) - Add form controls to adjust a component's props.
  - [Diff](https://github.com/c8r/kit/blob/master/docs/Diff.md) - Shows a visual diff between two elements.
  - [Font](https://github.com/c8r/kit/blob/master/docs/Font.md) - Set font-family and other typographic styles.  Also provides a convenient webfont loader using [Google Fonts](https://fonts.google.com/).
  - [Catch](https://github.com/c8r/kit/blob/master/docs/Catch.md) - React `componentDidCatch` component that displays errors. Kind of like react-native's RedBox.
- [MDX](https://github.com/mdx-js/mdx) - JSX in Markdown for ambitious projects.
  - Combines the readability of Markdown with the expressivity and power of JSX.
- [react-live](https://github.com/formidablelabs/react-live) - A production-focused playground for live editing react components.
  - Transpiles code from Prism editor via buble client-side.
  - Doesn't support imports but does support custom scope.
- [component-playground](https://github.com/formidablelabs/component-playground) - Renders react components with editable source and live preview.
  - Transpiles code from Codemirror editor via babel-standalone client-side.
- [react-docgen](https://github.com/reactjs/react-docgen) - Extracts documentation info from react component files.

#### Useful General Libraries

- [gray-matter](https://github.com/jonschlinkert/gray-matter) - Front-matter metadata parser.

#### Mad Science

- [react-suspense](https://github.com/facebook/react/tree/master/fixtures/unstable-async/suspense) - Consistent way of handling asynchronicity in react.
  - Could be used, for example, to easily async import components that are transpiled on the server.

## Reading

- [Pure UI](https://rauchg.com/2015/pure-ui)
- [Interfaces](https://spectrum.chat/thread/ac4cba39-0582-4b73-9582-9e863ed66346)

## License

MIT © [Hydrate](https://www.hydrate.io)
