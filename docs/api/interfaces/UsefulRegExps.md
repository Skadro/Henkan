[**henkan**](../README.md)

***

[henkan](../README.md) / UsefulRegExps

# Interface: UsefulRegExps

Defined in: [types.ts:1120](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L1120)

Some useful regular expressions

## Properties

### hiragana

> `readonly` **hiragana**: `RegExp`

Defined in: [types.ts:1124](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L1124)

Matches any *hiragana* character(s)

***

### kanji

> `readonly` **kanji**: `RegExp`

Defined in: [types.ts:1132](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L1132)

Matches any *kanji* character(s)

***

### katakana

> `readonly` **katakana**: `RegExp`

Defined in: [types.ts:1128](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L1128)

Matches any *katakana* character(s)

***

### regExChars

> `readonly` **regExChars**: `RegExp`

Defined in: [types.ts:1136](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L1136)

Matches any character that is part of the regex syntax

***

### tanakaID

> `readonly` **tanakaID**: `RegExp`

Defined in: [types.ts:1140](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L1140)

Matches the `#ID=` part in a Tanaka Corpus `examples.utf` file

***

### tanakaPart

> `readonly` **tanakaPart**: `RegExp`

Defined in: [types.ts:1144](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L1144)

Matches and splits a part found in the `B` section of a Tanaka Corpus `examples.utf` file

***

### tanakaReferenceID

> `readonly` **tanakaReferenceID**: `RegExp`

Defined in: [types.ts:1148](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L1148)

Matches the reference ID element of a Tanaka example part
