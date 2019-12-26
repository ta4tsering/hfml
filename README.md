# HFML - the human-friendly markup language

Why make things simple when they can be complicated?

## HFML Tags

### IE tags
| བོད། bo                    | ཨིན། en                       | རྟགས། tag        | དཔེར་བརྗོད། Example                       |
|---------------------------|------------------------------|-----------------|------------------------------------|
| མཚོན་བྱ།                       | what is defined              | (A .......)     |   (Aཤེས་བྱ)|
| མཚན་ཉིད།                      | definition                   | (B .......)     |   (Bབློའི་ཡུལ་དུ་བྱ་རུང་)|
| མཚན་གཞི།                      | instance                     | (C .......)     ||
| དབྱེ་གཞི།                       | what is enumerated           | (D .......)| (Dསྒྲ་ལ་བརྗོད་བྱེད་ཀྱི་སྒྲའི་སྒོས་)དབྱེ་ན་གཉིས་ཡོད་དེ། |
| དབྱེ་བ།                        | enumeration                  | (E .......)| (Eསེམས་ཅན་ལ་སྟོན་པའི་སྒྲ་དང་། སེམས་ཅན་ལ་མི་སྟོན་པའི་སྒྲ་)གཉིས་ཡོད་པའི་ཕྱིར། |
| སྒྲ་བཤད།                       | word part explanation        | (F .......)||
| སྒྲ་གཞི།                        | what is explained            | (L .......) ||
| ལུང་ཚིག                       | citation                      | (G .......)     |(Gའགྲོ་ལ་ཕན་པར་བྱེད་རྣམས་ལམ་ཤེས་ཉིད་ཀྱིས་འཇིག་རྟེན་དོན་སྒྲུབ་མཛད་པ་གང་)ཞེས་གསུངས་པ་ཡིན་པའི་ཕྱིར།|
| ལུང་ཁུངས།                      | source                        | (H .......)|(Hམངོན་རྟོགས་རྒྱན་ལས།) |
| མཛད་བྱང་།                      | colophon                      | (I .......)|(I བཤད་སྒྲུབ་བསྟན་པའི་འབྱུང་གནས་དཔལ་ལྡན་བཀྲ་ཤིས་འཁྱིལ་དུ་རབ་བྱུང་བཅུ་བཞི་པའི་ལྕགས་སྤྲེལ་གྱི་ལོར་པར་དུ་བསྐྲུན་པ་དགེ་ལེགས་འཕེལ།  སརྦ་མངྒ་ལཾ། །)|
| བསྒྱུར་བྱང་།                      | translation statement         | (J .......)     ||
| གོ་བྱ།                        | what is explained             | (N........)     ||
| གོ་དོན།                       | meaning                        | (N*........)    ||
| དཔེར་བརྗོད།                     | example                        | (N**........)   ||
| འགྲེལ་གཞི།                      | what is explained              | (O..........)   |(oདལ་བ་)ཞེས་བྱ་བ་ནི་|
| འགྲེལ་བཤད།                     | emplanation                    | (O*..........)  |oརི་བོ་)ནི་(o*ས་འཛིན་ནོ། །)|
| སྐབས་བསྟུན་འགྲེལ་བཤད།                 | context-specific explanation   | (O**..........) |(o** མི་ཁོམ་པ་ལས་ལོག་པ་སྟེ། འདིར་ནི་སྡོམ་པ་འཆགས་པ་ལ་དལ་བ་ཞེས་བྱའོ། །)|
| འཇུག་ཡུལ།                      | agreement female               | (P........)|(Pཐ་སྙད་ཀྱི་དབང་དུ་བྱས་པ་གསུམ་ལ་འཇུག་ཅིང་། དངོས་པོའ་ིདབང་གིས་བཞི་རུ་འཇུག་པར་འགྱུར་ལ། དུས་ཀྱི་དབང་གིས་གཉིས་ལ་འཇུག་པ་)ཡིན་པའི་ཕྱིར་རོ། །|
| འཇུག་བྱ།                       | agreement male                 | (P*........)    |(P*དེ་ཞེས་གྲུབ་པ་དེ་ནི། དོན་དགུ་ལ་འཇུག་)སྟེ། |
| མི་འཇུག་སའི་ཡུལ།                   | illegal agreement female        | (PP...)         ||
| མི་འཇུག་ས།                     | illegal agreement male          | (PP*...)        ||
| ས་བཅད།                      | outline                         | (Q........)     |  |
| ས་བཅད་ཀྱི་དབྱེ་གཞི།                  | outline node                    | (Q*........)    ||
| ས་བཅད་ཀྱི་ནང་གསེས།                  | outline branches               | (Q**........)   ||
| ངོས་འཛིན་བྱ།                     | what is identified              | (R.........)    ||
| ངོས་འཛིན་བྱེད།                     | identification                 | (R*.........)   ||
| རྩ་བ།                         | root text                      | (M.........)    |(Mསྦྱིན་དང་ཚུལ་ཁྲིམས་བཟོད་དང་བརྩོན་འགྲུས་དང༌། །བསམ་གཏན་ཤེས་རབ་ཕ་རོལ་ཕྱིན་པ་དྲུག)།ཅེས་གསུངས་པ་ལྟར།|
| འགྲེལ་བ།                       | commentary                      | (M*.........)   ||


### Source text pagination tags
`[1a]` folio, side 

`[1a.1]` folio, side, line

### TOC tags
`{T###}` text ID

`{T###-##}` section/chapter ID

### Layout tags

| བོད། bo                    | ཨིན། en                       | རྟགས། tag        | དཔེར་བརྗོད། Example                       |
|---------------------------|------------------------------|-----------------|------------------------------------|
| ཡིག་ཆུང་།                  | contains text usually smaller in size than the rest of the text.| (Y .......)|(I བཤད་སྒྲུབ་བསྟན་པའི་འབྱུང་གནས་དཔལ་ལྡན་བཀྲ་ཤིས་འཁྱིལ་དུ་རབ་བྱུང་བཅུ་བཞི་པའི་ལྕགས་སྤྲེལ་གྱི་ལོར་པར་དུ་བསྐྲུན་པ་དགེ་ལེགས་འཕེལ།  སརྦ་མངྒ་ལཾ། །)|
| མཛད་པ་པོ།             |contains the name(s) of an author, personal or corporate, of a work.| (AU.........)|(AUམཛད་པ་པོ། མཁས་གྲུབ་ཀརྨ་ཆགས་མེད། གཏེར་ཆེན་ཀརྨ་གླིང་པ།)|
| མཚན་བྱང་།                  |contains a title for any kind of work| (K .......)     |(K བྱང་ཆུབ་སེམས་དཔའི་སྤྱོད་པ་ལ་འཇུག་པ་བཞུགས་སོ།།)|

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
 
