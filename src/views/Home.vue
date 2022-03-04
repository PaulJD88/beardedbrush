<template>
  <div class="main">
    <b-container class="bv-example-row">
      <b-row>
        <b-col></b-col>
        <b-col class="maincontainer">
          The Bearded Brush Co.
          <b-img
            src="https://picsum.photos/1024/400/?image=41"
            fluid
            alt="Responsive image"
          >
          </b-img>
          <b-button size="sm" href="#">Images</b-button>
          <b-button size="sm" href="#">About</b-button>
          <b-button pill variant="primary" size="sm" href="#">Contact</b-button>
        </b-col>
        <b-col></b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
// @ is an alias to /src

export default {}
</script>
<style scoped lang="scss">
.maincontainer {
  border: solid black;
  padding: 10px;
  margin-top: 200px;
}
</style>
