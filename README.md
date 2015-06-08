# <a href="http://rosarior.github.io/awesome-django/"><img src="https://raw.githubusercontent.com/rosarior/awesome-django/gh-pages/images/logo-small.png" align="absmiddle"/> Awesome Django(了不起的Django)</a>

> 这是一个[awesome-python](https://github.com/vinta/awesome-python/) 项目的中文翻译，主要收集了一些 Django相关的资源，很多东西可以帮助我们快速的开发，很多东西的实现原理也可以带给我们一些启迪。

> 本项目地址[awesome-django](https://github.com/orangle/awesome-django), 由 [orangleiu](http://www.orangleliu.info/)业余翻译。
这个项目可以翻译成 **了不起的Django**。

- [Awesome Django](#awesome-django)
    - [Admin接口](#admin-interface)
    - [资源管理](#asset-management)
    - [认证](#authentication)
    - [授权](#authorization)
    - [缓存](#caching)
    - [兼容性](#compatibility)
    - [调试](#debugging)
    - [邮件](#email)
    - [字段](#fields)
    - [文件传输](#file-transfers)
    - [表单](#forms)
    - [迁移](#migrations)
    - [移动端支持](#mobile-support)
    - [模型拓展](#model-extensions)
    - [支付相关](#payment-processing)
    - [项目控制](#project-management)
    - [RESTful API](#restful-api)
    - [搜索](#search)
    - [安全](#security)
    - [SEO](#seo)
    - [Settings](#settings)
    - [存储](#storage)
    - [标签](#tagging)
    - [任务队列](#task-queue)
    - [测试](#testing)
    - [Thumbnail](#thumbnail)
    - [Cropping Images](#cropping-image)
    - [Translations](#translations)
    - [Web frontend integration](#web-frontend-integration)
    - [Wiki apps](#wiki-apps)
    - [WYSIWYG Editors](#wysiwyg-editors)
    - [Workflows](#workflows)
    - [Other](#other)
- [Projects](#projects)
    - [CMS](#cms)
    - [Document Management](#document-management)
    - [e-Commerce](#e-commerce)
    - [Project Management](#project-management)
    - [Other](#other)
- [Resources](#resources)
    - [Books](#books)
    - [Websites](#websites)
    - [Conferences](#conferences)
    - [Videos](#videos)
- [Contributing](#contributing)


## Admin接口

**Admin 接口的拓展，添加或者提升了一些特性**

* [django-flat-theme](https://github.com/elky/django-flat-theme) - 一个接地气的Django admin接口。 现代，新鲜，简单（可能老外那么觉得。。）
* [djamin](https://github.com/hersonls/djamin/) - 一种新风格的 Django admin
* [django-admin-bootstrap](https://github.com/douglasmiranda/django-admin-bootstrap/) - 给 Django Admin 换了个皮肤
* [django-admin-bootstrapped](https://github.com/django-admin-bootstrapped/django-admin-bootstrapped/) - 使用Twitter Bootstrap主题的Django admin
* [django-admin-tools](https://bitbucket.org/izi/django-admin-tools/) -  收集了一些 原生的那个 django admin 接口的扩展和工具
* [django-admin2](https://github.com/pydanny/django-admin2/) - 重写 django.contrib.admin，变得可拓展，适应性更好
* [django-grappelli](https://github.com/sehmaschine/django-grappelli/) - 这个界面比较花哨
* [django-fluent-dashboard](https://github.com/edoburu/django-fluent-dashboard/) - 增强了 django-admin-tools 仪表盘
* [django-hijack](https://github.com/arteria/django-hijack/) - 允许管理用户已其他用户的身份登录和操作（可以直接用你账号帮你操作操作)
* [django-suit](https://github.com/darklow/django-suit/) - 界面比较现代化.
* [django-xadmin](https://github.com/sshwsfc/django-xadmin/) - 这是咱们国产的项目，把原来的admin替换了，这个admin增加了很多好东西，插件机制，基于Bootstrap的Ui等。
* [yawd-admin](https://github.com/yawd/yawd-admin/) - 也是用Bootstrap，H5等重写了UI
* [django-wpadmin](https://github.com/barszczmm/django-wpadmin/) - 有WordPress的感觉
* [django-material](https://github.com/viewflow/django-material) 设计下Form，Admin. 模板驱动

## 资源管理

**打包和帮助管理项目的静态资源**

* [django-compressor](https://github.com/django-compressor/django-compressor/) - 压缩和内联javascript或CSS连接到一个单独的缓存文件
* [django-htmlmin](https://github.com/cobrateam/django-htmlmin/) - 压缩html到最小，也支持其他的web框架，flask什么的
* [django-gears](https://github.com/gears/django-gears/) - 编译连接 JavaScript and CSS
* [django-pipeline](https://github.com/cyberdelia/django-pipeline/) - 也是用来打包资源的

## 认证

**提高或者拓展 Django的认证方法的包**

* [django-allauth](https://github.com/pennersr/django-allauth/) - 集成了 Django应用的 认证，注册，账户管理以及第三方认证
* [django-organizations](https://github.com/bennylope/django-organizations) - 多用户的Django项目，类似小组，组织这种用户结构
* [django-otp](https://bitbucket.org/psagers/django-otp/) - 可插拔框架，使用一次性密码做到二重认证
* [django-rest-auth](https://github.com/Tivix/django-rest-auth) -  使用Restful Api 来处理用户注册和认证
* [python-social-auth](https://github.com/omab/python-social-auth/) - Python 社交认证 是一个简单好用的 社交认证、注册机制，支持好几种框架（django，flask，tornado等）
* [django-two-factor-auth](https://github.com/Bouke/django-two-factor-auth/) - 友好的二重认证
* [django-userena](https://github.com/bread-and-pepper/django-userena/) - 账户注册，激活，消息方面做的不错

## 授权

**授权和权限管理相关的包**

* [django-oauth-toolkit](https://github.com/evonove/django-oauth-toolkit) - OAuth2 工具箱
* [django-oauth2-provider](https://github.com/caffeinehit/django-oauth2-provider) - 给你的app提供OAuth2 授权
* [django-guardian](https://github.com/lukaszb/django-guardian/) - 实现了对每个对象的授权
* [django-oml](https://github.com/RouteAtlas/django-oml/) - Object Moderation Layer 的缩写，混合模型。（英文介绍没理解）
* [django-permission](https://github.com/lambdalisue/django-permission/) 基于逻辑授权的系统，可以处理复杂的权限模型

## 缓存

**可以帮助做缓存的包**

* [django-ormcache](https://github.com/educreations/django-ormcache/) - 一个可以管理 orm 对象缓存的缓存管理器
* [johnny-cache](https://github.com/jmoiron/johnny-cache/) - 主要是用memcached来做缓存
* [django-cacheops](https://github.com/Suor/django-cacheops) - A slick ORM cache with automatic granular event-driven invalidation.
* [django-cache-machine](https://github.com/jbalogh/django-cache-machine) - 自动缓存queryset结果，根据时间设定自动失效
* [django-cachalot](https://github.com/BertrandBordage/django-cachalot) -跟上面一个作用，缓存查询结果并自动失效
* [django-memoize](https://github.com/tvavrys/django-memoize) - 实现了 [memoization](http://en.wikipedia.org/wiki/Memoization) 技术


## 兼容性

**用来做兼容,可以让apps 在不同版本的django都可用**

* [django-compat](https://github.com/arteria/django-compat) - django1.4.x 到 1.7.x 向后兼容
* [django-compat-lint](https://github.com/ubernostrum/django-compat-lint) - 检查代码的兼容性


## 调试

**协助查找bug的包**

* [django-debug-toolbar](https://github.com/django-debug-toolbar/django-debug-toolbar/) - 通过可配置化的面板来展现每个请求和应答的debug信息
* [django-devserver](https://github.com/dcramer/django-devserver/) - 可以代替django自身的dev server的命令行工具
* [django-querycount](https://github.com/bradmontgomery/django-querycount/) - 可以查看django 查询数据库次数的中间件
* [django-silk](https://github.com/mtford90/silk/) - 分析django性能的工具

## Email

**邮件发送相关的包**

* [django-celery-email](https://github.com/pmclanahan/django-celery-email/) - 使用celery 的异步任务来发送邮件
* [django-drip](https://github.com/zapier/django-drip) - 通过django admin 来管理邮件情况，有邮件模板，还可以查询邮件记录
* [django-mailgun](https://github.com/BradWhittington/django-mailgun/) -  基于 Mailgun 的django邮件后端
* [django-post_office](https://github.com/ui/django-post_office/) - 一个简单的app，可以在django中发送和管理邮件，支持模板，也很容易集成到任务队列中
* [django-ses](https://github.com/hmarr/django-ses/) - Amazon's Simple Email Service 服务的django 后端实现
* [djrill](https://github.com/brack3t/Djrill/) - MailChimp 的Mandrill 事务性邮件的后端
* [django-templated-email](https://github.com/BradWhittington/django-templated-email) -
可以使用django templates 来发送邮件的模块，还可以集成 （mailchimp, silverpop, 等） 邮件服务提供商的服务
* [django-yubin](https://github.com/APSL/django-yubin) - django-mailer2 + django-mailviews 还有些拓展
* [django-spoolgore](https://github.com/20tab/django-spoolgore) -  基于Spoolgore daemon的后端


## 字段

* 拓展了现有字段的功能或者添加了新的字段类型 *

* [django-bitfield](https://github.com/disqus/django-bitfield/) -  添加了一个 BitField 类型
* [django-enumfield](https://github.com/5monkeys/django-enumfield/) -  用枚举命名常量来定义 django 字段
* [django-image-tools](https://github.com/bonsaistudio/django-image-tools/) - 用来处理图片的一个包
* [django-imagekit](https://github.com/matthewwithanm/django-imagekit/) - 自动处理Django中的图片
* [django-jsonfield](https://pypi.python.org/pypi/django-jsonfield) - django模型中的json类型字段
* [django-location-field](https://github.com/caioariede/django-location-field/) - 集成了 google maps的位置字段和外观
* [django-picklefield](https://github.com/gintas/django-picklefield/) - pickled 对象字段
* [django-uuidfield](https://github.com/dcramer/django-uuidfield/) - 添加了django uuid字段 UUIDField 
* [django-countries](https://github.com/SmileyChris/django-countries/) -  提供了国家表单中国家选择，国旗图标和CountryField 字段


## 文件传输

**可以帮助用户和项目之间传输文件的包**

* [django-downloadview](https://github.com/benoitbryon/django-downloadview/) - Django的文件服务
* [django-sendfile](https://github.com/johnsensible/django-sendfile/) - 封装了服务端往web客户端发送文件的方法，对于HTTPResponse 的封装

## 表单

**这些包拓展了表单的方法和类型**

* [django-bootstrap-form](https://github.com/tzangms/django-bootstrap-form/) -  基于Bootstrap的Form封装
* [django-bootstrap3](https://github.com/dyve/django-bootstrap3/) - 在你的django模板中使用Bootstrap，Django的方式
* [django-crispy-forms](https://github.com/maraujop/django-crispy-forms/) - The best way to have DRY Django forms. The app provides a tag and filter that lets you quickly render forms in a div format while providing an enormous amount of capability to configure and control the rendered HTML.
* [django-floppyforms](https://github.com/gregmuellegger/django-floppyforms/) - django-floppyforms is an application that gives you full control of the output of forms rendering. The forms API and features are exactly the same as Django’s, the key difference is that fields and widgets are rendered in templates instead of using string interpolation, giving you full control of the output using Django templates.

## RESTful API

** 用于开发RESTful API的包 **

* [django-nap](http://github.com/funkybob/django-nap/) - 用极简的方法来序列化对象， restful视图，RPC 视图
* [django-rest-framework](http://www.django-rest-framework.org/) -一个强大而灵活的工具，使得开发Web接口变的非常简单（推荐）
* [django-rest-swagger](https://github.com/marcgibbons/django-rest-swagger/) - Django REST Framework 的简单时髦的文档生成器 
* [django-tastypie](http://tastypieapi.org/) - 从2010年就可以在django中创建美味的APIs
* [restless](https://github.com/toastdriven/restless/) - 轻量级迷你python rest 框架

## 迁移

** 当数据库schema变更的时候，用来做数据迁移的包 **

* [South](https://bitbucket.org/andrewgodwin/south/src/) - 给Django应用提供了schema和数据迁移，支持到1.6.x 版本 ([Django1.7以上版本已经支持数据迁移，相当于south合并到django中了](https://docs.djangoproject.com/en/dev/topics/migrations/))

## 移动端支持

** iOS，Android 和其他移动端开发的支持 **

* [django-push-notifications](https://github.com/jleclanche/django-push-notifications) -
一个简单的Django app， 实现了设备模型，可以通过 APNS和GCM给客户端发送消息。

* [django-pushy](https://github.com/rakanalh/django-pushy) - Django app，它借助celery来提供消息通知的推送。这个app的主要目的就是帮助你发送推送提醒到用户，而且是有一定用户规模。 如果你有很多已经注册的设备keys， django－pushy将会吧keys分成很多小组，并行发送消息题想，使得发送速度更快。

## 模型拓展

** 拓展了models的功能或者是添加了新的模型 **

* [django-aggregate-if](https://github.com/henriquebastos/django-aggregate-if/) - Conditional aggregates for Django queries, just like the famous SumIf and CountIf in Excel.
* [django-localflavor](https://github.com/django/django-localflavor/) - Country-specific Django helpers, formerly of contrib fame.
* [django-model-utils](https://github.com/carljm/django-model-utils/) - Django model mixins and utilities.
* [django-mptt](https://github.com/django-mptt/django-mptt/) - Utilities for implementing a modified pre-order traversal tree in django.
* [django-treebeard](https://github.com/tabo/django-treebeard) -Alternative tree data structures for Django (provides 3 different methods for storing hierarchical data, including MPTT )

## Payment Processing

*Packages that provide payment processing provider integration.*

* [dj-stripe](https://github.com/pydanny/dj-stripe/) - Django + Stripe Made Easy.
* [django-merchant](https://github.com/agiliq/merchant/) - A Django app that provides helpers for multiple pluggable payment backends.
* [django-paypal](https://github.com/spookylukey/django-paypal) - A pluggable Django application for integrating PayPal Payments Standard or Payments Pro.
* [django-pinpayments](https://github.com/rossp/django-pinpayments/) - Django library to simplify payment processing with pin.
* [django-oscar-adyen](https://github.com/oscaro/django-oscar-adyen/) - This package provides integration with the Adyen payment gateway. It is designed to work seamlessly with the e-commerce framework django-oscar but can be used without Oscar.
* [django-oscar-paymentexpress](https://github.com/django-oscar/django-oscar-paymentexpress/) - This package provides integration with the payment gateway, PaymentExpress using their PX POST API. It is designed to work seamlessly with the e-commerce framework django-oscar but can be used without it.
* [django-oscar-paypal](https://github.com/django-oscar/django-oscar-paypal/) - PayPal integration for django-oscar. Can be used without Oscar too.
* [django-zebra](https://github.com/GoodCloud/django-zebra/) - Forms, widgets, template tags and examples that make Stripe + Django easier.

## Project Management

* [django-timepiece](https://github.com/caktus/django-timepiece/) - A multi-user Django application for tracking people's time on projects.

## Search

*Packages that provide search capabilities to projects.*

* [django-haystack](https://github.com/toastdriven/django-haystack/) - Modular search for Django.
* [django-watson](https://github.com/etianen/django-watson/) - Fast multi-model full-text search plugin.

## Security

*Packages that improve the security of a project.*

* [django-admin-honeypot](https://github.com/dmpayton/django-admin-honeypot/) - A fake Django admin login screen to notify admins of attempted unauthorized access.
* [django-axes](https://github.com/django-pci/django-axes/) - is a very simple way for you to keep track of failed login attempts, both for the Django admin and for the rest of your site.
* [django-debreach](https://github.com/lpomfrey/django-debreach/) - BREACH mitigation for Django apps.
* [django-password-session](https://github.com/atugushev/django-password-session/) - Invalidate all active sessions after change password ([not needed for Django 1.7+](https://docs.djangoproject.com/en/dev/topics/auth/default/#session-invalidation-on-password-change)).
* [django-secure](https://github.com/carljm/django-secure/) - Helping you remember to do the stupid little things to improve your Django site's security.
* [django-stronghold](https://github.com/mgrouchy/django-stronghold/) - Stronghold is middleware to default all your views to login required.
* [django-sslify](https://github.com/rdegges/django-sslify/) - Force SSL on your Django site.

## SEO

*Packages that help improve SEO ( Search Engine Optimization ) of projects.*

* [django-meta](https://github.com/nephila/django-meta/) - a pluggable app to allow Django developers to quickly add meta tags and OpenGraph, Twitter, and Google Plus properties to their HTML responses.
* [django-seo](https://github.com/willhardy/django-seo/) - Provides a set of tools for managing Search Engine Optimisation (SEO) for Django sites.
* [django-robots](https://github.com/jezdez/django-robots) - A Django app for managing robots.txt files following the robots exclusion protocol.

## Settings

*Packages that help manage the configurability of projects.*

* [django-configurations](https://github.com/jezdez/django-configurations/) - A helper for organizing Django project settings by relying on well established programming patterns.
* [django-constance](https://github.com/jezdez/django-constance/) - A Django app for storing dynamic settings in pluggable backends (Redis and Django model backend built in) with an integration with the Django admin app.
* [python-decouple](https://github.com/henriquebastos/python-decouple/) - Strict separation of config from code.

## Storage

*Packages that extend the functionality of the existing storage backend or provide new storage backends.*

* [django-storages](https://bitbucket.org/david/django-storages/src/) - django-storages is a collection of custom storage backends for Django.
* [django-queued-storage](https://github.com/jezdez/django-queued-storage/) - Provides a proxy for Django storage backends that allows you to upload files locally and eventually serve them remotely.

## Tagging

* [django-taggit](https://github.com/alex/django-taggit/) - Simple tagging for Django.

## Task Queue

*Packages that make working with task/background queues easier.*

* [django-celery](http://celery.github.io/django-celery/) - Celery Integration for Django. (no longer required for Celery 3.1 and up)
* [django-rq](https://github.com/ui/django-rq) - The easiest way to monitor and use [RQ](http://python-rq.org) in your Django projects.
* [huey](https://github.com/coleifer/huey/) - A little multi-threaded task queue for python.

## Testing

*Packages that help test code or generate test data.*

* [django-behave](https://github.com/django-behave/django-behave/) - TestRunner for the Behave BDD module.
* [django-faker](https://github.com/joke2k/django-faker/) - Fake-factory to generate test data.
* [django-dynamic-fixture](https://github.com/paulocheque/django-dynamic-fixture) - A complete library to create dynamic model instances for testing purposes.
* [django-jenkins](https://github.com/kmmbvnr/django-jenkins) - Plug and play continuous integration with django and jenkins.
* [django-nose](https://github.com/django-nose/django-nose/) - Test runner using nose.
* [django-selenium](https://github.com/dragoon/django-selenium/) - Selenium testing support.
* [django-slowtests](https://github.com/realpython/django-discover-slowest-tests-runner/) - Locate your slowest tests.
* [factory_boy](https://github.com/rbarrois/factory_boy/) - A test fixtures replacement for Python
* [lettuce-django-terrain](https://github.com/stringfellow/lettuce-django-terrain/) - Terrain file for lettuce in django projects
* [model-mommy](https://github.com/vandersonmota/model_mommy/) - Smart fixtures for better tests.
* [pytest-django](https://pypi.python.org/pypi/pytest-django/) - Test runner using py.test
* [splinter](https://github.com/cobrateam/splinter/) - Test framework for web applications.

## Thumbnail

*Packages that help generate thumbnails.*

* [sorl-thumbnail](https://github.com/mariocesar/sorl-thumbnail/) - Thumbnails for Django.
* [django-stdimage](https://github.com/codingjoe/django-stdimage/) - Thumbnails and image utils for Django.
* [easy-thumbnails](https://github.com/SmileyChris/easy-thumbnails) - Easy thumbnails for Django.

## Cropping Image

*Packages that help to crop Images.*

* [django-image-cropping](https://github.com/jonasundderwolf/django-image-cropping) - Cropping Image for Django.

## Translations

*Packages help with the task of translating projects.*

* [django-klingon](https://github.com/RouteAtlas/django-klingon/) - An attempt to make django model translations suckless and with no integrations pain in your app.
* [django-modeltranslation](https://github.com/deschler/django-modeltranslation/) - Translate dynamic content of existing Django models to an arbitrary number of languages without having to change the original model classes.
* [django-rosetta](https://github.com/mbi/django-rosetta/) - Rosetta is a Django application that eases the translation process of your Django projects.
* [django-parler](https://github.com/edoburu/django-parler) - Simple Django model translations without nasty hacks
* [django-hvad](https://github.com/KristianOellegaard/django-hvad) - Painless translations in django, using the regular ORM. Integrates easily into existing projects and apps. Easy convertible from django-multilingual-ng.

## Web frontend integration

* [django-angular](https://github.com/jrief/django-angular/) - Let AngularJS play well with Django.
* [djangular](https://github.com/appliedsec/djangular/) - A reusable Django app that provides better integration and tools for Angular.js.
* [django-js-reverse](https://github.com/ierror/django-js-reverse) - Javascript url handling for Django that doesn't hurt.

## WYSIWYG Editors

*Packages that makes text editing awesome.*

* [django-ckeditor](https://github.com/django-ckeditor/django-ckeditor/) - Django admin CKEditor integration.
* [django-summernote](https://github.com/summernote/django-summernote/) - Summernote is a simple WYSIWYG editor. django-summernote allows you to embed Summernote into Django very handy. Support admin mixins and widgets.
* [django-tinymce](https://github.com/aljosa/django-tinymce/) - TinyMCE integration for Django.
* [django-wysiwyg](https://github.com/pydanny/django-wysiwyg/) - A Django application for making Django textareas rich text editors. Certainly as a template tag and possibly as a form widget.
* [django-wysiwyg-redactor](https://github.com/douglasmiranda/django-wysiwyg-redactor/) - A lightweight wysiwyg editor for Django.

## Wiki apps

* [django-wiki](https://github.com/django-wiki/django-wiki) A wiki system with complex functionality for simple integration and a superb interface. Store your knowledge with style: Use django models.
* [waliki](https://github.com/mgaitan/waliki) An extensible wiki app for Django with a Git backend.

## Workflows

*Packages that do process, procedure and/or business tasks management.*

* [django-flows](https://github.com/carlio/django-flows/) - django-flows keeps state and position in complicated flows of logic, allowing optional branches and complicated paths through a series of individual user actions.
* [django-fsm](https://github.com/kmmbvnr/django-fsm/) - Django friendly finite state machine support.
* [django-states](https://github.com/vikingco/django-states2/) - State machine for django models.
* [django-viewflow](https://github.com/kmmbvnr/django-viewflow/) - Reusable workflow library for Django.
* [django-workflows](https://bitbucket.org/jerzyk/django-workflows/) - django-workflows provides a generic workflow engine for Django.
* [django-xworkflows](https://github.com/rbarrois/django_xworkflows/) - Library to plug xworkflows into django models.

## Other

* [cookiecutter](https://github.com/audreyr/cookiecutter/) - A command-line utility that creates projects from cookiecutters (project templates).
* [dj-database-url](https://github.com/kennethreitz/dj-database-url/) - Utilize the 12factor inspired DATABASE_URL environment variable to configure your Django application.
* [django-activeurl](https://github.com/hellysmile/django-activeurl) - Easy to use active URL highlighting for django
* [django-activity-stream](https://github.com/justquick/django-activity-stream/) - Generate generic activity streams from the actions on your site. Users can follow any actors' activities for personalized streams.
* [django-adminactions](https://github.com/saxix/django-adminactions/) - Collection of useful actions to use with django.contrib.admin.ModelAdmin and/or django.contrib.admin.AdminSite
* [django-autoadmin](https://github.com/rosarior/django-autoadmin/) - Automatic admin users for Django projects.
* [django-braces](https://github.com/brack3t/django-braces/) - Reusable, generic mixins for Django.
* [django-changuito](https://github.com/angvp/django-changuito/) - A cart app for your django site, an updated fork of django-cart
* [django-extensions](https://github.com/django-extensions/django-extensions/) - This is a repository for collecting global custom management extensions for the Django Framework.
* [django-filter](https://github.com/alex/django-filter/) - A generic system for filtering Django QuerySets based on user selections.
* [django-friendship](https://github.com/revsys/django-friendship/) - Django app to manage following and bi-directional friendships.
* [django-gravatar2](https://github.com/twaddington/django-gravatar/) - Essential Gravatar support for Django. Features helper methods, templatetags and a full test suite!
* [django-magic-embed](https://github.com/fitoria/django-magicembed/) - an easy and simple Django template tag and tool to embed video and get thumbnails from video providers.
* [django-markitup](https://bitbucket.org/carljm/django-markitup/src/) - A Django reusable application for end-to-end markup handling.
* [django-pagination](https://github.com/ericflo/django-pagination) - https://github.com/ericflo/django-pagination.
* [django-quiz-app](https://github.com/tomwalker/django_quiz/) - This is a configurable quiz app for Django.
* [django-recaptcha](https://github.com/praekelt/django-recaptcha/) - Django reCAPTCHA form field/widget integration app.
* [django-smuggler](https://github.com/semente/django-smuggler/) - Django Smuggler is a pluggable application for Django Web Framework that helps you to import/export fixtures via the automatically-generated administration interface.
* [django-solo](https://github.com/lazybird/django-solo/) - Helps working with singletons - things like global settings that you want to edit from the admin site.
* [django-sql-explorer](https://github.com/epantry/django-sql-explorer/) - Easily share data via SQL queries, right from Django
* [django-ratelimit](https://github.com/jsocol/django-ratelimit/) - provides a decorator to rate-limit views. Limiting can be based on IP address or a field in the request--either a GET or POST variable.
* [django-uuslug](https://github.com/un33k/django-uuslug/) - a slugify application that guarantees Uniqueness and handles Unicode.
* [django-watchman](https://github.com/mwarkentin/django-watchman/) - django-watchman exposes a status endpoint for your backing services like databases, caches, etc.
* [metamon](http://tryolabs.github.io/metamon/) - Collection of Ansible playbooks to quickly start your Django Application
* [micawber](https://github.com/coleifer/micawber/) - A small library for extracting rich content from urls.

# Projects

*Outstanding Django projects.*

## CMS

* [django-cms](https://github.com/divio/django-cms/) - The easy-to-use and developer-friendly CMS.
* [mezzanine](https://github.com/stephenmcd/mezzanine/) - A content management platform built using the Django framework.
* [wagtail](https://github.com/torchbox/wagtail/) - A new Django content management system.
* [django-fiber](https://github.com/ridethepony/django-fiber) - Django Fiber, a simple, user-friendly CMS for all your Django projects

## Document Management

* [mayan-edms](https://github.com/mayan-edms/mayan-edms/) - Open source, Django based DMS (document management system) with custom metadata indexing, file serving integration, OCR capabilities, document versioning and electronic signature verification.

## e-Commerce

* [Satchmo](https://bitbucket.org/chris1610/satchmo/src/) - Satchmo is an eCommerce framework created in Django which allows you to develop unique and robust online stores.
* [django-oscar](https://github.com/tangentlabs/django-oscar/) - Domain-driven e-commerce for Django.

## Other

* [Django packages](https://github.com/pydanny/djangopackages/) - Django Packages is a directory of reusable apps, sites, tools, and more for your Django projects.

## Project Management

* [ITSY](https://github.com/orges/itsy/) - Issue Tracking System
* [taiga](https://github.com/taigaio/taiga-back) - Agile, Free and Open Source Project Management Tool

# Resources

Where to discover new Django apps and projects.

## Books

* [Django by Example](http://www.lightbird.net/dbe/) (1.2)
* [Django by Example for Django 1.5](http://lightbird.net/dbe2/) (1.5)
* [Djen of Django](http://agiliq.com/books/djenofdjango/)
* [Effective Django](http://effectivedjango.com/) (1.5)
* [Getting started with Django](http://gettingstartedwithdjango.com/) (video)
* [Tango With Django](http://www.tangowithdjango.com/) (1.5)
* [Test-Driven Web Development with Python](http://chimera.labs.oreilly.com/books/1234000000754/index.html) (1.7)
* [The Django book](http://www.djangobook.com/en/2.0/)
* [Two Scoops of Django: Best Practices for Django 1.6](http://twoscoopspress.org/products/two-scoops-of-django-1-6/) - Making Python and Django as fun as ice cream.

## Websites

* [Django Packages](https://www.djangopackages.com/) - Django Packages is a directory of reusable apps, sites, tools, and more for your Django projects.
* [Django Sites](https://www.djangosites.org) - Django Sites is a showcase of websites powered by Django.
* [Full Stack Python's Django page](http://www.fullstackpython.com/django.html) - contains explanations for Django's philosophy and its components along with links to other resources and tutorials.
* [Django Introduction](http://www.django-introduction.com/) - A reusable set of slides to educate more people about Django.
* [Django Girls Tutorial](http://tutorial.djangogirls.org/) - A fun and engaging tutorial showing how to build a blog using Django and deploy it to Heroku.

## Conferences

* [Django Beer](http://www.djangobeer.com/) -  Florence 地区的django社区的聚会
* [Django Village](http://djangovillage.it/) - the Italian Django community conference. An opportunity to meet djangonauts from all over Italy and abroad.
* [Django Weekend](http://djangoweekend.org/) - is a Django/Python non-profit community event, organised and run entirely by volunteers. The conference is Django-focused, but all aspects of Python fall within its remit.
* [Django: Under The Hood](http://www.djangounderthehood.com/) - is an exciting new Django conference for experienced Django developers. Come and learn about the internals of Django, and help to shape its future.
* [DjangoCon Europe](http://www.djangocon.eu/) - is the annual largest European-based Django conference that is usually held in late spring.
* [DjangoCon US](http://www.djangocon.us/) - is the largest North American Django conference generally held the first week in September each year.

## Videos

* [Must Watch Django Videos](https://github.com/rosarior/django-must-watch/) - django 必看视频收集

# 贡献

fork 过来 然后发送一个 PR 到这个项目就行了。

