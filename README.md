# hoodie-camp-tutorial

> Hoodie Store & Account Tutorial for latest Hoodie Camp release

This is an app with instructions that you can follow
to learn all the basics about `hoodie.store` and `hoodie.account`.

## Requirements

- [git](http://www.git-scm.com/)
- [node](https://nodejs.org/en/) v4.4+
- npm v3+. npm comes with node, check with `npm -v`, install latest: `npm install -g npm`

## Installation & start

```
git clone https://github.com/hoodiehq/hoodie-camp-tutorial.git
cd hoodie-camp-tutorial
npm install
```

Once installation is done, you can start the app with

```
npm start
```

Now open [localhost:8080](http://localhost:8080)

## Offline First

This tutorial implments ServiceWorker and can be run offline using a Chrome or Firefox browser. To run offline, turn off the server (Ctrl + C) and refresh [localhost:8080](http://localhost:8080) using Chrome or Firefox. The tutorial page will still load.

To remove the offline tutorial from [localhost:8080](http://localhost:8080) visit chrome://serviceworker-internals/ if using Chrome, visit about:serviceworkers if using Firefox, or visit opera://serviceworker-internals/ if user Opera and unregister the ServiceWorker. 

Don’t worry if your browser doesn't support ServiceWorker yet, it only means that you can’t reload the page without the server running.



## License

[Apache 2.0](http://www.apache.org/licenses/LICENSE-2.0)
