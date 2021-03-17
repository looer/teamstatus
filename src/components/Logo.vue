<template>
  <svg :width="getWidth" :height="getHeight" viewBox="0 0 960 960" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xml:space="preserve" xmlns:serif="http://www.serif.com/" style="fill-rule:evenodd;clip-rule:evenodd;stroke-linecap:round;stroke-linejoin:round;stroke-miterlimit:1.5;">
    <g id="Livello3" transform="matrix(1,0,0,1,-160,0)">
        <g transform="matrix(1.33725,0,0,1.33725,-210.743,-145.699)">
            <g transform="matrix(1,0,0,1,-99.021,8.95101)">
                <path d="M789.2,588.83C789.128,587.665 789.091,586.494 789.091,585.315L789.091,423.357C789.091,392.557 814.096,367.552 844.895,367.552L956.503,367.552C987.303,367.552 1012.31,392.557 1012.31,423.357L1012.31,585.315C1012.31,589.195 1011.91,592.984 1011.15,596.644C1009.68,657.307 960.504,706.097 900.14,706.097C838.85,706.097 789.091,655.799 789.091,593.846C789.091,592.167 789.127,590.497 789.2,588.83Z" style="fill:rgb(80,89,201);"/>
            </g>
            <g transform="matrix(1,0,0,1,-118.042,5.03491)">
                <circle cx="919.72" cy="254.825" r="79.161" style="fill:rgb(80,89,201);"/>
            </g>
        </g>
        <g transform="matrix(1.33725,0,0,1.33725,-210.743,-145.699)">
            <g transform="matrix(0.939745,0,0,0.949015,-107.828,25.7939)">
                <circle cx="687.133" cy="209.65" r="120.699" style="fill:rgb(123,131,235);"/>
            </g>
            <g transform="matrix(1,0,0,1,-99.021,8.95101)">
                <path d="M439.274,646.683C436.836,638.776 435.524,630.379 435.524,621.678L435.524,451.888C435.524,405.033 473.565,366.993 520.42,366.993L753.426,366.993C800.281,366.993 838.322,405.033 838.322,451.888L838.322,612.383L838.322,612.448L838.322,612.512L838.322,621.678C838.322,627.47 837.74,633.126 836.634,638.59C823.798,737.187 739.403,813.427 637.343,813.427C538.088,813.427 455.542,741.322 439.274,646.683Z" style="fill:rgb(123,131,235);"/>
            </g>
        </g>
        <g transform="matrix(1.50749,0,0,1.50749,185.072,294.047)">
            <circle cx="357.762" cy="288.671" r="151.608" style="fill:rgb(134,219,75);"/>
        </g>
        <g transform="matrix(1.33725,0,0,1.33725,437.868,339.076)">
            <path d="M109.371,286.434L193.287,374.825L389.65,197.483" style="fill:none;stroke:white;stroke-width:34.68px;"/>
        </g>
    </g>
  </svg>
</template>

<script>
export default {
  props: {
    width: {
      type: Number,
      default: 40
    }
  },

  computed: {
    getWidth() {
      return this.width;
    },

    getHeight() {
      return Math.ceil((this.getWidth / 48) * 48);
    }
  }
};
</script>

