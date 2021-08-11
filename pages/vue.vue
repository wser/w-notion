<template>
  <NotionRenderer :blockMap="blockMap" fullPage />
</template>

<script>
export default {
  data: () => ({ blockMap: null }),
  async asyncData({ $notion, $config: { PAGE_BLOCK } }) {
    // get Notion blocks from the API via a Notion pageId
    const blockMap = await $notion.getPageBlocks(`${PAGE_BLOCK}`);
    return { blockMap }
  },
};
</script>

<style>
@import "vue-notion/src/styles.css"; /* optional Notion-like styles */
</style>