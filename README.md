Symfony certification guide
===========================

This is not an official guide, it's only a compilation of links extracted from the documentation based on the [Symfony Certification](http://sensiolabs.com/en/symfony/certification.html) page topics.

Even if you have no plans to take the Symfony certification exam, this list of resources may help you better understand the Symfony framework.

Feel free to fork and send a PR.

### **Topics**
---
#### **PHP**
* Object Oriented Programming  
http://www.php.net/manual/en/oop5.intro.php
* Namespaces  
http://www.php.net/manual/en/language.namespaces.php
https://knpuniversity.com/screencast/php-namespaces-in-120-seconds/namespaces
* Interfaces  
http://www.php.net/manual/en/language.oop5.interfaces.php
* Anonymous functions and closures  
http://www.php.net/manual/en/functions.anonymous.php
* Abstract classes  
http://www.php.net/manual/en/language.oop5.abstract.php

---

#### **HTTP**
* Client / Server interaction  
http://symfony.com/doc/current/book/http_fundamentals.html
* HTTP request  
http://symfony.com/doc/current/components/http_foundation/introduction.html#request
* HTTP response  
http://symfony.com/doc/current/components/http_foundation/introduction.html#response
* Status codes  
http://en.wikipedia.org/wiki/List_of_HTTP_status_codes

---

#### **Symfony2 Architecture**
* Standard edition of Symfony2  
http://symfony.com/distributions
* Components  
http://symfony.com/doc/current/components/index.html
* Bundles  
http://symfony.com/doc/current/cookbook/bundles/best_practices.html
http://symfony.com/doc/current/quick_tour/the_architecture.html#understanding-the-bundle-system
* Bridges  
http://stackoverflow.com/questions/11888522/what-are-symfony-bridges-bundles-and-vendor?answertab=votes#tab-top
*  Configuration  
http://symfony.com/doc/current/quick_tour/the_architecture.html#configuring-a-bundle  
http://symfony.com/doc/current/cookbook/configuration/index.html
http://symfony.com/doc/current/components/config/index.html
http://symfony.com/doc/current/cookbook/bundles/best_practices.html#configuration  
http://symfony.com/doc/current/cookbook/bundles/extension.html
Code organization  
http://symfony.com/doc/current/quick_tour/the_architecture.html#understanding-the-directory-structure
* Request handling  
http://symfony.com/doc/current/book/http_fundamentals.html#the-journey-from-the-request-to-the-response

---

#### **Standardisation**
* Naming conventions  
http://symfony.com/doc/current/contributing/code/standards.html#naming-conventions
* Coding standards  
http://symfony.com/doc/current/contributing/code/standards.html
* Integration of third-party libraries  
http://symfony.com/doc/current/cookbook/bundles/installation.html
* Composer packages handling  
http://symfony.com/doc/current/book/installation.html
https://knpuniversity.com/screencast/composer
* Development best practices  

* Overload the framework  

---

#### **The Bundles**
* Naming conventions  
http://symfony.com/doc/current/cookbook/bundles/best_practices.html#bundle-name
* Code organization  
http://symfony.com/doc/current/cookbook/bundles/best_practices.html#directory-structure
* The controllers  
http://symfony.com/doc/current/cookbook/bundles/best_practices.html#controllers
http://symfony.com/doc/current/cookbook/controller/index.html
http://symfony.com/doc/current/book/controller.html
* The views  
http://symfony.com/doc/current/quick_tour/the_view.html
* The resources  

---

#### **The controllers**
* Naming conventions  
http://symfony.com/doc/current/book/routing.html#controller-string-syntax
* Get the request  
http://symfony.com/doc/current/book/controller.html#requests-controller-response-lifecycle
* Generate the response  
http://symfony.com/doc/current/book/controller.html#requests-controller-response-lifecycle
* The cookies  
http://symfony.com/doc/current/book/controller.html#managing-the-session
* The session  
http://symfony.com/doc/current/book/controller.html#managing-the-session
* Session flashbag  
http://symfony.com/doc/current/book/controller.html#flash-messages
* Redirects  
http://symfony.com/doc/current/book/controller.html#redirecting
* Internal redirects  
http://symfony.com/doc/current/book/controller.html#forwarding
* Generate 404 pages  
http://symfony.com/doc/current/book/controller.html#managing-errors-and-404-pages
http://symfony.com/doc/current/cookbook/controller/error_pages.html#customizing-the-404-page-and-other-error-pages

---

#### **The Routing**
* Configuration (YAML / XML / PHP & annotations)  
http://symfony.com/doc/current/book/routing.html#basic-route-configuration
* Restrict URL parameters  
http://symfony.com/doc/current/book/routing.html#routing-with-placeholders
* Set default values to URL parameters  
http://symfony.com/doc/current/book/routing.html#required-and-optional-placeholders
* Generate URL parameters  
http://symfony.com/doc/current/book/routing.html#generating-urls
http://symfony.com/doc/current/book/routing.html#generating-urls-with-query-strings
* Trigger redirections  
http://symfony.com/doc/current/cmf/components/routing/dynamic.html#redirections

---

#### **Templating with Twig**
* Auto escape  
http://twig.sensiolabs.org/doc/tags/autoescape.html
* Template inheritance  
http://twig.sensiolabs.org/doc/tags/extends.html
* Global functions  
http://twig.sensiolabs.org/doc/functions/index.html
* Filters  
http://twig.sensiolabs.org/doc/filters/index.html
* Template includes  
http://twig.sensiolabs.org/doc/tags/include.html
* Control statements (loops and conditions)
http://twig.sensiolabs.org/doc/tags/for.html
* Urls generation  
http://symfony.com/doc/current/book/routing.html#generating-urls-from-a-template
* Call a controller from a view  
http://symfony.com/doc/current/book/templating.html#embedding-controllers
* Translations  
http://symfony.com/doc/current/book/translation.html#translations-in-templates

---

#### **Forms**
* Create forms  
http://symfony.com/doc/current/book/forms.html#creating-a-simple-form
* Handling forms  
http://symfony.com/doc/current/book/forms.html#handling-form-submissions
* Form types  
http://symfony.com/doc/current/book/forms.html#creating-form-classes
* Render forms with Twig  
http://symfony.com/doc/current/book/forms.html#rendering-a-form-in-a-template
* Forms security (CSRF)  
http://symfony.com/doc/current/book/forms.html#csrf-protection

---

#### **Validation**
* Validate a PHP object  
http://symfony.com/doc/current/book/validation.html#the-basics-of-validation
* Native validation rules  
* Validation scopes  
* Validation groups  
http://symfony.com/doc/current/book/validation.html#validation-groups

---

#### **Dependency Injection**
* The Service container  
http://symfony.com/doc/current/book/service_container.html
* Global configuration parameters
* Symfony2 services  
http://symfony.com/doc/current/book/service_container.html#what-is-a-service
* Register new services  
http://symfony.com/doc/current/book/service_container.html#creating-configuring-services-in-the-container
* Tags  
http://symfony.com/doc/current/book/service_container.html#tags
* Semantic configuration

---

#### **Security**
* Authentication  
http://symfony.com/doc/current/components/security/authentication.html
* Authorization  
http://symfony.com/doc/current/components/security/authorization.html
* Configuration  
* Providers  
* Firewalls  
* Users  
* Encoders  
* Roles  
http://symfony.com/doc/master/components/security/authorization.html#roles
* Access Control Rules  

---

#### **HTTP Cache**
* Cache types (browser, proxies and reverse proxies)  
* http://symfony.com/doc/current/book/http_cache.html#types-of-caches
* Expiration (Expires, Cache-control)  
http://symfony.com/doc/current/book/http_cache.html#expiration
* Validation (ETag, Last-Modified)  
* http://symfony.com/doc/current/book/http_cache.html#validation
* Client cache  
* Server cache  
* Edge Side Includes  
http://symfony.com/doc/current/book/http_cache.html#using-edge-side-includes

---

#### **The command line**
* Symfony2 commands  
http://symfony.com/doc/current/components/console/introduction.html#creating-a-basic-command
* Custom commands  
http://symfony.com/doc/current/cookbook/console/console_command.html
* Configuration  
* Options and arguments  
http://symfony.com/doc/current/components/console/introduction.html#using-command-options
http://symfony.com/doc/current/components/console/introduction.html#using-command-arguments
* Read the entry and write the output  

---

#### **Automated tests**
* Unit tests with PHPUnit  
http://symfony.com/doc/current/book/testing.html#the-phpunit-testing-framework
* Functional tests  
http://symfony.com/doc/current/book/testing.html#functional-tests
* The Client object  
http://symfony.com/doc/current/book/testing.html#working-with-the-test-client
* The Crawler object  
http://symfony.com/doc/current/book/testing.html#the-crawler
* The Profile object  
http://symfony.com/doc/current/book/testing.html#accessing-the-profiler-data
* Access framework objects  
http://symfony.com/doc/current/book/testing.html#accessing-the-container
* Configure the client  
* Introspect the request and response  
http://symfony.com/doc/current/book/testing.html#accessing-internal-objects

---

#### **Miscellaneous**
* Error handling  
http://symfony.com/doc/current/cookbook/controller/error_pages.html
* Debug the code  
http://symfony.com/doc/current/components/debug/introduction.html

### **Resources**
---
#### **Documentation**
* The Symfony Book  
http://symfony.com/doc/current/book/index.html
* The Symfony Cookbook  
http://symfony.com/doc/current/cookbook/index.html
* The Symfony Book Spanish  
http://librosweb.es/symfony_2_4/
* A Symfony Console tool to train on Symfony Certification  
https://github.com/certificationy/certificationy

---

#### **Books**
* Desarrollo web ágil con Symfony2  
http://symfony.es/libro/
* A year with Symfony  
https://leanpub.com/a-year-with-symfony  
* Un año con Symfony
https://leanpub.com/un-ano-con-symfony  
* Extending Symfony2 Web Application Framework  
http://www.packtpub.com/extending-symfony-2-web-application-framework/book

---

#### **Other**
* KNP University - PHP and Symfony Tutorial Screencasts  
http://knpuniversity.com/
* SymfonyBricks  
https://symfonybricks.com/
* Symfony2 cheat sheet  
http://www.symfony2cheatsheet.com/
* Symfony2 Tutorials  
http://www.screenfony.com/
* Symfony2 deployment checklist  
http://www.symfony2-checklist.com/
