Mystic API
==========

*Mystic API* is a public API providing crafting-like
information as a complement to the official Guild
Wars 2 API.

REST & JSON-LD
==============

Mystic API offers a REST, JSON-based interface
(level 3 [RMM](https://martinfowler.com/articles/richardsonMaturityModel.html)).
It supports the [JSON-LD protocol](http://json-ld.org/).

Because of the JSON-LD support, the API is assured
to be forward-compatible regarding the terms used,
but the shape of the API itself may change.

Versioning, given the current state of discussion
about the topic, is left unhandled.

JSON-LD Shape
=============

If the JSON-LD interface is used, the whole API
can be defined just by giving the list of terms
and the semantic of their attributes.

MysticAPIRoot
-------------

Inheritance: [Thing](http://schema.org/Thing) > MysticAPIRoot

Properties:
- `recipes` ([URL](http://schema.org/URL)): a link to the extended recipes ([ExtendedRecipes](#extendedrecipes)).
- `resultitemids` ([URL](http://schema.org/URL)): a link to the list of result item ids ([ResultItemIds](#resultitemids))
- `recipeunlocks` ([URL](http://schema.org/URL)): a link tothe recipe unlocks ([ExtendedRecipesUnlocks](#extendedrecipesunlocks)).

<a name="extendedrecipes"></a>ExtendedRecipes
---------------------------------------------

<a name="resultitemids"></a>ResultItemIds
-----------------------------------------

<a name="extendedrecipesunlocks"></a>ExtendedRecipesUnlocks
-----------------------------------------------------------