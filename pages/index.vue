<template>
  <main>
    <section class="self-center flex flex-col flex-1 items-center justify-center">
      <div class="p-5">
        <img :src="require('/static/cmsicon.png')" width="160px" />
      </div>
      <a href="https://gestionhseq.com"><h1 class="title text-center">GestionHSEQ</h1></a>
      <h2 class="subtitle text-center">CMS</h2>
    </section>
    <section class="mt-8">
      <h3 class="text-primary-600 dark:text-primary-400 max-w-5xl mx-auto">Último post</h3>
      <posts post-type="blog" :amount="1" />
    </section>
  </main>
</template>
