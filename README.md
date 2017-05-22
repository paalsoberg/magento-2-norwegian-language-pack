# magento-2-norwegian-language-pack
Norwegian Language Pack for Magento 2 based on https://crowdin.com/project/magento-2/no


**Install Norwegian pack**:

```
composer require paalsoberg/magento-2-norwegian-language-pack:dev-master
php bin/magento cache:clean
php bin/magento setup:static-content:deploy nb_NO
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush
```

**Update Norwegian pack**:

```
composer update paalsoberg/magento-2-norwegian-language-pack:dev-master
php bin/magento cache:clean
php bin/magento setup:static-content:deploy nb_NO
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush
```