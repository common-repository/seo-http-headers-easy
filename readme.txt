=== "SEO-HEADERS-Easy" Protocol HTTP 1.1 ===
Contributors: Smiling_Hemp
Donate link: goo.gl/qnrM08
Tags: http, protocol, http1.1, headers, heading, cache-control, last-modified, seo, seo-http-headers-easy, Post, page
Requires at least: 3.5.1
Tested up to: 4.4
Stable tag: 2.0.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Sends to a client correct HTTP headers Last Modified, Cache Control and 304 Not Modified

== Description ==

= ENG =

The plugin allows sending headers Last Modified, Cache Control and 304 Not Modified - headers HTTP, which are sent according to "client-server-client" principle. Absence of determined headers can adversely affect indexing your website by a search system or even be banned for incorrect sending of headers. Such headers as Last Modified, Cache Control are just related to this category. The plug-in allows to flexibly control data settings for each of these pages: Home, Single, Page, Author, Category, Tag, Search. For details please reffer to [the page of this plugin](http://avkproject.ru/useful-articles/headers-in-wordpress.html) and its [full version page](http://avkproject.ru/plugins/seo-headers-full.html).

= RUS =

Плагин дает возможность отправлять заголовки Last-Modified, Сache-Сontrol и 304 Not Modified – заголовки HTTP протокола, посылаемые по принципу: «клиент – сервер – клиент».  Отсутствие определенных заголовков может негативно сказаться на индексации вашего сайта поисковой системой или вообще получить бан за не корректно отправленные заголовки. К этой категории как раз и относятся заголовки, такие как Last-Modified и Сache-Сontrol. Плагин позволяет гибко управлять настройками данных заголовков для каждой из этих страниц: Home, Single, Page, Author, Category, Tag, Search. Более подроно вы можете почитать на [странице плагина](http://avkproject.ru/useful-articles/headers-in-wordpress.html) и на странице его [полной версии](http://avkproject.ru/plugins/seo-headers-full.html).

> If you like the plugin, feel free to rate it (on the right side of this page) or [donate via PayPal](http://goo.gl/qnrM08). Thanks a lot!)

= Warning =

Please read the installation instructions and FAQ before installing this plugin.

Пожалуйста, перед установкой этого плагина, прочитайте инструкцию по установке и FAQ.

**[Upgrade to Full Version](http://avkproject.ru/plugins/seo-headers-full.html)**

== Installation ==

1. Upload `SEO-HTTP-Headers-Easy` folder to the `/wp-content/plugins/` directory.
2. Activate the plugin through the `Plugins` menu in WordPress.
3. Visit your HTTP-Headers options (Tools > HTTP 1.1 headers).
4. Configure options as desired, and then save options plugin.
5. That's all.

== Frequently Asked Questions ==
= ENG =

= How  I can check which headers are sent from my site? =
On the Settings page (Tools > HTTP 1.1 headers), you will find a link service whereby you can test your headlines.

= I installed the plugin, but the headlines were not, what's the problem? =
In most cases this happens because of the fact that the user has set all options and do not save a changes.

= RUS =

= Как я могу проверить какие заголовки отправляются с моего сайта? =
На странице настроек(Инструменты > Заголовки HTTP 1.1) вы найдете ссылку сервиса, с помощью которого вы сможете проверить свои заголовки.

= Я установил плагин, но заголовки не появились, в чем проблема? =
В большинстве случаев это происходит, из-за того что пользователь настроил все опции и не сохранил изменения.

== Screenshots ==

1. Settings page SEO-HTTP-Headers-Easy

== Changelog ==
= 2.0.0 =
* Header 304 Not Modified is added

= 1.1.0 =
* Last-Modified date tracking engine was reprogrammed to take into account date of the latest comment

= 1.0.1 =
* Deleting header Author-Plugin

= 1.0.0 =
* first version