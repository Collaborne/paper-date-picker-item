paper-date-picker-item [![Bower version](https://badge.fury.io/bo/paper-date-picker-item.svg)](http://badge.fury.io/bo/paper-date-picker-item) [![Travis state](https://travis-ci.org/Collaborne/paper-date-picker-item.svg?branch=master)](https://travis-ci.org/Collaborne/paper-date-picker-item) [![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/Collaborne/paper-date-picker-item)
=========

`paper-date-picker-item` provides a Material Design item that shows a date and opens a date picker dialog on tap. The web component is built with [Polymer 1.x](https://www.polymer-project.org).

This component builds on the components [paper-date-picker](https://github.com/bendavis78/paper-date-picker) and [paper-time-picker](https://github.com/bendavis78/paper-time-picker)  by [Ben Davis](https://github.com/bendavis78).


To use the elements:

`bower install paper-date-picker-item`

<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="../iron-icons/iron-icons.html">
    <link rel="import" href="paper-datetime-picker-item.html">
    <custom-style>
      <style is="custom-style">
        body {
          min-height: 600px;
        }
      </style>
    <custom-style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<paper-datetime-picker-item
    icon="icons:today"
    placeholder="Add date and time"
    date-format="Do, MMMM, YYYY">
</paper-datetime-picker-item>
```

## i18n Support

`paper-date-picker-item` uses [Moment.js](http://momentjs.com), and so supports all locales that Moment.js supports. But,
the component does not reference any specific locale, so when you want to use it with a locale other than `en` you must
load the locales explicitly.

~~~~
<link rel="import" href="bower_components/paper-date-picker-item/paper-date-picker-item.html">
<script src="bower_components/moment/min/locales.js"></script>
~~~~

The `paper-date-picker-item` components all provide a `locale` property to set the locale used by the component.

## License

    This software is licensed under the Apache 2 license, quoted below.

    Copyright 2011-2017 Collaborne B.V. <http://github.com/Collaborne/>

    Licensed under the Apache License, Version 2.0 (the "License"); you may not
    use this file except in compliance with the License. You may obtain a copy of
    the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
    WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the
    License for the specific language governing permissions and limitations under
    the License.

