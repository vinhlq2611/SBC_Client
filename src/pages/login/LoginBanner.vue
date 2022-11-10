<template>
    <div class="login-banner-container  md:col-span-2  lg:col-span-3">
        <img class="w-5/12 mx-auto mb-8 " src="../../../public/imgs/login_loyalty.png" alt="">
        <h1 class="login-banner-title text-login-banner">Loyalty Club - you play, we pay!</h1>
        <div class="login-item-container w-4/6 mx-auto grid grid-cols-1 lg:grid-cols-3 gap-x-10">
            <!-- Login Item -->
            <div class="login-item mx-auto mb-6 grid grid-cols-5 max-w-xs">
                <div><img class="m-0 w-full" src="../../../public/imgs/login-banner-badge-1.svg" alt=""></div>
                <div class="col-span-4">
                    <h2 class="text-xl text-login-banner font-semibold mb-4">Fun</h2>
                    <p class="text-l text-login-banner font-medium">100s of free spins & up to 10% cash rebate</p>
                </div>
            </div>
            <div class="login-item mx-auto mb-6 grid grid-cols-5 max-w-xs">
                <div><img class="m-0 w-full" src="../../../public/imgs/login-banner-badge-1.svg" alt=""></div>
                <div class="col-span-4">
                    <h2 class="text-xl text-login-banner font-semibold mb-4">Fun</h2>
                    <p class="text-l text-login-banner font-medium">100s of free spins & up to 10% cash rebate</p>
                </div>
            </div>
            <div class="login-item mx-auto mb-6 grid grid-cols-5 max-w-xs">
                <div><img class="m-0 w-full" src="../../../public/imgs/login-banner-badge-1.svg" alt=""></div>
                <div class="col-span-4">
                    <h2 class="text-xl text-login-banner font-semibold mb-4">Fun</h2>
                    <p class="text-l text-login-banner font-medium">100s of free spins & up to 10% cash rebate</p>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>


<style scoped>
@media (max-width: 640px) {
    .login-banner-container {
        display: none !important;
    }
}

.login-banner-title {
    margin: 0 0 5vh;
    font-size: 3rem;
    line-height: 3.5rem;
    font-weight: 500;
    text-align: center;
}

.text-login-banner {
    color: rgb(161, 142, 180);
}

.login-banner-container {
    overflow: hidden;
    height: 100vh;
    width: 100%;
    display: flex;
    justify-items: center;
    align-content: center;
    flex-direction: column;
    padding: 2rem;
    color: rgb(255, 255, 255);
    background: url("../../../public/imgs/login_background_pattern.svg"), linear-gradient(0deg, rgba(36, 3, 63), rgb(36, 3, 63));
    background-size: cover;
}
</style>