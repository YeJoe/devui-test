<template>
  <d-layout>
    <d-aside class="daside">Aside</d-aside>
    <d-layout>
      <d-header class="dheader">Header</d-header>
      <d-content class="main-content">Content</d-content>
      <d-footer class="dfooter">Footer</d-footer>
    </d-layout>
  </d-layout>
</template>

<style>
    .daside {
        background: #f8f8f8;
        width: 100px;
        min-height: 200px;
        display: flex;
        align-items: center;
        justify-content: center;
    }
    .dheader, .dfooter {
        background: #333854;
        color: #fff;
        text-align: center;
        line-height: 40px;
        min-height: 40px;
    }
    .main-content {
        line-height: 200px;
        text-align: center;
    }
</style>
