<script>
  import { Card, Heading, Span, List, Li } from "flowbite-svelte";
</script>

<Card color="primary" padding="none" size="xl" class="grid md:grid-cols-2">
  <figure
    class="flex flex-col justify-center items-center p-8 text-center bg-white rounded-t-lg border-b border-gray-200 md:rounded-t-none md:rounded-tl-lg md:border-r dark:bg-gray-800 dark:border-gray-700"
  >
    <Heading tag="h3">Techniques</Heading>
    <List tag="ul" class="space-y-1">
      <Li>Agile</Li>
      <Li>CQRS/ES</Li>
      <Li>Clean Architecture</Li>
      <Li>TDD</Li>
      <Li>Pair Programming</Li>
      <Li>Event Storming</Li>
      <Li>CI/CD</Li>
    </List>
  </figure>
  <figure
    class="flex flex-col justify-center items-center p-8 text-center bg-white rounded-tr-lg border-b border-gray-200 dark:bg-gray-800 dark:border-gray-700"
  >
    <Heading tag="h3">Tools</Heading>
    <List tag="ul" class="space-y-1">
      <Li>Docker, Docker-compose, Docker Swarm</Li>
      <Li>NGINX</Li>
      <Li>Git</Li>
      <Li>PostgreSQL</Li>
      <Li>Grafana</Li>
      <Li>Ansible</Li>
      <Li>Terraform</Li>
      <Li>Gitlab CI/CD</Li>
    </List>
  </figure>
  <figure
    class="flex flex-col justify-center items-center p-8 text-center bg-white rounded-bl-lg border-b border-gray-200 md:border-b-0 md:border-r dark:bg-gray-800 dark:border-gray-700"
  >
    <Heading tag="h3">Platforms</Heading>
    <List tag="ul" class="space-y-1">
      <Li>AWS</Li>
      <Li>GitLab</Li>
    </List>
  </figure>
  <figure
    class="flex flex-col justify-center items-center p-8 text-center bg-white rounded-b-lg border-gray-200 md:rounded-br-lg dark:bg-gray-800 dark:border-gray-700"
  >
    <Heading tag="h3">Languages & Frameworks</Heading>
    <List tag="ul" class="space-y-1">
      <Li>Kotlin</Li>
      <Li>Golang</Li>
      <Li>Javascript</Li>
      <Li>Vert.x</Li>
      <Li>VueJS</Li>
    </List>
  </figure>
</Card>

<style>
</style>
