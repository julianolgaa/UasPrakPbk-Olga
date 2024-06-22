<template>
  <div class="bg">
  <q-layout view="lHr lpR lfr">
    <q-header class="bg-green text-black" height-hint="98">
      <q-toolbar>
        <q-toolbar-title>UAS Julian Olga®</q-toolbar-title>
        <q-tabs align="left">
          <q-route-tab to="/" label="weather" />
        </q-tabs>
      </q-toolbar>
      
    </q-header>
    <q-page-container>
      <router-view />
    </q-page-container>
    <q-footer class="bg-green text-black" height-hint="98">
      <q-toolbar>
        <q-toolbar-title>
          Copyright © Julian Olga ®. All rights reserved.
        </q-toolbar-title>
      </q-toolbar>
    </q-footer>
  </q-layout>
</div>
</template>

<script setup></script>

<style>
.bg{
  background-color: olivedrab;
}
.q-toolbar {
  padding: 0 75px !important;
}
.q-toolbar__title:first-child {
  padding-left: 32px !important;
}
.q-tab {
  padding: 0 20px !important;
  min-height: 75px !important;
}
</style>
