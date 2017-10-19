Fooþjónustan
Vefsíða: https://notendur.hi.is/svn5/vefforritun/stort-verkefni-1/index.html


Allar html síður eru tengdar við sömu styles.css skrá sem gerð úr styles.scss.

Inn á styles.scss er skrifuð sameiginleg style fyrir allar síðurnar, en neðst á styles.scss á að tengja við .scss skrá sem inniheldur style sem er einungis fyrir ákveðna síðu.
Til dæmis er núverandi styles.scss tengd þremur öðrum .scss skrám:
@import "scss/index";
@import "scss/buy";
@import "scss/about";, þar sem index.scss inniheldur style sem er einungis fyrir forsíðu o.s.frv.

Elements.html er til skoðunar á því hvernig síða á almennt að líta út en hefur ekki beina áhrif á verkefnið. Það á ekki að tengja elements.css við html síðurnar því það er ekki gert til þess styðja css kóðann. Í staðinn er það mikilvæga sem er í elements.css búið að skrifa beint inn í styles.scss. 

Allt er stílað samkvæmt .stylelintrc skrá sem er í möppunni

Vinna skal verkefnið í gengum Github https://github.com/SonVan/StortVerkefni1 í "master" branch og skila skal öllum tilbúnum síðum inná "Final" branch.


Kristín Henný - khi4@hi.is
Son Van Nguyen - svn5@hi.is
Þór Sverrisson - ths220@hi.is
