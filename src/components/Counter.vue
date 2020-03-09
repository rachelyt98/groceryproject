<template>
    <div>
        <button v-on:click = "increment()">+</button>
        <label>{{counter}}</label>
        <button v-on:click = "decrement()">-</button>
    </div>
</template>

<script>
export default {
    data() {
        return {
            counter:0
        }
    },

    methods: {
        increment:function() {
            this.counter++;
        },
        decrement:function() {
            this.counter--;
        }
    }
}
</script>