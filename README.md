# Shopify Development Resources
It can be hard to find the right resources for building Shopify apps and themes. Here's the best resources we've found to get you going in the world of Shopify app and theme development.



## Table Of Contents

1. [General](#General)
2. [Python](#Python)
3. [Javascript](#Javascript)
4. [Ruby](#Ruby)
4. [Theme Development](#ThemeDevelopment)
6. [Open Source Apps](#OpenSource)
7. [Contributing](#Contributing)



## <a name="General"></a>General
A list of resources that apply to every language.

- [Polaris](https://polaris.shopify.com/)  
Shopify's style guide for building embedded app interfaces.

- [Polaris React Components](https://github.com/shopify/polaris)  
Shopify's React component library. Usefully for building embedded app interfaces.

- [Supported Libraries](https://help.shopify.com/api/supported-libraries)  
A list of supported and third party libraries Shopify recommends.

- [Shopify API Reference](https://help.shopify.com/api/reference)  
The official and original shopify API Reference.

- [Shopify Storefront API Reference](https://help.shopify.com/api/storefront-api)
The official documentation for Shopify's new Storefront API. Build stores into just about any website using React and GraphQL!

- [Using Webhooks](https://help.shopify.com/api/getting-started/webhooks)  
Shopify's guide to using webhooks and authenticating them from the source.

- [How to Build a Shopify App in One Week](https://www.shopify.com.au/partners/blog/building-a-shopify-app-in-one-week)  
Written by Eric Davis this is a great resource with lots of tips for beginners building their first Shopify Apps.

- [How to Build Your First Shopify App](https://www.shopify.com.au/partners/blog/how-to-build-your-first-shopify-app)  
An article that covers the basic workflow of building a Shopify app.

- [5 Things We Learned Creating Our First Shopify App](https://www.shopify.com.au/partners/blog/16603843-5-things-we-learned-creating-our-first-shopify-app)  
An article by [Chris Houghton](https://twitter.com/CJHoughton) about things he learnt when building his first Shopify app.

- [Building a Shopify App that Sells](https://www.shopify.com/partners/blog/64209347-4-tips-for-building-a-shopify-app-that-sells)  
An article on how to build a best selling app  

- [Design Your Store Faster With Product CSVs and Images](https://www.shopify.ca/partners/blog/93467590-design-your-store-faster-with-product-csvs-and-images)  
A blog post with resources to populate your demo stores with products so you don't have to waste precious development time filling them out yourself.

- [How To GraphQL](https://www.howtographql.com/)  
The fullstack tutorial for GraphQL. If you want to give Shopify's new [Storefront API](https://help.shopify.com/api/storefront-api) a go then I recommend checking out this fullstack tutorial. It will teach you everything you need to know to get started with GraphQL.

- [Shopify Partner Training Courses](https://partner-training.shopify.com/my_courses)  
Learn from other successful Shopify Partners by taking free educational courses.

---

## <a name="Python"></a>Python
A list of resources for developing Shopify Apps in Python.  
There are tons of great resources and libraries available for Python. They're just all spread out over the internet.

- ### Demo Apps, Libraries and Addons
  - [Shopify API](https://github.com/Shopify/shopify_python_api)  
  The offical Shopify API implementation for Python. A must use for anyone developing apps in python

  - [Shopify Example Django App](https://github.com/Shopify/shopify_django_app)  
  An official example app from Shopify to help you get started building apps using Django

  - [Django Shopify Webhooks](https://github.com/discolabs/django-shopify-webhook)  
  Written by Gavin Ballard from [Disco Labs](https://www.discolabs.com/) this is a great addon that makes implementation of webhooks easy. Although it's not unmaintained so use at your own risk. It is open source however and available for any one to modify and patch for their own use.

  - [Django Shopify Auth](https://github.com/discolabs/django-shopify-auth)  
  Another one by [Gavin Ballard](http://www.gavinballard.com). This app shares many similiarities to the Shopify Example App above but adds user and shop authentication making it easier to implement common django patterns and resources.

- ### Articles and Tutorials  
  - [Build a Shopify App in 15 minutes with Django](http://gavinballard.com/shopify-app-in-15-minutes-with-django/)  
  [Gavin Ballard](http://www.gavinballard.com) (This man appears a lot!) provides a great resource on getting started building apps with Python and Django.

  - [Shopify Embedded SDK with Python and Flask](https://medium.com/@dernis/shopify-embedded-sdk-with-python-flask-6af197e88c63)  
  Building a Hello World embedded SDK app for Shopify with Flask

  - [Shopify Python Standards](https://github.com/Shopify/shopify_python)  
  This repository describes Python development standards at Shopify, and provides some utilities to assist other Python repositories adhere to these standards.
---

## <a name="Javascript"></a>Javascript

- ### Demo Apps, Libraries and Addons
  - [shopify-api-node](https://github.com/MONEI/Shopify-api-node)  
  The most popular and most user friendly Shopify API Interface for Node.

  - [CartJS](https://cartjs.org/)  
  A fantastic library by [Gavin Ballard](http://www.gavinballard.com) and DiscoLabs that uses Shopify's AJAX Cart API and Rivets to make adding things to Shopify Store carts so much easier!

  - [eslint-plugin-shopify](https://github.com/Shopify/eslint-plugin-shopify)  
  An ESLint plugin that contains all the rules used by Shopify for linting their javascript
  - [shopify-node-app](https://github.com/Elkfox/shopify-node-app)
  A skeleton node/express app to help ease the pain for prototyping a Shopify app.

- ### Articles, Tutorials and Other Text Based Resources.
  - [How to Make the Most of the Shopify Embedded App SDK](https://www.shopify.com.au/partners/blog/75776707-how-to-make-the-most-of-the-shopify-embedded-app-sdk)  
  A great article on building embedded Shopify apps with Node.

  - [Writing Javascript at Shopify](https://github.com/Shopify/javascript)  
  A resource that provides you with Shopify's own naming conventions and style guide for Javascript development.

  - Write some!!! Seriously. We're lacking so many javascript articles!
---
## <a name="Ruby"></a>Ruby
Ruby is the "official" language of Shopify so it makes sense that there would be the most resources for it. There are a lot of brilliant resources available so I'll try to list as many as I possibly can!

- ### Demo Apps, Libraries and Addons
  - [Shopify API](https://github.com/Shopify/shopify_api)  
  The official Ruby Gem for the Shopify REST API

  - [Shopify App Examples](https://github.com/Shopify/example-ruby-app)  
  The official repository for the Shopify API tutorials
  
  - [Shopify App](https://github.com/Shopify/shopify_app)  
  Adds a full Shopify API Application environment to your application

- ### Articles and Tutorials
  - [Building a Simple Shopify App](https://code.tutsplus.com/articles/building-a-simple-shopify-app--cms-26198)  
  A great tutorial on getting started building your first shopify app in Ruby

  - [Building a public Shopify application](https://help.shopify.com/api/tutorials/building-public-app)  
  An official tutorial by Shopify that covers building your first basic app in Ruby
  
  - [Shopify Scripts API Reference](https://help.shopify.com/api/tutorials/shopify-scripts)  
  Official reference to the Shopify Scripts for use on Plus Stores.

  - [Ruby Shopify Script Tutorial](http://gavinballard.com/ruby-shopify-script-tutorial/)  
  Automatting processes in Ruby by [Gavin Ballard](http://www.gavinballard.com)

---

## <a name="ThemeDevelopment"></a> Theme Development

- [Themekit](https://shopify.github.io/themekit)  
Shopify's theme development command line tool

- [Slate](https://shopify.github.io/slate)  
A theme scaffold and command line tool for developing Shopify themes

- [Concrete](https://github.com/Elkfox/Concrete)  
By [Elkfox](Elkfox), Concrete is a lightweight framework for building Shopify themes, supporting Slate and other methods

---

## <a name="OpenSource"></a> Open Source Apps
A list of open source working, full apps available for Shopify

- [Triggerify](https://github.com/christianblais/triggerify)  
By [Christian Blais](https://github.com/christianblais) from Shopify, this ruby app is similiar to [ITTT](https://ifttt.com), but for Shopify webhooks.

<s>- [Parcelify](https://github.com/christianblais/parcelify)  
By [Christian Blais](https://github.com/christianblais) Parcelify lets you create simple yet powerful shipping rates based on address fields.</s>

## <a name="Contributing"></a>Contributing
If you have an item you want to add to the list feel free to make a fork and make a pull request with you additions


By [Elkfox](https://www.elkfox.com)
