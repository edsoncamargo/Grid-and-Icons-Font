# Guia de ícones

## Ícones

- Estão dentro do arquivo de ícones (`icons.ttf`).
- Para instalar e ficar disponível para uso, primeiro importe a fonte no projeto usando `@font-face` da seguinte maneira:

```scss
@font-face {
  font-family: 'icons';
  src: url(/assets/icons/icons.ttf);
}

*,
body {
  font-family: 'Roboto', 'icons', sans-serif;
}
```

## Exemplo de uso

```scss
.icon-gamepad:before {
  content: '\e0100';
  font-size: 16px;
  color: #fff;
}
```

> Ícones disponíveis:

Gamepad = `\e900`

Mobile = `\e901`

House = `\e902`

Gráfico = `\e903`

Menu = `\e906`

Estrela = `\e905`

Notificação = `\e904`
