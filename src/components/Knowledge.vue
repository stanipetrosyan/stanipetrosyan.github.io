<script setup>
import {
  FwbCard, FwbHeading
} from 'flowbite-vue'
import KnowledgeItem from './KnowledgeItem.vue';


</script>

<template>
  <div class="grid grid-cols-2 grid-rows-2 gap-4">
    <fwb-card id="tech-card" class="text-center max-full md:max-w-full p-10 dark:bg-teal-600" variant="horizontal">
      <fwb-heading tag="h3">Techniques</fwb-heading>

      <div class="grid grid-cols-3 grid-rows-3 gap-4 mt-8">
        <KnowledgeItem name="Agile" color="green-blue" />
        <KnowledgeItem name="CQRS/ES" color="green-blue" />
        <KnowledgeItem name="Clean Architecture" color="green-blue" />
        <KnowledgeItem name="TDD" img="./resources/tdd.png" color="green-blue" />
        <KnowledgeItem name="Pair Programming" color="green-blue" />
        <KnowledgeItem name="Event Storming" color="green-blue" />
        <KnowledgeItem name="CI/CD" img="./resources/ci-cd.png" color="green-blue" />
      </div>
    </fwb-card>
    <fwb-card class="text-center max-full md:max-w-full p-10 p-10 dark:bg-teal-600" variant="horizontal">
      <fwb-heading tag="h3">Tools</fwb-heading>

      <div class="grid grid-cols-3 grid-rows-3 gap-4 mt-8">
        <KnowledgeItem img="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" name="Docker"
          link="https://www.docker.com/" color="pink-orange" />
        <KnowledgeItem img="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nginx/nginx-original.svg" name="NGINX"
          link="https://www.nginx.com/" color="pink-orange" />
        <KnowledgeItem img="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" name="Git"
          color="pink-orange" />
        <KnowledgeItem img="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg"
          name="PostgreSQL" link="https://www.postgresql.org/" color="pink-orange" />
        <KnowledgeItem img="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/grafana/grafana-original.svg" name="Grafana"
          link="https://grafana.com/" color="pink-orange" />
        <KnowledgeItem img="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/ansible/ansible-original.svg" name="Ansible"
          link="https://www.ansible.com/" color="pink-orange" />
        <KnowledgeItem img="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/terraform/terraform-original.svg" name="Terraform"
          link="https://www.terraform.io/" color="pink-orange" />
        <KnowledgeItem img="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/gitlab/gitlab-original.svg" name="Gitlab CI/CD"
          color="pink-orange" />
      </div>
    </fwb-card>
    <fwb-card class="text-center max-full md:max-w-full p-10 dark:bg-teal-600" variant="horizontal">
      <fwb-heading tag="h3">Platforms</fwb-heading>

      <div class="grid grid-cols-3 grid-rows-3 gap-4 mt-8">
        <KnowledgeItem
          img="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/amazonwebservices/amazonwebservices-plain-wordmark.svg"
          name="AWS" color="purple-blue" />
        <KnowledgeItem img="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/gitlab/gitlab-original.svg" name="GITLAB"
          color="purple-blue" />
      </div>
    </fwb-card>
    <fwb-card class="text-center max-full md:max-w-full p-10 dark:bg-teal-600" variant="horizontal">
      <fwb-heading tag="h3">Languages & Frameworks</fwb-heading>

      <div class="grid grid-cols-3 grid-rows-3 gap-4 mt-8">
        <KnowledgeItem img="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kotlin/kotlin-original.svg" name="Kotlin"
          link="https://kotlinlang.org/" color="teal-lime" />
        <KnowledgeItem img="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original.svg" name="Golang"
          link="https://go.dev/" color="teal-lime" />
        <KnowledgeItem img="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg"
          name="Javascript" color="teal-lime" />
        <KnowledgeItem img="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vuejs/vuejs-original.svg" name="VueJS"
          link="https://vuejs.org/" color="teal-lime" />
        <KnowledgeItem img="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/vertx/vertx-original.svg" name="Vert.x"
          link="https://vertx.io/" color="teal-lime" />
      </div>
    </fwb-card>
  </div>

</template>

<style scoped>

</style>
