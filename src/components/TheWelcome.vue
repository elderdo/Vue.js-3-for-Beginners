<script setup>
  import { reactive } from 'vue';
  import SocialPost from './molecules/SocialPost.vue';
  const posts = reactive([
    { username: "Username one",
      userId: "usernameId1",
      avatarSrc: "https://i.pravatar.cc/40",
      post:"This is post 1"
    },
    { username: "Username two",
      userId: "usernameId2",
      avatarSrc: "https://i.pravatar.cc/41",
      post:"This is post 2"
    },
    { username: "Username three",
      userId: "usernameId3",
      avatarSrc: "https://i.pravatar.cc/42",
      post:"This is post 3"
    },
  ]);
</script>
<template>
  <SocialPost
    :username="posts[0].username"
    :userId="posts[0].userId"
    :avatarSrc="posts[0].avatarSrc"
    :post="posts[0].post"></SocialPost>
  <SocialPost
    :username="posts[1].username"
    :userId="posts[1].userId"
    :avatarSrc="posts[1].avatarSrc"
    :post="posts[1].post"></SocialPost>
  <SocialPost
    :username="posts[2].username"
    :userId="posts[2].userId"
    :avatarSrc="posts[2].avatarSrc"
    :post="posts[2].post"></SocialPost>
</template>
