---
title: Use @each to Map Over Items in a List
---
## Use @each to Map Over Items in a List

This is a stub. <a href='https://github.com/freecodecamp/guides/tree/master/src/pages/certifications/front-end-libraries/sass/use-each-to-map-over-items-in-a-list/index.md' target='_blank' rel='nofollow'>Help our community expand it</a>.

<a href='https://github.com/freecodecamp/guides/blob/master/README.md' target='_blank' rel='nofollow'>This quick style guide will help ensure your pull request gets accepted</a>.

<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->
This is working solution of this stub
<style type='text/sass'>
 @each $color-bg in blue, black, red {
 .#{$color-bg}-background-color{background-color:$color-bg;}
 } 
.blue-bg{
background-color:blue;
} 
.black-bg{
background-color:black;
} 
.red-bg{
background-color:red;
}  
  
  div {
    height: 200px;
    width: 200px;
  }
</style>

<div class="blue-bg"></div>
<div class="black-bg"></div>
<div class="red-bg"></div>
