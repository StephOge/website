### List five significant features of React

1. Declarative: React allows you to describe how your application should look and behave in a declarative way, using a syntax called JSX. This makes it easier to reason about your code and reduces the likelihood of bugs.

2. Component-based: React is built around the idea of components, which are self-contained and reusable pieces of code that encapsulate a particular piece of functionality. This makes it easier to build complex applications by breaking them down into smaller, more manageable parts.

3. Virtual DOM: React uses a virtual DOM (Document Object Model) to keep track of changes to your application's state and to update the UI efficiently. When your application's state changes, React updates the virtual DOM and then compares it to the actual DOM to determine what needs to be updated, minimizing the number of actual DOM manipulations that need to take place.

4. One-way data flow: React uses a one-way data flow, which means that data only flows in one direction—from parent components down to child components. This makes it easier to reason about your code and reduces the likelihood of bugs.

5. Performance: React is designed to be highly performant, even with large and complex applications. Its use of the virtual DOM and one-way data flow help to minimize the number of actual DOM manipulations that need to take place, which can improve performance significantly. Additionally, React provides tools like code splitting and lazy loading to help optimize your application's performance.

### List five major advantages of React

1. Reusability and modularity: React is based on the concept of reusable components, which allows developers to break down their application into smaller, more manageable pieces. These components can then be reused across the application, as well as in other projects, making development faster and more efficient.

2. Virtual DOM: React uses a virtual DOM to efficiently update the UI based on changes to the application state. This approach improves performance and reduces the number of updates required to the actual DOM, resulting in a smoother user experience.

3. Flexibility and extensibility: React provides a high degree of flexibility and extensibility, allowing developers to build applications the way they want. This makes it easier to integrate React with other libraries and frameworks, as well as to customize it to meet specific needs.

4. Easy to learn: React has a relatively shallow learning curve, especially for developers who are already familiar with JavaScript. Its use of JSX syntax and component-based architecture make it easy to understand and use, even for beginners.

5. Large community and ecosystem: React has a large and active community of developers, which means that there are many resources available to help you learn and develop with React. There are also many third-party libraries and tools available that can help extend the functionality of React and make development faster and more efficient.


### What is the name of the Software Engineer that created React? Also, which company owns React?

React was created by Jordan Walke, a software engineer at Facebook. React is an open-source project, and while it was created and is maintained by Facebook, it is not owned by any company. React can be used freely by anyone for any purpose, and the code is available for anyone to view, modify, and contribute to on GitHub.

### What are the notable differences between HTML & JSX? Give at least 3 of them

1. Syntax: HTML and JSX have different syntaxes. HTML is a markup language that uses a tag-based syntax to define elements, while JSX is a syntax extension of JavaScript that allows developers to write HTML-like code using JavaScript syntax.

2. Attributes: In HTML, attributes are defined using a key-value pair syntax, where the key is the name of the attribute and the value is the attribute's value. In JSX, attributes are defined using JavaScript expressions. This means that instead of using a key-value pair syntax, developers can use JavaScript variables, functions, and expressions to define attributes.

3. Components: In HTML, developers can define elements using a set of predefined tags like <div>, <p>, <img>, etc. In JSX, developers can define their own components using JavaScript functions. Components can be reused across an application, making it easier to create and manage complex user interfaces.

    Overall, JSX offers more flexibility and dynamic functionality than HTML, but requires developers to have a strong understanding of JavaScript syntax and concepts.

### Why can’t browsers read JSX?

Browsers can't read JSX directly because JSX is not a standard web language. JSX is a syntax extension of JavaScript that was created to simplify the process of building user interfaces for web applications.

When developers write JSX code, they use a syntax that looks like HTML, but the code is actually a combination of JavaScript and XML-like syntax. This means that browsers can't understand JSX code on their own, as it's not a language that they recognize.

To make JSX code readable by browsers, it needs to be transformed into regular JavaScript code using a tool called a transpiler. The most commonly used transpiler for JSX is Babel, which converts JSX into plain JavaScript that can be understood and executed by browsers.

Once the JSX code is transpiled into JavaScript, it can be included in a web application like any other JavaScript code, allowing the browser to read and execute it properly.


