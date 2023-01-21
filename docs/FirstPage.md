## All About Me
Create the following file and put it in `components/Author.vue`
```HTML
<template>
  <div class="flex items-center w-3/4 min-h-screen mx-auto">
    <div class="flex-1">
      <h1 class="mb-3 text-3xl">Sammy</h1>
      <p class="mb-3 text-gray-700 pr-4">
        Hi 👋, I am a Full Stack Developer. I work
        with Nuxt, Vue, Tailwind and more.
      </p>
    </div>
    <div class="flex-1">
      <img
        class="w-full shadow-lg rounded"
        src="https://picsum.photos/600"
      />
    </div>
  </div>
</template>
```

## Update Index
Change `app.vue` to the following
```
<template>
  <section>
    <Author />
  </section>
</template>
```
