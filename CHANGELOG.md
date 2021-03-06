# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

### [1.5.4](https://github.com/FriendsOfFlarum/extension-generator/compare/v1.5.3...v1.5.4) (2020-01-14)

### [1.5.3](https://github.com/FriendsOfFlarum/extension-generator/compare/v1.5.2...v1.5.3) (2019-08-09)


### Bug Fixes

* **boilerplate:** remove unneeded cache clear command ([3d25556](https://github.com/FriendsOfFlarum/extension-generator/commit/3d25556))

### [1.5.2](https://github.com/FriendsOfFlarum/extension-generator/compare/v1.5.1...v1.5.2) (2019-08-09)


### Bug Fixes

* **package:** update node requirement to >= 8 ([67a2ffa](https://github.com/FriendsOfFlarum/extension-generator/commit/67a2ffa))

### [1.5.1](https://github.com/FriendsOfFlarum/extension-generator/compare/v1.5.0...v1.5.1) (2019-08-09)


### Bug Fixes

* **package:** use [@friendsofflarum](https://github.com/friendsofflarum) instead of [@fof](https://github.com/fof), already taken ([9653a07](https://github.com/FriendsOfFlarum/extension-generator/commit/9653a07))

## [1.5.0](https://github.com/FriendsOfFlarum/extension-generator/compare/v1.4.3...v1.5.0) (2019-08-09)

Moved from ReFlar (`@reflar/create-flarum-extension`) to FriendsOfFlarum (`@fof/create-flarum-extension`).

### Bug Fixes

* **boilerplate:** remove unnecessary code + simplify composer.json ([57b708e](https://github.com/FriendsOfFlarum/extension-generator/commit/57b708e))

<a name="1.4.3"></a>
## [1.4.3](https://github.com/ReFlar/extension-generator/compare/v1.4.2...v1.4.3) (2019-02-05)


### Bug Fixes

* **boilerplate:** use current full year instead of hardcoded "2018" ([9f93cb9](https://github.com/ReFlar/extension-generator/commit/9f93cb9))



<a name="1.4.2"></a>
## [1.4.2](https://github.com/ReFlar/extension-generator/compare/v1.4.1...v1.4.2) (2019-01-01)


### Bug Fixes

* **boilerplate:** fix header comment author name not priting ([a22c528](https://github.com/ReFlar/extension-generator/commit/a22c528))
* **boilerplate:** fix incorrect header comment formatting ([2e6d638](https://github.com/ReFlar/extension-generator/commit/2e6d638))
* **dependencies:** update prompts + prettier ([7184ab1](https://github.com/ReFlar/extension-generator/commit/7184ab1))



<a name="1.4.1"></a>
## [1.4.1](https://github.com/ReFlar/extension-generator/compare/v1.4.0...v1.4.1) (2018-12-08)


### Bug Fixes

* **boilerplate:** fix incorrect flarum/core version requirement in composer.json ([34cc47c](https://github.com/ReFlar/extension-generator/commit/34cc47c))



<a name="1.4.0"></a>
# [1.4.0](https://github.com/ReFlar/extension-generator/compare/v1.3.0...v1.4.0) (2018-11-29)


### Features

* **generator:** update for beta 8 + switch to 'prompts' ([0551c85](https://github.com/ReFlar/extension-generator/commit/0551c85))



<a name="1.3.0"></a>
# [1.3.0](https://github.com/ReFlar/extension-generator/compare/v1.2.2...v1.3.0) (2018-07-12)


### Features

* **bin:** add `cfe` as an alias to `create-flarum-extension` ([8d28f5c](https://github.com/ReFlar/extension-generator/commit/8d28f5c)), closes [#6](https://github.com/ReFlar/extension-generator/issues/6)
* **generator:** add examples next to prompted questions ([a46970a](https://github.com/ReFlar/extension-generator/commit/a46970a)), closes [#5](https://github.com/ReFlar/extension-generator/issues/5)



<a name="1.2.2"></a>
## [1.2.2](https://github.com/ReFlar/extension-generator/compare/v1.2.1...v1.2.2) (2018-05-05)


### Bug Fixes

* **boilerplate:** assets listener doesn't register when necessary ([f4e7446](https://github.com/ReFlar/extension-generator/commit/f4e7446)), closes [#4](https://github.com/ReFlar/extension-generator/issues/4)
* **boilerplate:** assets not registering if forum or admin are skipped ([c66e351](https://github.com/ReFlar/extension-generator/commit/c66e351)), closes [#3](https://github.com/ReFlar/extension-generator/issues/3)



<a name="1.2.1"></a>
## [1.2.1](https://github.com/ReFlar/extension-generator/compare/v1.2.0...v1.2.1) (2018-04-25)


### Bug Fixes

* **boilerplate:** fix incorrect namespace of AddClientAssets ([3d47be2](https://github.com/ReFlar/extension-generator/commit/3d47be2))
* **boilerplate:** fix psr4 package namespace ([58bc5a1](https://github.com/ReFlar/extension-generator/commit/58bc5a1))
* **generator:** fix resources folder error ([28d20ea](https://github.com/ReFlar/extension-generator/commit/28d20ea))



<a name="1.2.0"></a>
# [1.2.0](https://github.com/ReFlar/extension-generator/compare/v1.1.1...v1.2.0) (2018-04-23)


### Features

* **boilerplate:** option to move less & locale to resources folder ([84115bf](https://github.com/ReFlar/extension-generator/commit/84115bf))


<a name="1.1.1"></a>
# [1.1.1](https://github.com/ReFlar/extension-generator/compare/v1.1.0...v1.1.1) (2018-04-22)

* Require node 6.4.0 instead of node 8
* Fix some conditionals and code that wasn't removed when disabling forum / admin
* Add some more validation rules

<a name="1.1.0"></a>
# 1.1.0 (2018-04-22)

* Add spinners
* Add some more validation rules
* Add more info to root README

<a name="1.0.1"></a>
# 1.0.1 (2018-04-21)

Initial release
