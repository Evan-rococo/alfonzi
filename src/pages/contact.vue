<template>
  <Layout>
      

  <h3 style="text-align:left; background-color:none;font-weight:normal;font-family:ABC Helveesti Trial; line-height:1.125;">In your paypal payment, a tracking number will be added and can be searched right here. 
    PostNord delivers within 5 working days in the EU and somewhere around 6-8 in 
    North america and Asia.</h3>

  <Form />

 
  </Layout>
</template>


<script>
import Form from '~/components/Form.vue'
export default {
  components: {
    Form
  }
}
</script>

<style scoped>

@media (max-width: 33em) {
  .container {
    background:none;
    margin-left:5vw;
    margin-right:5vw;
    }

    .row {
  background-color:none;
  width: 100%;
}
 }

@media (max-width: 48em) {
  .container {
    margin-left:5vw;
    margin-right:5vw;
    margin-top: 0em;
    background-color:plum;
    }


  
h3 {
  margin-top: 4.8em;
  font-size:1.25em;
  margin-left: 5vw;
  margin-right: 5vw;
  background-color: none;
}

        }


 @media (min-width: 48em) {
  
h3 {
  margin-top:1.5em;
  margin-left:24vw;
  margin-right:2vw;
  background-color: none;
  padding: .67vw;
  font-size:1.25em;}

  

      }

  @media (min-width: 70em) {
  h3 {
  font-size:1.25em;
  margin-top:1.34em;
  margin-left:24vw;
  margin-right:2vw;
  background-color: none;}

  .container {
    margin-left:0vw;
    margin-right:5vw;
    margin-top: 0em;
    background-color:none;
    }
      }

@media (max-width: 33em) {  
  h3 {
  margin-top: 4.8em;
  font-size:1.25em;
  margin-left: 5vw;
  margin-right: 5vw;
  background-color: none;}
  }
</style>