<template>
  <ul class="sidenav app-sidenav open">
    <router-link
      v-for="link in links"
      :key="link.url"
      tag="li"
      active-class="active"
      :to="link.url"
      :exact="link.exact"
    >
      <a href="#" class="waves-effect waves-orange pointer">{{link.title}}</a>
    </router-link>
  </ul>
</template>
<script>
export default {
  data: () => ({
    links: [
      {
        title: "Detail",
        url: "/",
        exact: true
      },
      {
        title: "History",
        url: "/history"
      },
      {
        title: "Planning",
        url: "/planning"
      },
      {
        title: "New record",
        url: "/record"
      },
      {
        title: "Categories",
        url: "/categories"
      }
    ]
  })
};
</script>