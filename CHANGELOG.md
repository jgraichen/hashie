## Next Release

* Removed support for Ruby 1.8.7 - [@dblock](https://github.com/dblock).
* [#107](https://github.com/intridea/hashie/pull/107): Fixed excessive value conversions causing poor performance of deep merge in Hashie::Mash - [@davemitchell](https://github.com/dblock), [@dblock](https://github.com/dblock).
* [#69](https://github.com/intridea/hashie/issues/69): Fixed assigning multiple properties in Hashie::Trash - [@einzige](https://github.com/einzige).
* [#100](https://github.com/intridea/hashie/pull/100): IndifferentAccess#store will respect indifference - [@jrochkind](https://github.com/jrochkind).

## 2.0.5

* [#96](https://github.com/intridea/hashie/pull/96): Make coercion work better with non-symbol keys in Hashie::Mash - [@wapcaplet](https://github.com/wapcaplet).

## 2.0.4

* [#04](https://github.com/intridea/hashie/pull/94): Make #fetch method consistent with normal Hash - [@markiz](https://github.com/markiz).
* [#90](https://github.com/intridea/hashie/pull/90): Various doc tweaks - [@craiglittle](https://github.com/craiglittle).

## 2.0.3

* [#88](https://github.com/intridea/hashie/pull/88): Hashie::Mash.new(abc: true).respond_to?(:abc?) works - [@7even](https://github.com/7even).
* [#68](https://github.com/intridea/hashie/pull/68): Fix #replace - [@jimeh](https://github.com/jimeh).

## 2.0.2

* [#85](https://github.com/intridea/hashie/pull/85): adding symbolize_keys back to to_hash - [@cromulus](https://github.com/cromulus).

## 2.0.1

* [#81](https://github.com/intridea/hashie/pull/81): remove Mash#object_id override - [@matschaffer](https://github.com/matschaffer).
* Gem cleanup: removed VERSION, Gemfile.lock [@jch](https://github.com/jch), [@mbleigh](https://github.com/mbleigh).

## 2.0.0

* [#72](https://github.com/intridea/hashie/pull/72): Updated gemspec with license info - [@jordimassaguerpla](https://github.com/jordimassaguerpla).
* [#27](https://github.com/intridea/hashie/pull/27): Initialized with merge coerces values - [@mattfawcett](https://github.com/mattfawcett).
* [#28](https://github.com/intridea/hashie/pull/28): Hashie::Extensions::Coercion coerce_keys takes arguments - [@mattfawcett](https://github.com/mattfawcett).
* [#39](https://github.com/intridea/hashie/pull/39): Trash removes translated values on initialization - [@sleverbor](https://github.com/sleverbor).
* [#66](https://github.com/intridea/hashie/pull/66): Mash#fetch works with symbol or string keys - [@arthwood](https://github.com/arthwood).
* [#49](https://github.com/intridea/hashie/pull/49): Hashie::Hash inherits from ::Hash to avoid ambiguity - [@meh](https://github.com/meh), [@orend](https://github.com/orend).
* [#62](https://github.com/intridea/hashie/pull/62): update respond_to? method signature to match ruby core definition - [@dlupu](https://github.com/dlupu).
* [#41](https://github.com/intridea/hashie/pull/41): DeepMerge extension - [@nashby](https://github.com/nashby).
* [#63](https://github.com/intridea/hashie/pull/63): Dash defaults are dup'ed before assigned - [@ohrite](https://github.com/ohrite).
* [#77](https://github.com/intridea/hashie/pull/77): Remove id, type, and object_id as special allowable keys [@jch](https://github.com/jch).
* [#78](https://github.com/intridea/hashie/pull/78): Merge and update accepts a block - [@jch](https://github.com/jch).