<script setup>
import {
  FwbTimeline,
  FwbTimelineBody,
  FwbTimelineContent,
  FwbTimelineItem,
  FwbTimelinePoint,
  FwbTimelineTime,
  FwbTimelineTitle,
  FwbCard
} from 'flowbite-vue'
</script>

<template>
  <fwb-timeline>
    <fwb-timeline-item class="dark">
      <fwb-timeline-point />
      <fwb-timeline-content>
        <fwb-timeline-time>
          October 2024 - Present
        </fwb-timeline-time>
        <fwb-timeline-title>
         Analyst & Software Developer at Afliant s.r.l
        </fwb-timeline-title>
        <fwb-timeline-body>
          <fwb-card href="#" class="w-sm">
            <div class="p-5">
              <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">
                Cisalfa Sport
              </h5>
              <p class="font-normal text-gray-700 dark:text-gray-400">
                Functional analysis of the flows requested by the customer to
                implement the new OMS system for managing shipments
              </p>
            </div>
          </fwb-card>
          <fwb-card href="#" class="w-sm">
            <div class="p-5">
              <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">
                Trentino electronic school register system
              </h5>
              <p class="font-normal text-gray-700 dark:text-gray-400">
                Development of microservice solutions as a Full Stack Developer
              </p>
            </div>
          </fwb-card>
        </fwb-timeline-body>
      </fwb-timeline-content>
    </fwb-timeline-item>
    <fwb-timeline-item>
      <fwb-timeline-point />
      <fwb-timeline-content>
        <fwb-timeline-time>
          August 2020 - October 2024
        </fwb-timeline-time>
        <fwb-timeline-title>
          Software Developer at CherryChain s.r.l
        </fwb-timeline-title>
        <fwb-timeline-body>
           <fwb-card href="#" class="w-sm">
            <div class="p-5">
              <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">
                Loyalty customer management for DAO partners
              </h5>
              <ul>
                <li>Development of microservice solutions as a Full Stack Developer;
                </li>
                <li>Native Android application development for the release of
                loyalty cards and retrieval of personal data via CIE 3.0;
                </li>
                <li>Prototyping and implementation of RESTful API for third
                parties;
                </li>
                <li>Supervisor and implementer of infrastructure change using
                Terraform;
                </li>
                <li>Transition from a system managed by AWS EC2 servers and Docker
                Swarm to an AWS ECS system and Application Load Balancer;</li>
              </ul>
            </div>
          </fwb-card>
          <fwb-card href="#" class="w-sm">
            <div class="p-5">
              <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">
                Real-time consumption display system for Dolomiti Energia
              </h5>
              <ul>
                <li>RPA development for extraction, transformation, and loading of
                consumption data per user on an MSSQL database;
                </li>
                <li>Development of RESTful API service for retrieval of consumption
                data;
                </li>
              </ul>
            </div>
          </fwb-card>
        </fwb-timeline-body>
      </fwb-timeline-content>
    </fwb-timeline-item>
    <fwb-timeline-item>
      <fwb-timeline-point />
      <fwb-timeline-content>
        <fwb-timeline-time>
          September 2017 - September 2020
        </fwb-timeline-time>
        <fwb-timeline-title>
          Bachelor Degree at University of Trento
        </fwb-timeline-title>
        <fwb-timeline-body>
        </fwb-timeline-body>
      </fwb-timeline-content>
    </fwb-timeline-item>
  </fwb-timeline>

</template>

<style>
</style>
