<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link>
      | <router-link to="/about">about</router-link>
      | <router-link to="/add">add</router-link>
    </div>
    <router-view />
  </div>
</template>