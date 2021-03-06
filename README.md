# How to make app with vue.js

- npm i -g @vue/cli
- vue --version
- vue create \<appName>
- cd appName
- npm run serve
- or vue ui
- Extension: Vetur
- Devtools - Vue - Can see "Components Structure"

# Basic Structure

1. \<template>\</template>
2. \<script></br>
   import Component from './'; </br>
   export default {</br>
   name: 'app', </br>
   components:{}, </br>
   data(){}, </br>
   methods:{} </br>
   created(){} React의 componentDidmount(){}같은 것</br>
   };</br>
   \</script>
3. \<style>\</style> or \<style scoped>\</style>

# Basic Grammar

1. v-bind, v-bind:key, v-bind:class={"className: true/false"}
2. v-for
3. v-on:eventName="function", @click="\$emit('del-todo', todo.id)"
   - del-todo is code convention
   - \$emit을 이용하면 클릭한 대상을 상위 컴포넌트로 보내줄 수 있다.
4. v-model
5. Vue-router: vue ui - plugins 에서 클릭해주면 알아서 설치하고, App.vue를 덮어씀. 그러니 router 사용할거면 처음에 설치할 것

# Tips

- npm i uuid(for unique id)
- fake Rest API(https://jsonplaceholder.typicode.com/) https://jsonplaceholder.typicode.com/todos
- npm i axios(for Rest API)
- npm run build or ui - build - run task

# traversy_vue_todolist

## Project setup

```
npm install
```

### Compiles and hot-reloads for development

```
npm run serve
```

### Compiles and minifies for production

```
npm run build
```

### Lints and fixes files

```
npm run lint
```

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).
