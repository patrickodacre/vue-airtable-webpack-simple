# Vue.js & Airtable Webpack Simple Starter

A starter kit including Vue.js CLI webpack-simple starter, Axios and examples on how to connect with Airtable.

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build
```

## Connecting with Airtable

Just change env.example.js to env.js and add your API Key.

Your API key can be found in the Airtable API docs for your project.

1. Create a new project in Airtable
2. With your project open, click on the '?' at the top-right of your browser window and open the API docs.
3. Again at the top-right of the window you'll see a checkbox for showing your API key.
4. Next find your Table in the left menu. Select any of the options like 'List records' and you'll see some example code under the CURL tab like this:

```
$ curl "https://api.airtable.com/v0/appI5uUz57wbvjWfz/Roasters?maxRecords=3&view=Main%20View" \
-H "Authorization: Bearer YOUR_KEY_HERE"
```

Grab your key from there.

Enjoy!

For detailed explanation on how things work, consult the [docs for vue-loader](http://vuejs.github.io/vue-loader).
