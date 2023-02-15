<template>
   
</template>

<script>
export default {
  name: 'IndexPage',
  head(){
    return {
      // js this page only
      script : [
        { 
          hid: 'stripe4', 
          src: '/assets/plugins/custom/fullcalendar/fullcalendar.bundle.js', 
          // defer: true,
          body:true,
          // callback: () => { this.isStripeLoaded = true } 
        },
		    { 
          hid: 'stripe5', 
          src: '/assets/js/pages/widgets.js', 
          // defer: true,
          body:true,
          // callback: () => { this.isStripeLoaded = true } 
        },
      ]
        
    }
  },
}
</script>
