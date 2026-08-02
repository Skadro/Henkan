[**henkan**](../README.md)

***

[henkan](../README.md) / Kana

# Interface: Kana

Defined in: [types.ts:980](https://github.com/Ronokof/Henkan/blob/main/src/types.ts#L980)

Kana information

## Extends

- [`ResultEntry`](ResultEntry.md)\<`"kana"`\>

## Properties

### audio?

> `optional` **audio?**: `string`

Defined in: [types.ts:992](https://github.com/Ronokof/Henkan/blob/main/src/types.ts#L992)

The filename of an audio file for the kana reading

***

### deckPath?

> `optional` **deckPath?**: `string`

Defined in: [types.ts:668](https://github.com/Ronokof/Henkan/blob/main/src/types.ts#L668)

The full path of the Anki deck

#### Inherited from

[`ResultEntry`](ResultEntry.md).[`deckPath`](ResultEntry.md#deckpath)

***

### doNotCreateNote?

> `optional` **doNotCreateNote?**: `true`

Defined in: [types.ts:676](https://github.com/Ronokof/Henkan/blob/main/src/types.ts#L676)

Whether or not this entry should be converted into an Anki note

#### Inherited from

[`ResultEntry`](ResultEntry.md).[`doNotCreateNote`](ResultEntry.md#donotcreatenote)

***

### id?

> `optional` **id?**: `` `${number}` ``

Defined in: [types.ts:660](https://github.com/Ronokof/Henkan/blob/main/src/types.ts#L660)

ID used for the Anki note ID

#### Inherited from

[`ResultEntry`](ResultEntry.md).[`id`](ResultEntry.md#id)

***

### kana

> `readonly` **kana**: `string`

Defined in: [types.ts:984](https://github.com/Ronokof/Henkan/blob/main/src/types.ts#L984)

The kana character

***

### noteID?

> `optional` **noteID?**: `string`

Defined in: [types.ts:656](https://github.com/Ronokof/Henkan/blob/main/src/types.ts#L656)

ID used for the resulting Anki note

#### Inherited from

[`ResultEntry`](ResultEntry.md).[`noteID`](ResultEntry.md#noteid)

***

### noteTypeName?

> `optional` **noteTypeName?**: `string`

Defined in: [types.ts:664](https://github.com/Ronokof/Henkan/blob/main/src/types.ts#L664)

Anki note type name

#### Inherited from

[`ResultEntry`](ResultEntry.md).[`noteTypeName`](ResultEntry.md#notetypename)

***

### reading

> **reading**: `string`

Defined in: [types.ts:988](https://github.com/Ronokof/Henkan/blob/main/src/types.ts#L988)

The romaji reading of the kana

***

### svg?

> `optional` **svg?**: `string`

Defined in: [types.ts:996](https://github.com/Ronokof/Henkan/blob/main/src/types.ts#L996)

The kana SVG filename

***

### tags?

> `optional` **tags?**: `string`[]

Defined in: [types.ts:672](https://github.com/Ronokof/Henkan/blob/main/src/types.ts#L672)

Tags generated based on the entry's information

#### Inherited from

[`ResultEntry`](ResultEntry.md).[`tags`](ResultEntry.md#tags)
