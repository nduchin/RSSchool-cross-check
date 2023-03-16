## Requirements:

<!--  complete: &#09989;
      incomplete: &#10071;
      unperform: &#10060;
      note: &#08505;
-->

1. <details><summary> &#10071; Everything is done from `Repository requirements and how to submit task` section <b>27.5 / 30</b></summary>

    1. &#09989; Create public repository `cssBayan`
    2. &#09989;Create `gh-pages` branch (if you don't have)
    3. &#09989;Switched to it (gh-pages) and create folder called `cssBayan`. Your deployed accordion will be available,
      e.g.: `https://${YOUR_GITHUB_NAME}.github.io/cssBayan/cssBayan/index.html`
    4. &#09989;Implement your solutions in this folder (cssBayan). There should be at least **5** commits.
    5. &#09989; [You should call your commits accordingly to the guideline](https://docs.rs.school/#/git-convention) + Each your commit should contain time-stamp.
    6. &#10071; When the solution is ready - open Pull Request from `gh-pages` branch to `main` branch. Pull Request name should be equal to the task name. [Description of the Pull Request should be accordingly to the guideline](https://docs.rs.school/#/pull-request-review-process?id=%D0%A2%D1%80%D0%B5%D0%B1%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F-%D0%BA-pull-request-pr). Do NOT merge this Pull Request. The link to this Pull Request should be submitted to the cross check form. Pull request should contain full description - what was done and what was skipped.
      > PR name, description not corresponds [guideline](https://docs.rs.school/#/pull-request-review-process?id=%D0%A2%D1%80%D0%B5%D0%B1%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F-%D0%BA-pull-request-pr)

  </details>
  
2. &#10071; The accordion component is centered on the screen, with equal indents on the left and right **5 / 10**
  > `accordion` elements inside `container` anen't centered
3. &#09989; Icons, meme texts and meme images are exist **5 / 5**
4. &#09989; Placement of the meme, icons and meme text are the same as in provided example gif images **5 / 5**
5. &#10071; Smooth change (transition) of the meme images and icons is done **10 / 20**
  > Only icon animation is performed
6. &#09989; Responsive design with three breakpoints for mobile, tablet, and desktop exist. Accordion is displayed correctly at `mobile 320x568, tablet 820x1180, desktop 1920×1080`. (Note:  breakpoints don't have to be 320x568, 820x1180, 1920x1080). **10 / 10**
7. &#10071; All visual effects when the cursor is hovering over the memes, when the mouse is down on a meme, and when a meme is selected are implemented **5 / 10**
  > Mousedown effect isn't performed
  > Hower page effect (task note 1) isn't performed
8. &#10071; The entire row (text, icon, and meme image) clickable **2.5 / 5**
  > Meme image isn't clickable
9. &#10060; Cursor over the memes (hover) effect only exists for devices that can support hover. **0 / 10**
  > Hover effects persists on no-hover devices (after accordion close, checked on two devices)
10. &#09989; The cursor when it is hovering over the rows of the accordion is changing **5 / 5**
11. &#09989; Only flexible dimensions are used `rem, em, %, vh, vw, fr` and etc... The accordion is responsive **10 / 10**
  > &#08505; style.css: `.accordion, border-radius: 3px`, but reset next 
12. &#10071; All blocks/parts of the accordion are in base flow of the dom elements. All elements are not positioned with `top, left, right, bottom`. `float` is not used. The value of `position` is only `static` **2.5 / 5**
  > `top: 50%` and `position: absolute` are used
13. &#10060; Pseudo-elements are not used (note 1: pseudo-classes are allowed; note 2: pseudo-elements only from FontAwesome are allowed) **0 / 5**
  > `::after` element is used for icon, no FontAwesome usage evidance is found
14. &#09989; Initially, the first meme should be expanded **5 / 5**
15. &#09989; Font size is changed at each device (mobile, tablet, desktop) **5 / 5**

## Rank 97.5/140

## Note:
- &#08505; Wrong accordion type (radio-button type required, no rank downgrade)
- If you fix some of issues, please contact me at [telegram](https://t.me/nduchin) or [discord](https://discordapp.com/users/nduchin)
- Full review you can find at [Github](https://github.com/nduchin/RSSchool-cross-check)