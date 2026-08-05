[**henkan**](../README.md)

***

[henkan](../README.md) / Kanji

# Interface: Kanji

Defined in: [types.ts:772](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L772)

Kanji information

Converted from [DictKanji](DictKanji.md) and extra info added

## Extends

- [`ResultEntry`](ResultEntry.md)\<`"kanji"`\>

## Properties

### components?

> `optional` **components?**: [`KanjiComponent`](KanjiComponent.md)[]

Defined in: [types.ts:804](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L804)

The kanji radicals/components

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

### externalInfo?

> `optional` **externalInfo?**: `true`

Defined in: [types.ts:836](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L836)

Whether or not this kanji object contains information extracted from [source](#source)

***

### frequency?

> `optional` **frequency?**: `string`

Defined in: [types.ts:820](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L820)

#### See

[DictKanjiMisc.frequency](DictKanjiMisc.md#frequency)

***

### grade?

> `optional` **grade?**: `string`

Defined in: [types.ts:816](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L816)

#### See

[DictKanjiMisc.grade](DictKanjiMisc.md#grade)

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

Defined in: [types.ts:824](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L824)

#### See

[DictKanjiMisc.jlpt](DictKanjiMisc.md#jlpt)

***

### kanji

> `readonly` **kanji**: `string`

Defined in: [types.ts:776](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L776)

#### See

[DictKanji.kanji](DictKanji.md#kanji)

***

### kokuji?

> `optional` **kokuji?**: `true`

Defined in: [types.ts:828](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L828)

Whether or not the kanji is a kokuji

***

### kunyomi?

> `optional` **kunyomi?**: `string`[]

Defined in: [types.ts:792](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L792)

The kanji kunyomi readings

***

### meanings?

> `optional` **meanings?**: `string`[]

Defined in: [types.ts:784](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L784)

#### See

[DictKanjiReadingMeaningGroup.meanings](DictKanjiReadingMeaningGroup.md#meanings)

***

### mnemonic?

> `optional` **mnemonic?**: `string`

Defined in: [types.ts:808](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L808)

The kanji mnemonic

***

### nanori?

> `optional` **nanori?**: `string`[]

Defined in: [types.ts:796](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L796)

#### See

[DictKanjiReadingMeaning.nanori](DictKanjiReadingMeaning.md#nanori)

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

### onyomi?

> `optional` **onyomi?**: `string`[]

Defined in: [types.ts:788](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L788)

The kanji onyomi readings

***

### source?

> `optional` **source?**: `string`

Defined in: [types.ts:832](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L832)

The source (besides KANJIDIC) from which data for this kanji has been extracted

***

### strokes?

> `optional` **strokes?**: `string`

Defined in: [types.ts:780](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L780)

#### See

[DictKanjiMisc.strokeNumber](DictKanjiMisc.md#strokenumber)

***

### svg?

> `optional` **svg?**: `string`

Defined in: [types.ts:800](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L800)

The kanji SVG filename

***

### tags?

> `optional` **tags?**: `string`[]

Defined in: [types.ts:672](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L672)

Tags generated based on the entry's information

#### Inherited from

[`ResultEntry`](ResultEntry.md).[`tags`](ResultEntry.md#tags)

***

### words?

> `optional` **words?**: [`Word`](Word.md)[]

Defined in: [types.ts:812](https://github.com/Skadro/Henkan/blob/main/src/types.ts#L812)

Words that use the kanji
