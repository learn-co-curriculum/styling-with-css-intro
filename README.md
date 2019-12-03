# Making The Web Look Good With CSS

We've learned a bit about HTML. While HTML does a great job of putting words and pictures on the page, CSS exists to make your content _look good_. 

![Make This Look Good](https://web-dev-readme-photos.s3.amazonaws.com/js/make-this-look-good.gif)

Let's take a look at a rather simple example of what CSS does. Go ahead and flip between the HTML and CSS tabs of the CodePen below. You'll see the HTML sections has just a simple header: `<h1>This Is My Header</h1>`. The text turns up red though. How is that possible? The magic of CSS is how. Click on the CSS tab. You'll notice we set the color to red with this line: `color: red`. If you change the `red` to `green` what happens? It turns green! BOOM You just wrote your first CSS. Congrats!

<iframe height='265' scrolling='no' title='EWozNm' src='//codepen.io/joemburgess/embed/EWozNm/?height=265&theme-id=0&default-tab=html,result&embed-version=2&editable=true' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='http://codepen.io/joemburgess/pen/EWozNm/'>EWozNm</a> by Joe Burgess (<a href='http://codepen.io/joemburgess'>@joemburgess</a>) on <a href='http://codepen.io'>CodePen</a>.
</iframe>

In the CSS, `color` is what we refer to as an property. The `color` property defines what the text color of *all* `h1` HTML elements should be. If we change the value of `color` to `blue`, any `h1` element on the page will turn blue.

**Note**: Normally, every CSS property we define needs to end with a semi-colon (`;`). The one exception is when there is only a single property defined as is the case here. It is good practice to go ahead and add a semi-colon, though: 

```css
h1 {
  color: redl;
}
```

Now that you understand the basics of CSS, continue onto the next lesson and get a deeper understanding of CSS.

<p class='util--hide'>View <a href='https://learn.co/lessons/styling-with-css-intro'>Styling With Css Intro</a> on Learn.co and start learning to code for free.</p>
