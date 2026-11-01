# Question Markup

Plain text loses underline/dot formatting from the original paper. This dataset
uses visible inline markers:

| Marker | Meaning |
|---|---|
| `【画线】…【/画线】` | sentence is underlined in the original |
| `【波浪线】…【/波浪线】` | sentence has a wavy underline |
| `【加点】…【/加点】` | word/character has emphasis dots |

`marks` records `{type, status}` for marked records.

If the exact span could not be located in the text layer, `mark_note` is set to:

```text
画线部分见原卷；文本层未保留格式
加点词见原卷；文本层未保留格式
```

This is deliberate: the converter does not guess which sentence was underlined.
The original PDF remains the authoritative source for those unresolved items.
