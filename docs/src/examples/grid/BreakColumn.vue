<template>
  <div class="q-pa-md">

    <div class="column inline items-start example-container">
      <div class="example-cell" tabindex="0">Col 1 / Row 1</div>
      <div class="example-cell" tabindex="0">Col 2 / Row 1 - 1<br>Col 2 / Row 1 - 2</div>
      <div class="flex-break"></div>
      <div class="example-cell" tabindex="0">Col 1 / Row 2</div>
      <div class="flex-break q-px-md"></div>
      <div class="example-cell" tabindex="0">Col 1 / Row 3</div>
      <div class="example-cell" tabindex="0">Col 2 / Row 3</div>
      <div class="example-cell" tabindex="0">Col 3 / Row 3</div>
    </div>

  </div>
</template>

<style lang="sass" scoped>
.flex-break
  flex: 1 0 100% !important
  width: 0 !important

.example-container
  height: 100px

  .example-cell
    margin: 1px
    padding: 4px 8px
    box-shadow: inset 0 0 0 2px $grey-6
</style>
