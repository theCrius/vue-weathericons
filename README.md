vue-weathericons
=============

A simple VueJS component made as first attempt of messing around with VueJs (and publishing my first NPM).

## Requirements

This package require [weathericons](https://www.npmjs.com/package/weathericons) as peer dependency and of course needs to be used inside a VueJS application.

## Installation

``` sh
npm install --save vue-weathericons
```

## Usage

In your component:

```vue
<script>
import WeatherIcon from 'WeatherIcons';

export default {
  name: 'myComponentName',
  // [...]
  components: {
    WeatherIcon
  }
};
</script>

<template>
  <div class="whatever">
    <p>All attributes are optional and non mutually exclusive, apart from the 'icon' of course:</p>
    <weather-icon icon="day-sunny" />
    <weather-icon icon="wind" wind="towards-160" />
    <weather-icon icon="tornado" flip="horizontal" />
    <weather-icon icon="alien" rotate="45" />
    <weather-icon icon="fog" fixed="true" />
  </div>
</template>
```

## Contributions
---------------
All contributions are welcome as they'll help me keep messing up with Vue.
