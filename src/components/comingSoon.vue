<template>
  <main>
    <div id="glitch">█  █  <spanm style="color:#FFF">█ █ █ █ █ █ █ █ █ </spanm>    60%
        <br>&gt; Vikash's portfolio  comming soon&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
        <br>&gt; Devolepment in Progress <span id="cursor" style="color:#00b0a3">█</span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
      </div>
  </main>
</template>

<script>
export default {
}
</script>

<style scoped>
main{
  user-select: none;
}
div{
  color: rgb(250, 36, 121);
  font-family: Monaco, monospace !important;
  font-size: 1.5rem ;
  width: 100%;
  text-align: center;
  position: absolute;
  top: 45%;
  left: 0;
  animation: 120ms infinite normal glitch;
}
span {
  animation: 1.5s infinite normal cursor;
}

@keyframes glitch{
  0%{
    opacity: 0;
    left: 0;
  }
  40%,80%{
    opacity: 1;
    left: -2px;
  }
}
@keyframes cursor{
  0%{
    opacity: 0;
    left: 0;
  }
  40%{
    opacity:0;
    left: -2px;
  }
  80%{
    opacity: 1;
    left: -2px;
  }
}
 
/* Media querry */

@media (max-width: 786px) {

}

</style>
