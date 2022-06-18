<template>
  <section>
    <h2>My Friends</h2>
    <ul>
      <li></li>
    </ul>
  </section>
</template>

<script>
export default {
  data() {
    return {
      friends: [
        {
          id: "manuel",
          name: "Manuel Lorenz",
          phone: "0705246698",
          email: "hammedakeeb@gmail.com",
        },
        {
          id: "julie",
          name: "Julie Jones",
          phone: "08123061496",
          email: "hammedakeeb@gmail.com",
        },
      ],
    };
  },
};
</script>
