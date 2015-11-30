Joomlatools Console - Example Plugin
====================================

This is an example plugin for use with the [Joomlatools Console](https://github.com/joomlatools/joomlatools-console).

The plugin adds a `site:backup` command which you can use to
quickly create a database dump and tar file of any installed Joomla site.

Installation
------------

1.  Run the following command

 `$ joomla plugin:install joomlatools/console-backup`

1. Verify that the plugin is available:

 `$ joomla plugin:list`

1. You can now create a backup of a site by running the following command:

  `$ joomla site:backup sitename`

   The tarball and mysql dump will be stored in your home folder. You can change this using the `--directory` flag.

1. For available options, run

   `$ joomla help site:backup`

Writing your own plugin
-----------------------

It's very easy to add custom commands to the tool. We recommended installing this plugin on your local setup and then starting off from there. You can find a step-by-step description in [our developer documentation](http://developer.joomlatools.com/tools/console/plugins.html#creating-custom-plugins).

## Requirements

* Composer
* [Joomlatools Console](https://github.com/joomlatools/joomlatools-console) >= 1.3

## Contributing

The `joomlatools/console-backup` plugin is an open source, community-driven project. Contributions are welcome from everyone. We have [contributing guidelines](CONTRIBUTING.md) to help you get started.

## Contributors

See the list of [contributors](https://github.com/joomlatools/joomlatools-console-backup/contributors).

## License 

This plugin is free and open-source software licensed under the [MPLv2 license](LICENSE.txt).

## Community

Keep track of development and community news.

* Follow [@joomlatoolsdev on Twitter](https://twitter.com/joomlatoolsdev)
* Join [joomlatools/dev on Gitter](http://gitter.im/joomlatools/dev)
* Read the [Joomlatools Developer Blog](http://developer.joomlatools.com/blog/)
* Subscribe to the [Joomlatools Developer Newsletter](http://developer.joomlatools.com/newsletter)
