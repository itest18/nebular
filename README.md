Symfony certification guide
===========================

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
* Client / Server interaction / Request handling  
http://symfony.com/doc/2.3/book/http_fundamentals.html  
* Status codes  
http://en.wikipedia.org/wiki/List_of_HTTP_status_codes
* RFC 2616                                                                                                
http://www.ietf.org/rfc/rfc2616.txt

---

#### **Symfony2 Architecture**
* Standard edition of Symfony2  
http://symfony.com/distributions
* Components  
http://symfony.com/doc/2.3/components/index.html  
* Bundles  
http://symfony.com/doc/2.3/cookbook/bundles/best_practices.html  
http://symfony.com/doc/2.3/quick_tour/the_architecture.html  
* Bridges  
http://stackoverflow.com/questions/11888522/what-are-symfony-bridges-bundles-and-vendor?answertab=votes
*  Configuration  
http://symfony.com/doc/2.3/cookbook/configuration/index.html  
http://symfony.com/doc/2.3/components/config/index.html  
http://symfony.com/doc/2.3/cookbook/bundles/extension.html    

---

#### **Standardisation**
* Naming conventions / Coding standards   
http://symfony.com/doc/2.3/contributing/code/standards.html  
* Integration of third-party libraries  
http://symfony.com/doc/2.3/cookbook/bundles/installation.html  
* Composer packages handling  
http://symfony.com/doc/2.3/book/installation.html                                                  
https://knpuniversity.com/screencast/composer
* Development best practices                                                
http://symfony.com/doc/2.3/best_practices/index.html  

* Override the framework  
http://symfony.com/doc/2.3/cookbook/bundles/override.html  

---

#### **The Bundles**
* The controllers  
http://symfony.com/doc/2.3/cookbook/controller/index.html                              
* The views  
http://symfony.com/doc/2.3/quick_tour/the_view.html  
* The resources  

---

#### **The controllers**
* Naming conventions  
* Get the request / Generate the response  
* The cookies / The session / Session flashbag  
* Redirects / Internal redirects  
* Generate 404 pages  
http://symfony.com/doc/2.3/book/routing.html  
http://symfony.com/doc/2.3/book/controller.html  
http://symfony.com/doc/2.3/components/http_foundation/introduction.html  
http://symfony.com/doc/2.3/components/http_foundation/sessions.html  
http://symfony.com/doc/2.3/cookbook/controller/error_pages.html  

---

#### **The Routing**
* Configuration (YAML / XML / PHP & annotations)  
* Restrict URL parameters  
* Set default values to URL parameters  
* Generate URL parameters  
http://symfony.com/doc/2.3/book/routing.html  
* Trigger redirections  
http://symfony.com/doc/master/cmf/components/routing/dynamic.html  
http://symfony.com/doc/2.3/cookbook/routing/redirect_in_config.html  

---

#### **Templating with Twig**
* Templating / Call a controller from a view  
http://symfony.com/doc/2.3/book/templating.html  
http://twig.sensiolabs.org/doc/templates.html  
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
* Translations  
http://symfony.com/doc/2.3/book/translation.html  
https://symfony.com/doc/2.8/reference/twig_reference.html

---

#### **Forms**
* Create forms / Handling forms / Form types / Render forms with Twig / Forms security (CSRF)  
http://symfony.com/doc/2.3/book/forms.html  

---

#### **Validation**
* Validate a PHP object / Native validation rules / Validation scopes / Validation groups  
http://symfony.com/doc/2.3/book/validation.html  

---

#### **Dependency Injection**
* The Service container/ Symfony2 services / Register new services / Tags  
http://symfony.com/doc/2.3/book/service_container.html  
http://symfony.com/doc/2.3/reference/dic_tags.html  
* Global configuration parameters                                                
http://symfony.com/doc/2.3/components/dependency_injection/parameters.html  
http://symfony.com/doc/2.3/components/dependency_injection/introduction.html  
* Semantic configuration  
http://symfony.com/doc/2.3/cookbook/bundles/extension.html  

---

#### **Security**
* Security / Providers / Firewalls / Users / Encoders / Roles / Access Control Rules  
http://symfony.com/doc/2.3/book/security.html
* Authentication  
http://symfony.com/doc/2.3/components/security/authentication.html  
* Authorization / Roles  
http://symfony.com/doc/2.3/components/security/authorization.html  
* Configuration  
http://symfony.com/doc/2.3/reference/configuration/security.html  
* Firewalls  
http://symfony.com/doc/2.3/components/security/firewall.html  

---

#### **HTTP Cache**
* Cache types (browser, proxies and reverse proxies)  
* Expiration (Expires, Cache-control)  
* Validation (ETag, Last-Modified)  
* Client cache  
* Server cache  
* Edge Side Includes  
http://symfony.com/doc/2.3/book/http_cache.html  

---

#### **The command line**
* Symfony2 commands  
http://symfony.com/doc/2.3/components/console/usage.html  
* Custom commands / Configuration/ Options and arguments / Read the entry and write the output  
http://symfony.com/doc/2.3/components/console/introduction.html    
http://symfony.com/doc/2.3/cookbook/console/console_command.html  
http://symfony.com/doc/2.8/components/console/events.html

---

#### **Automated tests**
* Unit tests with PHPUnit  
* Functional tests  
* The Client object  
* The Crawler object 
* The Profile object  
* Access framework objects  
* Configure the client  
* Introspect the request and response  
http://symfony.com/doc/2.3/book/testing.html  
http://symfony.com/doc/2.3/cookbook/testing/profiling.html  

---

#### **Miscellaneous**
* Error handling  
http://symfony.com/doc/2.3/cookbook/controller/error_pages.html  
* Debug the code  
http://symfony.com/doc/2.3/cookbook/debugging.html  
