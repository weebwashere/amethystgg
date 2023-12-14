<style>
  .center {
    display: flex;
    flex-direction: column;
    align-items: flex-start; /* Updated: align items to the left */
    justify-content: center;
    height: 100vh;
    text-align: left; /* Updated: align text to the left */
    margin-top: -30vh; /* Adjust the value as needed */
  }

  .header {
    text-align: left; /* Updated: align header text to the left */
  }

  .text {
    text-align: left; /* Updated: align text to the left */
    white-space: pre-line;
  }

  .btn-container {
    display: flex;
    justify-content: flex-start; /* Updated: align buttons to the left */
  }
</style>

<div class="center">
  <div class="container mx-auto p-8 space-y-8">
    <h1 class="h1 font-abc header">Hello! I'm <span class="bg-gradient-to-br from-red-500 to-yellow-500 bg-clip-text text-transparent box-decoration-clone">Reminder</span></h1>
    <p class="font-dm text">A <a class="anchor" href="https://guilded.gg">Guilded</a> reminder bot capable of creating reminders for users 
    to receive directly from Guilded! :D</p>
    <section class="btn-container">
      <a class="btn text-xl font-abc variant-soft-surface rounded py-3 px-7" href="https://www.guilded.gg/b/2e702266-2dfe-4796-b61c-ccbb0536444c">Invite Today!</a>
    </section>
  </div>
</div>

//wtf