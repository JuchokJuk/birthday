<script>
  import Header from "../../../shared/fontSystem/Header.svelte";
  import Text from "../../../shared/fontSystem/Text.svelte";
</script>

<div class="card">
  <div class="steps">
    <div class="step">
      <!-- svelte-ignore a11y-missing-attribute -->
      <img src="/images/1.png" />
      <Text>1. о Буся!</Text>
    </div>
    <div class="step">
      <!-- svelte-ignore a11y-missing-attribute -->
      <img src="/images/2.png" />
      <Text>2. привет</Text>
    </div>
    <div class="step">
      <!-- svelte-ignore a11y-missing-attribute -->
      <img src="/images/3.png" />
      <Text>3. падади</Text>
    </div>
    <div class="step">
      <!-- svelte-ignore a11y-missing-attribute -->
      <img src="/images/4.png" />
      <Text>3. ам!</Text>
    </div>
  </div>
  <div class="header">
    <Header>С днём рождения,</Header>
    <Header>Буся!!11!!!!1</Header>
  </div>
</div>

<style>
  .card {
    display: grid;
    grid-template-columns: 1fr;
    gap: 58px;
    justify-items: center;
    align-content: center;

    width: 100%;
    height: 100%;
    max-width: 506px;
    max-height: 506px;

    padding: 32px;

    background: #eeb7bf;
    border-radius: 8px;
  }

  .header {
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  .steps {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 12px;
  }

  .step {
    display: grid;
    grid-template-columns: 1fr;
    gap: 4px;
    justify-items: center;
  }

  img {
    width: 100%;
    border-radius: 4px;
  }
</style>
