---
jsApi: true
title: "[I] ProjectionMemberExpressionNode"

---
## Extends

- [`BaseNode`](Interface.BaseNode.md)

## Properties

| Property | Type | Description |
| :------ | :------ | :------ |
| `readonly` `base` | [`ProjectionExpression`](Type.ProjectionExpression.md) | - |
| `directives`? | *readonly* [`DirectiveExpressionNode`](Interface.DirectiveExpressionNode.md)[] | - |
| `docs`? | *readonly* [`DocNode`](Interface.DocNode.md)[] | - |
| `readonly` `end` | `number` | The ending position measured in UTF-16 code units from the start of the<br />full string. Exclusive. |
| `readonly` `flags` | [`NodeFlags`](Enumeration.NodeFlags.md) | - |
| `readonly` `id` | [`IdentifierNode`](Interface.IdentifierNode.md) | - |
| `readonly` `kind` | [`ProjectionMemberExpression`](Enumeration.SyntaxKind.md#projectionmemberexpression) | - |
| `parent`? | [`Node`](Type.Node.md) | - |
| `readonly` `pos` | `number` | The starting position of the ranger measured in UTF-16 code units from the<br />start of the full string. Inclusive. |
| `readonly` `selector` | `"."` \| `"::"` | - |
| `readonly` `symbol` | [`Sym`](Interface.Sym.md) | Could be undefined but making this optional creates a lot of noise. In practice,<br />you will likely only access symbol in cases where you know the node has a symbol. |
