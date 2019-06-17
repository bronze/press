June 10, 2019

Detailing blog mode metadata configuration.

# Configuring metadata

You can change the metadata displayed in the default blog template
by setting some options in `nuxt.config.js`:

```js
export default {
  modules: ['@nuxt/press'],
  press: {
    blog: {
      title: 'My NuxtPress Blog',
      author: {
        github: 'http://github.com/nuxt/nuxt.js',
        twitter: 'https://twitter.com/nuxt_js'
      },
      // Used in RFC4151-based RSS feed entry tags
      tagDomain: 'nuxtjs.org'
    }
  }
}
```

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cras a orci 
sollicitudin diam ultrices varius. Ut sit amet bibendum leo. Donec nec enim 
nisi. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin vehicula 
lacus massa, sit amet elementum turpis tincidunt eu. Vestibulum ante ipsum 
primis in faucibus orci luctus et ultrices posuere cubilia Curae; Sed ut 
efficitur ipsum. Cras consequat in purus in dictum. Proin accumsan sem at 
facilisis facilisis. Suspendisse risus sem, faucibus vehicula pretium quis, 
dapibus at sapien.