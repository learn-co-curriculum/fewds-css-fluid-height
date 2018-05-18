# Fluid Height

In creating full-screen layouts, you will often find yourself wanting an element to have a fluid height. For example, a content column that extends from the top of your layout all the way down to the bottom. In the same way that you can set the width of and element to 100%, you can also set the height to 100%, but there is one main difference--in the browser, the body element is always 100% percent wide, but the height of the body element is, by default, only as tall as the content. 

![alt text](https://curriculum-content.s3.amazonaws.com/fewds-css/fluid-height/default.png "default display")

Even if you set the height of the inner div to 100%, it will only stretch 100% vertically until it runs into the parent that it's inside of, which is the body. 

<p data-height="265" data-theme-id="light" data-slug-hash="yjRoWE" data-default-tab="html,result" data-user="FlatironWebDev" data-embed-version="2" data-pen-title="36 Fluid Height" class="codepen">See the Pen <a href="https://codepen.io/FlatironWebDev/pen/yjRoWE/">36 Fluid Height</a> by Kellye Greene (<a href="https://codepen.io/FlatironWebDev">@FlatironWebDev</a>) on <a href="https://codepen.io">CodePen</a>.</p>
<script async src="https://static.codepen.io/assets/embed/ei.js"></script>

In order to set the element to actually scale 100% percent vertically, you'll also have to set both the `body` and the `html` element to have
`height: 100%` and `min-height: 100%`. That is all that is required! The div and any parent that it happens to be inside of, as well
as the `body` and the `html` element all need to be set with the height of 100%. Once those properties are set, you can see (with a refresh) that the inner div will expand 100% vertically on the screen.

![alt text](https://curriculum-content.s3.amazonaws.com/fewds-css/fluid-height/final.png "final display")
