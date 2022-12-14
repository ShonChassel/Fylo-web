<template>
    <header class="main-header full">

        <div class="logo">
            <img src="../assets/imgs/logo.svg" alt="" />
        </div>

        <div class="txt-header">
            <button>Features</button>
            <button>Team</button>
            <button>Sign In</button>
        </div>
        
    </header>
</template>
<script>
export default {
    computed: {
        loggedInUser() {
            return this.$store.getters.loggedinUser;
        },
    },
};
</script>
