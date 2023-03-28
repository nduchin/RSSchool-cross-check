## Requirements:

<!--  complete: &#09989; 
      incomplete: &#10071; 
      unperform: &#10060; 
      note: &#08505; 
      warning: &#09888; 
      ## Unperformed and incomplete items:
-->

### Page Main
1. Layout check:

    - &#10060; valid layout (correspond [validator](https://validator.w3.org/)) (0/4)
      > [validator report](https://validator.w3.org/nu/?doc=http%3A%2F%2Fs29645vv.beget.tech%2FNataliaPW%2Fshelter%2F) returns 2 errors


2. Layout corresponds figma draft

    - &#10060; block `Not only` (0/5)
      > layout error `>10px`  
      > wrong title style, button width  
      > wrong background position/section height  
    - &#10071; block `About` (2.5/5)
      > wrong sectioin paddings  
      > wrong title font style (font size, line height, letter spacing)  
    - &#10071; block `Our Friends` (2.5/5)  
      > wrong title, card caption font styles  
    - &#10071; block `Help` (2.5/5)
      > wrong title text, style  
      > wrong elements caption style  
      > wrong elements layout (is caused by fixing alignment, no downgrade)  
    - &#10071; block `In addition` (2.5/5)
      > wrong title, descriptions styles  
      > wrong elements spacing (`>10px` total)  
      > wrong credit-card field style (width `+30px`, border radius , padding)  
    - &#10071; block `&lt;footer>` (2.5/5)
      > wrong grid layout  
      > wrong background layout  
      > excess third party content  

4. Elements interactions

    - &#10060; Each pet-card in block `Our friends` is interactive at full area (0/2)
      > Cards are inserted as photo gallery (propbply with libs) and don't work as required

### Page Pets
5. Layout check

    - &#10060; valid layout (correspond [validator](https://validator.w3.org/)) (0/4)
      > [validator report](https://validator.w3.org/nu/?doc=http%3A%2F%2Fs29645vv.beget.tech%2FNataliaPW%2Fshelter%2Fpets-page.html) returns 7 errors  
      > 5 of them are coused by use `<span>` inside for closing, instead of `</span>` 

6. Layout corresponds figma draft

    - &#10071; block `Our Friends` (2.5/5)
      > wrong title, card caption font styles  
      > wrong card height causes layout error `>10px` in total  
      > wrong card button height (error `>10px`)  
      > wrong layout at window width `>1280px`  
    - &#10071; block `&lt;footer>` (2.5/5)
      > wrong grid layout
      > wrong background layout 
      > excess third party content

8. Elements interactions

    - &#10071; `Our pets` Element is highlighted and inactive, other navigation elements are interactive (1/2)
      > `Our pets` isn't inactive, and causes header bug (all links are hovered)  
    - &#10071; Accessable pagination buttons (to right) are active, inccessable pagination buttons (to left) are inactive (1/2)
      > inccessable buttons are active  
    - &#10060; Each pet-card in block `Our friends` is interactive at full area (0/2)
      > Cards are inserted as photo gallery (propbply with libs) and don't work as required

---

Rest of items are complete (44/44)

## Penalties:

2. &#09888; Forbidden libraries or frameworks is used (-100)
  - 5. Outdated libraries are forbidden (JQuery and so on.)
    > index.html #821: `<script src="js/jquery-3.6.0.min.js"></script>`

## Rank 0/100
  **63.5** before penalties


## Notes:
  - Full review with screenchots you can find at [Github](https://github.com/nduchin/RSSchool-cross-check)
