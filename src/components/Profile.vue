<template>
    <body>
      <div class="Profile">
        <h2 style="color: black">{{ message }}</h2>
        <p>
          {{ msg }}
        </p>
  
        <p>
          {{ msg2 }}
        </p>
        <p>
          {{ msg3 }}
        </p>
        <p>
          {{ msg4 }}
        </p>
        <p>
          {{ msg5 }}
        </p>
        <hr class="style1" />
      </div>
    </body>
  </template>
  
  <script>
  export default {
    name: 'Profile',
    data() {
      return {
        message: 'Personal Information',
        msg: 'Name: Sundiang, Francis Carl A.',
        msg2: 'Age: 20',
        msg3: 'Email: fasundiang@student.hau.edu.ph',
        msg4: ' Contact Number: +63 962 621 2713',
      };
    },
  };
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped>
  h2 {
    margin: 40px 0 0;
  }
  ul {
    list-style-type: none;
    padding: 0;
  }
  li {
    display: inline-block;
    margin: 0 10px;
  }
  a {
    color: black;
  }
  </style>