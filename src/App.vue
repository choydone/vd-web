<template>
  <div class="page">
    <header class="navbar navbar-expand-md">
      <div class="container-xl">
        <a class="navbar-brand" href="#">VD Web</a>
        <div class="navbar-nav ms-auto">
          <a class="nav-link" href="https://tabler.io" target="_blank" rel="noreferrer">
            Tabler UI
          </a>
        </div>
      </div>
    </header>

    <div class="page-wrapper">
      <main class="page-body">
        <div class="container-xl">
          <router-view />
        </div>
      </main>
    </div>
  </div>
</template>
