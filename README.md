# HFML - the human-friendly markup language

Why make things simple when they can be complicated?

## HFML Tags

### NER tags
`<E >` definition

... more tags

### Source text pagination tags
`[1a]` folio, side 

`[1a.1]` folio, side, line

### TOC tags
`{T###}` text ID

`{T###-##}` section/chapter ID

### Layout tags
`[text]` yig chung

### Spell-checking tags

`(eror,error)` potential error, correction suggestion

### Critical aparatus
`[ ]` uncertain reading

`(* )`  editorial restoration of lost text

`⟨* ⟩`  editorial addition of omitted text

`⟪ ⟫` scribal insertion

`{ }` editorial deletion of redundant text

`{{ }}` scribal deletion

`///` textual loss at left or right edge of support

## Notes

- we don't encode lines as annotations and generate them on the fly from the pagination layer and line returns in the base

## Sources
- [gandhari.org](https://gandhari.org/a_dpreface.php)
- [esukhia/derge-kangyur](https://github.com/Esukhia/derge-kangyur)
 
