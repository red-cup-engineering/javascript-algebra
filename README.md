# javascript-algebra

<!-- 561-group-standards:badges:start -->
[![Red Cup Engineering](https://img.shields.io/badge/561%20Group-Red%20Cup%20Engineering-c0392b)](https://github.com/red-cup-engineering)
[![License: MIT](https://img.shields.io/badge/license-MIT-c0392b)](LICENSE)
[![Indigenous data: CARE](https://img.shields.io/badge/Indigenous%20data-CARE-4b6f44)](https://github.com/red-cup-engineering/.github/blob/main/GOVERNANCE.md)
[![Tips welcome](https://img.shields.io/badge/tips-welcome-d4a017)](https://github.com/561-group/.github/blob/main/TIPS.md)
<!-- 561-group-standards:badges:end -->

JavaScript type category — types as objects, functions as morphisms (a multicategory of types, domain is a tuple), and assignability as the carrier relation. Pure structure and operation; closures and section reads live in the javascript-topology package.

Use `jsFn` to describe a function by its ordered domain and optional codomain.
`composeAt(outer, slot, inner)` replaces the input at the zero-based integer
`slot` with the inner function's domain when its codomain matches that input
type by name. The composed function keeps the outer codomain.

Run `npm test` to exercise the public package export. The suite covers type
identity, slot composition, and direct assignability.
