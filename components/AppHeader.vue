<template>
 <!-- ヘッダー -->
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <NuxtLink class="navbar-brand" to="/">ウェブサイト名</NuxtLink>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ml-auto">
        <li class="nav-item">
          <NuxtLink class="nav-link" to="/home">ホーム</NuxtLink>
        </li>
        <li class="nav-item">
          <NuxtLink class="nav-link" to="#">ログイン</NuxtLink>
        </li>
        <li class="nav-item">
          <NuxtLink class="nav-link" to="#">サインアップ</NuxtLink>
        </li>
      </ul>
    </div>
  </nav>
</template>