# hosting

[more list](https://dev.to/fullstack_to/services-for-your-jamstack-application-45e5)

## web
* https://surge.sh/ -- surge -- CLI for deploying
* netlify -- github listener
* https://vercel.com/ -- github listener

## ipfs
* fleek -- tad web and magic ipfs hosting
* https://play2.temporal.cloud/auth -- playground -- ipfs pinning
* ethoFS -- https://ethofs.com/

## database
* fauna -- https://fauna.com/ -- "severless" db
* [firebase](https://firebase.google.com/) -- free tier
* [airtable](https://airtable.com/)

## CMS
* https://www.sanity.io/
* https://www.datocms.com/
* https://forestry.io/
* Contentful -- free/10 users, "micro" space
* https://prismic.io/ -- $7/3 users
* netlify CMS -- free -- makes commits to your repo

## "stores"
* snipcart -- payments and cart UI
"Display and manage orders, customers and discounts inside your own CMS admin."
* square

------------------------

## snipcart info

https://user-guides.prismic.io/en/articles/868753-sample-ecommerce-site-with-snipcart-in-node-js

https://www.contentful.com/blog/2016/02/10/snipcart-middleman-contentful/

https://snipcart.com/blog/hugo-tutorial-static-site-ecommerce


## email
* https://sendgrid.com/


# notes

## ssr
Render the markup for each route as a static page

each page links to the same JS app, which handles client side routing.

If the href is local to the server, then re-render the HTML via the client-side JS

------------------------------

# square CMS
Go to https://squareup.com/dashboard/items/library to add/remove "products" from the CMS.

-------------------------------

# faunaDB

* [Example of using FaunaDB with Netlify functions](https://github.com/netlify/netlify-faunadb-example/blob/master/README.md)
* [Netlify integration with fauna](https://docs.fauna.com/fauna/current/integrations/netlify.html)

