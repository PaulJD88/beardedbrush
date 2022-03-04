<template>
  <div class="main">
    <b-container class="bv-example-row">
      <b-row>
        <b-col></b-col>
        <b-col class="maincontainer">
          <b-jumbotron header="Bearded Brush Co.">
            <b-img
              src="https://picsum.photos/1024/400/?image=41"
              fluid
              alt="Responsive image"
            >
            </b-img>
            <div class="text-center">
              <b-button-group>
                <b-button variant="outline-dark" size="sm">
                  <b-link to="/">Home</b-link>
                </b-button>
                <b-button variant="outline-dark" size="sm">
                  <b-link to="/images">Images</b-link>
                </b-button>
                <b-button variant="outline-dark" size="sm"
                  ><b-link to="/about">About</b-link>
                </b-button>
                <b-button variant="outline-dark" size="sm">
                  <b-link to="/contact">Contact</b-link>
                </b-button>
              </b-button-group>
            </div>
          </b-jumbotron>
        </b-col>
        <b-col> </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>

export default {}
</script>
<style scoped lang="scss">
.maincontainer {
  border: solid black;
  padding: 10px;
  margin-top: 200px;
  border-radius: 5px;
}
.text-center {
  margin: 10px;
}
</style>
