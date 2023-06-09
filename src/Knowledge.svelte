<script>
  import Card from "./components/Card.svelte";
</script>

<h2>This is what I lernead</h2>

<h3>Methodologies</h3>

<p>AGILE, TDD, Pair programming, CQRS/ES, Event stormign, Clean Code, Clean Architecture, Hexagonal Architecture </p>

<h3>Languages</h3>
<x-grid>
  <x-cell>
    <Card title="Kotlin" icon="" description="" />
  </x-cell>
  <x-cell>
    <Card title="Golang" icon="" description="" />
  </x-cell>
</x-grid>

<h3>Tools</h3>
<x-grid>
  <x-cell>
    <Card title="Docker" icon="" description="" />
  </x-cell>
  <x-cell>
    <Card title="AWS" icon="" description="" />
  </x-cell>
  <x-cell>
    <Card title="Grafana" icon="" description="" />
  </x-cell>
  <x-cell>
    <Card title="Terraform" icon="" description="" />
  </x-cell>
  <x-cell>
    <Card title="Gitlab CI/CD" icon="" description="" />
  </x-cell>
</x-grid>


<style>
  p {
    font-size: 17px;
  }
</style>
