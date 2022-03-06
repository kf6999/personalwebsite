<script lang="ts">
	import Typewriter from 'svelte-typewriter'
</script>

<main>
  <div class="flex h-screen justify-center mt-20">
    <div class="text-center">
      <Typewriter interval={75} cursor={false}>
        <h1 class="text-5xl font-semibold">Kenneth Fan</h1>
      </Typewriter>

        <p class="mt-2">Fouth year CIT student at <a target="_blank" rel="noopener noreferrer" href="http://rit.edu">RIT</a></p>
        <button class="btn btn-success btn-xs mt-3">Currently Looking</button>

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
