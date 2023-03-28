# Shelter #1: Desktop

## Key dates:
- Start: 03.21.2023
- Deadline: 03.28.2023

## Resourses:
1. Task description: [Shelter desktop](https://github.com/rolling-scopes-school/tasks/blob/master/tasks/shelter/shelter-part1.md)
2. [Figma draft](https://www.figma.com/file/Yk6EnbY63FyG2PJTFkJDMh/shelter)

## Repository:
1. Complete in privat school repository
2. Complete in branch and folder `shelter`
3. Complete task requirement
4. Check work requirement
5. Alert completion requirement correspondence in browser console
6. Daploy your work in `gh-pages` branch
7. Open Pull Request from `shelter` to `main` with description according to [guide](https://docs.rs.school/#/pull-request-review-process?id=%D0%A2%D1%80%D0%B5%D0%B1%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F-%D0%BA-pull-request-pr)
8. Submit work in [rs app](https://app.rs.school/)
9. Complete cross-check after deadline

## Requirement:
### Page Main (60)
<details><summary>1. Layout check (7)</summary>

- valid layout (correspond [validator](https://validator.w3.org/)) (4)
- header logo consists of test elements (1)
- page contains the only <code>&lt;h1></code> element (1)
- <code>favicon</code> is added (1)

</details>
<details><summary>2. Layout corresponds figma draft (35)</summary>

- block <code>&lt;header></code> (5)
- block <code>Not only</code> (5)
- block <code>About</code> (5)
- block <code>Our Friends</code> (5)
- block <code>Help</code> (5)
- block <code>In addition</code> (5)
- block <code>&lt;footer></code> (5)

</details>
<details><summary>3. CSS Requirement (6)</summary>

- flexbox or grid is used for <code>Help</code> block (2)
- page content aligns center if window width is more than 1280px (2)
- background color is stretched to full page width (2)

</details>
<details><summary>4. Elements interactions (12)</summary>

- <code>About the Shelter</code> Element is highlighted and inactive, other navigation elements are interactive (2)
- Each pet-card in block <code>Our friends</code> is interactive at full area (2)
- Smooth anchor crolling (2)
- All linkages are processed according <a href="#Linkage list">linkage list</a> at <code>Main</code> page (2)
- Completed interaction for links and buttons. Should contain not only cursor changing but also use draft interactions design (2)
- Interactive changes should be applied smoothly (2)

</details>

### Page Pets (40)
<details><summary>5. Layout check (7)</summary>

- valid layout (correspond [validator](https://validator.w3.org/)) (4)
- header logo consists of test elements (1)
- page contains the only <code>&lt;h1></code> element (1)
- <code>favicon</code> is added (1)

</details>
<details><summary>6. Layout corresponds figma draft (15)</summary>

- block <code>&lt;header></code> (5)
- block <code>Our Friends</code> (5)
- block <code>&lt;footer></code> (5)

</details>
<details><summary>7. CSS Requirement (4)</summary>

- page content aligns center if window width is more than 1280px (2)
- background color is stretched to full page width (2)

</details>
<details><summary>8. Elements interactions (14)</summary>

- <code>Our pets</code> Element is highlighted and inactive, other navigation elements are interactive (2)
- Accessable pagination buttons (to right) are active, inccessable pagination buttons (to left) are inactive (2)
- Each pet-card in block <code>Our friends</code> is interactive at full area (2)
- Smooth anchor crolling (2)
- All linkages are processed according <a href="#Linkage list">linkage list</a> at <code>Main</code> page (2)
- Completed interaction for links and buttons. Should contain not only cursor changing but also use draft interactions design (2)
- Interactive changes should be applied smoothly (2)

</details>

## Linkage list
### Main gage:
1. Linkages to the `Pets` Page:
  - navigation element `Our Pets`;
  - button `Get to know the rest` in block `Our Friends`.
2. Linkages to `Help` block (anchor link):
  - button `Help the shelter`
3. Linkages to `Our Friends` block (anchor link):
  - button `Make a Friend` in block `Not only`
4. Linkages to `footer` (anchor link):
  - navigation element `Contacts`
5. Empty linkages:
  - Logo
  - Card number in block `In addition`
6. Other options:
  - mail service launch at email click at `footer`
  - phone number should be opened at tel or icon click at `footer`
  - `google map` with specific (of your choice) should be opened in new window at location click in `footer`

### Pets page:
1. Linkages to the `Main` Page:
  - navigation element `About the shelter`;
  - header logo
2. Linkages to `Help` block at `Main` page (anchor link):
  - navigation element `Help the shelter`
3. Linkages to `footer` (anchor link):
  - navigation element `Contacts`
4. Other options:
  - mail service launch at email click at `footer`
  - phone number should be opened at tel or icon click at `footer`
  - `google map` with specific (of your choice) should be opened in new window at location click in `footer`

## Specifications:
- Layout deviation up to 10px is allowed, while visual similarity is preserved
- Fixes of imprecise measures are allowed and recommended
- Use [PerfectPixel](https://chrome.google.com/webstore/detail/perfectpixel-by-welldonec/dkaagdgjmgdmbnecmcefdhjekcoceebi?hl=ru) extension for precise layout check
- Each block and sections should be checked independent, with alignment check image to it beginning
- Text width can vary, if it attributes correspond layout draft.