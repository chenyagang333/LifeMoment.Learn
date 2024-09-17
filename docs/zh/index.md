---
# https://vitepress.dev/reference/default-theme-home-page
layout: home

hero:
  name: "LifeMoment"
  text: "记录生活的网站"
  tagline: 技术栈：MySQL + .NET8 WebAPI + EF Core + Vue3
  actions:
    - theme: brand
      text: 项目背景
      link: /zh/guide/project-context
    - theme: alt
      text: 快速开始
      link: /zh/guide/project-context
    - theme: alt
      text: GitHub
      link: https://github.com/chenyagang333/LifeMoment
  image:
      src: /vitepress-logo-mini.svg
      alt: VitePress

features:
  - icon: <svg xmlns="http://www.w3.org/2000/svg" width="30" viewBox="0 0 256 220.8"><path fill="#41B883" d="M204.8 0H256L128 220.8 0 0h97.92L128 51.2 157.44 0h47.36Z"/><path fill="#41B883" d="m0 0 128 220.8L256 0h-51.2L128 132.48 50.56 0H0Z"/><path fill="#35495E" d="M50.56 0 128 133.12 204.8 0h-47.36L128 51.2 97.92 0H50.56Z"/></svg>
    title: Feature A
    link: https://www.bilibili.com/video/BV1Xh411V7b5/?spm_id_from=333.1007.top_right_bar_window_custom_collection.content.click&vd_source=766fad692fb72f85fdc46526d087aab0
    linkText: 哈哈
    details: Lorem ipsum dolor sit amet, consectetur adipiscing elit
  - title: Feature B
    details: Lorem ipsum dolor sit amet, consectetur adipiscing elit
  - title: Feature C
    details: Lorem ipsum dolor sit amet, consectetur adipiscing elit
---

<style>
:root {
  --vp-home-hero-name-color: transparent;
  /* --vp-home-hero-name-background: -webkit-linear-gradient(120deg, #bd34fe 30%, #41d1ff);

  --vp-home-hero-image-background-image: linear-gradient(-45deg, #bd34fe 50%, #47caff 50%); */
  --vp-home-hero-name-background: -webkit-linear-gradient(120deg, #827efe 30%, #ffa237);

  --vp-home-hero-image-background-image: linear-gradient(-45deg, #827efe 50%, #ffa237 50%);
  --vp-home-hero-image-filter: blur(44px);
}

@media (min-width: 640px) {
  :root {
    --vp-home-hero-image-filter: blur(56px);
  }
}

@media (min-width: 960px) {
  :root {
    --vp-home-hero-image-filter: blur(68px);
  }
}
</style>
