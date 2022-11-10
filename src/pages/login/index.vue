<template>
    <div class=" grid grid-cols-4">
        <LoginForm />
        <LoginBanner />
    </div>
</template>

<script>
import LoginBanner from './LoginBanner.vue'
import LoginForm from './LoginForm.vue'

export default {
    components: {
        LoginBanner,
        LoginForm
    }
}
</script>
