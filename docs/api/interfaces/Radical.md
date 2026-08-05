[**henkan**](../README.md)

***

[henkan](../README.md) / Radical

# Interface: Radical

Defined in: [types.ts:842](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L842)

Kanji radical/component information

## Extends

- [`ResultEntry`](ResultEntry.md)\<`"radical"`\>

## Properties

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

### externalInfo?

> `optional` **externalInfo?**: `true`

Defined in: [types.ts:878](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L878)

Whether or not this radical/component object contains information extracted from [sources](#sources)

***

### id?

> `optional` **id?**: `` `${number}` ``

Defined in: [types.ts:660](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L660)

ID used for the Anki note ID

#### Inherited from

[`ResultEntry`](ResultEntry.md).[`id`](ResultEntry.md#id)

***

### kanji?

> `optional` **kanji?**: [`Kanji`](Kanji.md)[]

Defined in: [types.ts:870](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L870)

Kanji that include the radical/component

***

### meanings

> **meanings**: `string`[]

Defined in: [types.ts:854](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L854)

The radical/component meanings

***

### mnemonic?

> `optional` **mnemonic?**: `string`

Defined in: [types.ts:866](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L866)

The radical/component mnemonic

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

### radical

> `readonly` **radical**: `string`

Defined in: [types.ts:846](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L846)

The radical/component character

***

### reading

> **reading**: `string`

Defined in: [types.ts:850](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L850)

The radical/component reading (in kana)

***

### sources?

> `optional` **sources?**: `string`[]

Defined in: [types.ts:874](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L874)

The sources from which data for this radical/component has been extracted

***

### strokes?

> `optional` **strokes?**: `string`

Defined in: [types.ts:858](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L858)

The stroke count of the radical/component

***

### svg?

> `optional` **svg?**: `string`

Defined in: [types.ts:862](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L862)

The radical/component SVG filename

***

### tags?

> `optional` **tags?**: `string`[]

Defined in: [types.ts:672](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L672)

Tags generated based on the entry's information

#### Inherited from

[`ResultEntry`](ResultEntry.md).[`tags`](ResultEntry.md#tags)
