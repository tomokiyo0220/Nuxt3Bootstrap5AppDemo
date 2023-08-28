<template>
  <div class="container">
    <h1>ホームページ</h1>
    <p>ID:{{user.id}}</p>
    <p>名前:{{user.name}}</p>
    <p>あどれす:{{user.mail}}</p>
    <img src="~/assets/img/rf122825093_o-1536x1024.jpg"/>
  </div>
</template>

<script setup>
const user = useLoginUser();
</script>
