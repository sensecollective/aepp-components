<template>
  <div class="ae-switch">
    <template v-for='c in choices'>
      <input v-model='selected' :value='c.value' type="radio" :name="name" :id="c.value" />
      <label :for='c.value'>{{c.label}}</label>
    </template>
  </div>
</template>

<script src="./aeSwitch.js"/>
/* eslint no-unused-expressions: "off" */
<style src="./aeSwitch.scss" scoped lang="scss" />
