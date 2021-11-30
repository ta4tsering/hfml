# HFML - the human-friendly markup language

Simple markup language for semantic annotations.

## HFML Tags

### Pagination
`[#]` page

### Pecha format pagination
`[1a]` folio, side

`[1a.1]` folio, side, line

### TOC tags
`{T###}` text ID

`{T###-##}` section/chapter ID

### Footnote tags
`[^##]` inline note marker
`[^##]: ` note content prefix

### Endnote tags without page reference
`(##)` endnote marker
`(##): ` endnote content prefix 

### Endnote tags with page reference
`(##)` endnote marker
`[###](##): ` endnote content prefix


### Spell-checking tags

`(error,suggestion)` potential error, correction suggestion

### Critical aparatus
`[? ]` uncertain reading

`\<* \>`  editorial restoration of lost text

`⟨* ⟩`  editorial addition of omitted text

`⟪ ⟫` scribal insertion

`{ }` editorial deletion of redundant text

`{{ }}` scribal deletion

`///` textual loss at left or right edge of support

### Layout tags

| བོད། bo         | ཨིན། en                                                  | རྟགས། tag    | དཔེར་བརྗོད། Example                                                                                           |
| -------------- | ------------------------------------------------------- | ----------- | ---------------------------------------------------------------------------------------------------------- |
| ཡིག་ཆུང་།        | contains smaller text size                              | \<y...y\>     | \<yབཤད་སྒྲུབ་བསྟན་པའི་འབྱུང་གནས་དཔལ་ལྡན་བཀྲ་ཤིས་འཁྱིལ་དུ་རབ་བྱུང་བཅུ་བཞི་པའི་ལྕགས་སྤྲེལ་གྱི་ལོར་པར་དུ་བསྐྲུན་པ་དགེ་ལེགས་འཕེལ།  སརྦ་མངྒ་ལཾ། །y\> |
| མཛད་པ་པོ།       | Name\<s\> of an author, personal or corporate, of a work. | \<au....\>    | \<auམཛད་པ་པོ། མཁས་གྲུབ་ཀརྨ་ཆགས་མེད། གཏེར་ཆེན་ཀརྨ་གླིང་པ།\>                                                             |
| དཔེ་ཆའི་མཚན་བྱང་། | contains pecha title                                    | \<k1.......\> | \<k1བྱང་ཆུབ་སེམས་དཔའི་སྤྱོད་པ་ལ་འཇུག་པ་བཞུགས་སོ།།\>                                                                    |
| པོ་ཏིའི་མཚན་བྱང་།  | contains poti title                                     | \<k2.......\> | \<k2༄༅། །འདུལ་བ་ཀ་བཞུགས་སོ། །\>                                                                                 |
| ལེའུ་ཡི་མཚན་བྱང་།  | contains chapter title                                  | \<k3.......\> | \<k3དཀོན་མཆོག་གསུམ་ལ་ཕྱག་འཚལ་ལོ། །\>                                                                              |



## Notes

- we don't encode lines as annotations and generate them on the fly from the pagination layer and line returns in the base

## Sources
- https://ubsicap.github.io/usfm/
- [gandhari.org]\<https://gandhari.org/a_dpreface.php\>
- [esukhia/derge-kangyur]\<https://github.com/Esukhia/derge-kangyur\>
- https://www.markdownguide.org/extended-syntax/#fn:bignote

