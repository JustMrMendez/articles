# Understand CSS Units or be Doomed  -  A Fun Look into the World of CSS Units
![Understand CSS Units or be Doomed — A Fun Look into the World of CSS Units](../../assets/img/css-units.png)

Hello there, future coders. Let's dive deep into **CSS Units**, dive, dive! Today, we hit the road to CSS units. No need to roll your eyes. Yes, measurements sound like a less-fun version of Disneyland. But hold on, these units are the secret ingredients to make your website the king of the internet!

## Why CSS Units, Though?

Why do we need CSS units? Imagine ordering a custom pair of shoes, but there are no sizes. They make it by looking at a photo of your foot. No, just no! Same goes for webpages. CSS units bring order, structure, and the necessary sizing rules to your projects!

We have two types of CSS units in our toolkit:

- **Absolute Units**: They’ll never change, even if you sweet talk them.
- **Relative Units**: They like to go with the flow, dancing to the tune you play.

## Absolute Units - No Nonsense Here!

Absolute units stick by the rules. Their minds are as clear as a blue sky on a sunny day.

#### - `px` (Pixels): 

Pixel is a tiny dot in the world of your computer screen. They're like the grains of rice in a paella. Each one adds to the whole picture.

```css
h1 {
  font-size: 28px;  /* The size of the h1 tag will always be 28px */
}
```

#### - `pt` (Points): 

Points come from the print world. One point equals to 1/72 of an inch. Fancy, isn't it?

#### - `in` (Inches), `cm` (Centimeters), `mm` (Millimeters): 

These units act just like a normal ruler. They work best in print design. But who said you can’t paint your web canvas with these?

## Relative Units - Flexible and Fun!

Relative units are like notes in a song. They change to maintain harmony with the parent element or the viewport size. 

```css
body {
    font-size: 20px;  /* A clear-minded absolute unit */
}
div {
    font-size: 2em;  /* It gets 2 times bigger than body’s font size. Dancing to the tune, eh?  */
}
```

There are plenty in this fun bunch - `em`, `rem`, `vh`, `vw`, `%,` and more! Picking between absolute and relative units comes down to your game plan. 

- **`em`**: The chameleon; it adjusts its size according to the parent element.

- **`rem`**: The wise elder; always refers to the root element to maintain a consistent size across the webpage.

- **`vh`**: The tall friend; a unit that ensures your elements are height-perfect on all screens, big or small.

- **`vw`**: The wide-angle lens; keeps your element widths in check, ensuring they look great on screens of all sizes.

- **`%`**: The harmonizer; works relative to the size of the parent element, maintaining the right proportions no matter the context.

## Decoding the Jargon

Before you go, let’s decode some tech jargon - 

- **Parent element**: In CSS, elements can have parents, children, and siblings. Fancy, huh? The parent is the element that encloses another element. If an element is a sandwich, the parent element is the plate that holds it. 
- **Viewport**: This is just a fancy way to say the user's visible area on the web page. On a hot day, your viewport is like the ice in your cola, the part you're actually seeing.

And that's it! Hopefully, CSS units are now less of a mystery and more of a friend. Practice and play around with them. Don't fear to make mistakes. That’s how all great coders start. Happy coding! 🎉
