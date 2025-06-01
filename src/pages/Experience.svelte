<script>
  import { Timeline, TimelineItem, Card, Blockquote } from "flowbite-svelte";
</script>

<span>
  <div class="grid grid-cols-3 gap-4">
    <div class="col-start-2">
      <Timeline order="vertical">
        <TimelineItem title="Analyst  & Software Developer at Afliant s.r.l">
          <Blockquote size="xs">October 2024 - Present</Blockquote>
          <Card class="p-4 sm:p-6 md:p-8">
            <h5
              class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white"
            >
              Noteworthy technology acquisitions 2021
            </h5>
            <p
              class="leading-tight font-normal text-gray-700 dark:text-gray-400"
            >
              Here are the biggest enterprise technology acquisitions of 2021 so
              far, in reverse chronological order.
            </p>
          </Card>
        </TimelineItem>

        <TimelineItem title="Software Developer at CherryChain s.r.l">
          <Blockquote size="xs">August 2020 - October 2024</Blockquote>
          <Card class="p-4 sm:p-6 md:p-8">
            <h5
              class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white"
            >
              Noteworthy technology acquisitions 2021
            </h5>
            <p
              class="leading-tight font-normal text-gray-700 dark:text-gray-400"
            >
              Here are the biggest enterprise technology acquisitions of 2021 so
              far, in reverse chronological order.
            </p>
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
