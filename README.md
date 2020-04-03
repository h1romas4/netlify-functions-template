# netlify-functions-template

[![](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/h1romas4/netlify-functions-template)

Includes access counter(accessories) sample program.

Note that, The counter disappears when the Lambda instance rebuild.

## Example

![](https://raw.githubusercontent.com/h1romas4/netlify-functions-template/master/assets/2020-03-30_01-19.png)

> [https://maple4estry.netlify.com/](https://maple4estry.netlify.com/)

## Develop

### Local develop

[![Netlify Status](https://api.netlify.com/api/v1/badges/ace22b90-5f18-4681-89d0-dfa40207706a/deploy-status)](https://app.netlify.com/sites/sample-counter/deploys)

Build & Start application:

```
git clone https://github.com/h1romas4/netlify-functions-template.git
cd netlify-functions-template
npm install
npm run devel # or npm run devel:debug
```

Access browser:

```
http://localhost:9000/.netlify/functions/counter

http://localhost:9000/.netlify/functions/digit?width=500&digit=6&number=10
```

## Cloud develop

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/h1romas4/netlify-functions-template)

Build & Start application:

![](https://raw.githubusercontent.com/h1romas4/netlify-functions-template/master/assets/gitpod-01.png)

Access browser:

paste this command-lines on gitpod terminal(open preview  browser)

```
gp preview $(gp url 9000)/.netlify/functions/digit/200/5/12345
```

## Thanks

* Counter SVG & CSS/JS by [@Fujix](https://github.com/Fujix1)
