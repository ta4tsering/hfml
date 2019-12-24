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
`bt<Book Title>` contains a title for any kind of work. Eg (bt༈ ཕན་ཡོན་ཕྱོགས་སྒྲིག་འདོད་འཇོའི་བུམ་བཟང་བཞུགས་སོ།)

`au<Author>` contains the name(s) of an author, personal or corporate, of a work. Eg (auམཛད་པ་པོ། མཁས་གྲུབ་ཀརྨ་ཆགས་མེད། གཏེར་ཆེན་ཀརྨ་གླིང་པ།)

`rt<Root text>` contains a phrase or passage attributed by the narrator or author to some agency external to the text.

Eg. (rtསྦྱིན་དང་ཚུལ་ཁྲིམས་བཟོད་དང་བརྩོན་འགྲུས་དང༌། །

བསམ་གཏན་ཤེས་རབ་ཕ་རོལ་ཕྱིན་པ་དྲུག)།ཅེས་གསུངས་པ་ལྟར།

`q<Citation>` contains a quotation from some other document. Eg གཞན་ཡང་འཕགས་པ་སྤྱན་རས་གཟིགས་ཀྱི་མདོ་ལས། (qསངས་རྒྱས་ཆེན་པོར་མར་མེ་གཅིག་ཕུལ་ན།)

`s<Sabche>` contains the sub topic titles. Eg (sབཞི་པ་དཀོར་ནོར་དུ་འབུལ་བའི་ཚེ་ཐར་ལུང་ནི)

`yc<Yikchung>` contains text usually smaller in size than the rest of the text and it can be titiles,hommage or colophon.

Eg. ཧཱུྃ་ཆེན་ཀཱ་ར་སྟེ་བོད་སྐད་ཧཱུྃ་མཛད་སོགས་(ycའོག་ཏུ་ཡོད་དོ། །)སོ། །

 `#<Peydurma>` denotes the peydurma notes. Eg #དག་འཇོག་པར་བྱེད་པས་བདག་ཅག་རེ་ཞིག་བཅོམ་ལྡན་འདས་ལ་བལྟ་བ་དང་བསྙེན་བཀུར་བྱ་བའི་ཕྱིར་འདོང་བ་སྔས་ཀྱིས།

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
 
