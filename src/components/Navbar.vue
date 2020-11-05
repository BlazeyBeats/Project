<template>
<div class="navbar">
    <button v-on:click="popupsignin" class="signinBtn">Sign In</button>
    <button class="signupBtn">Sign Up</button>
</div>
</template>

<script>
export default {

}
</script>

<style>
.navbar {
    display: flex;
    justify-content: flex-end;
}

.navbar button {
    font-size: 20px;
    margin: 30px 10px;
    border: none;
    background: transparent;
    cursor: pointer;
}

.signupBtn {
    padding-right: 100px;
}
</style>
