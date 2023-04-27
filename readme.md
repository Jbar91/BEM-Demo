# BEM

## What is BEM?

The Block, Element, Modifier methodology (commonly referred to as BEM) is a popular naming convention for classes in HTML and CSS. Developed by the team at Yandex, its goal is to help developers better understand the relationship between the HTML and CSS in a given project.

## Why BEM?

CSS is a language that’s easy to learn but very hard to maintain. As the project grows larger, without proper structure, maintaining CSS is unbearable, hence we use the BEM methodology to make CSS maintainable.

## Benefits of BEM

BEM provides a modular structure to your CSS project. Because of its unique naming scheme, we won’t run into conflicts with other CSS names. BEM also provides a relationship between CSS and HTML.

## Blocks, Elements and Modifiers:

- Blocks: A standalone entity that is meaningful on its own. Examples:

  - `<header>` `<section>` `<menu>` `<checkbox>` `<input>`
  - `.header` `.menu` `.checkbox`

- Element: A part of a block that has no standalone meaning and is semantically tied to its block. Examples:

  - `menu item`, `list item`, `checkbox caption`, `header title`
  - `.menu__item`, `list__item`, `.header__title`

- Modifier: A flag on a block or element. Use them to change appearance or behavior. Examples:
  - `disabled`, `highlighted`, `checked`, `fixed`, `color yellow`
  - `btn--disabled`, `text--highlighted`, `title--color-yellow`
