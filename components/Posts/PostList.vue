<template>
  <div>
    <section class="posts-list">
      <PostPreview
        id="1"
        title="Post Title 1"
        previewText="Preview Text"
        thumbnail="https://www.paxforpeace.nl/media/imagick/pax-report-killer-robots-dont-be-evil-700.jpg"
      />
      <PostPreview
        id="2"
        title="Post Title 2"
        previewText="Preview Text"
        thumbnail="https://www.journalismlab.nl/wp-content/uploads/2019/02/Diekerhof-Jlab-pict.-feiten-zijn-heilig-feb.-2019.jpg"
      />
    </section>
  </div>
</template>

<script>
import PostPreview from "@/components/Posts/PostPreview";
export default {
  components: {
    PostPreview
  }
};
</script>

<style scoped>
.posts-list {
  display: flex;
  padding: 20px;
  box-sizing: border-box;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
}
</style>