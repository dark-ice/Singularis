# Singularis
Install
=======

1. Go to Magento2 root folder

2. Enter following commands to install module:

    ```
    composer config repositories.singularis vcs git@github.com:dark-ice/Singularis.git
    ```

    ```
    composer require magecom/singularis:dev-master
    ```
   Wait while dependencies are updated.

3. Enter following commands to enable module:

    ```
    php bin/magento module:enable Magecom_Singularis
    ```

    ```
    php bin/magento setup:upgrade
    ```

4. Enable and configure Singuaris in Magento Admin under Singularis
