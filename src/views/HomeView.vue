<template>
  <main class="flex flex-col justify-center min-h-screen m-40">
    <!-- Title Section -->
    <div class="text-left group relative">
      <h1 class="text-7xl font-light tracking-tight">MARKUS LIEN</h1>
      <h2 class="text-9xl font-light">Psychologist</h2>

      <!-- Hover Subtitle -->
      <div
        class="absolute opacity-0 transform transition-opacity duration-300 -bottom-12 right-0 w-full group-hover:opacity-100">
        <h2 class="text-sm font-light p-4 bg-white rounded-lg shadow-lg max-w-md">
            I am skilled in assessing and diagnosing neurodevelopmental disorders like ADHD, ADD, and Autism spectrum disorders, certified in ADOS-2. I also conduct intelligence assessments for adolescents and adults using WAIS and WISC.<br><br>
            I am an authorized psychologist, a title granted by the Danish Supervisory Board of Psychological Practice, and a member of Dansk Psykologforening.
        </h2>
      </div>
    </div>

    <!-- Quote Section with Hover Effect for Citation -->
    <div class="mt-20 max-w-screen-md text-left group relative">
      <p class="text-2xl italic font-light leading-relaxed">
        “ Everything can be taken from a man but one thing: <br />
        the last of the human freedoms – to choose one's attitude in any given
        set of circumstances, to choose one's own way ”
      </p>

      <!-- Citation Box (appears on hover over the quote) -->
      <div
        class="absolute opacity-0 transition-opacity duration-300 -bottom-10 left-0 group-hover:opacity-100">
        <span class="text-sm font-light bg-grey-200 px-2 py-1 rounded shadow-lg" >
          Viktor Frankl, 1946
        </span>
      </div>
    </div>
  </main>
</template>
