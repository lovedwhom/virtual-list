<template>
    <div>
        <ul>
            <li v-for="(item,index) in listData" :key="index">
                {{ index }} 
            </li>
        </ul>
    </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

// interface ListData {

// }
export default defineComponent({
    setup() {
        let listData:Array<any> = new Array(10000)
            
            return {
                listData
            }
    },
})
</script>

<style lang="scss" scoped>

</style>


