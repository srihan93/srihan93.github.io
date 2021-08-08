---
published: true
---
## Implementing Simple Distributed Caching Techinique using Redis in .Net Core

Caching Techinques in Web Applications are very crucial when we needs to increase the performance of the Application.

There are multiple ways and techniques are available to implementing this caching, they are
1.In Memory Cache
2.Distributed Cache

### In Memory Cache
The In-Memory cache lives within the application and the cache data persists until the application stops. We will discuss in this in other article. .Net core's chaining oriented feature helps us to do this very simple.

### Distributed Cache
Distrubted cache is bit different from In-Memory caching, where we can store our caching data outside the application may be in different server. The data can be shared across from multiple application anywhere in the world

In this article, we will be implementing Redis cache, which is very famous and widely used provider. Its not neccessary that we have to only Redis to implement cache, we can implement this any noSql database like cosmos, mongo and even more.

Techinically Redis is a simple to implement the feature, using other database techniques may need more time to mimic the caching logics.

### How to Implement Caching in Code





In this Artic
