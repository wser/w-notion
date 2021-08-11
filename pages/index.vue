<template>

  <div class="container">
    <div class="content">
      
      <h1>vue-notion -> An unofficial Notion renderer</h1>

      <h3 class="nav">

        <span> · </span>
        <a target="_blank" href="https://github.com/janniks/vue-notion#docs"
          >Docs</a
        >

      </h3>

      <h2>Example from README</h2>
      <div class="links">
        <NuxtLink class="button--green" to="/nuxt">Basic Example</NuxtLink>
      </div>

      <h2>Static Generated Examples</h2>
      <div class="links">
        <p>Blog-style Examples (use Notion as a CMS for Nuxt)</p>
        <div class="links">
          <NuxtLink class="button--green" to="/posts">All Blog Posts</NuxtLink>
          <NuxtLink class="button--green" to="/example">
            Post via slug <i>(e.g. /example)</i>
          </NuxtLink>
        </div>
      </div>
    </div>
  </div>

</template>

<script>
export default {}
</script>
