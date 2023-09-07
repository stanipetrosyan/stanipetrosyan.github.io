<script>
  import { Card, Heading, Span, List, Li } from "flowbite-svelte";
    import Item from "./components/Item.svelte";
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
      <Item 
        img="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg"
        name="Docker, Docker-compose, Docker Swarm"
      ></Item>
      <Item 
        img="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nginx/nginx-original.svg"
        name="NGINX"
      ></Item>
      <Item 
        img="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg"
        name="Git"
      ></Item>
      <Item 
        img="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg"
        name="PostgreSQL"
      ></Item>
      <Item 
        img="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/grafana/grafana-original.svg"
        name="Grafana"
      ></Item>
      <Item 
        img="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/ansible/ansible-original.svg"
        name="Ansible"
      ></Item>
      <Item 
        img="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/terraform/terraform-original.svg"
        name="Terraform"
      ></Item>
      <Li>Gitlab CI/CD</Li>
    </List>
  </figure>
  <figure
    class="flex flex-col justify-center items-center p-8 text-center bg-white rounded-bl-lg border-b border-gray-200 md:border-b-0 md:border-r dark:bg-gray-800 dark:border-gray-700"
  >
    <Heading tag="h3">Platforms</Heading>
    <List tag="ul" class="space-y-1">
      <Item
        img="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-original.svg"
        name="AWS"
      ></Item>
      <Item
        img="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/gitlab/gitlab-original.svg"
        name="GITLAB"
      ></Item>
    </List>
  </figure>
  <figure
    class="flex flex-col justify-center items-center p-8 text-center bg-white rounded-b-lg border-gray-200 md:rounded-br-lg dark:bg-gray-800 dark:border-gray-700"
  >
    <Heading tag="h3">Languages & Frameworks</Heading>
    <List tag="ul" class="space-y-1">
      <Item
        img="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kotlin/kotlin-original.svg"
        name="Kotlin"
      ></Item>
      <Item
        img="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original.svg"
        name="Golang"
      ></Item>
      <Item
        img="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg"
        name="Javascript"
      ></Item>
      <Item
        img="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vuejs/vuejs-original.svg"
        name="VueJS"
      ></Item>
      <Item
        img=""
        name="Vert.x"
      ></Item>
    </List>
  </figure>
</Card>

<style>
</style>
