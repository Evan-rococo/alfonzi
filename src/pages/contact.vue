<template>
  <Layout>
      

  <h3>In your paypal payment, a tracking number will be added and can be searched right here. 
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
.container {
  display: flex;
  flex-direction: column;
  margin-left: 26vw;
  margin-right: 0em;
  margin-bottom: 8em;
  width: 50vw;
  }

@media (max-width: 33em) {
  .container {
    background:none;
    }

    .row {
  background-color:none;
  width: 100%;
}
 }

@media (max-width: 48em) {
  .container {
    margin-left:2vw;
    margin-right:2vw;
    margin-bottom:8em;
    margin-top: 0em;
    width: 75.67vw;
     background-color:none;
    }


  
h3 {
  margin-top: 4.8em;
  font-size:1.25em;
  margin-left: 2vw;
  margin-right: 2vw;
  background-color: whitesmoke;
  padding:2vw;
}

        }


 @media (min-width: 48em) {
  
h3 {
  margin-top:1.5em;
  margin-left:24.67vw;
  margin-right:2vw;
  background-color: whitesmoke;
  padding: .67vw;
  font-size:1.25em;
}

      }

  @media (min-width: 64em) {
  


h3 {
  font-size:1.25em;
  margin-top:1.5em;
  margin-left:25vw;
  margin-right:2vw;
  background-color: whitesmoke;
  padding:.67vw;
}
      }

@media (max-width: 33em) {
     
      


h3 {
  margin-top: 4.8em;
  font-size:1.25em;
  margin-left: 2vw;
  margin-right: 2vw;
  background-color: whitesmoke;
  padding:2vw;}
  }
</style>