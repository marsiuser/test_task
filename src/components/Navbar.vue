<template>
    <div class="wrapper">
            <md-toolbar class="md-transparent" md-elevation="0">
                Navigation
            </md-toolbar>
        <md-list>
            <md-list-item>
                <span class="md-list-item-text">Inbox</span>
            </md-list-item>
            <md-list-item>
                <span class="md-list-item-text">Sent Mail</span>
            </md-list-item>

            <md-list-item>
                <span class="md-list-item-text">Trash</span>
            </md-list-item>

            <md-list-item>
                <span class="md-list-item-text">Spam</span>
            </md-list-item>
        </md-list>
    </div>
</template>

<script>
    export default {}
</script>

<style lang="scss">
  .md-card-header{
    text-align: center;
  }
</style>