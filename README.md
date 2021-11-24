# WGL Reports

## Start

Add .env and run

```
yarn start
```

Open: http://localhost:5488/

## Deploy

To deploy to heroku, run

```
heroku buildpacks:add https://github.com/jontewks/puppeteer-heroku-buildpack.git -a wgl-report
```

where wgl-report is the app name
