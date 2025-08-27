<script setup>
import {
  FwbCard, FwbHeading
} from 'flowbite-vue'
import KnowledgeItem from './KnowledgeItem.vue';


const techniques = [
  { name: "Agile", color: "green-blue" },
  { name: "CQRS/ES", color: "green-blue" },
  { name: "Clean Architecture", color: "green-blue" },
  { name: "TDD", color: "green-blue" },
  { name: "Pair Programming", color: "green-blue" },
  { name: "Event Storming", color: "green-blue" },
  { name: "CI/CD", color: "green-blue" },
]

const tools = [
  { img: "https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg", name: "Docker", link: "https://www.docker.com/", color: "pink-orange" },
  { img: "https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nginx/nginx-original.svg", name: "NGINX", link: "https://www.nginx.com/", color: "pink-orange" },
  { img: "https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg", name: "Git", color: "pink-orange" },
  { img: "https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg", name: "PostgreSQL", link: "https://www.postgresql.org/", color: "pink-orange" },
  { img: "https://cdn.jsdelivr.net/gh/devicons/devicon/icons/grafana/grafana-original.svg", name: "Grafana", link: "https://grafana.com/", color: "pink-orange" },
  { img: "https://cdn.jsdelivr.net/gh/devicons/devicon/icons/ansible/ansible-original.svg", name: "Ansible", link: "https://www.ansible.com/", color: "pink-orange" },
  { img: "https://cdn.jsdelivr.net/gh/devicons/devicon/icons/terraform/terraform-original.svg", name: "Terraform", link: "https://www.terraform.io/", color: "pink-orange" },
  { img: "https://cdn.jsdelivr.net/gh/devicons/devicon/icons/gitlab/gitlab-original.svg", name: "Gitlab CI/CD", color: "pink-orange" }
]

const platforms = [
  { img: "https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/amazonwebservices/amazonwebservices-plain-wordmark.svg", name: "AWS", color: "purple-blue" },
  { img: "https://cdn.jsdelivr.net/gh/devicons/devicon/icons/gitlab/gitlab-original.svg", name: "GITLAB", color: "purple-blue" },
]

const languages = [
  { img: "https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kotlin/kotlin-original.svg", name: "Kotlin", color: "teal-lime", link: "https://kotlinlang.org/" },
  { img: "https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original.svg", name: "Golang", color: "teal-lime", link: "https://go.dev/" },
  { img: "https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg", name: "Javascript", color: "teal-lime" },
  { img: "https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vuejs/vuejs-original.svg", name: "VueJS", color: "teal-lime", link: "https://vuejs.org/" },
  { img: "https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/vertx/vertx-original.svg", name: "Vertx", color: "teal-lime", link: "https://vertx.io/" }
]

</script>

<template>
  <div class="grid grid-cols-2 grid-rows-2 gap-4">
    <fwb-card class="text-center max-full md:max-w-full p-10 bg-gray-900 dark:bg-teal-600" variant="horizontal">
      <fwb-heading tag="h3" class="text-white">Techniques</fwb-heading>

      <div class="grid grid-cols-3 grid-rows-3 gap-10 mt-8">
        <div v-for="item in techniques">
          <KnowledgeItem :name="item.name" :color="item.color" />
        </div>
      </div>

    </fwb-card>
    <fwb-card class="text-center max-full md:max-w-full p-10 bg-gray-900 dark:bg-teal-600" variant="horizontal">
      <fwb-heading tag="h3" class="text-white">Tools</fwb-heading>

      <div class="grid grid-cols-3 grid-rows-3 gap-10 mt-8">
        <div v-for="item in tools">
          <KnowledgeItem :img="item.img" :link="item.link" :name="item.name" :color="item.color" />
        </div>
      </div>
    </fwb-card>
    <fwb-card class="text-center max-full md:max-w-full p-10 bg-gray-900 dark:bg-teal-600" variant="horizontal">
      <fwb-heading tag="h3" class="text-white">Platforms</fwb-heading>
      <div class="grid grid-cols-3 grid-rows-3 gap-10 mt-8">
        <div v-for="item in platforms">
          <KnowledgeItem :img="item.img" :name="item.name" :color="item.color" />
        </div>
      </div>
    </fwb-card>
    <fwb-card class="text-center max-full md:max-w-full p-10 bg-gray-900 dark:bg-teal-600" variant="horizontal">
      <fwb-heading tag="h3" class="text-white">Languages & Frameworks</fwb-heading>

      <div class="grid grid-cols-3 grid-rows-3 gap-10 mt-8">
        <div v-for="item in languages">
          <KnowledgeItem :img="item.img" :link="item.link" :name="item.name" :color="item.color" />
        </div>
      </div>
    </fwb-card>
  </div>

</template>

<style scoped></style>
