# Redux Quiz

<img src="https://chriscourses.com/img/blog/redux/redux.jpg" height="400px"/>

## Getting Started

- Fork and Clone

## Questions

1. What is Redux?

```
Redux is a standalone library that can be used with other front end frameworks. We will mostly use it with React, but it is not limited to React. Redux helps manage state for particularly large apps.
```

2. What packages do we install to use Redux?

```
We would run these commands:

npm install react-redux redux

This is for a React app, and I assume there would be different commands with a different framework.
```

3. In your own words, describe the flow of how Redux is used to manage state.

```
The flow of Redux manages state by creating a store where state’s are managed. Instead of each state needing to be passed down through multiple paths on a component tree, it can be accessed by accessing the store.
```

4. What do we use in order to manage different pieces of state?

```
We use reducers to manage different pieces of state (specifically by breaking up up state into little modules)
```

5. What do we use to perform an update to state?

```
We use actions to perform updates to state.
```

6. How do we access state from Redux?

```
We can access state using the redux store that wraps our App tag in the Index.js file of the src folder.
```

7. In your own words, describe how to set up Redux for a React App.

```
First I’d run all the necessary install commands in the terminal. Then I’d start making folders. Inside the src folder, I’d make a store folder, and inside that, make folders for my actions and reducers. I’d also make an index.js file and a types.js file. My index.js file would export the contents of my other files as a store. From there, I'd import the store into the index.js file of my src folder, and I'd add tags to wrap around the App tag. These tags would be Provider tags, wtih store passed in as a prop.
```

## Submission

Pull Request due by **9AM EST** following the [PR Submission Guidelines](https://github.com/SEI-R-2-22/template_pull_request).
