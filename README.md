# app

## Project setup

```
yarn install
```

### Compiles and hot-reloads for development

```
yarn serve
```

### Compiles and minifies for production

```
yarn build
```

### Run your unit tests

```
yarn test:unit
```

### Run your end-to-end tests

```
yarn test:e2e
```

### Lints and fixes files

```
yarn lint
```

### Change FARM ID
change farm id in farmer.vue

```
const farm = ref<string>("HERE YOUR FARM ID");
```

### Change Cluster Devnet / Mainnet 
Change cluster in ConfigPane.vue

```
setCluster(Cluster.Mainnet); /  setCluster(Cluster.Devnet);
````