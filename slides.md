## Elm is&hellip;

- The best of functional programming in your browser <!-- .element: class="fragment" -->
- Usable — Targeted towards JavaScript developers <!-- .element: class="fragment" -->
- Inclusive — Evan Czaplicki: "Let's be mainstream" <!-- .element: class="fragment" -->
- Reliable – No runtime exceptions - compilation finds errors <!-- .element: class="fragment" -->
- Fast — Faster than React <!-- .element: class="fragment" -->
- Inspiring — Angular 2.0, Brendan Eich <!-- .element: class="fragment" -->

---

## Example

```elm
import Html exposing (span, text)
import Html.Attributes exposing (class)

main =
  span [class "welcome-message"] [text "Hello, World!"]
```
---

# Don't fear the type system
It's not like Java

---

```elm
import Graphics.Element exposing (..)
import Mouse


main =
  Signal.map show Mouse.position
```

Catching type errors at compile time makes code more reliable (vs runtime)

---

## Binary Tree
```elm
type Tree a = Empty | Node a (Tree a) (Tree a)
```

???

Imagine doing this in Java. One super class and two sub classes just to define a tree in the first place!

Imagine JS. It is not quite as bad at first,

but imagine trying to refactor the resulting code later if you need to change the core representation.

Sneaky breakages everywhere!

---

### Dev Environment and workflow
- Atom
```
apm install linter linter-elm-make language-elm
```
- Vim
  - https://github.com/ElmCast/elm-vim

- Elm Brunch
  - https://github.com/ivanoats/elm-brunch-starter

---

## Demonstration of
## Elm Brunch

---

### Other Elm Resources

- [Pragmatic Studio](https://pragmaticstudio.com/elm) video tutorials
- [Elm Discuss](https://groups.google.com/forum/?fromgroups#!forum/elm-discuss) mailing list
- [#elm](seattlehacks.herokuapp.com) channel on seattlehacks Slack
- [Elmcasts.io](http://elmcasts.io)

---

### People to follow:
- [Evan Czaplicki](https://twitter.com/evancz)
- [Richard Feldman](https://twitter.com/rtfeldman)
- [Yan Cui](https://twitter.com/theburningmonk)
- [Pete Vilter](https://twitter.com/)
- [Ivan Storck](https://twitter.com/ivanoats)

---
### Organizations on Twitter:
- [Elm](https://twitter.com/elmlang)
- [ElmSeattle](https://twitter.com/elmseattle)
