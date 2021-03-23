<template>
    <div>
        <h1> Example desde TEST</h1>
        <p> Text variable : {{ textVar }}</p>
    </div>
</template>

<script>
import { defineComponent } from '@vue/composition-api'

export default defineComponent({
    setup() {
        
    },
    data(){
        return {
            textVar:"Variable"
        }
    }
})
</script>
