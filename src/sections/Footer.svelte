<script lang="ts">
  function onClick() {
    console.log("hello world");
  }
</script>

<footer class="w-full mt-16">
  <div class="flex justify-between text-sm text-zinc-500">
    <div>February 2023</div>
    <a
      href="https://blinpete-resume.vercel.app/"
      class="hover:underline active:text-zinc-900"
      target="_blank"
      rel="noopener noreferrer"
      >inspired by <span class="italic">blinpete</span></a
    >
    <div>Resumee · Luca Müller</div>
    <a
      href="https://github.com/cuvar/resumee"
      target="_blank"
      rel="noopener noreferrer"
      class="hover:underline active:text-zinc-900">Source Code</a
    >
    <button on:click={onClick} class="underline decoration-dotted"
      >PDF version</button
    >
  </div>
</footer>
