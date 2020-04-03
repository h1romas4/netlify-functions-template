# netlify-functions-template

Includes joke access counter sample program.

Note that, The counter disappears when the Lambda instance rebuild.

## Netlify Deploy

[![](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/h1romas4/netlify-functions-template)

## Example

![](https://raw.githubusercontent.com/h1romas4/netlify-functions-template/master/assets/2020-03-30_01-19.png)

> [https://maple4estry.netlify.com/](https://maple4estry.netlify.com/)

## Local build & Devel

[![Netlify Status](https://api.netlify.com/api/v1/badges/ace22b90-5f18-4681-89d0-dfa40207706a/deploy-status)](https://app.netlify.com/sites/sample-counter/deploys)

```
git clone https://github.com/h1romas4/netlify-functions-template.git
cd netlify-functions-template
npm install
npm run devel
```

browser access

```
http://localhost:9000/.netlify/functions/counter

http://localhost:9000/.netlify/functions/digit?width=500&digit=6&number=10
```

## Import Gitpod for cloud develop

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/h1romas4/netlify-functions-template)

Start Debug

![](https://raw.githubusercontent.com/h1romas4/netlify-functions-template/master/assets/gitpod-01.png)

and Open preview internal browser (paste this command-lines on gitpod terminal):

```
gp preview $(gp url 9000)/.netlify/functions/digit/200/5/12345
```

## Thanks

* Counter SVG & CSS/JS by [@Fujix](https://github.com/Fujix1)
