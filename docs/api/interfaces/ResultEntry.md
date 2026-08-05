[**henkan**](../README.md)

***

[henkan](../README.md) / ResultEntry

# Interface: ResultEntry\<E\>

Defined in: [types.ts:652](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L652)

Basic Anki note information

## Extended by

- [`Kanji`](Kanji.md)
- [`Radical`](Radical.md)
- [`Word`](Word.md)
- [`Name`](Name.md)
- [`Kana`](Kana.md)
- [`Grammar`](Grammar.md)

## Type Parameters

### E

`E` *extends* [`EntryType`](../type-aliases/EntryType.md)

## Properties

### deckPath?

> `optional` **deckPath?**: `string`

Defined in: [types.ts:668](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L668)

The full path of the Anki deck

***

### doNotCreateNote?

> `optional` **doNotCreateNote?**: `true`

Defined in: [types.ts:676](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L676)

Whether or not this entry should be converted into an Anki note

***

### id?

> `optional` **id?**: `` `${number}` ``

Defined in: [types.ts:660](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L660)

ID used for the Anki note ID

***

### noteID?

> `optional` **noteID?**: `string`

Defined in: [types.ts:656](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L656)

ID used for the resulting Anki note

***

### noteTypeName?

> `optional` **noteTypeName?**: `string`

Defined in: [types.ts:664](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L664)

Anki note type name

***

### tags?

> `optional` **tags?**: `string`[]

Defined in: [types.ts:672](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L672)

Tags generated based on the entry's information
