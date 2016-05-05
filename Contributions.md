# Contributions

This document lists current and past contributions made to standards that has some relationship with the jQuery Foundation projects.

# W3C

## Pointer Events

- [Recommendation 24 February 2015](https://www.w3.org/TR/pointerevents/)
- [Editor's draft](https://w3c.github.io/pointerevents/)
- [Github](https://github.com/w3c/pointerevents)
- participants: [Scott Gonzalez]

## Touch Events

- [Recommendation 10 October 2013](https://www.w3.org/TR/touch-events/)
- [Editor's draft](https://w3c.github.io/touch-events/)
- [Github](https://github.com/w3c/touch-events)
- participants: [Scott Gonzalez]

## Other contributions

- [fixed the behavior](https://lists.w3.org/Archives/Public/public-whatwg-archive/2009Oct/0057.html) of `stepUp()` and `stepDown()` for `<input type="number">` based on the behavior of the spinner widget in __jQuery UI__. ([Scott Gonzalez]).
- [Should a captured pointer send transition events by default?](https://github.com/w3c/pointerevents/issues/61) ([Scott Gonzalez])

# ECMAScript / TC39

## Current proposals:

| Proposal | Champion | Stage |
|----------|----------|-------|
| [String padding](https://github.com/tc39/proposal-string-pad-start-end) | [Jordan Harband] | 3 |
| [Asynchronous Iterators](https://github.com/tc39/proposal-async-iteration) | [Kevin Smith] | 2 |
| [Observable](https://github.com/zenparsing/es-observable) | [Kevin Smith] & [Jafar Husain] | 1 |
| [Private Fields](https://github.com/zenparsing/es-private-fields) | [Kevin Smith] | 1 |
| [Class and Property Decorators](https://github.com/wycats/javascript-decorators/blob/master/README.md) | [Yehuda Katz] & Jonathan Turner | 1 |
| [`String.prototype.at`](https://github.com/mathiasbynens/String.prototype.at) | [Mathias Bynens] & [Rick Waldron] | 0 |
| [Function Bind Syntax](https://github.com/zenparsing/es-function-bind) | [Kevin Smith] | 0 |

## Landed features:

| Feature | Version | Champion |
|---------|---------|----------|
| `Array.from` & `Array.of` | [ES2015][Array.from] | [Dave Herman] & [Rick Waldron] |
| `Array#find` & `Array#findIndex` | [ES2015][Array#find] | [Rick Waldron] |
| `Object.assign` | [ES2015][Object.assign] | [Rick Waldron] |
| Exponentiantion Operator (`**`) | [ES2016][Exp Operator] | [Rick Waldron] |
| [`Object.values` & `Object.entries`][Object.entries-proposal] | [ES2016][Object.entries] | [Jordan Harband] |

[ES2015]: http://www.ecma-international.org/ecma-262/6.0/index.html
[Array.from]: http://www.ecma-international.org/ecma-262/6.0/index.html#sec-array.from
[Array.of]: http://www.ecma-international.org/ecma-262/6.0/index.html#sec-array.of
[Object.entries-proposal]: https://github.com/tc39/proposal-object-values-entries
[Exp Operator]: https://tc39.github.io/ecma262/2016/#sec-exp-operator
[Object.entries]: https://tc39.github.io/ecma262/#sec-object.entries
[Array#find]: http://www.ecma-international.org/ecma-262/6.0/index.html#sec-array.prototype.find
[Object.assign]: http://www.ecma-international.org/ecma-262/6.0/index.html#sec-object.assign

## Failed proposals:

| Feature | Champion |
|---------|----------|
| [`Math.TAU`](https://esdiscuss.org/topic/math-tau) | [Rick Waldron] |

## TC39 Meeting Notes

- https://github.com/rwaldron/tc39-notes
- The notes taken since [Rick Waldron] joined TC39 as a representative of the jQuery Foundation.

## Spec fixes

- [TypedArrays/ArrayBuffer/DataView constructor normalization/spec reform](https://github.com/tc39/ecma262/pull/410) ([Leo Balter])

## Test262

- TODO: list contributions
- participants from the jQuery Foundation: [Rick Waldron], [Leo Balter]

# [ECMAScript Internationalization API Specification (Ecma-402)](https://github.com/tc39/ecma402)

[Rick Waldron] was the editor for the Second Edition and is [still a contributor](http://tc39.github.io/ecma402/) on the current 4th edition.

## Current proposals

| Proposal | Champion | Stage |
|----------|----------|-------|
| [Intl.NumberFormat round option](https://github.com/rxaviers/ecma402-number-format-round-option) | [Rafael Xavier] | 0 |
| [Fix 9.2.3 LookupMatcher algorithm](https://github.com/rxaviers/ecma402-fix-lookup-matcher) | [Rafael Xavier] | 0 |

[Dave Herman]: https://github.com/dherman
[Jafar Husain]: https://github.com/jhusain
[Jordan Harband]: https://github.com/ljharb
[Kevin Smith]: https://github.com/zenparsing
[Leo Balter]: https://github.com/leobalter
[Mathias Bynens]: https://github.com/mathiasbynens
[Rafael Xavier]: https://github.com/rxaviers
[Rick Waldron]: https://github.com/rwaldron
[Scott Gonzalez]: https://github.com/scottgonzalez
[Yehuda Katz]: https://github.com/wycatz
