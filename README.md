<div align="center">
<h2>Lighthouse GraphQL</h2>


[![Validate](https://github.com/nuwave/lighthouse/workflows/Validate/badge.svg)](https://github.com/nuwave/lighthouse/actions)
[![Code Coverage](https://codecov.io/gh/nuwave/lighthouse/branch/master/graph/badge.svg)](https://codecov.io/gh/nuwave/lighthouse)
[![PHPStan](https://img.shields.io/badge/PHPStan-enabled-brightgreen.svg?style=flat)](https://github.com/phpstan/phpstan)

[![Packagist](https://img.shields.io/packagist/dt/nuwave/lighthouse.svg)](https://packagist.org/packages/nuwave/lighthouse)
[![Latest Stable Version](https://poser.pugx.org/nuwave/lighthouse/v/stable)](https://packagist.org/packages/nuwave/lighthouse)
[![GitHub license](https://img.shields.io/github/license/nuwave/lighthouse.svg)](https://github.com/nuwave/lighthouse/blob/master/LICENSE)

[![Ask on Stack Overflow](https://img.shields.io/badge/StackOverflow-ask-orange.svg)](https://stackoverflow.com/questions/tagged/laravel-lighthouse)
[![Get on Slack](https://img.shields.io/badge/Slack-join-blueviolet.svg)](https://join.slack.com/t/lighthouse-php/shared_invite/zt-4sm280w1-wu21r94f3kLRRtBXRbXVfw)

**A framework for serving GraphQL from Laravel**

</div>

Lighthouse is a GraphQL framework that integrates with your Laravel application.
It takes the best ideas of both and combines them to solve common tasks with ease
and offer flexibility when you need it.

# Advantages: 
1. <b>Efficient Data Fetching:</b> Clients request only the exact data they need, preventing overfetching and optimizing performance.
2. <b> Flexible Schema Definition:</b> Create a descriptive schema that accurately reflects your data structure and evolves effortlessly as your API grows.
3. <b> Improved Developer Experience: </b> GraphQL's introspection abilities and powerful developer tools enable efficient client-side development.
4. <b> Strong Authentication and Authorization: </b> Leverage Laravel's robust security features to protect your API.

# Key Features:

1. Leverages existing Laravel models and migrations for familiarity and minimal boilerplate.
2. Offers automatic caching strategies and query optimization for enhanced performance.
3. Provides built-in directives for common tasks like authentication, authorization, and field resolution.
4. Extensible architecture allows for deep customization and advanced use cases.



# Getting Started:

1. Install <a href="https://laravel.com/"> Laravel </a> Project.
2. Install Lighthouse package using <a href="https://lighthouse-php.com/6/getting-started/installation.html">lighthouse-php.com.</a>
3. Install via composer 
``` composer require nuwave/lighthouse ```

4. Publish the default schema
``` php artisan vendor:publish --tag=lighthouse-schema ```

5. IDE Support
``` php artisan lighthouse:ide-helper ```

6. Install GraphQL DevTools
``` composer require mll-lab/laravel-graphiql ```

7. Run the project using below command
``` php artisan serve ```

8. Run this URL
``` http://127.0.0.1:8000/graphiql ```

Yeppiiii Your graphql IDE look like this.
[![Kj-JLYolp-Roy-RKLu-Sj-H7-Bkw.png](https://i.postimg.cc/28JJ3FWH/Kj-JLYolp-Roy-RKLu-Sj-H7-Bkw.png)](https://postimg.cc/WhGSHZXr)

<b> Here is the list of users display. </b>

[![W8-RRHyzm-SMu-Pm3-UGjy-LYJA.png](https://i.postimg.cc/L6ZDQdqT/W8-RRHyzm-SMu-Pm3-UGjy-LYJA.png)](https://postimg.cc/nCpqMPGj)

<b> Here you can get single user. </b>
[![Ie7-PVOcj-Sx-VQd-Yx21t-Ug.png](https://i.postimg.cc/xdxYxN7B/Ie7-PVOcj-Sx-VQd-Yx21t-Ug.png)](https://postimg.cc/CZqWd5w4)


Now, you have a powerful Basic GraphQL setup for your Laravel project!

# <a href="https://github.com/graphql"> Learn More </a>