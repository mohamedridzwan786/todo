
<template>
    <div class="center examplex">
      <vs-navbar center-collapsed v-model="active">
        <template #left>
          <img src="https://cdn.pixabay.com/photo/2020/01/21/18/39/todo-4783676_1280.png" alt="" width="55" height="50">
        </template>
        <vs-navbar-item :active="active == 'hackerscollective'" id="hackerscollective">
          Hacker's Collective Todo App
        </vs-navbar-item>
        
      </vs-navbar>
    </div>
  </template>


        