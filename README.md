# Camden Council - Camden Renewal

[![Netlify Status](https://api.netlify.com/api/v1/badges/be54ba80-d87e-4c7e-b9ab-e6488e8c7d51/deploy-status)](https://app.netlify.com/sites/sad-fermi-1a0978/deploys)

simple static site and jekyll blog

## running it locally

you need ruby and jekyll installed. [instructions on that here](https://jekyllrb.com/docs/installation/).

```
bundle install
bundle exec jekyll serve
```

...should do the job. it'll be on **localhost:4000**.

content is in the `_data` and `_posts` folders. remember that .yaml files care deeply about indentation!

## putting it on the web

[![Deploy to netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/wearefuturegov/camden-renewal)

you can host it for free on any static file host, such as github pages or netlify.

just run `jekyll build` and host the `_site` directory.
