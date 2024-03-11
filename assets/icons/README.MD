# Icon Guide

## Icon

- The TTF file (which is read as a font) was created on [Icomoon](https://icomoon.io/)
- They are inside the icons file (icons.ttf).
- To install and make it available for use, first import the font into the project using @font-face as follows:

```scss
@font-face {
  font-family: "icons";
  src: url(/assets/icons/icons.ttf);
}

*,
body {
  font-family: "Roboto", "icons", sans-serif;
}
```

## Exemplo de uso

```scss
.icon-gamepad:before {
  content: "\e0100";
  font-size: 16px;
  color: #fff;
}
```

### Available Icons:

| Icon         | Content (code) |
| ------------ | -------------- |
| Gamepad      | \e900          |
| Mobile       | \e901          |
| House        | \e902          |
| Graph        | \e903          |
| Notification | \e904          |
| Star         | \e905          |
| Menu         | \e906          |
