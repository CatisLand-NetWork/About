## About Site for CatisLand-NetWork

CatisLand NetWork is a non-profit organization registered in the capital city of Yunping in the United States of Starry Sky. This is our 'About' page.

It is deployed by Hugo and GitHub Pages on about.otokonoko.top

## Local Development

Pre-requisites: [Hugo](https://gohugo.io/getting-started/installing/), [Go](https://golang.org/doc/install) and [Git](https://git-scm.com)

```shell
# Clone the repo
git clone https://github.com/imfing/hextra-starter-template.git

# Change directory
cd hextra-starter-template

# Start the server
hugo mod tidy
hugo server --logLevel debug --disableFastRender -p 1313
```

### Update theme

```shell
hugo mod get -u
hugo mod tidy
```

See [Update modules](https://gohugo.io/hugo-modules/use-modules/#update-modules) for more details.


[![Netlify Status](https://api.netlify.com/api/v1/badges/88303fd9-ae09-4c0f-8b8c-3c8224a072bd/deploy-status)](https://app.netlify.com/sites/catisland-network/deploys)
