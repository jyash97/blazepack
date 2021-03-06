<h1 align="center">Blazepack ⚡</h1>

<p align="center">
  Blazing fast dev server powered by <a href="https://www.npmjs.com/package/smooshpack">sandpack</a>
</p>

## Motivation

I always wanted the super fast feedback that codesandbox provides in my local environment, so I have built a tiny wrapper around the codesandbox bundler sandpack and it runs locally 🎉

## Why Blazepack?

* It is blazing fast ⚡
* Super tiny (24kb) 👌
* Run projects without npm install 💃
* React fast refresh ❤️
* Supports React, Vue 2, Vue 3, Angular 🔨

## Usage

Install it globally

```
npm i -g blazepack
```

Start using it in your **create react app** or **vue cli app** 

```
blazepack
```

It will start the dev server at port **3000** and open it in browser, you can change the default port by using the **port** option

```
blazepack --port 3001
```

You can also run it using the **npx** command and not install it globally

```
npx blazepack
```

You can install a new package pretty fast using the below command. It does not create **node_modules** so you are gonna save a lot of space 😉

```
blazepack install redux
```


To know the version of blazepack you are running use the **--version** option

```
blazepack --version
```

Show your support by ⭐ the repo

## License

GPL © [Ameer Jhan](mailto:ameerjhanprof@gmail.com)
