## Requirements:

## Unperformed and incomplete items:

### Basic requirements
  - &#10071; 3.2 Meaningfull names 1/2
    > All changes included to commit `refactor:`<...>`rule 3.1`
  - &#10071; 3.4 Unwanted tag selectors 1/2
    > Various changes complete in commit `refactor:`<...>`rule 3.1` before specified rule commit  

### Extended requirements
  - &#10071; 2.1 BEM-notation 2.5/5
    > Elements of elements not allowed on BEM `index.html :37`<...>`class="list__item__checkbox">`, `:58`<...>`class="list__item__button__image"` and so on. Should be element of block (eg. `list-item__button-image`)  
    > Wrong BEM modificator usage: `list__item__button_edit` and <...>`_delete` is not boolean type. Should contain key mod name (eg. <...>`_type_delete` and so on)
    > Universal selector `*` is not allowed on BEM `style.css :123 .list__item > * {`

Rest of ithem are complete 36/36

### Git, GitHub and application requirements (**- 20**)
  - &#10060; Each commit covers only one rule, and contains rule id in description. Commit can cover bounded rules, if completion one automaticaly completes the others (each rule should be included in description). (- 20 *if is not pass*)
    > initial commit `init: start clean-code-s1e1 task` is included to PR at contains changes of various rules (basic-1.1, basic-1.2, basic-2.1)  
    > commit `refactor:`<...>`rule 3.1` contains changes of rules basic-3.2, ext-1.1  
    > commit `fix: add some buggy changes in styles` contains changes of rule basic-3.4, which isn't declared in description nor in prevous commits   
    > commit `refactor:`<...>`rules 3.6, 3.7 and 3.8` contains non-bonded rules  
    > commit `fix:`<...>`rule 3.4`<...>`rule 3.5` contains non-bonded rules  
    > commit `refactor:`<...>`rules 3.6, 3.7 and 3.8`(css formatting) contain not described html changes  

## Rank 20.5/45

## Note:
  - Full review you can find at [Github](https://github.com/nduchin/RSSchool-cross-check)