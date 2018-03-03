<template>
    <div>
        <section class="level">
            <div class="level-item">
                <p class="is-size-2 is-uppercase">Latest posts</p>
            </div>
        </section>
        <PostPreview />
        <PostPreview />
        <PostPreview />
    </div>

</template>

<script>
import PostPreview from '@/components/Posts/PostPreview'

export default {
  components: {
    PostPreview
  }
}
</script>

<style scoped>

</style>