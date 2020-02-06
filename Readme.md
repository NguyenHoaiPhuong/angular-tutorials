# Angular tutorials

## Angular CLI

To install the Angular CLI, in a terminal or command prompt type:

```
npm install -g @angular/cli
```

This may take a few minutes to install. You can now create a new Angular application by typing:

```
ng new my-app
```

`my-app` is the name of the folder for your application. This may take a few minutes to create the Angular application in TypeScript and install its dependencies.

Let's quickly run our Angular application by navigating to the new folder and typing `ng serve` to start the web server and open the application in a browser:

```
cd my-app
ng serve
```

## Remarks

### Local and global Angular CLI versions mismatched issue
It is necessary to have both a global and local install for the `ng` tools to work.

If you try to run `ng serve` on an application without the local install of the CLI (global install only), you will get the following error.

> Your global Angular CLI version (8.3.25) is greater than your local version (7.0.7). The local Angular CLI version is used.

Please take the following steps to avoid issues:

```
npm install --save-dev @angular/cli@latest
```

```
npm install --save-dev @angular/cli@latest
```

### Global typescript version issue

The Angular Compiler requires TypeScript >=3.4.0 and <3.6.0 but 3.7.5 was found instead

```
npm i --save-dev typescript@3.5.3
```


## References

https://angular.io/start

https://cli.angular.io/

https://code.visualstudio.com/docs/nodejs/angular-tutorial