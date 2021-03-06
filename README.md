paper-random-term-card [![Build Status](https://travis-ci.org/Collaborne/paper-random-term-card.svg?branch=master)](https://travis-ci.org/Collaborne/paper-random-term-card) [![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/Collaborne/paper-random-term-card)
=========

A Material Design card that displays a random term from the given array (Polymer)

## Install

`bower install paper-random-term-card`

<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="my-element.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<paper-random-term-card
    id="random"
    selected="----"
    values="[[values]]">
</paper-random-term-card>

<script>
    values = [
        "Value 1",
        "Value 2",
        "Value 3",
        "Value 4"
    ];
</script>
```

## License

    This software is licensed under the Apache 2 license, quoted below.

    Copyright 2011-2015 Collaborne B.V. <http://github.com/Collaborne/>

    Licensed under the Apache License, Version 2.0 (the "License"); you may not
    use this file except in compliance with the License. You may obtain a copy of
    the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
    WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the
    License for the specific language governing permissions and limitations under
    the License.
