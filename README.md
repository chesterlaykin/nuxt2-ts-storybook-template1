# vue-nuxt-templates

- [vue-nuxt-templates](#vue-nuxt-templates)
  - [DEPENDENCIES](#dependencies)
  - [**Storybook**](#storybook)
    - [**@nuxtjs/storybook**](#nuxtjsstorybook)
    - [**Added to gitignore: .nuxt-storybook + storybook-static**](#added-to-gitignore-nuxt-storybook--storybook-static)
    - [**Command was run: yarn nuxt storybook**](#command-was-run-yarn-nuxt-storybook)
    - [**Command was run: yarn nuxt storybook eject**](#command-was-run-yarn-nuxt-storybook-eject)
    - [**main.js**](#mainjs)
    - [**@storybook/addon-a11y**](#storybookaddon-a11y)
    - [**postcss 8**](#postcss-8)
    - [**css-loader@5.2.0 -D**](#css-loader520--d)
    - [**ts-node**](#ts-node)
  - [**SASS**](#sass)
    - [**Sass**](#sass-1)
    - [**@nuxtjs/style-resources**](#nuxtjsstyle-resources)

Starter projects with different dependencies and setups, ready to use

## DEPENDENCIES

Nuxt 2 (Created with `yarn create nuxt-app` )

**NPM project Options:**

- Typescript
  - (adds: @nuxt/types, @nuxt/typescript-build )
- Axios

## **Storybook**

### **@nuxtjs/storybook**

Storybook for Nuxt 2

### **Added to gitignore: .nuxt-storybook + storybook-static**

.nuxt-storybook
storybook-static

### **Command was run: yarn nuxt storybook**

It generated the .nuxt-storybook folder.

### **Command was run: yarn nuxt storybook eject**

It generated the ".storybook" folder

### **main.js**

main.js in ".storybook" was edited:

```text
stories: [
    "../stories/**/*.stories.mdx",
    "../stories/**/*.stories.@(js|jsx|ts|tsx)"
  ],
```

^ pointing to a location for the stories (in this case a "stories" folder was created (can be changed))

### **@storybook/addon-a11y**

Accessibility addon (added to main.js config)

### **postcss 8**

Latest postcss version (Storybook may need it, but might not be necessary)

### **css-loader@5.2.0 -D**

Css-loader 5.2 (Storybook may need it, but might not be necessary)

### **ts-node**

Required for Storybook if using Typescript

## **SASS**

### **Sass**

Sass

### **@nuxtjs/style-resources**

To enable use of sass variables etc in vue components
