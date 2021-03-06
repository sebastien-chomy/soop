# DEPENDENCIES TO EXTERNAL LIBRARIES
## List of components to be installed when creating the project skeleton

| LIBRARIES | USE |
| --------- | --- |
| symfony/cache | The Cache component provides an extended PSR-6 implementation as well as a PSR-16 "Simple Cache" implementation for adding cache to your applications. It is designed for performance and resiliency, and ships with ready to use adapters for the most common caching backends, including proxies for adapting from/to Doctrine Cache. [Documentation](https://symfony.com/doc/current/components/cache.html)  |
| symfony/config | The Config component provides several classes to help you find, load, combine, autofill and validate configuration values of any kind, whatever their source may be (YAML, XML, INI files, or for instance a database). [Documentation](https://symfony.com/doc/current/components/config.html) |
| symfony/console | The Console component eases the creation of beautiful and testable command line interfaces. [Documentation](https://symfony.com/doc/current/components/console.html) |
| symfony/debug | The Debug component provides tools to ease debugging PHP code. [Documentation](https://symfony.com/doc/current/components/debug.html)|
| symfony/dependency-injection |The DependencyInjection component implements a PSR-11 compatible service container that allows you to standardize and centralize the way objects are constructed in your application. [Documentation](https://symfony.com/doc/current/components/dependency_injection.html) |
| symfony/dotenv (dev) | The Dotenv Component parses .env files to make environment variables stored in them accessible via getenv(), $_ENV or $_SERVER. [Documentation](https://symfony.com/doc/current/components/dotenv.html) |
| symfony/event-dispatcher | The EventDispatcher component provides tools that allow your application components to communicate with each other by dispatching events and listening to them. [Documentation](https://symfony.com/doc/current/components/event_dispatcher.html) |
| symfony/filesystem | The Filesystem component provides basic utilities for the filesystem. [Documentation](https://symfony.com/doc/current/components/filesystem.html) |
| symfony/finder | The Finder component finds files and directories via an intuitive fluent interface. [Documentation](https://symfony.com/doc/current/components/finder.html) | 
| symfony/flex | The Finder component finds files and directories via an intuitive fluent interface. |
| **symfony/framework-bundle** | The FrameworkBundle defines the main framework configuration, from sessions and translations to forms, validation, routing and more. All these options are configured under the framework key in your application configuration. [Framework configuration reference](https://symfony.com/doc/current/reference/configuration/framework.html) |
| symfony/http-foundation | The HttpFoundation component defines an object-oriented layer for the HTTP specification. [Documentation](https://symfony.com/doc/current/components/http_foundation.html) |
| symfony/http-kernel | The HttpKernel component provides a structured process for converting a Request into a Response by making use of the EventDispatcher component. [Documentation](https://symfony.com/doc/current/components/http_kernel.html) |
| symfony/polyfill-mbstring | This component provides a partial, native PHP implementation for the mbstring PHP extension. [Documentation](https://symfony.com/doc/current/components/polyfill_intl_normalizer.html) |
| symfony/routing | The Routing component maps an HTTP request to a set of configuration variables. [Documentation](https://symfony.com/doc/current/components/routing.html) |
| symfony/yaml | The Yaml component loads and dumps YAML files. [Documentation](https://symfony.com/doc/current/components/yaml.html) |

## Require prod
| LIBRARIES | USE |
| --------- | --- |
| symfony/form | The Form component allows you to easily create, process and reuse forms. [Documentation](https://symfony.com/doc/current/components/form.html) |
| symfony/orm-pack | Symfony doesn't provide a component to work with the database, but it does provide tight integration with a third-party library called Doctrine. [Documentation](https://symfony.com/doc/current/doctrine.html) |
| symfony/security-bundle | The Security component provides a complete security system for your web application. [Documentation](https://symfony.com/doc/current/components/security.html) |
| symfony/swiftmailer-bundle | The SwiftmailerBundle integrates the Swiftmailer library in Symfony applications to send emails. All these options are configured under the swiftmailer key in your application configuration. [Documentation](https://symfony.com/doc/current/email.html) |
| symfony/translation |The Translation component provides tools to internationalize your application. [Documentation](https://symfony.com/doc/current/components/translation.html) |
| symfony/twig-bundle | twig |
| symfony/validator | The Validator component provides tools to validate values following the JSR-303 Bean Validation specification. [Documentation](https://symfony.com/doc/current/components/validator.html) |


## Require dev

| LIBRARIES | USE |
| --------- | --- |
| DoctrineFixturesBundle | Fixtures are used to load a "fake" set of data into a database that can then be used for testing or to help give you some interesting data while you're developing your application. [Documentation](https://symfony.com/doc/current/bundles/DoctrineFixturesBundle/index.html) |
| fzaninotto/faker | Faker is a PHP library that generates fake data for you. Whether you need to bootstrap your database, create good-looking XML documents, fill-in your persistence to stress test it, or anonymize data taken from a production service, Faker is for you.[Documentation](https://github.com/fzaninotto/Faker) |
| symfony/profiler-pack | The profiler is a powerful development tool that gives detailed information about the execution of any request. [Documentation](https://symfony.com/doc/current/profiler.html) |





