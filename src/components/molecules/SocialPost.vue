<template>
    <div class="SocialPost">
        <div class="header">
            <img class="avatar" src="https://i.pra-vatar.cc/40"/>
            <div class="name">Name of User</div>
            <div class="userId">@userId</div>
        </div>
        <div class="post">This is a dummy post</div>
    </div>
</template>
<script setup>
</script>
<style lang="scss">
.SocialPost {
    .header {
        display: flex;
        align-items: center;
        margin-bottom: 8px;;
    }
    .avatar {
        border-radius: 50%;
        margin-right: 8px;
        color: white;
    }
}
</style>