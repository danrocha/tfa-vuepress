<template>
  <footer class="bg-black p-8 w-full text-white">
    <div class="flex justify-center mb-8">
      <ul class="list-reset flex flex-row justify-center">
        <li class="mx-8 uppercase">
          <a href="#navigation" class="link link-dark" alt="Back to Top">&uarr;&nbsp;Back to Top</a>
        </li>
        <li v-if="!$page.frontmatter.home" class="mx-8 uppercase">
          <a href="/" class="link link-dark" alt="Home">Home</a>
        </li>
        <li class="mx-8 uppercase">
          <a href="/guides" class="link link-dark" alt="Back to Top">Guides</a>
        </li>
        <li class="mx-8 uppercase">
          <a href="/blog" class="link link-dark" alt="Blog">Blog</a>
        </li>
        <li class="mx-8 uppercase">
          <a href="/about" class="link link-dark" alt="About">About</a>
        </li>
        <li class="mx-8 uppercase">
          <a href="/newsletter" class="link link-dark" alt="Newsletter">Newsletter</a>
        </li>
      </ul>
    </div>
    <div class="flex justify-center text-white mb-4">
      <a
        href="https://twitter.com/theForeignArch"
        class="mr-4 text-white shadow-none hover:shadow-none hover:text-grey-light"
        target="_blank"
        alt="@theForeignArch on Twitter"
        aria-label="Open my profile on Twitter"
        rel="noopener"
      >
        <i class="fab fa-twitter-square fa-2x"></i>
      </a>
      <a
        href="https://www.linkedin.com/in/danrocha/"
        class="mr-4 text-white shadow-none hover:shadow-none hover:text-grey-light"
        target="_blank"
        alt="Daniel da Rocha on LinkedIn"
        aria-label="Open my profile on Linkedin"
        rel="noopener"
      >
        <i class="fab fa-linkedin fa-2x"></i>
      </a>
      <a
        href="https://www.pinterest.de/theforeignarchitect/pins/"
        class="mr-4 text-white shadow-none hover:shadow-none hover:text-grey-light"
        alt="@theForeignArchitect on Pinterest"
        target="_blank"
        aria-label="Open my profile on Pinterest"
        rel="noopener"
      >
        <i class="fab fa-pinterest-square fa-2x"></i>
      </a>
      <a
        href="https://www.instagram.com/danroc/"
        class="mr-4 text-white shadow-none hover:shadow-none hover:text-grey-light"
        target="_blank"
        alt="@danroc on Instagram"
        aria-label="Open my profile on Instagram"
        rel="noopener"
      >
        <i class="fab fa-instagram fa-2x"></i>
      </a>
    </div>
    <div class="text-white w-full flex justify-center items-center flex-no-shrink">
      © Daniel da Rocha 2019. Made with &nbsp;
      <a
        href="https://vuepress.vuejs.org"
        target="_blank"
        rel="noopener noreferrer"
        class="link link-dark"
      >VuePress</a>.
    </div>
  </footer>
</template>

<script>
export default {
  name: 'Footer',
};
</script>

<style scoped>
</style>