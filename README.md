      publicPath: process.env.NODE_ENV === "production" ? "/quasar-standardapp-deploy/" : "/",

      git subtree push --prefix dist/spa origin gh-pages4
