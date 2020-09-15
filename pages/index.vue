<template>

<div class="tile is-ancestor">
      <div class="tile is-parent is-1">
        <article class="tile is-child notification">
          <!--<p class="title">Vertical...</p>
          <p class="subtitle">Top tile</p>-->
        </article>
      </div>
      <div class="tile is-parent is-6">
        <article class="tile is-child notification is-info">
          <p class="title">Middle tile</p>
          <p class="subtitle">With an image</p>
          <figure class="image is-4by3">
            <!--<img src="https://bulma.io/images/placeholders/640x480.png">-->
            <iframe src="" style="width: 100%; height: 100%;"></iframe>
          </figure>
        </article>
      </div>

  <div class="tile is-parent is-4">
    <article class="tile is-child notification is-success">
      <div class="content">
        <p class="title">Tall tile</p>
        <p class="subtitle">With even more content</p>
        <div class="content">
          <!-- Content -->
        </div>
      </div>
    </article>
  </div>
</div>
</template>

<script>
export default {}
</script>

<style>

</style>
