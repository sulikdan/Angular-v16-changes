# Testing

The following file will contain informaiton about testing since version v16/v17

Whereas Karma is being depracted and replacements are:
* Modern Web - browser-like
* Jest - browseless

Will includes experience of other developers - reddit, stackoverflow, etc..

## Jest

Features(Pros-Cons):
* Fast(er)
* Browser-less

* Sorta mut like tool
* Not fully supporting ES Modules(Should be dealt by angular itself - experimental mode thingy)

## Web test runner (Modern Web)

Features(Pros-Cons):
* Browser based
* Runs in full DOM enviroment
* Parially using dom


I pulled information from multiple sources:
* https://dev.to/konnorrogers/why-jest-is-not-for-me-46c5 ( react app view on the jest - take look at comments)
 * Bashing ES support
 * Mut like behaviour
 * Speed
 * Mocking issues with Dom functions
* https://dev.to/this-is-angular/angular-testing-in-2023-past-present-and-future-j5m
 * Recapitulating history of testing for angular
  * Before v16 - one-sidely using Karma
  * During v16 - Karma depricated, Jest as possible replacement
  * After v16+ - New player in the field - Modern Web - Web test runner
 * Discussing performance and issues with JEST
 * Most important take out -> stay for now with jasmine(karma) -> later there should be seemless move to Web test runner(Modern web)
 * It also recommends to stay with Karma(Jasmine) as of now
 * Also mentioned(comments reply) that as of v17 there is not much of improvement as per Jest
* https://blog.angular.io/moving-angular-cli-to-jest-and-web-test-runner-ef85ef69ceca
  * Mentioned that there is plan to make migration from karma -> moder-web as seemless as possible with ng update
  

## Interesting feedback of migraiton
* https://www.reddit.com/r/angular/comments/17t085u/have_you_switched_away_from_karma_and_what_did/
