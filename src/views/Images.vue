<template>
  <div class="main">
    <b-container class="bv-example-row">
      <b-row>
        <b-col></b-col>
        <b-col class="maincontainer">
          <b-jumbotron header="Bearded Brush Co.">
            <div class="text-center">
              <b-embed
                type="iframe"
                aspect="16by9"
                src="https://www.youtube.com/embed/zpOULjyy-n8?rel=0"
                allowfullscreen
              ></b-embed>
            </div>
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

<style></style>
