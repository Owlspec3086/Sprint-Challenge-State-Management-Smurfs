1. What problem does the context API help solve?
Answer: The context API aims to solve the problem of prop drilling. It enables us to store data on the context object and pass it to the components that need it.


1. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?
Answer: In Redux, the store is the central hub for all the state of an App. The state is stored as an object and is immutable. Actions are objects that enable data to be sent to the store, using dispatch. Actions come with a type property that detail what state will change, and a payload property that carries the actual data being changed. This is passed through to the reducer. The reducer takes in the state and the action to return a new state to be passed into the store, which will make the necessary changes to the data.


1. What is the difference between Application state and Component state? When would be a good time to use one over the other?
Answer: The difference between the two is that application is more of a global bank while components act more like a local bank.. An example will be if your using a login you may want to store the users information into a global state to be used over and over while completing a form in a component would be stored on a component state.


1. Describe `redux-thunk`, what does it allow us to do? How does it change our `action-creators`?
Answer: Redux-thunk stands as a middleware to take in actions and changes multiple states

1. What is your favorite state management system you've learned and this sprint? Please explain why!
Answer: Favorite state management system, I would pick context API it seems easier to use because we were learning the more difficult way to use react without hooks
