<template>

  <div class="container">
    <div class="content">
      
      <h1>An unofficial Notion renderer</h1>

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

      <h2>Example Notion Playground Pages</h2>
      <div class="links">
        <NuxtLink class="button--grey" to="/2e22de6b770e4166be301490f6ffd420">
          react-notion tester
        </NuxtLink>
        <NuxtLink class="button--grey" to="/067dd719a912471ea9a3ac10710e7fdf">
          react-notion-x tester
        </NuxtLink>
      </div>
      
    </div>
  </div>

</template>

<script>
export default {}
</script>
