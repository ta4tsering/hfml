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
`{bt ####}` `(Book Title)`contains a title for any kind of work.

`{au ####}` `(Author)` contains the name(s) of an author, personal or corporate, of a work

`{rt ######}` `(Root text)`contains a phrase or passage attributed by the narrator or author to some agency external to the text

`{q ######}` `(Citation)` contains a quotation from some other document

`{s ######}` `(Sabche)`contains the sub topic titles.

`[text]` `(Yikchung)` contains text usually smaller in size than the rest of the text and it can be titiles,hommage or colophon.

 `#` `(Peydurma)`denotes the peydurma notes

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
 
