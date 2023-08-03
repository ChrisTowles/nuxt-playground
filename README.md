# Nuxt Playground


Created as a playground to learn [Nuxt 3](https://nuxt.com/) and [nuxt ui](https://ui.nuxtlabs.com/)

The goal is to create a working example before integrating into a larger project at work.

- [Nuxt 3 documentation](https://nuxt.com/docs/getting-started/introduction)
- [Nuxt Awesome](https://github.com/nuxt-community/awesome-nuxt)
- [nuxt ui](https://ui.nuxtlabs.com/)



## Goals

- [x] Nuxt 3
- [ ] breakup folder layout as areas which have their components, pages, layouts, etc 
- [ ] Component UI library
  - [x] [Nuxt UI](https://ui.nuxtlabs.com/getting-started/installation) with tailwind
    - Still to new as of 2023-07-18
    - supported by company so not likely to die as they have built their paid products with it.
    - quickly adding features every 2 weeks
    - over 2 years old but just recently opened source.
    - made by names we know like Daniel roe and [Anthony Fu](https://github.com/antfu).  
  - [x] ~~[Native UI](https://www.naiveui.com/en-US/os-theme/docs/introduction)~~
    - Used by Patrick Towles Team, has bugs due to its port from vue 2 and not being fixed very fast. having to patch it
  - [x] ~~[flowbite](https://github.com/themesberg/flowbite)~~ 
    - not native vue 3 enough
  - [x] ~~[tailwindui](https://tailwindui.com/)~~ not really vue components
  - [ ] [quasar](https://quasar.dev/vue-components/)
    - [layout builder](https://quasar.dev/layout-builder/)
    - [quasar.dev layout examples](https://quasar.dev/layout/gallery/) 
  - [x] ~~[vuetifyjs](https://next.vuetifyjs.com/en/introduction/roadmap/)~~
    - check the discord for vue 3 info, the website is not up to date, Datatable still isn't ready. [good summary comment](https://www.reddit.com/r/vuejs/comments/135v44s/comment/jiofprd/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button)
  - [x] ~~[primevue](https://primevue.org/) so this is a wrapper around primefaces, which is a wrapper around jquery.~~
    - Not Vue focused, more of a rapper around a core and leaky abstraction.
  - [ ] [element plus](https://element-plus.org/#/en-US)
  - [x] ~~[buefy](https://buefy.org/)~~
    - didn't really feel enterprise look or feel.
  - [x] ~~[bootstrap vue](https://bootstrap-vue.org/)~~ no vue 3 support
  - [x] ~~[anu](https://anu-vue.netlify.app/)~~
    - really new Vue framework build using UnoCSS & VueUse.
    - too small of a community to use for work
- [ ] Form validation
  - [ ] zod and vee validate
- [ ] component unit tests
- [ ] e2e tests with playwright
- [ ] Storybook or similar for component testing?
- [ ] JWT auth


## Components to Test

- Navigation
  - Multipage and areas
- Table
  - Filter
  - search
  - sort
- Form
  - validation
    - zod and veeValidate
  - submit
- Vue 3

- Calendar
  - Likely to be outside library
- Cards
  - Collapsible
- Responsive

## Ideas for navigation

We seem to have complex areas and the left side nav bar isn't cutting it. 

- Github Nav
- Azure or AWS?
- ???

## Storybook

Setup a way to prevent components

## Setup

Make sure to install the dependencies:


```bash

pnpm install

# Start the development server 
pnpm run dev

# Build the application for production
pnpm run build

# Locally preview production build:
pnpm run preview

```


