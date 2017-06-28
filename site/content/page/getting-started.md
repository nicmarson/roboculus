---
title       : "Getting Started"
description : "The basic building blocks of the Roboculus framework."
comments    : false
menu: main
weight: 20
---

The component library was designed to help developers quickly create the best experience for Shopify merchants.

Each component includes information to help you implement them, such as:

*   Explanations of the merchant problem it solves in the interface
*   Interactive examples so you can see the component in action
*   Best practices and guidelines to use the component correctly

***

## Installing and implementing React components

Use React components in most cases, especially if you’re building a highly interactive experience. This can be done with or without a build system.

*   [Implementation instructions](https://github.com/Shopify/polaris) (requires HTML, React, a JS build tool)
*   Have a look at the [React component examples](https://github.com/Shopify/polaris/tree/master/examples) to see how it’s done

***

## Using the components

You can find comprehensive [instructions](https://github.com/Shopify/polaris) on how to use components in the Polaris GitHub repo. There are also [example applications](https://github.com/Shopify/polaris/tree/master/examples) to explore.

Here are some basic instructions to help you get started for both React and CSS-only:

### React components (Recommended)

Include the CSS in your HTML:

    <link rel="stylesheet" href="https://sdks.shopifycdn.com/polaris/1.0.2/polaris.css">

Include the component in your project:

    import {Button} from '@shopify/polaris';

Tell React to render the element in the DOM:

    ReactDOM.render(<Button onClick={() => alert('Button clicked!')}>Example button</Button>, domContainerNode);

***

## Learning resources

These resources have information on getting started with React.

### React

If you’re new to React, start with the official [React Getting Started documentation](https://facebook.github.io/react/docs/hello-world.html). As you read through the topics, follow along using the [React Hello World CodePen](http://codepen.io/gaearon/pen/ZpvBNJ?editors=0010) example.

Here are some additional resources:

*   Online training at [reacttraining.com](https://reacttraining.com/), [buildwithreact.com](http://buildwithreact.com), and [reactforbeginners.com](https://reactforbeginners.com)
*   Community resources in [Awesome React](https://github.com/enaqx/awesome-react)
*   Answers in the various [React support communities](https://facebook.github.io/react/community/support.html)

***

## Methodology

We set out to make our components easy to use. Each of our components has a well-documented public interface (API) with guidelines and well-defined conventions. This way, developers don’t need to worry about the underlying implementation. Instead, they can focus on creating amazing merchant experiences.

We ensure that our components are made for everyone. They meet accessibility standards and are responsive to any screen or device. We also put a lot of effort into optimizing the performance of the components, so everyone can build inclusive experiences that work.

We make our components flexible enough to meet diverse needs. Our components are set up to be restructured based on the information passed in. No matter what type of experience you’re creating, you can use components as the building blocks of your product or feature.

