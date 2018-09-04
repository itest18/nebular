Symfony certification guide
===========================

#### **PHP**
* Object Oriented Programming  
https://www.php.net/manual/en/oop5.intro.php
* Namespaces  
https://www.php.net/manual/en/language.namespaces.php  
https://knpuniversity.com/screencast/php-namespaces-in-120-seconds/namespaces  
* Interfaces  
https://www.php.net/manual/en/language.oop5.interfaces.php
* Anonymous functions and closures  
https://www.php.net/manual/en/functions.anonymous.php
* Abstract classes  
https://www.php.net/manual/en/language.oop5.abstract.php

---

#### **HTTP**
* Client / Server interaction / Request handling  
https://symfony.com/doc/2.8/book/http_fundamentals.html  
* Status codes  
https://en.wikipedia.org/wiki/List_of_HTTP_status_codes
* RFC 2616                                                                                                
https://www.ietf.org/rfc/rfc2616.txt

---

#### **Symfony2 Architecture**
* Standard edition of Symfony2  
https://symfony.com/distributions
* Components  
https://symfony.com/doc/2.8/components/index.html  
* Bundles  
https://symfony.com/doc/2.8/cookbook/bundles/best_practices.html  
https://symfony.com/doc/2.8/quick_tour/the_architecture.html  
* Bridges  
https://stackoverflow.com/questions/11888522/what-are-symfony-bridges-bundles-and-vendor?answertab=votes
*  Configuration  
https://symfony.com/doc/2.8/cookbook/configuration/index.html  
https://symfony.com/doc/2.8/components/config/index.html  
* New    
https://symfony.com/doc/2.8/components/event_dispatcher.html  
https://symfony.com/doc/2.8/reference/configuration/framework.html  
https://symfony.com/doc/2.8/cookbook/bundles/extension.html    
---

#### **Standardisation**
* Naming conventions / Coding standards   
https://symfony.com/doc/2.8/contributing/code/standards.html  
* Integration of third-party libraries  
https://symfony.com/doc/2.8/cookbook/bundles/installation.html  
* Composer packages handling  
https://symfony.com/doc/2.8/book/installation.html                                                  
https://knpuniversity.com/screencast/composer
* Development best practices                                                
https://symfony.com/doc/2.8/best_practices/index.html  
* Override the framework  
https://symfony.com/doc/2.8/cookbook/bundles/override.html  

---

#### **The Bundles**
* The controllers  
https://symfony.com/doc/2.8/cookbook/controller/index.html                              
* The views  
https://symfony.com/doc/2.8/quick_tour/the_view.html  
* New    
https://symfony.com/doc/2.3/bundles/SensioFrameworkExtraBundle/index.html  

---

#### **The controllers**
* Naming conventions  
* Get the request / Generate the response  
* The cookies / The session / Session flashbag  
* Redirects / Internal redirects  
* Generate 404 pages  
https://symfony.com/doc/2.8/book/routing.html  
https://symfony.com/doc/2.8/book/controller.html  
https://symfony.com/doc/2.8/components/http_foundation/introduction.html  
https://symfony.com/doc/2.8/components/http_foundation/sessions.html  
https://symfony.com/doc/2.8/cookbook/controller/error_pages.html  

---

#### **The Routing**
* Configuration (YAML / XML / PHP & annotations)  
* Restrict URL parameters  
* Set default values to URL parameters  
* Generate URL parameters  
https://symfony.com/doc/2.8/book/routing.html  
* Trigger redirections  
https://symfony.com/doc/master/cmf/components/routing/dynamic.html  
https://symfony.com/doc/2.8/cookbook/routing/redirect_in_config.html  

---

#### **Templating with Twig**
* Templating / Call a controller from a view  
https://symfony.com/doc/2.8/book/templating.html  
https://twig.sensiolabs.org/doc/templates.html  
* Auto escape  
https://twig.sensiolabs.org/doc/tags/autoescape.html  
* Template inheritance  
https://twig.sensiolabs.org/doc/tags/extends.html  
* Global functions  
https://twig.sensiolabs.org/doc/functions/index.html  
* Filters  
https://twig.sensiolabs.org/doc/filters/index.html  
* Template includes  
https://twig.sensiolabs.org/doc/tags/include.html  
* Control statements (loops and conditions)  
https://twig.sensiolabs.org/doc/tags/for.html  
* Translations  
https://symfony.com/doc/2.8/book/translation.html  
https://symfony.com/doc/2.8/reference/twig_reference.html

---

#### **Forms**
* Create forms / Handling forms / Form types / Render forms with Twig / Forms security (CSRF)  
https://symfony.com/doc/2.8/book/forms.html  
* New  
https://symfony.com/doc/2.8/form/events.html  
https://symfony.com/doc/2.8/form/dynamic_form_modification.html  
https://symfony.com/doc/2.3/cookbook/controller/upload_file.html#using-a-doctrine-listener
https://symfony.com/doc/2.8/form/data_transformers.html  
https://symfony.com/doc/2.8/form/csrf_protection.html  
https://symfony.com/doc/2.8/form/without_class.html  
---

#### **Validation**
* Validate a PHP object / Native validation rules / Validation scopes / Validation groups  
https://symfony.com/doc/2.8/book/validation.html  

---

#### **Dependency Injection**
* The Service container/ Symfony2 services / Register new services / Tags  
https://symfony.com/doc/2.8/book/service_container.html  
https://symfony.com/doc/2.8/reference/dic_tags.html  
* Global configuration parameters                                                
https://symfony.com/doc/2.8/components/dependency_injection/parameters.html  
https://symfony.com/doc/2.8/components/dependency_injection/introduction.html  
* Semantic configuration  
https://symfony.com/doc/2.8/cookbook/bundles/extension.html  
* New  
https://symfony.com/doc/2.8/service_container/definitions.html  
https://symfony.com/doc/2.8/service_container/tags.html
https://symfony.com/doc/2.8/service_container/lazy_services.html  
https://symfony.com/doc/2.8/components/dependency_injection/compilation.html
https://symfony.com/doc/2.8/service_container/autowiring.html  
https://symfony.com/doc/2.8/service_container/calls.html  
https://symfony.com/doc/2.8/service_container/compiler_passes.html  
https://symfony.com/doc/2.8/service_container/scopes.html  

---

#### **Security**
* Security / Providers / Firewalls / Users / Encoders / Roles / Access Control Rules  
https://symfony.com/doc/2.8/book/security.html
* Authentication  
https://symfony.com/doc/2.8/components/security/authentication.html  
* Authorization / Roles  
https://symfony.com/doc/2.8/components/security/authorization.html  
* Configuration  
https://symfony.com/doc/2.8/reference/configuration/security.html  
* Firewalls  
https://symfony.com/doc/2.8/components/security/firewall.html  
* New  
https://symfony.com/doc/2.8/security/voters.html  

---

#### **HTTP Cache**
* Cache types (browser, proxies and reverse proxies)  
* Expiration (Expires, Cache-control)  
* Validation (ETag, Last-Modified)  
* Client cache  
* Server cache  
* Edge Side Includes  
https://symfony.com/doc/2.8/book/http_cache.html  

---

#### **The command line**
* Symfony2 commands  
https://symfony.com/doc/2.8/components/console/usage.html  
* Custom commands / Configuration/ Options and arguments / Read the entry and write the output  
https://symfony.com/doc/2.8/components/console/introduction.html    
https://symfony.com/doc/2.8/cookbook/console/console_command.html  
https://symfony.com/doc/2.8/components/console/events.html  
https://symfony.com/doc/2.8/console/calling_commands.html  
https://symfony.com/doc/2.8/console/verbosity.html  
https://symfony.com/doc/2.8/components/console/helpers/questionhelper.html  
https://symfony.com/doc/2.8/console/coloring.html  

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
https://symfony.com/doc/2.8/book/testing.html  
https://symfony.com/doc/2.8/cookbook/testing/profiling.html  

---

#### **Miscellaneous**
* Error handling  
https://symfony.com/doc/2.8/cookbook/controller/error_pages.html  
* Debug the code  
https://symfony.com/doc/2.8/cookbook/debugging.html  

---

#### **Components**
* Debug  
https://symfony.com/doc/2.8/components/debug.html  
