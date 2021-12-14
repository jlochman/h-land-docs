# Docs
Based on [ReType](https://retype.com/).

## Prerequisities
You need `npm` to install the `retypeapp` package
```
npm install retypeapp --global
```

## Install

clone repository
```
git clone https://github.com/jlochman/h-land-docs.git
cd h-land-docs
```

copy configuration to allow its customization
```
cp _retype.yml retype.yml
```

and edit following lines in `retype.yml`

for explanation:
- url: https://retype.com/configuration/project/#url
- server: https://retype.com/configuration/project/#server
- integrations: https://retype.com/configuration/project/#integrations

```
url: docs.h-land.io
server:
  host: 127.0.0.1:5000
integrations:
  googleAnalytics:
    id: UA-12345678-1
```

run server with configutaion specified in `retype.yml` file
```
retype watch
```

> Note: server will watch for any changes in `h-land-docs` folder. To update content, you'll need only to pull the newest version from repository. It's recommended to check if there are any changes in _retype.yml.

## Quick Links

- icons: https://octicons-primer.vercel.app/octicons/