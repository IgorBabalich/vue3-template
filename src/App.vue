<template>
<div>
    Hello!
    <Capacity/>
</div>
</template>

<script>
import Capacity from "./Capacity.vue"

export default {
    components: { Capacity },
    data:() => ({
        modalOpen: false
    }),
    methods: {
        toggleModal() {
            this.modalOpen = !this.modalOpen;
        }
    }
}
</script>
