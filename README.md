# HFML - the human-friendly markup language

Simple markup language for semantic annotations.

## HFML Tags

### IE tags

| བོད། bo           | ཨིན། en                       | རྟགས། tag        | དཔེར་བརྗོད། Example                                                                                           |
|------------------|------------------------------|-----------------|------------------------------------------------------------------------------------------------------------|
| མཚོན་བྱ།           | what is defined              | <a.......>      | <aཤེས་བྱ>                                                                                                    |
| མཚན་ཉིད།          | definition                   | <b.......>      | <bབློའི་ཡུལ་དུ་བྱ་རུང་>                                                                                           |
| མཚན་གཞི།          | instance                     | <c.......>      |                                                                                                            |
| དབྱེ་གཞི།           | what is enumerated           | <d.......>      | <dསྒྲ་ལ་བརྗོད་བྱེད་ཀྱི་སྒྲའི་སྒོས་>དབྱེ་ན་གཉིས་ཡོད་དེ།                                                                       |
| དབྱེ་བ།            | enumeration                  | <e.......>      | <eསེམས་ཅན་ལ་སྟོན་པའི་སྒྲ་དང་། སེམས་ཅན་ལ་མི་སྟོན་པའི་སྒྲ་>གཉིས་ཡོད་པའི་ཕྱིར།                                                  |
| སྒྲ་བཤད།           | word part explanation        | <f.......>      |                                                                                                            |
| སྒྲ་གཞི།            | what is explained            | <l.......>      |                                                                                                            |
| ལུང་ཚིག            | citation                     | <g.......g>     | <gའགྲོ་ལ་ཕན་པར་བྱེད་རྣམས་ལམ་ཤེས་ཉིད་ཀྱིས་འཇིག་རྟེན་དོན་སྒྲུབ་མཛད་པ་གང་g>ཞེས་གསུངས་པ་ཡིན་པའི་ཕྱིར།                                |
| ལུང་ཁུངས།          | source                       | <h.......>      | <hམངོན་རྟོགས་རྒྱན་ལས།>                                                                                          |
| མཛད་བྱང་།         | colophon                     | <i.......>      | <iབཤད་སྒྲུབ་བསྟན་པའི་འབྱུང་གནས་དཔལ་ལྡན་བཀྲ་ཤིས་འཁྱིལ་དུ་རབ་བྱུང་བཅུ་བཞི་པའི་ལྕགས་སྤྲེལ་གྱི་ལོར་པར་དུ་བསྐྲུན་པ་དགེ་ལེགས་འཕེལ། སརྦ་མངྒ་ལཾ། །>   |
| བསྒྱུར་བྱང་།         | translation statement        | <j.......>      |                                                                                                            |
| གོ་བྱ།             | what is explained            | <n........>     |                                                                                                            |
| གོ་དོན།            | meaning                      | <n*........>    |                                                                                                            |
| དཔེར་བརྗོད།         | example                      | <n**........>   |                                                                                                            |
| འགྲེལ་གཞི།          | what is explained            | <o..........>   | <oདལ་བ་>ཞེས་བྱ་བ་ནི་                                                                                          |
| འགྲེལ་བཤད།         | emplanation                  | <o*..........>  | <oརི་བོ་>ནི་<o*ས་འཛིན་ནོ། །>                                                                                    |
| སྐབས་བསྟུན་འགྲེལ་བཤད། | context-specific explanation | <o**..........> | <o** མི་ཁོམ་པ་ལས་ལོག་པ་སྟེ། འདིར་ནི་སྡོམ་པ་འཆགས་པ་ལ་དལ་བ་ཞེས་བྱའོ། །>                                                  |
| འཇུག་ཡུལ།          | agreement female             | <p........>     | <pཐ་སྙད་ཀྱི་དབང་དུ་བྱས་པ་གསུམ་ལ་འཇུག་ཅིང་། དངོས་པོའ་ིདབང་གིས་བཞི་རུ་འཇུག་པར་འགྱུར་ལ། དུས་ཀྱི་དབང་གིས་གཉིས་ལ་འཇུག་པ་>ཡིན་པའི་ཕྱིར་རོ། ། |
| འཇུག་བྱ།           | agreement male               | <p*........>    | <p*དེ་ཞེས་གྲུབ་པ་དེ་ནི། དོན་དགུ་ལ་འཇུག་>སྟེ།                                                                          |
| མི་འཇུག་སའི་ཡུལ།     | illegal agreement female     | <pp...>         |                                                                                                            |
| མི་འཇུག་ས།         | illegal agreement male       | <pp*...>        |                                                                                                            |
| ས་བཅད།           | outline                      | <q........q>    |                                                                                                            |
| ས་བཅད་ཀྱི་དབྱེ་གཞི།   | outline node                 | <q*........>    |                                                                                                            |
| ས་བཅད་ཀྱི་ནང་གསེས།  | outline branches             | <q**........>   |                                                                                                            |
| ངོས་འཛིན་བྱ།        | what is identified           | <r.........>    |                                                                                                            |
| ངོས་འཛིན་བྱེད།       | identification               | <r*.........>   |                                                                                                            |
| རྩ་བ།             | root text                    | <m.........m>   | <mསྦྱིན་དང་ཚུལ་ཁྲིམས་བཟོད་དང་བརྩོན་འགྲུས་དང༌། །བསམ་གཏན་ཤེས་རབ་ཕ་རོལ་ཕྱིན་པ་དྲུགm>།ཅེས་གསུངས་པ་ལྟར།                             |
| འགྲེལ་བ།           | commentary                   | <m*.........>   |                                                                                                            |


### Source text pagination tags
`[1a]` folio, side

`[1a.1]` folio, side, line

### TOC tags
`{T###}` text ID

`{T###-##}` section/chapter ID

### Layout tags

| བོད། bo         | ཨིན། en                                                  | རྟགས། tag    | དཔེར་བརྗོད། Example                                                                                           |
| -------------- | ------------------------------------------------------- | ----------- | ---------------------------------------------------------------------------------------------------------- |
| ཡིག་ཆུང་།        | contains smaller text size                              | \<y...y\>     | \<yབཤད་སྒྲུབ་བསྟན་པའི་འབྱུང་གནས་དཔལ་ལྡན་བཀྲ་ཤིས་འཁྱིལ་དུ་རབ་བྱུང་བཅུ་བཞི་པའི་ལྕགས་སྤྲེལ་གྱི་ལོར་པར་དུ་བསྐྲུན་པ་དགེ་ལེགས་འཕེལ།  སརྦ་མངྒ་ལཾ། །y\> |
| མཛད་པ་པོ།       | Name\<s\> of an author, personal or corporate, of a work. | \<au....\>    | \<auམཛད་པ་པོ། མཁས་གྲུབ་ཀརྨ་ཆགས་མེད། གཏེར་ཆེན་ཀརྨ་གླིང་པ།\>                                                             |
| དཔེ་ཆའི་མཚན་བྱང་། | contains pecha title                                    | \<k1.......\> | \<k1བྱང་ཆུབ་སེམས་དཔའི་སྤྱོད་པ་ལ་འཇུག་པ་བཞུགས་སོ།།\>                                                                    |
| པོ་ཏིའི་མཚན་བྱང་།  | contains poti title                                     | \<k2.......\> | \<k2༄༅། །འདུལ་བ་ཀ་བཞུགས་སོ། །\>                                                                                 |
| ལེའུ་ཡི་མཚན་བྱང་།  | contains chapter title                                  | \<k3.......\> | \<k3དཀོན་མཆོག་གསུམ་ལ་ཕྱག་འཚལ་ལོ། །\>                                                                              |

 `#\<Peydurma\>` denotes the peydurma notes. Eg #དག་འཇོག་པར་བྱེད་པས་བདག་ཅག་རེ་ཞིག་བཅོམ་ལྡན་འདས་ལ་བལྟ་བ་དང་བསྙེན་བཀུར་བྱ་བའི་ཕྱིར་འདོང་བ་སྔས་ཀྱིས།

### Spell-checking tags

`\<error,suggestion\>` potential error, correction suggestion

### Critical aparatus
`[ ]` uncertain reading

`\<* \>`  editorial restoration of lost text

`⟨* ⟩`  editorial addition of omitted text

`⟪ ⟫` scribal insertion

`{ }` editorial deletion of redundant text

`{{ }}` scribal deletion

`///` textual loss at left or right edge of support

## Notes

- we don't encode lines as annotations and generate them on the fly from the pagination layer and line returns in the base

## Sources
- [gandhari.org]\<https://gandhari.org/a_dpreface.php\>
- [esukhia/derge-kangyur]\<https://github.com/Esukhia/derge-kangyur\>

