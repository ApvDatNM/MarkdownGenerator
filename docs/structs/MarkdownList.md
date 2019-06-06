**STRUCT**

# `MarkdownList`

```swift
public struct MarkdownList: MarkdownConvertible
```

> Render a list of elements in Markdown format
>
> Unordered lists:
>
>     - One item
>     - Another item that expands to multiple
>       lines.
>         - A nested item.
>             - Third-level.
>     - Back to first-level.
>
> Ordered lists:
>
>     1. First item
>     1. Second item
>         1. Nested item (second-level)
>     1. Back to first-level

## Properties
### `items`

```swift
public var items: [MarkdownConvertible]
```

> List of items to be converted to a list.

### `markdown`

```swift
public var markdown: String
```

> Generated Markdown output

## Methods
### `init(items:style:)`

```swift
public init(items: [MarkdownConvertible], style: MarkdownListStyle = .unordered)
```

> MarkdownList initializer
>
> - Parameter items: List of items to be converted to a list.

#### Parameters

| Name | Description |
| ---- | ----------- |
| items | List of items to be converted to a list. |