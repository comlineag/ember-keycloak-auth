[![Build Status](https://travis-ci.org/JFTechnology/ember-keycloak-auth.svg)](https://travis-ci.org/JFTechnology/ember-keycloak-auth)
[![Ember Observer Score](http://emberobserver.com/badges/ember-keycloak-auth.svg)](http://emberobserver.com/addons/ember-keycloak-auth)
[![npm version](https://badge.fury.io/js/ember-keycloak-auth.svg)](https://badge.fury.io/js/ember-keycloak-auth)
[![Dependency Status](https://david-dm.org/JFTechnology/ember-keycloak-auth.svg)](https://david-dm.org/JFTechnology/ember-keycloak-auth)
[![devDependency Status](https://david-dm.org/JFTechnology/ember-keycloak-auth/dev-status.svg)](https://david-dm.org/JFTechnology/ember-keycloak-auth#info=devDependencies)

@jftechnology/ember-keycloak-auth
==============================================================================

This README outlines the details of collaborating on this Ember addon.

@jftechnology/ember-keycloak-auth is an addon that can be installed with Ember CLI. It is intended for EmberJS applications accessing 
REST services secured by the Keycloak authentication server from Redhat/JBoss (http://keycloak.jboss.org). 

See [addon docs](https://jftechnology.github.io/ember-keycloak-auth/versions/master) for full API details.


## Features overview

 * Presents the Keycloak JS adapter in a service that can be injected into an EmberJS app.
 * Provides a mixin that can be used with Ember Routes to check authentication on transition.
 * Provides a mixin that can be used with Ember data adapters to manage authentication headers whenever calls 
 are made to a Keycloak secured backend via the Ember data framework.
 * Small utility components for displaying user login state.

## Ember version
Versions 0.9+ of this library depend require the LTS version 3.8 of Ember or greater. Versions 0.9+ uses native classes 
and Stage 1 decorators and requires ember-decorators-polyfill for environments before Ember 3.10. 

If you are using a version of Ember older than 3.8, please use ember-keycloak-auth version 0.3.0 (no @jftechnology scope).

Compatibility
------------------------------------------------------------------------------

## @jftechnology/ember-keycloak-auth v0.9+
* Ember.js (LTS) v3.8 or above (requires ember-decorators-polyfill for Ember versions < 3.10)
* Ember CLI (LTS) v3.8 or above

## ember-keycloak-auth v0.3
* Ember.js v2.18 or above
* Ember CLI v2.18 or above

Installation
------------------------------------------------------------------------------

* `git clone <repository-url>` this repository
* `cd ember-keycloak-auth`
* `yarn install`

Run:

```
ember install @jftechnology/ember-keycloak-auth
```

Usage
------------------------------------------------------------------------------

See [addon docs](https://jftechnology.github.io/ember-keycloak-auth/versions/master) for usage and API details.

## Running

There is a trivial demo app that allows testing of the service and route mixin. Enter the details of your Keycloak server 
and then navigate around a selection of access protected and unprotected routes.

* `ember serve`
* Visit the dummy application at [http://localhost:4200](http://localhost:4200).

## Running Tests

* `yarn test` (Runs `ember try:each` to test your addon against multiple Ember versions)
* `ember test`
* `ember test --server`

## Building

* `ember build`

For more information on using ember-cli, visit [https://ember-cli.com/](https://ember-cli.com/).
For more information on Keycloak, visit [http://keycloak.jboss.com/](http://keycloak.jboss.com/).

Contributing
------------------------------------------------------------------------------

See the [Contributing](CONTRIBUTING.md) guide for details.


License
------------------------------------------------------------------------------

This project is licensed under the [MIT License](LICENSE.md).
