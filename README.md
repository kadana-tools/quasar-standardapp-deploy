current result:

      blank page


specific edits:

in quasar.config file:

      publicPath: process.env.NODE_ENV === "production" ? "/quasar-standardapp-deploy/" : "/",

when pushing to gh-pages4, used dist/spa instead of just dist:

      git subtree push --prefix dist/spa origin gh-pages4
