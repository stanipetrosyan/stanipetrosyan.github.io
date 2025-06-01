<script>
  import { Card, Heading, Span, List, Li } from "flowbite-svelte";
  import Item from "../components/Item.svelte";
</script>

<div class="grid grid-cols-2 grid-rows-2 gap-4">
  <Card class="text-center" size="xl" padding="xl">
    <Heading tag="h3">Techniques</Heading>

    <div class="grid grid-cols-3 grid-rows-3 gap-4 mt-8">
      <Item name="Agile" color="greenToBlue" />
      <Item name="CQRS/ES" color="greenToBlue" />
      <Item name="Clean Architecture" color="greenToBlue" />
      <Item name="TDD" img="./resources/tdd.png" color="greenToBlue" />
      <Item name="Pair Programming" color="greenToBlue" />
      <Item name="Event Storming" color="greenToBlue" />
      <Item name="CI/CD" img="./resources/ci-cd.png" color="greenToBlue" />
    </div>
  </Card>
  <Card class="text-center" size="xl" padding="xl">
    <Heading tag="h3">Tools</Heading>

    <div class="grid grid-cols-3 grid-rows-3 gap-4 mt-8">
      <Item
        img="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg"
        name="Docker"
        link="https://www.docker.com/"
        color="pinkToOrange"
      />
      <Item
        img="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nginx/nginx-original.svg"
        name="NGINX"
        link="https://www.nginx.com/"
        color="pinkToOrange"
      />
      <Item
        img="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg"
        name="Git"
        color="pinkToOrange"
      />
      <Item
        img="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg"
        name="PostgreSQL"
        link="https://www.postgresql.org/"
        color="pinkToOrange"
      />
      <Item
        img="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/grafana/grafana-original.svg"
        name="Grafana"
        link="https://grafana.com/"
        color="pinkToOrange"
      />
      <Item
        img="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/ansible/ansible-original.svg"
        name="Ansible"
        link="https://www.ansible.com/"
        color="pinkToOrange"
      />
      <Item
        img="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/terraform/terraform-original.svg"
        name="Terraform"
        link="https://www.terraform.io/"
        color="pinkToOrange"
      />
      <Item
        img="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/gitlab/gitlab-original.svg"
        name="Gitlab CI/CD"
        color="pinkToOrange"
      />
    </div>
  </Card>
  <Card class="text-center" size="xl" padding="xl">
    <Heading tag="h3">Platforms</Heading>

    <div class="grid grid-cols-3 grid-rows-3 gap-4 mt-8">
      <Item
        img="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/amazonwebservices/amazonwebservices-plain-wordmark.svg"
        name="AWS"
        color="purpleToBlue"
      />
      <Item
        img="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/gitlab/gitlab-original.svg"
        name="GITLAB"
        color="purpleToBlue"
      />
    </div>
  </Card>
  <Card class="text-center" size="xl" padding="xl">
    <Heading tag="h3">Languages & Frameworks</Heading>

    <div class="grid grid-cols-3 grid-rows-3 gap-4 mt-8">
      <Item
        img="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kotlin/kotlin-original.svg"
        name="Kotlin"
        link="https://kotlinlang.org/"
        color="tealToLime"
      />
      <Item
        img="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original.svg"
        name="Golang"
        link="https://go.dev/"
        color="tealToLime"
      />
      <Item
        img="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg"
        name="Javascript"
        color="tealToLime"
      />
      <Item
        img="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vuejs/vuejs-original.svg"
        name="VueJS"
        link="https://vuejs.org/"
        color="tealToLime"
      />
      <Item
        img="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/vertx/vertx-original.svg"
        name="Vert.x"
        link="https://vertx.io/"
        color="tealToLime"
      />
    </div>
  </Card>
</div>

<style>
</style>
