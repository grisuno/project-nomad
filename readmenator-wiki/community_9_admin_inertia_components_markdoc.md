# admin/inertia/components/markdoc

*Community 9 | 6 files | cohesion 1.00*

## Definition

This community groups 6 file(s) rooted at `admin/inertia/components/markdoc` with dominant language tsx (cohesion 1.00). Central symbols: `Callout`, `CodeBlock`, `Heading`, `HorizontalRule`, `Image`, `InlineCode`, `Link`, `List`. Core file: `admin/inertia/components/MarkdocRenderer.tsx` (6 symbols).

## Files

| File | Language | Layer | Symbols | Doc |
|------|----------|-------|---------|-----|
| `admin/inertia/components/MarkdocRenderer.tsx` | tsx | presentation | 6 | no |
| `admin/inertia/components/markdoc/Heading.tsx` | tsx | presentation | 1 | no |
| `admin/inertia/components/markdoc/Image.tsx` | tsx | presentation | 1 | no |
| `admin/inertia/components/markdoc/List.tsx` | tsx | presentation | 1 | no |
| `admin/inertia/components/markdoc/ListItem.tsx` | tsx | presentation | 1 | no |
| `admin/inertia/components/markdoc/Table.tsx` | tsx | presentation | 6 | no |

## Key Symbols

- `Paragraph` (function, `admin/inertia/components/MarkdocRenderer.tsx:10`) - Paragraph component
- `Link` (function, `admin/inertia/components/MarkdocRenderer.tsx:15`) - Link component
- `InlineCode` (function, `admin/inertia/components/MarkdocRenderer.tsx:38`) - Inline code component
- `CodeBlock` (function, `admin/inertia/components/MarkdocRenderer.tsx:47`) - Code block component
- `HorizontalRule` (function, `admin/inertia/components/MarkdocRenderer.tsx:74`) - Horizontal rule component
- `Callout` (function, `admin/inertia/components/MarkdocRenderer.tsx:81`) - Callout component
- `Heading` (function, `admin/inertia/components/markdoc/Heading.tsx:3`)
- `Image` (function, `admin/inertia/components/markdoc/Image.tsx:1`)
- `List` (function, `admin/inertia/components/markdoc/List.tsx:1`)
- `ListItem` (function, `admin/inertia/components/markdoc/ListItem.tsx:1`)
- `Table` (function, `admin/inertia/components/markdoc/Table.tsx:1`)
- `TableHead` (function, `admin/inertia/components/markdoc/Table.tsx:11`)
- `TableBody` (function, `admin/inertia/components/markdoc/Table.tsx:15`)
- `TableRow` (function, `admin/inertia/components/markdoc/Table.tsx:19`)
- `TableHeader` (function, `admin/inertia/components/markdoc/Table.tsx:23`)
- `TableCell` (function, `admin/inertia/components/markdoc/Table.tsx:31`)

## Internal vs External Edges

- Internal resolved imports (EXTRACTED): 5
- Cross-boundary resolved imports (EXTRACTED): 0

## Connections

- No cross-community bridges recorded. This community is self-contained.

## Risks

- No scoped security, taint, cycle, or layer risks.

## Open Questions

- Why do 6 file(s) lack file-level docs (e.g. `admin/inertia/components/MarkdocRenderer.tsx`)? What purpose do they serve?
- What would break if the most connected file in admin/inertia/components/markdoc changed?
- Should admin/inertia/components/markdoc be split, given cohesion 1.00?

## Sources

- `admin/inertia/components/MarkdocRenderer.tsx`
- `admin/inertia/components/markdoc/Heading.tsx`
- `admin/inertia/components/markdoc/Image.tsx`
- `admin/inertia/components/markdoc/List.tsx`
- `admin/inertia/components/markdoc/ListItem.tsx`
- `admin/inertia/components/markdoc/Table.tsx`
