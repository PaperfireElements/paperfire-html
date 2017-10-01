[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg?style=flat-square)](https://www.webcomponents.org/element/paperfire-elements/paperfire-html)

# \<paperfire-html\>

an element to render html from firebase

<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="../polymerfire/firebase-app.html">
    <link rel="import" href="paperfire-html.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<firebase-app
  id="app"
  auth-domain="paperfireelements.firebaseapp.com"
  database-url="https://paperfireelements.firebaseio.com/"
  storage-bucket:
  "paperfireelements.appspot.com"
  api-key="AIzaSyBV90mRwJOGY7uO_RVWkchk9oUBx2E-sac"
  messagingSender-id="637337808974"></firebase-app>
<paperfire-html html="{{html}}" loaded="{{loaded}}" url="/demo/html"></paperfire-html>
<pre>loaded: [[loaded]]</pre>
<pre>[[html]]</pre>
```

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

## Viewing Your Element

```
$ polymer serve
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
