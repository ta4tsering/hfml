# HFML - the human-friendly markup language

Simple markup language for semantic annotations.

## Pagination tags

### `[1]`

**Syntax:**
`[<page number>]`

**Use:**
Mark for modern pagination information in modern book or arabic page numbers in traditional text layout.

**Text Sample:**

![image](https://user-images.githubusercontent.com/17675331/144010744-750229ef-0e79-4952-9403-a6dc1b14f492.png)


``བཀྲ་ཤིས་ཆེན་པའི་མདོ་རྫོགས་སོ།།
[32]``

**Type:**
Pagination

### `[1a]`

**Syntax:**
`[<page number><a/b side>]`

**Use:**
Tag for traditional pecha page numbers spelled out in Tibetan on the front side of a folio.

**Text Sample:**

![image](https://user-images.githubusercontent.com/17675331/144010914-f86f66d9-6d41-4fd6-b271-3e8924d38ee5.png)

``[16b]ནི་བཀྲ་ཤིས་གསུམ་པའོ།། [..] བཀྲ་ཤིས་ཆེན་པའི་མདོ་རྫོགས་སོ།།
[32]``

**Type:**
Pecha pagination


### `[1a.1]`

**Syntax:**
`[<page number><a/b side>.<line number>]`

**Use:**
Tag for line numbers in traditional pecha layout.

**Text Sample:**

![image](https://user-images.githubusercontent.com/17675331/144011119-bd4474a8-6fc3-44fa-b254-0aa2a4df228b.png)

``[16b][16b.1]ནི་བཀྲ་ཤིས་གསུམ་པའོ།། [..] [16b.4]བཀྲ་ཤིས་ཆེན་པའི་མདོ་རྫོགས་སོ།།
[32]``

༌༌༌
[180b]
[180b.1]{D31}༄༅། །རྒྱ་གར་སྐད་དུ། དྷརྨ་ཙཀྲ་པྲ་བརྟ་ན་སཱུ་ཏྲ། བོད་སྐད་དུ། ཆོས་ཀྱི་འཁོར་ལོ་རབ་ཏུ་བསྐོར་བའི་མདོ། འཕགས་པ་དཀོན་མཆོག་གསུམ་ལ་གུས་པས་ཕྱག་འཚལ་ལོ། །འདི་སྐད་བདག་གིས་ཐོས་པ་དུས་གཅིག་ན། བཅོམ་ལྡན་འདས་ཡུལ་བཱ་རཱ་ཎ་སཱིའི་
[180b.2]དྲང་སྲོང་ལྷུང་བ་{རི་དགས་,རི་དྭགས་}རྒྱུ་བའི་གནས་ན་བཞུགས་སོ། །དེ་ནས་བཅོམ་ལྡན་འདས་ཀྱིས་དགེ་སློང་ལྔ་སྡེ་རྣམས་བོས་ཏེ་བཀའ་སྩལ་པ། དགེ་སློང་དག་རབ་ཏུ་བྱུང་བ་མཐའ་གཉིས་པོ་འདི་ལ་གནས་པར་མི་བྱའོ། །གང་སུ་དག་འདིར་འདོད་པ་རྣམས་དང་བདེ་བ་ལ་ཞེན་པ་ནི་མི་རིགས་པ་
[180b.3]དང་དམན་པར་འགྱུར་རོ། །སོ་སོའི་སྐྱེ་བོ་རྣམས་ནི་དོན་མེད་པ་དང་ལྡན་པའི་ཕྱིར་གང་སུ་དག་ལུས་དུབ་པ་དང་འབྲལ་བའི་སྡུག་བསྔལ་བསྔགས་པར་བྱ་བ་མ་ཡིན་པ་རྣམས་ཀྱི་དོན་མེད་པ་དང་ལྡན་ནོ། །དགེ་སློང་དག་འདི་རྣམས་ནི་མཐའ་གཉིས་ཀྱི་མཐའ་སྟེ་དེ་ལ་འཇུག་པར་མི་བྱའོ། །
[180b.4]དེ་བཞིན་གཤེགས་པ་མངོན་པར་རྫོགས་པར་སངས་རྒྱས་ནས་དབུ་མའི་ལམ་འདི་གསུངས་སོ། །མིག་བྱེད་པ་དང་། ཡེ་ཤེས་བྱེད་པ་དང་། ཞི་བར་བྱེད་པ་དང་། མངོན་པར་ཤེས་པ་དང་། ཡང་དག་པར་ཁོང་དུ་ཆུད་པ་དང་། མྱ་ངན་ལས་འདས་པ་ལ་ཡང་དག་པར་འཇུག་གོ། །དགེ་སློང་


**Type:**
Pecha pagination


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

