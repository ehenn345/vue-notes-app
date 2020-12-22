<template>
  <div class="note-selectors">
        <NoteSelector1 />
        <div class="note-selector">
          <p class="note-selector-title">Second note...</p>
          <p class="note-selector-timestamp">Timestamp here...</p>
        </div>
        <div class="note-selector">
          <p class="note-selector-title">Third note...</p>
          <p class="note-selector-timestamp">Timestamp here...</p>
        </div>
      </div>
</template>

<script>
import NoteSelector1 from "./NoteSelector1.vue";
export default {
  components: {
    NoteSelector1,
  },
};
</script>