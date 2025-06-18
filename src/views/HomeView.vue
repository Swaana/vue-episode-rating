<script setup lang="ts">

</script>

<template>
  <div class="filters">
    <div class="season-selection card">
      <span>Season:</span>
      <ul>
        <li>
          <span>1</span>
          <input type="checkbox" name="season" value="1" />
        </li>
      </ul>
    </div>
  </div>
  <div class="episode-list">
    <div class="episode-container">
      <div class="episode-info">
        <div class="card">
          <div>
            <span>Title</span>
            <span>?</span>
          </div>
          <div>
            <span>Released</span>
            <span>?</span>
          </div>
          <div>
            <span>Season</span>
            <span>?</span>
          </div>
          <div>
            <span>Episode</span>
            <span>?</span>
          </div>
          <div>
            <span>Rating</span>
            <span>
              <StarIcon star-shine />
              <StarIcon star-shine />
              <StarIcon />
              <StarIcon />
              <StarIcon />
            </span>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
