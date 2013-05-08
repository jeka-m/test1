To use spring-social-vkontakte you need to get application key and and its secret code.

### Creating new application
First go to http://vk.com/editapp?act=create

There you need to select **Standalone Application**

![create app](https://raw.github.com/wiki/vkolodrevskiy/spring-social-vkontakte/images/createApp.png)

You will be asked for phone validation:

![create app](https://raw.github.com/wiki/vkolodrevskiy/spring-social-vkontakte/images/phoneVerif.png)

Your app settings should look something like:

![create app](https://raw.github.com/wiki/vkolodrevskiy/spring-social-vkontakte/images/testAppConf.png)

Here you need to copy **Application ID** and **Secure key**.

You also need to add toy your `/etc/hosts`

`127.0.0.1      example.com`

To view list of application managed by you go to http://vk.com/apps?act=settings