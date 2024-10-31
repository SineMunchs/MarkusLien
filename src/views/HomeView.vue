<template>
  <main class="flex flex-col justify-center min-h-screen m-40">
    <!-- Title Section -->
    <div class="text-left group relative">
      <h1 class="text-7xl font-light tracking-tight">MARKUS LIEN</h1>
      <h2 class="text-9xl mt-2 font-light">Psychologist</h2>

      <!-- Hover Subtitle -->
      <div
        class="absolute opacity-0 transform transition-opacity duration-300 -bottom-12 left-0 w-full group-hover:opacity-100"
      >
        <h2
          class="text-sm mt-3 font-light p-4 bg-white rounded-lg shadow-lg max-w-md"
        >
          I assess and diagnose ADHD, ADD, and Autism, certified in ADOS-2, and
          conduct intelligence testing with WAIS and WISC.
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
        class="absolute opacity-0 transition-opacity duration-300 -bottom-10 left-0 group-hover:opacity-100"
      >
        <span
          class="text-sm font-light bg-white px-2 py-1 rounded shadow-lg"
        >
          Viktor Frankl, 1946
        </span>
      </div>
    </div>
  </main>
</template>
