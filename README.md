# tictactoe
component = self explanatory, "object"like. Provides the building blocks to a React app
state = interactable client "feature" that isn't stored in the database. for example, a like button
hook = functions that manage state (and some that modify props too???)
prop = data that can pass from a parent component to a child component. can even pass down functions

Props are usually one directional, but if you declare a function in a parent component, you can modify the parent component's values in the child component -> kind of a loophole to "send" data back up to the parent