<template>
    <p>Server statys: {{status}}</p>
    <button @click="changeStatus">Change Status</button>
</template>

<script>
    export default {
        data() {
            return {
                status: 'Critical'
            }
        },
        methods: {
            changeStatus() {
                this.status = 'Normal';
            }
        }
    }
</script>