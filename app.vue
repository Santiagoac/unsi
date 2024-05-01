<template>
  <div class="relative bg-white">
    <div class="mx-auto max-w-7xl lg:grid lg:grid-cols-12 lg:gap-x-8 lg:px-8">
      <div class="px-6 pb-24 pt-10 sm:pb-32 lg:col-span-7 lg:px-0 lg:pb-56 lg:pt-48 xl:col-span-6">
        <div class="mx-auto max-w-2xl lg:mx-0">
          <nuxt-img src="/logo.svg" alt="Unsi Logo" class="h-11" />
          <div class="hidden sm:mt-32 sm:flex lg:mt-16">
          </div>
          <h1 class="mt-24 text-4xl font-bold tracking-tight text-gray-900 sm:mt-10 sm:text-6xl">Un sí, definitivo</h1>
          <p class="mt-6 text-lg leading-8 text-gray-600">Conoce a una persona y prevee riesgos.</p>
          <div class="mt-10 flex items-center gap-x-6">
            <a href="#" class="rounded-md bg-teal-600 px-3.5 py-2.5 text-sm font-semibold text-white shadow-sm hover:bg-teal-500 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-teal-600">Solicitar una validación</a>
            <a href="#" class="text-sm font-semibold leading-6 text-gray-900">Solicitar información <span aria-hidden="true">→</span></a>
          </div>
        </div>
      </div>
      <div class="relative lg:col-span-5 lg:-mr-8 xl:absolute xl:inset-0 xl:left-1/2 xl:mr-0">
        <nuxt-img src="/heroimage.webp" alt="Dynamic and engaging relevant image" class="aspect-[3/2] w-full bg-gray-50 object-cover lg:absolute lg:inset-0 lg:aspect-auto lg:h-full" />
      </div>
    </div>
  </div>
</template>
