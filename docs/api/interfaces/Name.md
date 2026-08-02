[**henkan**](../README.md)

***

[henkan](../README.md) / Name

# Interface: Name

Defined in: [types.ts:950](https://github.com/Ronokof/Henkan/blob/main/src/types.ts#L950)

Name information

Converted from [DictName](DictName.md)

## Extends

- [`ResultEntry`](ResultEntry.md)\<`"name"`\>

## Properties

### common?

> `optional` **common?**: `true`

Defined in: [types.ts:974](https://github.com/Ronokof/Henkan/blob/main/src/types.ts#L974)

#### See

[DictName.isCommon](DictName.md#iscommon)

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

### kanji?

> `optional` **kanji?**: [`Kanji`](Kanji.md)[]

Defined in: [types.ts:966](https://github.com/Ronokof/Henkan/blob/main/src/types.ts#L966)

A list of kanji used in the kanji forms

***

### kanjiForms?

> `optional` **kanjiForms?**: [`KanjiForm`](KanjiForm.md)[]

Defined in: [types.ts:962](https://github.com/Ronokof/Henkan/blob/main/src/types.ts#L962)

The name kanji forms

***

### nameReadings

> **nameReadings**: [`Reading`](Reading.md)[]

Defined in: [types.ts:954](https://github.com/Ronokof/Henkan/blob/main/src/types.ts#L954)

The name readings (in kana)

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

### phrases?

> `optional` **phrases?**: [`Phrase`](Phrase.md)[]

Defined in: [types.ts:970](https://github.com/Ronokof/Henkan/blob/main/src/types.ts#L970)

Phrases associated to the name

***

### tags?

> `optional` **tags?**: `string`[]

Defined in: [types.ts:672](https://github.com/Ronokof/Henkan/blob/main/src/types.ts#L672)

Tags generated based on the entry's information

#### Inherited from

[`ResultEntry`](ResultEntry.md).[`tags`](ResultEntry.md#tags)

***

### translations

> **translations**: [`Translation`](Translation.md)[]

Defined in: [types.ts:958](https://github.com/Ronokof/Henkan/blob/main/src/types.ts#L958)

The name translations
