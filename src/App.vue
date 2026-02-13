<template>
  <main class="page">
    <section class="card">
      <img class="logo" src="./assets/logo-rec.png" alt="RealEstateCare logo" />

      <h1>Hello World</h1>
      <p>Mobiele applicatie voor RealEstateCare.</p>

      <div class="features">
        <span>Dashboard</span>
        <span>Rapportages</span>
        <span>Kennisbase</span>
        <span>Instellingen</span>
      </div>
    </section>
  </main>
</template>

<style scoped>
.page {
  height: 100vh;
  display: grid;
  place-items: center;
  padding: 24px;

  background-color: var(--rec-bg);

  background-image: url("./assets/Achtergrondafbeeldingboven.png"),
    url("./assets/Achtergrondafbeeldingonder.png");
  background-repeat: no-repeat, no-repeat;
  background-position: top center, bottom center;
  background-size: 100% auto, 100% auto;

  overflow: hidden;
}

.card {
  background: white;
  width: min(720px, 100%);
  padding: 40px;
  border-radius: 16px;
  text-align: center;
  border-top: 8px solid var(--rec-primary);
  box-shadow: 0 10px 30px rgba(0, 0, 0, 0.08);
}

.logo {
  width: 180px;
  margin-bottom: 16px;
}

h1 {
  margin: 0 0 16px;
  color: var(--rec-dark);
  font-size: 32px;
}

p {
  margin: 0 0 20px;
  color: var(--rec-text);
  font-size: 16px;
}

.features {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  justify-content: center;
}

.features span {
  padding: 8px 14px;
  border-radius: 999px;
  background: rgba(0, 170, 162, 0.12);
  border: 1px solid rgba(0, 170, 162, 0.35);
  color: var(--rec-dark);
  font-size: 15px;
  cursor: pointer;
}

.features span:hover {
  background: rgba(0, 170, 162, 0.18);
}
</style>