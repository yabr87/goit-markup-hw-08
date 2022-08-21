# goit-markup-hw-08

```scss
.container {
  margin: 0 auto;
  padding: 0 15px;

  @media screen and (min-width: 480px) {
    width: 480px;
  }

  @media screen and (min-width: 768px) {
    width: 768px;
  }
}
```

```SCSS
.element {
  flex-basis: calc(
    (100% - кол-во маржинов в строке *
    значение маржина) /
    кол-во элементов в строке
  );
}
```

```SCSS
.backdrop {
overflow-y: scroll;
}

прокрутка мадального вікна

body.modal-open {
overflow: hidden;
}

заборона прокрутки сайту через js

```

```scss
.menu {
  @media screen and (max-width: 767px) {
    display: none;
    position: absolute;
    top: 100%;
    left: 0;
    width: 100%;

    &.is-open {
      display: block;
    }
  }
}

меню при поворачивании экрана пропадает
```
