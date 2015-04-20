---
layout: page
title: What Is Virtual DOM
---

## What is virtual DOM?

Almost everything viewed in a browser window is defined by DOM elements, a set of parts like text, pictures and decorative elements, styled and arranged using CSS. DOM is accessible to JavaScript, and so any web-app renders its internal state using DOM elements to display it to the user. But browser DOM happens to be slow and unwieldy, making it hard to write good maintainable code that's also snappy and fast. This is a compounding problem, as user interfaces get more and more complex!

Virtual DOM is a fast, lightweight, immutable equivalent of native browser DOM. It is a data structure, generated in pure JavaScript and passed between functions just like regular DOM would be.

There are libraries like [virtual-dom](https://github.com/Matt-Esch/virtual-dom), [ReactJS](https://github.com/facebook/react) and others that convert it to a user-visible presentation - virtual DOM maps one-to-one to the resulting browser DOM. Formats like JSX and Hyperscript can be used to generate virtual DOM objects.

## So why bother?

Virtual DOM is immutable and fast, and the browser screen can be updated just by re-generating the virtual DOM tree instead of tweaking and tracking updates to the slow browser DOM. **Clean, modular, testable front-end application code is now vastly simpler to write but stays just as performant.**

Moreover, virtual DOM has become a lean and stable interchange format that allows to compose application modules and external libraries. **A rich ecosystem of 3rd party virtual DOM components and user interface widgets is now possible without framework lock-in and learning curve.**

The [resources page](//virtualdom.gallery/resources/) provides more background on componentizing user interfaces for the modern Web.
