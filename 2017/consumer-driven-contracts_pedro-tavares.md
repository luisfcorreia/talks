Boost your confidence with Consumer-Driven Contracts
========================

* Speaker   : [Pedro Tavares](https://pixels.camp/ordepdev)
* Length    : 30~45 minutes
* Language  : English

Description
-----------

In a monolithic application we don't need to worry about breaking contracts between different services because the compiler will do that job for us. If a given method signature changes, the contract between shared services is broken, and the build will automatically fail.

In a microservices application, we have a whole new scenario where different services are deployed in different runtimes and don't know anything about each others. We don't have the compiler to detect those breaking changes and they became hard to detect. Usually, they're found during end-to-end testing in a pre-production environment.

We need to ensure that when we deploy a new service into production, our changes won't break any consumer; We can do this kind of testing without the need of a real consumer by using consumer-driven contracts.

In this talk, I will show you how to implement consumer-driven contracts and we'll move TDD to the level of software architecture.

Speaker Bio
-----------

**Pedro Tavares**

![Speaker Image](https://avatars2.githubusercontent.com/u/1714825?v=4&s=460)

I'm a passionate Software Engineer with interests around automated workflows, microservices, test-driven development, design patterns, and databases. Currently, I work at Jumia Services, the leading e-commerce fulfillment and delivery in Africa. If you can't find me building software, I bet you'll find me playing videogames or surfing waves in Portugal's Northern Coast.

Links
-----

* Blog: http://ordepdev.me
* Company: https://group.jumia.com/
* Github: http://github.com/ordepdev
* Twitter: https://twitter.com/ordepdev

Click [here][1] to see the full calendar and pick your favorite talks

[1]: https://pixels.camp/schedule/
