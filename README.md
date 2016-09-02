## Magento 2 Module Skēlet.
a quick package with all files required to start building your custom module for Magento 2, from scratch.

###1 - Installation ModuleSkelet
##### Manual Installation
Install ModuleSkelet for Magento2
 * Download the extension
 * Unzip the file
 * Create a folder {Magento root}/app/code/Selekkt/ModuleSkelet
 * Copy the content from the unzip folder


#####Using Composer

```
composer config repositories.selekkt-module-skelet git git@github.com:selekkt/module-skelet.git
composer require selekkt/module-skelet
```

####2 -  Enable ModuleSkelet
 * php -f bin/magento module:enable --clear-static-content Selekkt_ModuleSkelet
 * php -f bin/magento setup:upgrade

####3 - Setup
To get started you need to replace/rename, if you want, all the names (you find inside files): 
	Selekkt_ModuleSkelet
	Selekkt
	ModuleSkelet
	moduleskelet
	skelet.phtml

and rename these folders:

Selekkt (vendor name)
ModuleSkelet (module name)

with the names you wish.

after that you can start writing your custom Magento 2 module.
