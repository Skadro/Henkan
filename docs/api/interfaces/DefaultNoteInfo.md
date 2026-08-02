[**henkan**](../README.md)

***

[henkan](../README.md) / DefaultNoteInfo

# Interface: DefaultNoteInfo

Defined in: [types.ts:1068](https://github.com/Ronokof/Henkan/blob/main/src/types.ts#L1068)

Default note ID, note type and deck name of a note

Setting any of the properties to:

- a `string` will make that string the default note ID/note type/deck name of the note in case [Result.noteID](Kana.md#noteid)/[Result.noteTypeName](Kana.md#notetypename)/[Result.deckPath](Kana.md#deckpath) is `undefined`.

- `true` will require all [Result](../type-aliases/Result.md) objects to have [Result.noteID](Kana.md#noteid)/[Result.noteTypeName](Kana.md#notetypename)/[Result.deckPath](Kana.md#deckpath) set (*no default values*).

- `undefined` (*or not set*) will require all [Result](../type-aliases/Result.md) objects to either have [Result.noteID](Kana.md#noteid)/[Result.noteTypeName](Kana.md#notetypename)/[Result.deckPath](Kana.md#deckpath) set or not set (*no default values*).

## Properties

### deckPath?

> `optional` **deckPath?**: `string` \| `true`

Defined in: [types.ts:1082](https://github.com/Ronokof/Henkan/blob/main/src/types.ts#L1082)

A default for [Result.deckPath](Kana.md#deckpath)

***

### guid?

> `optional` **guid?**: `true` \| `"main_information"`

Defined in: [types.ts:1074](https://github.com/Ronokof/Henkan/blob/main/src/types.ts#L1074)

A default for [Result.noteID](Kana.md#noteid)

`main_information` will make either the ID or kana/kanji/radical character the default note ID of the note.

***

### noteType?

> `optional` **noteType?**: `string` \| `true`

Defined in: [types.ts:1078](https://github.com/Ronokof/Henkan/blob/main/src/types.ts#L1078)

A default for [Result.noteTypeName](Kana.md#notetypename)
