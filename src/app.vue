<template>
    <div id="app">
      <header>
        <h1>Mental Health Care App</h1>
        <nav>
          <router-link to="/">Home</router-link>
          <router-link to="/journals">Journals</router-link>
          <router-link to="/resources">Resources</router-link>
        </nav>
      </header>
  
      <main>
        <router-view />
      </main>
  
      <footer>
        <p>&copy; 2024 Mental Health Care</p>
      </footer>
    </div>
  </template>
  
  <script>
  export default {
    name: 'App',
    data() {
      return {
        // Global app data can go here if necessary
      };
    }
  };
  </script>
  
  <style scoped>
  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }
  
  header {
    background-color: #4CAF50;
    padding: 10px 0;
    color: white;
  }
  
  nav a {
    margin: 0 15px;
    color: white;
    text-decoration: none;
  }
  
  footer {
    margin-top: 20px;
  }
  </style>
  