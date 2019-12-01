<template>
    <div>
        <h1>{{ message }}</h1>
        <app-input :msg="message"></app-input>
    </div>
</template>

<script>
import Input from './Field.vue';

export default {
    data(){
        return {
            message: 'Exampled Text'
        }
    },
    components: {
        'app-input': Input
    }
}
</script>