<script lang="ts">
  export let title;
  export let icon;
  export let description;
</script>

<div class="card">
  <div class="card-title">
      <h3>{title}</h3>
      <img src={icon} alt=""/>
  </div>
  <div class="card-description">
      <p>
          {description}
      </p>
  </div>
</div>

<style>
  .card {
  width: 300px;
  min-height: 200px;
  background-color: transparent;
  border: 2px solid white;
  border-radius: 14px;
  display: flex;
  flex-direction: column;
  padding: 20px;
  transition: all 0.2s ease-in-out;
}

.card:hover {
  background-color: var(--primary-color-less-alpha);
}

.card-title {
  display: flex;
  padding: 20px 0px;
  width: 100%;
  flex-direction: row;
  justify-content: space-evenly;
  align-items: center;
  gap: 10px;
}

.card-title h3 {
  width: 50%;
  font-family: "K2D Bold";
  color: white;
  letter-spacing: 1px;
  font-weight: bold;
  font-size: 20px;
  margin: 0;
  padding: 0;
}

img {
  object-fit: contain;
  max-width: 64px;
  max-height: 64px;
}

.card-description {
  letter-spacing: 1px;
  width: 100%;
}
</style>