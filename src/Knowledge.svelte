<script>
  import { Blockquote, Card, Heading, Mark, Span } from "flowbite-svelte";
</script>

<Card color="primary" padding="none" size="xl" class="grid md:grid-cols-2">
  <figure class="flex flex-col justify-center items-center p-8 text-center bg-white rounded-t-lg border-b border-gray-200 md:rounded-t-none md:rounded-tl-lg md:border-r dark:bg-gray-800 dark:border-gray-700">
  <Blockquote alignment="center">
    <Heading tag="h3">Techniques</Heading>
  </Blockquote>    
  <p class="my-4 font-light">
    AGILE, TDD, Pair programming, CQRS/ES, Event stormign, Clean Code, Clean
    Architecture, Hexagonal Architecture
  </p>
  </figure>
  <figure class="flex flex-col justify-center items-center p-8 text-center bg-white rounded-tr-lg border-b border-gray-200 dark:bg-gray-800 dark:border-gray-700">
    <Blockquote alignment="center">
      <Heading tag="h3"><Span gradient>Tools</Span></Heading>
    </Blockquote>
    <p class="my-4 font-light">Designing with Figma components that can be easily translated to the utility classes of Tailwind CSS is a huge timesaver!"</p>

  </figure>
  <figure class="flex flex-col justify-center items-center p-8 text-center bg-white rounded-bl-lg border-b border-gray-200 md:border-b-0 md:border-r dark:bg-gray-800 dark:border-gray-700">
    <Blockquote alignment="center">
      <Heading tag="h3"><Span gradient gradientClass="red">Platforms</Span></Heading>

    </Blockquote>
    <p class="my-4 font-light">Aesthetically, the well designed components are beautiful and will undoubtedly level up your next application."</p>

  </figure>
  <figure class="flex flex-col justify-center items-center p-8 text-center bg-white rounded-b-lg border-gray-200 md:rounded-br-lg dark:bg-gray-800 dark:border-gray-700">
    <Blockquote alignment="center">
      <Heading tag="h3"><Span gradient>Languages & Frameworks</Span></Heading>
    </Blockquote>
    <p class="my-4 font-light">You have many examples that can be used to create a fast prototype for your team."</p>

  </figure>
</Card>



<style>
</style>
