<script lang="ts">
    import '../app.postcss';
    import { AppShell, AppBar, Avatar } from '@skeletonlabs/skeleton';
    import { LightSwitch, CodeBlock } from '@skeletonlabs/skeleton';
</script>

<style>
  .center {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: center;
    height: 100vh;
    text-align: left; 
    margin-top: -30vh; /* Adjust the value as needed */
  }

  .header {
    text-align: left;
  }

  .text {
    text-align: left;
    white-space: pre-line;
  }

  .btn-container {
    display: flex;
    justify-content: flex-start;
  }
</style>

<div class="center">
  <div class="container mx-auto p-8 space-y-8">
    <h1 class="h1 font-abc header">Hello! I'm <span class="bg-gradient-to-br from-yellow-500 to-yellow-300 bg-clip-text text-transparent box-decoration-clone">Zap</span></h1>
    <p class="font-dm text">A Multipurpose Guilded bot capable of doing multiple 
    things! such as fun, utility, and much more.</p>
    <section class="btn-container">
      <a class="btn text-xl font-abc variant-soft-surface rounded py-3 px-7" href="https://www.guilded.gg/b/2e702266-2dfe-4796-b61c-ccbb0536444c">Invite Today!</a>
    </section>
  </div>
  
</div>
