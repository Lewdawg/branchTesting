<template>
  <div class="container">
    <h1>{{ title }}</h1>
    <p>
      Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quod quis ullam
      veritatis odio ipsa. Iusto reiciendis cupiditate eveniet, ex suscipit nemo
      temporibus incidunt debitis quibusdam, recusandae ab facere ipsum numquam,
      autem iure fugit at dolorum? Fugiat sint laborum consequuntur repudiandae!
    </p>
  </div>
</template>

<script>
export default {
  //   props: ["title"],
  data() {
    return {
      title: "Home Page",
    };
  },
};
</script>

<style scoped>
.container {
  display: flex;
  flex-direction: column;
  align-items: center;

  padding: 20px 70px;
}

h1 {
  color: red;
}

p {
  color: blue;
}
</style>
