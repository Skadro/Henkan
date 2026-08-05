[**henkan**](../README.md)

***

[henkan](../README.md) / Grammar

# Interface: Grammar

Defined in: [types.ts:1016](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L1016)

Grammar point information

## Extends

- [`ResultEntry`](ResultEntry.md)\<`"grammar"`\>

## Properties

### audio?

> `optional` **audio?**: `string`

Defined in: [types.ts:1048](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L1048)

The filename of an audio file for the grammar point

***

### deckPath?

> `optional` **deckPath?**: `string`

Defined in: [types.ts:668](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L668)

The full path of the Anki deck

#### Inherited from

[`ResultEntry`](ResultEntry.md).[`deckPath`](ResultEntry.md#deckpath)

***

### doNotCreateNote?

> `optional` **doNotCreateNote?**: `true`

Defined in: [types.ts:676](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L676)

Whether or not this entry should be converted into an Anki note

#### Inherited from

[`ResultEntry`](ResultEntry.md).[`doNotCreateNote`](ResultEntry.md#donotcreatenote)

***

### id?

> `optional` **id?**: `` `${number}` ``

Defined in: [types.ts:660](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L660)

ID used for the Anki note ID

#### Inherited from

[`ResultEntry`](ResultEntry.md).[`id`](ResultEntry.md#id)

***

### jlpt?

> `optional` **jlpt?**: `` `N${number}` ``

Defined in: [types.ts:1040](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L1040)

The [post-2010 JLPT](https://en.wikipedia.org/wiki/Japanese-Language_Proficiency_Test#Test_format) level

***

### meaning

> **meaning**: [`GrammarMeaning`](GrammarMeaning.md)

Defined in: [types.ts:1024](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L1024)

The English meaning/translation of the grammar point

***

### noteID?

> `optional` **noteID?**: `string`

Defined in: [types.ts:656](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L656)

ID used for the resulting Anki note

#### Inherited from

[`ResultEntry`](ResultEntry.md).[`noteID`](ResultEntry.md#noteid)

***

### noteTypeName?

> `optional` **noteTypeName?**: `string`

Defined in: [types.ts:664](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L664)

Anki note type name

#### Inherited from

[`ResultEntry`](ResultEntry.md).[`noteTypeName`](ResultEntry.md#notetypename)

***

### phrases?

> `optional` **phrases?**: [`Phrase`](Phrase.md)[]

Defined in: [types.ts:1036](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L1036)

Example phrase using the grammar point

***

### point

> `readonly` **point**: `string`

Defined in: [types.ts:1020](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L1020)

The most common form in which the grammar point written in

***

### readings?

> `optional` **readings?**: [`Reading`](Reading.md)[]

Defined in: [types.ts:1028](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L1028)

The readings of the grammar point

***

### source?

> `optional` **source?**: `string`

Defined in: [types.ts:1044](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L1044)

The source from which data for this grammar point has been extracted

***

### tags?

> `optional` **tags?**: `string`[]

Defined in: [types.ts:672](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L672)

Tags generated based on the entry's information

#### Inherited from

[`ResultEntry`](ResultEntry.md).[`tags`](ResultEntry.md#tags)

***

### usages?

> `optional` **usages?**: `string`[]

Defined in: [types.ts:1032](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L1032)

Ways in which the grammar point is used in Japanese
