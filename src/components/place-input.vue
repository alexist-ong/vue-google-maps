<template>
    <label>
        <span v-text="label"></span>
        <input type="text" :placeholder="placeholder" :class="className"
          ref="input"/>
    </label>
</template>

<script>
import placeInput from "../components-implementation/place-input";
export default ((x) => x.default || x)(placeInput)
</script>
