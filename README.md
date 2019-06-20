# Elm GraphQL Workshop Environment Setup

## Basic environment
Run these steps to make sure that your basic environment is ready to go for the workshop.

**Note**: if you run into any NPM errors, make sure you are running NPM version >= 6. To update NPM, you can run a command like `npm install -g npm@6` from your terminal.

1. `cd` into the top-level workshop repository, and then run:

```
npm install
```

2. Open `elm-graphql-workshop` the top-level workshop repository in your editor of choice.

3. Try running this command and opening `localhost:8000` to ensure that everything is working:

```
./run.sh ./src/hello
```

If you see a nice friendly message show up in your browser after running that command, then you're good to go!

## Editor Setup

Having autocompletion is a big plus for this workshop. It makes it a lot easier to write `elm-graphql` queries, and it is recommended for this workshop.

Here are some instructions for setting up Atom with autocompletion for Elm 0.19:

https://incrementalelm.com/learn/editor-config

You can also setup the Elm Language Server, which will give you autocompletion for your language of choice. Just follow the [Elm Language Server setup instructions for different editors here](https://github.com/elm-tooling/elm-language-server#editor-support).
