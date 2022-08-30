Nuxt2-ts-storybook : template 1

- [Installed dependencies + configurations](#installed-dependencies--configurations)
  - [**Typescript**](#typescript)
    - [nuxt-property-decorator](#nuxt-property-decorator)
  - [**Storybook**](#storybook)
    - [**@nuxtjs/storybook**](#nuxtjsstorybook)
    - [**Gitignore**](#gitignore)
    - [**Command: yarn nuxt storybook**](#command-yarn-nuxt-storybook)
    - [**Command: yarn nuxt storybook eject**](#command-yarn-nuxt-storybook-eject)
    - [**main.js**](#mainjs)
    - [**@storybook/addon-a11y**](#storybookaddon-a11y)
    - [**postcss 8**](#postcss-8)
    - [**css-loader@5.2.0 -D**](#css-loader520--d)
    - [**ts-node**](#ts-node)
  - [**SASS**](#sass)
    - [**Sass**](#sass-1)
    - [**@nuxtjs/style-resources**](#nuxtjsstyle-resources)

Starter projects with different dependencies and setups, ready to use

# Installed dependencies + configurations

Nuxt 2 (Created with `yarn create nuxt-app` )

**NPM project Options:**

- Typescript
  - (adds: @nuxt/types, @nuxt/typescript-build )
- Axios

## **Typescript**

### nuxt-property-decorator

To use with class based components (provided by @nuxt/typescript-build)

## **Storybook**

### **@nuxtjs/storybook**

Storybook for Nuxt 2

### **Gitignore**

Added to gitignore:

.nuxt-storybook

storybook-static

### **Command: yarn nuxt storybook**

Command `yarn nuxt storybook` was run, which generated the **.nuxt-storybook** folder.

### **Command: yarn nuxt storybook eject**

Command `yarn nuxt storybook eject` was run, which generated the ".storybook" folder

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