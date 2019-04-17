# system-config
Create system config in magento 2

Installation process-

You can upload zip file on magento directory app\code and extract this zip folder

Module path like this app\code\Megha\System\...

Then run below commands-

php bin/magento setup:upgrade

php bin/magetno setup:static-content:deploy

php bin/magento cache:flush
