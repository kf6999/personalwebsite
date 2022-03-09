<script lang="ts">
	import Typewriter from 'svelte-typewriter'
    function playAudio() {

        var number= Math.floor(Math.random()*7);
        if (number==0) {
            var audio = new Audio("https://kennethfanresume.s3.amazonaws.com/among.mp3");
        } else if (number ==1 ){
            var audio = new Audio("https://kennethfanresume.s3.amazonaws.com/vine-boom.mp3");
        } else if (number ==2 ){
            var audio = new Audio("https://kennethfanresume.s3.amazonaws.com/amongus.mp3");
        } else if (number ==3 ){
            var audio = new Audio("https://kennethfanresume.s3.amazonaws.com/bruh.mp3");
        } else if (number ==4 ){
            var audio = new Audio("https://kennethfanresume.s3.amazonaws.com/android.mp3");
        } else if (number ==5 ){
            var audio = new Audio("https://kennethfanresume.s3.amazonaws.com/boing.mp3");
        } else if (number ==6 ){
            var audio = new Audio("https://kennethfanresume.s3.amazonaws.com/boi.mp3");
        }
        audio.play();
    }
</script>

<main>
  <div class="flex h-screen justify-center mt-20">
    <div class="text-center">
      <Typewriter interval={75} cursor={false}>
        <h1 class="text-5xl font-semibold">Kenneth Fan</h1>
      </Typewriter>

        <p class="mt-2">Fourth year CIT student at <a target="_blank" rel="noopener noreferrer" href="http://rit.edu">RIT</a></p>
        <button on:click={playAudio} class="btn btn-success btn-xs mt-3">Currently Looking</button>
    <div class="mt-10 space-y-2">      
        
      <a target="_blank" rel="noopener noreferrer" href="https://kennethfanresume.s3.amazonaws.com/ResumeKennethFan.pdf">Resume</a><p></p>
      <a target="_blank" rel="noopener noreferrer" href="https://github.com/kf6999">GitHub</a><p></p>
      <a href="mailto:kf6999@rit.edu">Email</a>  

      </div>
    </div>
  </div>

</main>

<style>


</style>
