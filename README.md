# magento-1.9.3.4
magento-1.9.3.4

## Install magento 1.9.3.4 via ssh
mkdir ~/magento
cd ~/magento
git clone https://github.com/studio-webb/magento-1.9.3.4.git
mv mv ./magento-1.9.3.4/magento-1.9.3.4-2017-07-12-04-19-23.tar.gz .
tar -zxvf magento-1.9.3.4-2017-07-12-04-19-23.tar.gz
mv magento/* magento/.htaccess .
chmod -R o+w media var
chmod o+w app/etc
rm -rf magento-1.9.3.4 magento magento-1.9.3.4-2017-07-12-04-19-23.tar.gz
