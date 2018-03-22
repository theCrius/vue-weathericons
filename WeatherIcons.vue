<template>
  <i class="wi" :class="[
    icon ? 'wi-' + icon : '',
    wind ? wind + '-deg' : '',
    flip ? 'wi-flip-' + flip : '',
    rotate ? 'wi-rotate-' + rotate : '',
    fixed ? 'wi-fw' : ''
  ]"></i>
</template>

<script>
import "weathericons/sass/weather-icons.scss";
import "weathericons/sass/weather-icons-wind.scss";

export default {
  props: {
    icon: { required: true, type: String },
    wind: String,
    flip: String,
    rotate: Number,
    fixed: Boolean
  }
}
</script>
