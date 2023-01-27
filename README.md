<!-- # react-brick-layout

[![NPM version][npm-image]][npm-url]
[![Build][github-build]][github-build-url]
![npm-typescript]
[![License][github-license]][github-license-url]

`react-brick-layout` is lightweight, performant, and responsive masonry layout component that arranges elements in a grid-like structure, with elements of varying heights. The elements are placed in such a way that there are minimal gaps between them, creating a cohesive and visually appealing layout.

[**Live Demo**](https://joshnwosu.github.io/react-brick-layout/)

## Installation:

```bash
npm install react-brick-layout --save-dev
```

or

```bash
yarn add -D react-brick-layout
```

## Usage :

To use the `react-brick-layout` library, you would first need to install it in your project by running `npm install react-brick-layout` or `yarn add react-brick-layout`. Once the library is installed, you can import the Masonry component and use it in your application.

Here's an example of how you can use the `BrickLayout` component to create a simple Masonry layout in a React application:

```js
import React from 'react'
import { BrickLayout } from 'react-brick-layout'

const Masonry = () => {
  return (
    <BrickLayout gutter={10} column={5}>
      <div>Element 1</div>
      <div>Element 2</div>
      <div>Element 3</div>
      <div>Element 4</div>
      <div>Element 5</div>
    </BrickLayout>
  )
}

export default Masonry
```

## Props

| name            | type    | required | default                                     | description                                                                                     |
| --------------- | ------- | -------- | ------------------------------------------- | ----------------------------------------------------------------------------------------------- |
| style           | object  | No       | `{}`                                        | CSS style for the `BrickLayout` component                                                       |
| children        | null    | No       | `null`                                      | ❌❗ Do not pass children as props. Instead, nest children between the opening and closing tags |
| column          | number  | No       | `3`                                         | Column count                                                                                    |
| gutter          | number  | No       | `10`                                        | The size(px) of the gap between elements                                                        |
| animateOnResize | boolean | No       | `true`                                      | Animate layout on screen resize                                                                 |
| className       | string  | No       | `react-brick-layout`                        | Custom class name of layout container                                                           |
| rtl             | boolean | No       | `false`                                     | Change layout `right to left`                                                                   |
| breakPoint      | object  | No       | `{350: 1, 450: 2, 645: 3, 900: 4, 1200: 5}` | Used for responsive layout. The point at which the screen size(px) changes                      |

[npm-url]: https://www.npmjs.com/package/my-react-typescript-package
[npm-image]: https://img.shields.io/npm/v/my-react-typescript-package
[github-license]: https://img.shields.io/github/license/gapon2401/my-react-typescript-package
[github-license-url]: https://github.com/gapon2401/my-react-typescript-package/blob/master/LICENSE
[github-build]: https://github.com/gapon2401/my-react-typescript-package/actions/workflows/publish.yml/badge.svg
[github-build-url]: https://github.com/gapon2401/my-react-typescript-package/actions/workflows/publish.yml
[npm-typescript]: https://img.shields.io/npm/types/my-react-typescript-package

## Conclusion

This package provides a simple, lightweight solution for creating responsive brick-style layouts in React. It allows for customization of the layout to suit your specific needs and requirements. If you find it useful, please consider giving it a positive rating or review. Thank you! -->

# Notice:

This repository as been moved to [react-brick-view](https://github.com/joshnwosu/react-brick-view)
