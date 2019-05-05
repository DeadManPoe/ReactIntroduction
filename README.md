# An introduction to React
When it comes to understand what is the purpose and utility of React, two things are key: abstraction and reactivity.

Abstraction is the idea of using strategies to describe and represent things that are best suitable for a specific purpose: if we are going to build a dynamic ui, we would want to use abstractions that put directly in front of the our eyes what's the shape of look of the ui, and how it is dynamic, i.e, how it changes w.r.t data.

Reactivity is the idea of responding automatically to a change occurred to something: if we are going to build a dynamic ui, an interesting, effective and natural approach would be to make it reactive w.r.t data, so that we don't have to manually update ui components when a change in some data happen.

Let's see how React is able to guarantee abstraction and reactivity, while vanilla JS is not.

* Live demo on the material under `simple-dynamic-ui` and `todo-ui`*

## Abstraction
React elements abstract away ui generation and guarantee that what you is almost what you get. They do so by supporting an XML/HTML syntax within JS called JSX, and by offering a simple and complete API for everything you can imagine about possibily complex UI trees. What they don't do is to offer to the user strategies to make the UI react to data changes, that's what React components offer.

## Reactivity
React components put together data with a declaritive and abstracted UI, by making React elements automatically and smartly change whenever some piece of data changes. Such data can be of 2 types: internal to the component(*state*) or external to the component but supplied to it(*props*); whenever either the state of a component changes or its props, then a new React element is rendered to the DOM, an element that reflects correctly the changes in the data.

