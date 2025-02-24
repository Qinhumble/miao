React is a IavaScript library for building user interfaces 


* **Declarative**: React makes it painless to create interactive UIs. Design simple views for each state in your application, and React will efficiently update and render just the right components when your data changes. Declarative views make your code more predictable, simpler to understand, and easier to debug.

* **Component-Based**:Build encapsulated components that manage their own state, then compose them to make complex UIs. Since component logic is written in JavaScript instead of templates, you can easily pass rich data through your app and keep the state out of the DOM.

* **Learn Once, Write Anywhere**:We don't make assumptions about the rest of your technology stack, so you can develop new features in React without rewriting existing code. React can also render on the server using <u>[Node](https://nodejs.org/en)</u> and power mobile apps using <u>[React Native](https://reactnative.dev/)</u>.


<u>[Learn how to use React in your project](https://react.dev/learn)</u>.

**Installation**

React has been designed for gradual adoption from the start, and **you can use as little or as much React as you need**:

* Use <u>[Quick Start](https://react.dev/learn)</u> to get a taste of React.
* <u>[Add React to an Existing Project](https://react.dev/learn/add-react-to-an-existing-project)</u> to use as little or as much React as you need.
* <u>[Create a New React App](https://react.dev/learn/creating-a-react-app)</u> if you're looking for a powerful JavaScript toolchain.


**Documentation**

You can find the React documentation <u>[on the website](https://react.dev/)</u>.

Check out the <u>[Getting Started page](https://react.dev/learn)</u> for a quick overview.

The documentation is divided into several sections:

* <u>[Quick Start](https://react.dev/learn)</u>
* <u>[Tutorial](https://react.dev/learn/tutorial-tic-tac-toe)</u>
* <u>[Thinking in React](https://react.dev/learn/thinking-in-react)</u>
* <u>[Installation](https://react.dev/learn/installation)</u>
* <u>[Describing the UI](https://react.dev/learn/describing-the-ui)</u>
* <u>[Adding Interactivity](https://react.dev/learn/adding-interactivity)</u>
* <u>[Managing State](https://react.dev/learn/managing-state)</u>
* <u>[Advanced Guides](https://react.dev/learn/escape-hatches)</u>
* <u>[API Reference](https://react.dev/reference/react)</u>
* <u>[Where to Get Support](https://react.dev/community)</u>
* <u>[Contributing Guide](https://legacy.reactjs.org/docs/how-to-contribute.html)</u>


You can improve it by sending pull requests to <u>[this repository](https://github.com/reactjs/react.dev)</u>.


**Examples**


We have several examples <u>[on the website](https://react.dev/)</u>. Here is the first one to get you started:
```
import { createRoot } from 'react-dom/client';

function HelloMessage({ name }) {
  return <div>Hello {name}</div>;
}
const root = createRoot(document.getElementById('container'));
root.render(<HelloMessage name="Taylor" />);
```
This example will render "Hello Taylor" into a container on the page.

You'll notice that we used an HTML-like syntax; <u>[we call it JSX](https://react.dev/learn#writing-markup-with-jsx)</u>. JSX is not required to use React, but it makes code more readable, and writing it feels like writing HTML.

**Contributing**

The main purpose of this repository is to continue evolving React core, making it faster and easier to use. Development of React happens in the open on GitHub, and we are grateful to the community for contributing bugfixes and improvements. Read below to learn how you can take part in improving React.


[**Code of Conduct**](https://opensource.fb.com/code-of-conduct/)

Facebook has adopted a Code of Conduct that we expect project participants to adhere to. Please read <u>[the full text](https://opensource.fb.com/code-of-conduct/)</u> so that you can understand what actions will and will not be tolerated.

**Contributing Guide**

Read our <u>[contributing guide](https://legacy.reactjs.org/docs/how-to-contribute.html)</u> to learn about our development process, how to propose bugfixes and improvements, and how to build and test your changes to React.

[**Good First Issues**](https://legacy.reactjs.org/docs/how-to-contribute.html)

To help you get your feet wet and get you familiar with our contribution process, we have a list of <u>[good first issues](https://github.com/facebook/react/labels/good%20first%20issue)</u> that contain bugs that have a relatively limited scope. This is a great place to get started.

**License**

React is <u>[MIT licensed](https://github.com/facebook/react/blob/main/LICENSE)</u>.
