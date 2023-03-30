## Requirements:

<!--  complete: &#09989; 
      incomplete: &#10071; 
      unperform: &#10060; 
      note: &#08505; 
      warning: &#09888; 
      ## Unperformed and incomplete items:
-->

### Page Main (31.5/60)
1. &#09989; Layout check (7/7)

    - &#09989; valid layout (correspond [validator](https://validator.w3.org/)) (4/4)
    - &#09989; header logo consists of text elements (1/1)
    - &#09989; page contains the only `&lt;h1>` element (1/1)
    - &#09989; `favicon` is added (1/1)

2. &#10071; Layout corresponds figma draft (12.5/35)

    - &#10071; block `&lt;header>` (2.5/5)
      > text styles not corresponds figma draft (invisible on white)
      > layout error `21px` (logo/nav)  
    - &#10060; block `Not only` (0/5)
      > layout error `>250px`  
      > wrong title style, button width  
      > wrong background position/section height  
      > <img src="./nataliapw_content/not_only_pp_3003.png" alt="Not only layout" style="max-height: 200px">
    - &#10071; block `About` (2.5/5)  
      > wrong sectioin paddings  
      > wrong title font style (font size, line height, letter spacing)  
      > <img src="./nataliapw_content/about_pp.png" alt="About layout" style="max-height: 200px">
    - &#10060; block `Our Friends` (0/5)  
      > wrong title, card caption font styles  
      > layout error `>20px`  
      > <img src="./nataliapw_content/our_friends_pp_3003.png" alt="Our friends layout" style="max-height: 200px">
    - &#10071; block `Help` (2.5/5)
      > wrong title text, style  
      > wrong elements caption style  
      > wrong elements layout (is caused by fixing alignment, no downgrade)  
      > <img src="./nataliapw_content/help_pp.png" alt="Help layout" style="max-height: 200px">
    - &#10071; block `In addition` (2.5/5)
      > wrong title, descriptions styles  
      > wrong elements spacing (`>10px` total)  
      > wrong credit-card field style (width `+30px`, border radius , padding)  
      > <img src="./nataliapw_content/donation_pp.png" alt="Donation layout" style="max-height: 200px">
    - &#10071; block `&lt;footer>` (2.5/5)
      > wrong grid layout  
      > wrong background layout  
      > excess third party content  
      > <img src="./nataliapw_content/footer_pp.png" alt="Footer layout" style="max-height: 200px">


3. &#09989; CSS Requirement (6/6)

    - &#09989; flexbox or grid is used for `Help` block (2/2)
    - &#09989; page content aligns center if window width is more than 1280px (2/2)
    - &#09989; background color is stretched to full page width (2/2)

4. &#10071; Elements interactions (6/12)

    - &#10071; `About the Shelter` element is highlighted and inactive, other navigation elements are interactive (1/2)
      > `About the Shelter` element isn't inactive and causes page scrolling
    - &#10060; Each pet-card in block `Our friends` is interactive at full area (0/2)
      > Cards are inserted as photo gallery (propbply with libs) and don't work as required
    - &#09989; Smooth anchor crolling (2/2)
    - &#10071; All linkages are processed according linkage list at `Main` page (1/2)
      > Credit card empty link isn't performed  
      > Page logo likn isn't empty
      > email linkage isn't initiate mail agent (`mail:` insted of `mailto:`)
    - &#10071; Completed interaction for links and buttons. Should contain not only cursor changing but also use draft interactions design (1/2)
      > footer links show no hover/active behavior, while poiner is shown at full list area hover (instead of link hover only)  
      > navigation interactions styles don't correspond draft interactions design
    - &#10071; Interactive changes should be applied smoothly (1/2)
      > slider scrolling buttons, logo, navigation links (color) aren't transitioned smoothly

### Page Pets (25.5/40)
5. &#09989; Layout check (7/7)

    - &#09989; valid layout (correspond [validator](https://validator.w3.org/)) (4/4)
    - &#09989; header logo consists of test elements (1/1)
    - &#09989; page contains the only `&lt;h1>` element (1/1)
    - &#09989; `favicon` is added (1/1)

6. &#10071; Layout corresponds figma draft (7.5/15)

    - &#10071; block `&lt;header>` (2.5/5)
      > layout error `21px` (logo/nav) 
    - &#10071; block `Our Friends` (2.5/5)
      > wrong title, card caption font styles  
      > wrong card height causes layout error `>10px` in total  
      > wrong card button height (error `>10px`)  
      > <img src="./nataliapw_content/pets_our_friends_pp.png" alt="Our friends layout" style="max-height: 200px">  
      > wrong layout at window width `>1280px`  
      > <img src="./nataliapw_content/pets_our_friends_pp_2560px.png" alt="Our friends layout at 2560px" style="max-height: 200px">  
    - &#10071; block `&lt;footer>` (2.5/5)
      > wrong grid layout  
      > wrong background layout  
      > excess third party content  
      > <img src="./nataliapw_content/footer_pp.png" alt="Footer layout" style="max-height: 200px">

7. &#09989; CSS Requirement (4/4)

    - &#09989; page content aligns center if window width is more than 1280px (2/2)
    - &#09989; background color is stretched to full page width (2/2)

8. &#10071; Elements interactions (7/14)

    - &#10071; `Our pets` element is highlighted and inactive, other navigation elements are interactive (1/2)
      > `Our pets` element isn't inactive, and causes page scrolling
    - &#10071; Accessable pagination buttons (to right) are active, inccessable pagination buttons (to left) are inactive (1/2)
      > inccessable buttons are active  
      > <img src="./nataliapw_content/pets_pug_buttons.png" alt="Pets buttons" style="max-height: 200px">
    - &#10060; Each pet-card in block `Our friends` is interactive at full area (0/2)
      > Cards are inserted as photo gallery (propbply with libs) and don't work as required
    - &#09989; Smooth anchor crolling (2/2)
    - All linkages are processed according linkage list at `Page` page (1/2)
      > email linkage isn't initiate mail agent (`mail:` insted of `mailto:`)
    - &#10071; Completed interaction for links and buttons. Should contain not only cursor changing but also use draft interactions design (1/2)
      > footer links show no hover/active behavior, while poiner is shown at full list area hover (instead of link hover only)
      > navigation interactions styles don't correspond draft interactions design
    - &#10071; Interactive changes should be applied smoothly (1/2)
      > slider pagination button, logo, navigation links (color) aren't transitioned smoothly

## Notes:

- &#09888; Task is deployed on wrong resource (should be completed in private school repository and deployed on gh-pages or netlify)  
- &#08505; Several type mistakes are found: "shelder" in nav meny, "Leare more" on cards  

## Rank 57/100

## Notes:
  - Full review with screenchots you can find at [Github](https://github.com/nduchin/RSSchool-cross-check)
