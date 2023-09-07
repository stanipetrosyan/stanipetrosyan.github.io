<script>
  import { Card, Heading, Span, List, Li } from "flowbite-svelte";
    import Item from "./components/Item.svelte";
</script>

<Card color="primary" size="xl" class="w-full grid md:grid-cols-2">
  <figure
    class="flex flex-col justify-center items-center p-8 text-center bg-white rounded-t-lg border-b border-gray-200 md:rounded-t-none md:rounded-tl-lg md:border-r dark:bg-gray-800 dark:border-gray-700"
  >
    <Heading tag="h3">Techniques</Heading>
    <List tag="ul" class="space-y-1">

      <div class="grid grid-cols-3 grid-rows-3 gap-4">
        <Item
          name="Agile"
        ></Item>
        <Item
          name="CQRS/ES"
        ></Item>
        <Item
          name="Clean Architecture"
        ></Item>
        <Item
          name="TDD"
        ></Item>
        <Item
          name="Pair Programming"
        ></Item>
        <Item
          name="Event Storming"
        ></Item>
        <Item
          name="CI/CD"
        ></Item>
    </div>
  </List>
    
  </figure>
  <figure
    class="flex flex-col justify-center items-center p-8 text-center bg-white rounded-tr-lg border-b border-gray-200 dark:bg-gray-800 dark:border-gray-700"
  >
    <Heading tag="h3">Tools</Heading>
    <List tag="ul" class="space-y-1">
      <div class="grid grid-cols-3 grid-rows-3 gap-4">
        <Item 
        img="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg"
        name="Docker"
        link="https://www.docker.com/"
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
      <Item 
        name="Gitlab CI/CD"
      ></Item>
      </div>
    </List>
  </figure>
  <figure
    class="flex flex-col justify-center items-center p-8 text-center bg-white rounded-bl-lg border-b border-gray-200 md:border-b-0 md:border-r dark:bg-gray-800 dark:border-gray-700"
  >
    <Heading tag="h3">Platforms</Heading>
    <List tag="ul" class="space-y-1">
      <div class="grid grid-cols-3 grid-rows-3 gap-4">
        <Item
          img="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-original.svg"
          name="AWS"
        ></Item>
        <Item
          img="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/gitlab/gitlab-original.svg"
          name="GITLAB"
        ></Item>
      </div>  
    </List>
  </figure>
  <figure
    class="flex flex-col justify-center items-center p-8 text-center bg-white rounded-b-lg border-gray-200 md:rounded-br-lg dark:bg-gray-800 dark:border-gray-700"
  >
    <Heading tag="h3">Languages & Frameworks</Heading>
    <List tag="ul" class="space-y-1">
      <div class="grid grid-cols-3 grid-rows-3 gap-4">
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
      </div>
    </List>
  </figure>
</Card>

<style>
</style>
