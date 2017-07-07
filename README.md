# React Redux Rails Boilerplate

This is a boilerplate to create a React Redux application on top of a
Rails backend. It has all the necessary configuration for testing 
setup as well using the Karma Enzyme testing setup.

Everything is setup to display a default puppy gif from the Giphy API.
This information gives a fetch call, actions, reducers and connected
components to get started.

It is also built using the new Rails 5.1 webpacker configuration for
React. Please be aware that this means the React application will be
within the `app/javascript/react` folder. This setup uses yarn to manage
dependencies. Please be aware of this for debugging purposes.

In order to get the application up and running, you need to run the 
following commands in one tab to get rails server running:

```
bundle
rails s
```

In another tab, you'll need to run the following commands to get the 
React application placed into the app's Javascript files:

```
yarn
yarn start
```

Then you should be ready to develop! Enjoy!

#### Note to Launchers

Please use this boilerplate with caution. Learning Redux is a fairly
significant departure from the way you're used to using React. If you
decide to take learning this technology on, it will take a fairly large time 
investment! This should inform your decision to try to learn 
React since it likely will not be strictly *necessary* for an
application of your size. 



