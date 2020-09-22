# api-sass-css-template

If you want to create a navbar:

![Navbar demo](demo_navbar.png)

CSS:

```css
.class-name {/*some code*/}
elem-name {/*some code*/}
elem-name .class-name {/*Some code*/}
elem-name another-elem-name {/*some code*/}
.class-name elem-name {/*some code*/}
.class-name .another-class-name {/*some code*/}
```

SCSS:

```scss
elem-name {
  .class-name {/*some code*/}
  another-elem-name {/*some code*/}
  // some code
}
.class-name {
  elem-name {/*some code*/}
  .another-class-name {/*some code*/}
  // some code
}
```

To create the same result?

But...

- which is most efficent and simple?
- which has more features?
- why did the devolper make (css or scss)?
- which do you want to use?

**It depends on you, the project, and many other features.**
