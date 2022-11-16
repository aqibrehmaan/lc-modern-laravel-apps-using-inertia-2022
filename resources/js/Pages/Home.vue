<template>
    <h1>Home</h1>

    <p>In this series, we will use the following frameworks:</p>

    <Nav />
  </template>

  <script>

import Nav from '../Shared/Nav';

  export default {
    props: {
      name: String,
      frameworks: Array,
    },
    components: { Nav },
  };
  </script>
