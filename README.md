# Drupal8 Vuejs Webpack template

> A simple Vue 2.0 Webpack & `vue-loader` to install on Drupal 8


### Usage

This is a project template for [vue-cli](https://github.com/vuejs/vue-cli).

``` bash
$ npm install -g vue-cli
$ composer create-project drupal-composer/drupal-project:8.x-dev some-dir --stability dev --no-interaction
$ ( https://github.com/drupal-composer/drupal-project )
$ cd drupal
$ vue init drupal8-vuejs-webpack
$ npm install
```

Then include "/dist/build.js"

and call wherever you want vuejs mount point. Do not forget "verbatim"
to disabled symfony php interpolation with curly braces

```
            {% verbatim %}
              <div id="app">
                <articles-list-container />
              </div>
            {% endverbatim %}
```

### What's Included

- `npm run dev`: Webpack + `vue-loader` with proper config for source maps & hot-reload.

- `npm run build`: build with HTML/CSS/JS minification.

For detailed explanation on how things work, consult the [docs for vue-loader](http://vuejs.github.io/vue-loader). Also check out the [breaking changes in vue-loader@9.0.0](https://github.com/vuejs/vue-loader/releases/tag/v9.0.0).

### Fork It And Make Your Own

You can fork this repo to create your own boilerplate, and use it with `vue-cli`:

``` bash
vue init username/repo my-project
```
