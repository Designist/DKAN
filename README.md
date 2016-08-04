# Rhode Island Transparency Portal
[DKAN](http://demo.getdkan.com/) is the Drupal-specific version of [CKAN](http://ckan.org/), an open source data portal and data management system. Build instructions with a [Vagrant virtual development environment](https://www.vagrantup.com/) can be found [here](https://github.com/Designist/DKAN_Vagrant). In 2017, this site is slated to replace [Rhode Island's transparency portal](http://www.transparency.ri.gov/), which stores municipal finance data, as well as various other state expenditures.

## Using this Repository
This repository is a *development build* of the final site and is *not* intended to be used as a production site. Follow the instructions in my [DKAN Vagrant repository](https://github.com/Designist/DKAN_Vagrant) and visit dkan-test.local.com to view the site. You can then add this repository as a remote and pull from it. Pulled modules will need to be enabled, either via the admin UI or with `drush en`.

## Curent Projects
Most of the current work on this website involves the upload interface, which is significantly more complicated than the upload interfaces of services like [Airtable](https://airtable.com/), [Screendoor](https://www.dobt.co/screendoor/), and [Typeform](https://www.typeform.com/). If we use one of these third-party services for data uploading, we'll need to use a webhook service like [Zapier](https://zapier.com/app/explore) to transfer data to the DKAN site.

We're also currently working on a redesign, based on some of the comments on [this issue](https://github.com/Designist/DKAN/issues/3). While the current site has a number of bugs, several of them seem to disappear on non-Vagrant build versions of DKAN, such as [this one](http://testmunicipalwnxxm9jfdc.devcloud.acquia-sites.com/) on Acquia Devcloud.

## Resources
* 
