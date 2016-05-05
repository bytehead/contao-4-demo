Contao 4 demo
=======================

This is an example website for Contao Open Source CMS. Visit the [project website](https://contao.org) for more information.


What's inside?
--------------

The Contao standard edition is configured with the following defaults:

  * Twig as template engine;
  * Doctrine DBAL;
  * Swiftmailer;
  * Annotations enabled for everything.

It comes pre-configured with the following Symfony bundles:

  * **FrameworkBundle** - The core Symfony framework bundle
  * **SecurityBundle** - Integrates Symfony's security component
  * **TwigBundle** - Adds support for the Twig templating engine
  * **MonologBundle** - Adds support for Monolog, a logging library
  * **SwiftmailerBundle** - Adds support for Swiftmailer
  * **DoctrineBundle** - Adds support for the Doctrine ORM
  * **LexikMaintenanceBundle** - Allows to toggle maintenance mode
  * **SensioFrameworkExtraBundle** - Adds various annotation capabilities
  * **DebugBundle** (in dev/test env) - Adds the `dump()` function
  * **WebProfilerBundle** (in dev/test env) - Adds the web debug toolbar
  * **SensioDistributionBundle** (in dev/test env) - Adds functionality for
    configuring and working with Symfony distributions

It also comes pre-configured with the following Contao bundles:

  * **ContaoCoreBundle** - The Contao core bundle
  * **ContaoCalendarBundle** - The Contao calendar bundle
  * **ContaoCommentsBundle** - The Contao comments bundle
  * **ContaoFaqBundle** - The Contao FAQ bundle
  * **ContaoListingBundle** - The Contao listing bundle
  * **ContaoNewsBundle** - The Contao news bundle
  * **ContaoNewsletterBundle** - The Contao newsletter bundle
  * **ContaoInstallationBundle** - The Contao installation bundle

The Contao offical demo includes:

  * A usable Contao4 database dump
  * All files needed
  * All assets (scss/js) needed
  
How to use it:
--------------

1. Create project with composer: `composer create-project bytehead/contao-4-demo contao-4-demo`
2. Start the included webserver: `php app/console server:start`
3. Install contao: `http://127.0.0.1:8000/install.php`
4. Import the sql dump: `mysql -u user -p password contao4_database < dump.sql`
5. Go to the backend: `http://127.0.0.1:8000/contao`
6. Login with user `k.jones` and password `kevinjones`
7. See your Contao 4 demo at `http://127.0.0.1:8000`
  
Enjoy!
