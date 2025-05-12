<script>
  import { Card } from "flowbite-svelte";
</script>

<span>
  <div class="grid grid-cols-6 grid-rows-6 gap-4">
    <div class="col-start-3 col-end-4 row-start-2 row-end-5">
     <Card class="sm:p-10 md:p-12 p-12">
        <a href="/">
          <h5
            class="mb-2 text-2xl font-semibold tracking-tight text-gray-900 dark:text-white"
          >
            Full Stack Developer
          </h5>
        </a>
        <p class="mb-3 font-normal text-gray-500 dark:text-gray-400">
          Se vuoi conoscere la mia storia lavorativa e conoscenze professionale da Full Stack Developer
        </p>
        <a
          href="/software"
          class="text-primary-600 inline-flex items-center hover:underline"
        >
          See our guideline
        </a>
      </Card>
    </div>
   <div class="col-start-4 col-end-5 row-start-2 row-end-5">
      <Card class="sm:p-10 md:p-12 p-12">
        <a href="/">
          <h5
            class="mb-2 text-2xl font-semibold tracking-tight text-gray-900 dark:text-white"
          >
          Game Developer
          </h5>
        </a>
        <p class="mb-3 font-normal text-gray-500 dark:text-gray-400">
          Se vuoi conoscere la mia passione per la creazione dei videogiochi e il mio portfolio
        </p>
        <a
          href="/game"
          class="text-primary-600 inline-flex items-center hover:underline"
        >
          See our guideline
        </a>
      </Card>
    </div>
  </div>
</span>
