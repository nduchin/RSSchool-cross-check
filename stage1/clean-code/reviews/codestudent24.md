## Requirements:

<!--  complete: &#09989;
      incomplete: &#10071;
      unperform: &#10060;
      note: &#08505;
      ## Unperformed and incomplete items:
-->

### Basic requirements (**28**)
  - &#09989; 1.1 Indents 2/2
  - &#09989; 1.2 Lower case 2/2
  - &#09989; 1.3 Quotes 2/2
  - &#09989; 2.1 HTML Formatting 2/2
    > main changes completed in `init: start clean-code-s1e1 task` commit
  - &#09989; 2.2 Doctype HTML5 2/2
  - &#09989; 2.3 Irrelevant mnemonics 2/2
  - &#09989; 2.4 Unnecessery type attribute 2/2
    > obsolete link attribute `charset` isn't removed
  - &#09989; 2.5 (optional) HTML Line-Wrapping (no rank)
  - &#09989; 3.1 Uniform selectors naiming style 2/2
  - &#10071; 3.2 Meaningfull names 1/2
    > All changes included to commit `refactor:`<...>`rule 3.1`
  - &#09989; 3.3 Brevite names 2/2
  - &#10071; 3.4 Unwanted tag selectors 1/2
    > Various changes complete in commit `refactor:`<...>`rule 3.1` before specified rule commit  
  - &#09989; 3.5 Block line indents 2/2
  - &#09989; 3.6 CSS declaration indents 2/2
  - &#09989; 3.7 Semicolon 2/2
  - &#09989; 3.8 Selectors wrapping 2/2

### Extended requirements (**12.5**)
  - &#09989; 1.1 HTML semantics 5/5
    > Various changes complete in commit `fix: add some buggy changes in styles` before specified rule commit  
  - &#09989; 1.2 Media alternatives 5/5
  - &#10071; 2.1 BEM-notation 2.5/5
    > Elements of elements not allowed on BEM `index.html :37`<...>`class="list__item__checkbox">`, `:58`<...>`class="list__item__button__image"` and so on. Should be element of block (eg. `list-item__button-image`)  
    > Wrong BEM modificator usage: `list__item__button_edit` and <...>`_delete` is not boolean type. Should contain key mod name (eg. <...>`_type_delete` and so on)
    > Universal selector `*` is not allowed on BEM `style.css :123 .list__item > * {`

### Git, GitHub and application requirements (**- 20**)
  - &#09989; Should be complete in public user repository. (- 45 *if is not pass*)
  - &#10060; Each commit covers only one rule, and contains rule id in description. Commit can cover bounded rules, if completion one automaticaly completes the others (each rule should be included in description). (- 20 *if is not pass*)
    > initial commit `init: start clean-code-s1e1 task` is included to PR at contains changes of various rules (basic-1.1, basic-1.2, basic-2.1)  
    > commit `refactor:`<...>`rule 3.1` contains changes of rules basic-3.2, ext-1.1  
    > commit `fix: add some buggy changes in styles` contains changes of rule basic-3.4, which isn't declared in description nor in prevous commits   
    > commit `refactor:`<...>`rules 3.6, 3.7 and 3.8` contains non-bonded rules  
    > commit `fix:`<...>`rule 3.4`<...>`rule 3.5` contains non-bonded rules  
    > commit `refactor:`<...>`rules 3.6, 3.7 and 3.8`(css formatting) contain not described html changes  
  - &#09989; Each commit should correspond [commit requirements](https://docs.rs.school/#/git-convention?id=%d0%a2%d1%80%d0%b5%d0%b1%d0%be%d0%b2%d0%b0%d0%bd%d0%b8%d1%8f-%d0%ba-%d0%b8%d0%bc%d0%b5%d0%bd%d0%b0%d0%bc-%d0%ba%d0%be%d0%bc%d0%bc%d0%b8%d1%82%d0%be%d0%b2) and task [guideline](https://github.com/rolling-scopes-school/tasks/blob/master/stage1/modules/clean-code/clean-code-s1e1.md#%D1%80%D0%B5%D0%BA%D0%BE%D0%BC%D0%B5%D0%BD%D0%B4%D0%B0%D1%86%D0%B8%D0%B8) (- 45 *if is not pass*)
  - &#09989; Application performance should be preserved. (- 45 *if is not pass*)
  - &#09989; Task **Pull Request** should be planed from branch `clean-code-s1e1` into `master` (or `main`) (- 25 *if is not pass*)
  - &#09989; Task **Pull Request** should be planed on personal user's repository (- 15 *if is not pass*)
  - &#09989; **Pull Request** should correspond [PR requirements](https://docs.rs.school/#/pull-request-review-process?id=%d0%a2%d1%80%d0%b5%d0%b1%d0%be%d0%b2%d0%b0%d0%bd%d0%b8%d1%8f-%d0%ba-pull-request-pr) (- 45 *if is not pass*)
  - &#09989; **Pull Request**'s link should be submitted in app.rs (- 45 *if is not pass*)

## Rank 20.5/45

<!--
## Note:
    - If you fix some of issues, please contact me at [telegram](https://t.me/nduchin) or [discord](https://discordapp.com/users/nduchin)
    - Full review you can find at [Github](https://github.com/nduchin/RSSchool-cross-check)
-->