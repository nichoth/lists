## fonts
* [pointy](https://www.fontmirror.com/pointy) -- [bitfoundry](https://bitfoundry.ca/collections/frontpage/products/pointy-font)

## more notes and examples and stuff
* https://github.com/nichoth/fauna-netlify
* https://github.com/nichoth/buying-things 
* https://github.com/nichoth/netlify-notes

## hosting
[more list](https://dev.to/fullstack_to/services-for-your-jamstack-application-45e5)

## web
* https://surge.sh/ -- surge -- CLI for deploying
* netlify -- github listener
* https://vercel.com/ -- github listener

## ipfs
* fleek -- traditional web and magic ipfs hosting
* https://play2.temporal.cloud/auth -- playground -- ipfs pinning
* ethoFS -- https://ethofs.com/

## database
* fauna -- https://fauna.com/ -- "severless" db
* [firebase](https://firebase.google.com/) -- free tier
* [airtable](https://airtable.com/)

## CMS
* https://www.sanity.io/ -- free/3 users. Seems to be it's own DB (not just git)
  - https://www.sanity.io/docs/datastore
  - [sanity ecommerce](https://www.sanity.io/solutions/e-commerce)
  - [sanity ecommerce again](https://www.sanity.io/blog/e-commerce-sample-schema)
* https://www.datocms.com/ -- free/2 users
* https://forestry.io/ -- free/1 user i think -- git based, not DB
* [Contentful](https://www.contentful.com/) -- free/10 users, "micro" space
* https://prismic.io/ -- free/1 user
* netlify CMS -- free -- makes commits to your repo
* [storyblok](https://www.storyblok.com/) -- free/1 user

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
Render the markup for each route as a static page.  Each page links to the same JS app, which handles client side routing.  If the href is local to the server, then re-render the HTML via the client-side JS.

------------------------------

## square CMS
Go to https://squareup.com/dashboard/items/library to add/remove "products" from the CMS.

-------------------------------

## faunaDB
* [Example of using FaunaDB with Netlify functions](https://github.com/netlify/netlify-faunadb-example/blob/master/README.md)
* [Netlify integration with fauna](https://docs.fauna.com/fauna/current/integrations/netlify.html)
* [ecommerce](https://docs.fauna.com/fauna/current/tutorials/ecommerce.html)
* https://github.com/nichoth/fauna-netlify


## netlify cms
Put the netlify CMS single page app in the route `/admin`. It allows you to save content to your repository via github.



