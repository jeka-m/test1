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

You also need to add to your `/etc/hosts` (`c:\Windows\System32\drivers\etc\hosts` on windows machine)

`127.0.0.1      something.com`

So when you will be testing your application on localhost do not forget to go to `http://something.com` instead of `http://localhost`

To view list of application managed by you go to http://vk.com/apps?act=settings