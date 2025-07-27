<script>
  import {
    Timeline,
    TimelineItem,
    Card,
    Blockquote,
    List,
    Li,
    Heading
  } from "flowbite-svelte";
</script>

<span>
  <div class="grid grid-cols-3 gap-4">
    <div class="col-start-2">
      <Timeline order="vertical">
        <TimelineItem title="Analyst  & Software Developer at Afliant s.r.l">
          <Blockquote size="xs" class="mb-4">October 2024 - Present</Blockquote>
          <Card class="p-4 sm:p-6 md:p-8 mb-4" size="xl">
            <Heading tag="h5"
              class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white"
            >
              Cisalfa Sport
            </Heading>
            <List tag="ul" class="space-y-1 text-gray-500 dark:text-gray-400">
              <Li>
                Functional analysis of the flows requested by the customer to
                implement the new OMS system for managing shipments
              </Li>
            </List>
          </Card>
          <Card class="p-4 sm:p-6 md:p-8 mb-4" size="xl">
            <Heading tag="h5"
              class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white"
            >
              Trentino electronic school register system
            </Heading>
            <List tag="ul" class="space-y-1 text-gray-500 dark:text-gray-400">
              <Li>
                Development of microservice solutions as a Full Stack Developer
              </Li>
            </List>
          </Card>
        </TimelineItem>

        <TimelineItem title="Software Developer at CherryChain s.r.l">
          <Blockquote size="xs" class="mb-4"
            >August 2020 - October 2024</Blockquote
          >
          <Card class="p-4 sm:p-6 md:p-8 mb-4" size="xl">
            <Heading tag="h5"
              class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white"
            >
              Loyalty customer management for DAO partners
            </Heading>
            <List tag="ul" class="space-y-1 text-gray-500 dark:text-gray-400">
              <Li
                >Development of microservice solutions as a Full Stack
                Developer;</Li
              >
              <Li
                >Native Android application development for the release of
                loyalty cards and retrieval of personal data via CIE 3.0;</Li
              >
              <Li
                >Prototyping and implementation of RESTful API for third
                parties;</Li
              >
              <Li
                >Supervisor and implementer of infrastructure change using
                Terraform;</Li
              >
              <Li
                >Transition from a system managed by AWS EC2 servers and Docker
                Swarm to an AWS ECS system and Application Load Balancer;</Li
              >
            </List>
          </Card>

          <Card class="p-4 sm:p-6 md:p-8 mb-4" size="xl">
            <Heading tag="h5"
              class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white"
            >
              Real-time consumption display system for Dolomiti Energia
            </Heading>
            <List tag="ul" class="space-y-1 text-gray-500 dark:text-gray-400">
              <Li
                >RPA development for extraction, transformation, and loading of
                consumption data per user on an MSSQL database;
              </Li>
              <Li
                >Development of RESTful API service for retrieval of consumption
                data;</Li
              >
            </List>
          </Card>
        </TimelineItem>
        <TimelineItem title="Bachelor Degree at University of Trento">
          <Blockquote size="xs">September 2017 - September 2020</Blockquote>
        </TimelineItem>
      </Timeline>
    </div>
  </div>
</span>

<style>
</style>
