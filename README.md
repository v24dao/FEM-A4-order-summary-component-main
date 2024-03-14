### Links:

[Live link](https://v24dao-fem-a2.netlify.app/) |
[Front End Mentor Challenge]() |
[All my Front End Mentor Solutions](https://github.com/v24dao/Front-End-Mentor-Challenges)

### Challenge Screenshot:

<img src="challenge-screenshot.png" width="300">

### Main takeaways:

#### 1. Semantics

After realising that this checkout card would most likely be a small component on a website, I changed some html semantics to reflect this.

For example, I changed `card__title` from a `h1` to a `h3`.

I also encountered some styling issues when trying to create a button using an `a` tag inside of a `div`. This issue was quickly resolved by using the `button` semantic.

I have learnt that using the correct semantic tags is not only important from an accessiblity perspective; it could also make styling in CSS easier!

#### 2. Block vs Inline-Block vs Inline

<u>Inline Elements</u>
An inline element is one that does not start on a new line. It also takes up as little space as possible.

We are unable to set a width or height on Inline elements. We are also unable to add Top/Bottom paddings and margins.

Examples of inline elements are: `<a>`, `<span>`, `<img>`

<u>Inline Block Elements</u>
Similar to Inline Elements, Inline-block elements do not start on a new line.

However, we are able to set a width and height on Inline-block elements. Top/Bottom Margins and paddings are also respected on Inline Block elements.
