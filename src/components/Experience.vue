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
  <div class="grid grid-cols-3 gap-4">
    <div class="col-start-2">
      <fwb-timeline>
        <fwb-timeline-item class="mt-12">
          <fwb-timeline-point>
            <svg aria-hidden="true" class="w-3 h-3 text-blue-600 dark:text-teal-400" fill="#009689"
              viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
              <path clip-rule="evenodd"
                d="M6 2a1 1 0 00-1 1v1H4a2 2 0 00-2 2v10a2 2 0 002 2h12a2 2 0 002-2V6a2 2 0 00-2-2h-1V3a1 1 0 10-2 0v1H7V3a1 1 0 00-1-1zm0 5a1 1 0 000 2h8a1 1 0 100-2H6z"
                fill-rule="evenodd" />
            </svg>

          </fwb-timeline-point>
          <fwb-timeline-content>
            <fwb-timeline-time class="text-zinc-200 dark:text-gray-400">
              October 2024 - Present
            </fwb-timeline-time>
            <fwb-timeline-title class="text-white mb-4">
              Analyst & Software Developer at Afliant s.r.l
            </fwb-timeline-title>
            <fwb-timeline-body>
              <fwb-card class="w-lg mb-4 bg-gray-900 dark:bg-teal-600" variant="horizontal">
                <div class="p-5">
                  <h5 class="mb-2 text-2xl font-bold tracking-tight text-white">
                    Cisalfa Sport
                  </h5>
                  <p class="font-normal text-gray-400 dark:text-gray-200">
                    Functional analysis of the flows requested by the customer to
                    implement the new OMS system for managing shipments
                  </p>
                </div>
              </fwb-card>
              <fwb-card class="w-lg mb-4 bg-gray-900 dark:bg-teal-600" variant="horizontal">
                <div class="p-5">
                  <h5 class="mb-2 text-2xl font-bold tracking-tight text-white">
                    Trentino electronic school register system
                  </h5>
                  <p class="font-normal text-gray-400 dark:text-gray-200">
                    Development of microservice solutions as a Full Stack Developer
                  </p>
                </div>
              </fwb-card>
            </fwb-timeline-body>
          </fwb-timeline-content>
        </fwb-timeline-item>
        <fwb-timeline-item>
         <fwb-timeline-point>
            <svg aria-hidden="true" class="w-3 h-3 text-blue-600 dark:text-teal-400" fill="#009689"
              viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
              <path clip-rule="evenodd"
                d="M6 2a1 1 0 00-1 1v1H4a2 2 0 00-2 2v10a2 2 0 002 2h12a2 2 0 002-2V6a2 2 0 00-2-2h-1V3a1 1 0 10-2 0v1H7V3a1 1 0 00-1-1zm0 5a1 1 0 000 2h8a1 1 0 100-2H6z"
                fill-rule="evenodd" />
            </svg>

          </fwb-timeline-point>
          <fwb-timeline-content>
            <fwb-timeline-time class="text-zinc-200 dark:text-gray-400">
              August 2020 - October 2024
            </fwb-timeline-time>
            <fwb-timeline-title class="text-white mb-4">
              Software Developer at CherryChain s.r.l
            </fwb-timeline-title>
            <fwb-timeline-body>
              <fwb-card class="w-lg mb-4 bg-gray-900 dark:bg-teal-600" variant="horizontal">
                <div class="p-5">
                  <h5 class="mb-2 text-2xl font-bold tracking-tight text-white">
                    Loyalty customer management for DAO partners
                  </h5>
                  <ul class="max-w-md space-y-1 text-gray-500 list-disc list-inside dark:text-gray-400">
                    <li class=" text-gray-400 dark:text-gray-200">Development of microservice solutions as a Full Stack
                      Developer;
                    </li>
                    <li class=" text-gray-400 dark:text-gray-200">Native Android application development for the release
                      of
                      loyalty cards and retrieval of personal data via CIE 3.0;
                    </li>
                    <li class=" text-gray-400 dark:text-gray-200">Prototyping and implementation of RESTful API for
                      third
                      parties;
                    </li>
                    <li class=" text-gray-400 dark:text-gray-200">Supervisor and implementer of infrastructure change
                      using
                      Terraform;
                    </li>
                    <li class=" text-gray-400 dark:text-gray-200">Transition from a system managed by AWS EC2 servers
                      and Docker
                      Swarm to an AWS ECS system and Application Load Balancer;</li>
                  </ul>
                </div>
              </fwb-card>
              <fwb-card class="w-lg mb-4 bg-gray-900 dark:bg-teal-600" variant="horizontal">
                <div class="p-5">
                  <h5 class="mb-2 text-2xl font-bold tracking-tight text-white">
                    Real-time consumption display system for Dolomiti Energia
                  </h5>
                  <ul class="max-w-md space-y-1 text-gray-500 list-disc list-inside dark:text-gray-400">
                    <li class=" text-gray-400 dark:text-gray-200">RPA development for extraction, transformation, and
                      loading of
                      consumption data per user on an MSSQL database;
                    </li>
                    <li class=" text-gray-400 dark:text-gray-200">Development of RESTful API service for retrieval of
                      consumption
                      data;
                    </li>
                  </ul>
                </div>
              </fwb-card>
            </fwb-timeline-body>
          </fwb-timeline-content>
        </fwb-timeline-item>
        <fwb-timeline-item>
          <fwb-timeline-point>
            <svg aria-hidden="true" class="w-3 h-3 text-blue-600 dark:text-teal-400" fill="#009689"
              viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
              <path clip-rule="evenodd"
                d="M6 2a1 1 0 00-1 1v1H4a2 2 0 00-2 2v10a2 2 0 002 2h12a2 2 0 002-2V6a2 2 0 00-2-2h-1V3a1 1 0 10-2 0v1H7V3a1 1 0 00-1-1zm0 5a1 1 0 000 2h8a1 1 0 100-2H6z"
                fill-rule="evenodd" />
            </svg>

          </fwb-timeline-point>
          <fwb-timeline-content>
            <fwb-timeline-time class="text-zinc-200 dark:text-gray-400">
              September 2017 - September 2020
            </fwb-timeline-time>
            <fwb-timeline-title class="text-white mb-4">
              Bachelor Degree at University of Trento
            </fwb-timeline-title>
            <fwb-timeline-body>
            </fwb-timeline-body>
          </fwb-timeline-content>
        </fwb-timeline-item>
      </fwb-timeline>
    </div>
  </div>

</template>

<style>

</style>
