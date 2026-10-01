# Atributos Globais em HTML

## O que são?

São atributos que podem ser usados em qualquer elemento HTML, embora nem todos tenham efeito em todos os elementos. Eles adicionam informações ou configuram comportamentos.

## Principais atributos

| Atributo | Para que serve? |
| --- | --- |
| `id` | Identifica um elemento de forma única na página. |
| `class` | Agrupa elementos para seleção com CSS e JavaScript. |
| `style` | Aplica CSS diretamente no elemento. |
| `title` | Fornece uma informação complementar sobre o elemento. |
| `lang` | Define o idioma do conteúdo. |
| `hidden` | Oculta um elemento. |
| `data-*` | Armazena dados personalizados no elemento. |
| `contenteditable` | Permite editar o conteúdo na página. |

## Exemplos

### `id` e `class`

O `id` não deve se repetir no documento. A mesma classe pode aparecer em vários elementos; um elemento pode ter várias classes.

```html
<h1 id="titulo-principal">Estudos de HTML</h1>
<p class="texto destaque">Aprendendo atributos globais.</p>
<p class="texto">Mais um exemplo.</p>
```

### `style` e `title`

```html
<p style="color: blue;">Texto azul.</p>
<p title="HyperText Markup Language">HTML</p>
```

### `lang` e `hidden`

```html
<p lang="en">Hello, world!</p>
<p hidden>Conteúdo oculto.</p>
```

### `data-*` e `contenteditable`

```html
<button data-curso="fullstack">Ver curso</button>
<p contenteditable="true">Clique aqui e edite este texto.</p>
```

## Para lembrar

- Prefira organizar o CSS em arquivos separados.
- Editar com `contenteditable` não salva automaticamente as alterações.

## Referência

[MDN Web Docs — Atributos Globais](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Reference/Global_attributes)