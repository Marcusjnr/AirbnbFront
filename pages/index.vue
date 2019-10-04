<template>
    <div>
        <div id="NW"></div>
        <div id="NE"></div>
        <div id="SE"></div>​
        <div id="SW"></div>
    </div>
</template>

<script>
import Chicago from '../components/Chicago'
import Denver from '../components/Denver'
import Indianapolis from '../components/Inidanapolis'
import NewYork from '../components/NewYork'

export default {
  components: {

  },

    created(){

    }
}
</script>

<style>
    html, body { height:100%; margin:0; padding:0 }
    div { position:fixed; width:50%; height:50% }
    #NW { top:0;
        left:0;
        border-right: 3px solid gray;
        border-bottom:  3px solid gray
    }

    #NE { top:0;   left:50%;   border-bottom:  3px solid gray}
    #SW { top:50%; left:0;    border-right: 3px solid gray; }
    #SE { top:50%; left:50%;     }
</style>
