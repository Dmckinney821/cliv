
<template>
    <div>
        <p>Server Status: {{ status }}</p>
        <hr>
        <button @click='changestatus'>Change Status</button>
    </div>
   
</template>


<script>
    export default {
        data: function() {
            return {
                status: 'Critical'
            }
        },
        methods: {
            changestatus() {
                this.status = 'Normal'
            }
        }
    }
</script>