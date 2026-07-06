> Derived from the full Settlement Gate working packet.

# Conditional Permission Examples

## Sentence

`Visitors may board the next ferry after ticket inspection.`

## Packet point

The working packet treats this as a condition-to-permission structure. The sentence licenses boarding only once ticket inspection has been satisfied.

## Important blocked reading

This must not be read as unconditional permission. The packet's A6 explicitly blocks the rival reading that visitors may board without the governing ticket-inspection condition.

## Candidate AI-audit use

A future agent should not act on “may board” alone. It should preserve the condition:

```text
ticket inspection -> permission to board
```

The sentence should require evidence that inspection has occurred before boarding permission is treated as actionable.
