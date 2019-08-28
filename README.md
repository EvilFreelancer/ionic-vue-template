# ionic-vue-template

A small blank with Ionic and VueJS to simplify the process of creating mobile applications


## Preparation

We need to install `npx` command line tool first (details [is here](https://ionic.zone/capacitor/cli)):

```
npm install -g @capacitor/cli
```

Install dependencies of project:

```
npm install
```

Compiles and minify for production:

```
npm run build
```

## Building application

### Android APK

```
npx cap add android
```

Copy compiled files to NPX application build roots:

```
npm run copy
```

Build then

```
cd android
./gradlew build
```

Result of build will be in `app/build/outputs/apk` of `android` folder.

### IOS package

Coming soon.

## Links

* https://ionicframework.com/blog/a-vue-from-ionic/
* https://www.techiediaries.com/ionic-vue/
* https://ionic.zone/capacitor/cli
* https://capacitor.ionicframework.com/docs/getting-started/
