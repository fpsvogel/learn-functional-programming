<!-- omit in toc -->
# Learn functional programming: a Rubyist's list

Hi! I'm on a journey to learn functional programming (FP). Won't you join me?

If you notice any broken links here, please let me know by [opening an issue](https://github.com/fpsvogel/learn-functional-programming/issues/new).

<!-- omit in toc -->
## Table of contents

- [Roc](#roc)
  - [Community](#community)
  - [Learning](#learning)
  - [Reference](#reference)
  - [Exercises](#exercises)
  - [Projects](#projects)
- [FP in non-FP languages](#fp-in-non-fp-languages)
  - [TypeScript](#typescript)
  - [Ruby](#ruby)

## Roc

I originally started with Haskell, but it was a bit of a slog. [The raw file of this list](https://raw.githubusercontent.com/fpsvogel/learn-functional-programming/main/README.md) still contains commented-out sections for Haskell and Elixir (another one I *probably* won't learn).

Roc seems like an easier place to start because it's intentionally small and tries to incorporate some of the strengths of dynamic languages, while being fully statically typed.

### Community

- [Roc Zulip Chat](https://roc.zulipchat.com/)

### Learning

- [x] [Official tutorial](https://www.roc-lang.org/tutorial)
- [x] [Introduction to Roc (video)](https://www.youtube.com/watch?v=7R204VUlzGc)
- [ ] [Abilities](https://www.roc-lang.org/abilities)

### Reference

- [Examples](https://www.roc-lang.org/examples)
- Docs: [builtins](https://www.roc-lang.org/builtins), [basic-cli](https://www.roc-lang.org/packages/basic-cli/0.15.0)
- [Roc packages](https://hasnep.github.io/roc-packages/)

### Exercises

- [ ] [Exercism - Roc](https://exercism.org/tracks/roc)
- [ ] [Advent of Code](https://adventofcode.com) with [Roc template](https://github.com/lukewilliamboswell/aoc-template) and [Roc solutions for 2023](https://github.com/scott2000/advent-of-code-2023)

### Projects

- [ ] Make a text-based game.

<!-- ## Haskell

Because it's often recommended for learning FP in its purest form.

### Community

- [Functional Programming Discord server](https://discord.com/invite/K6XHBSh)
- [Haskell - Community page](https://www.haskell.org/community/)

### Reference

- [Hoogle](https://hoogle.haskell.org/). Since its search uses a query param, you can add a search keyword to your browser to let you quickly search from the address bar, for example `hs partition` would take you to [https://hoogle.haskell.org/?hoogle=partition](https://hoogle.haskell.org/?hoogle=partition)

### Courses, etc.

- [x] [Try Haskell](https://tryhaskell.org)
- [ ] [Haskell MOOC](https://haskell.mooc.fi/) and exercise solutions ([1](https://github.com/tinfoil-knight/haskell-mooc), [2](https://github.com/mikkom/haskell-mooc/tree/master/exercises), [3](https://github.com/dandax123/haskell-mooc-solutions), [4](https://github.com/bobbrahms/haskell-mooc/tree/master/exercises), [5](https://github.com/Qualia91/haskell-mooc/tree/master/exercises), [6](https://github.com/davide-butera/haskell-mooc/tree/master/exercises), [7](https://github.com/lucastarche/haskell-mooc/tree/master/exercises), [8](https://github.com/shyba/haskell-mooc/tree/master/exercises))
- [ ] [Well-Typed - Introduction to Haskell](https://teaching.well-typed.com/intro/)
- [ ] [Wikibooks - Haskell](https://en.wikibooks.org/wiki/Haskell)
- [ ] [System F - Functional Programming Course](https://github.com/system-f/fp-course#progression) and [exercise solutions](https://github.com/tonymorris/fp-course/tree/master/src/Course)
- [ ] [What I Wish I Knew When Learning Haskell](https://smunix.github.io/dev.stephendiehl.com/hask/tutorial.pdf) ([Markdown source](https://github.com/sdiehl/wiwinwlh/blob/master/tutorial.md))
- [ ] [Haskell for Imperative Programmers](https://www.youtube.com/playlist?list=PLe7Ei6viL6jGp1Rfu0dil1JH1SHk9bgDV) (videos)
- [ ] [Implement With Types, Not Your Brain!](https://reasonablypolymorphic.com/blog/typeholes/)
- [ ] 💲[Soar with Haskell](https://www.amazon.com/Soar-Haskell-beginners-functional-programming/dp/1805128450)
- [ ] [thoughtbot - Maybe Haskell: Programming without Null](https://github.com/thoughtbot/maybe_haskell)
- [ ] [The Haskell Phrasebook](https://typeclasses.com/phrasebook)
- [ ] [Typeclassopedia](https://wiki.haskell.org/Typeclassopedia)
- [ ] 💲[Thinking with Types](https://leanpub.com/thinking-with-types)
- [ ] 💲[Algebra-Driven Design](https://leanpub.com/algebra-driven-design)
- [ ] 💲[Effective Haskell](https://pragprog.com/titles/rshaskell/effective-haskell/)
- [ ] 💲[Haskell (almost) Standard Libraries](https://leanpub.com/haskell-stdlibs)
- [ ] 💲[Haskell in Depth](https://www.manning.com/books/haskell-in-depth)
- [ ] Explore language extensions
  - [ ] [GHC User's Guide - Language extensions](https://downloads.haskell.org/ghc/latest/docs/users_guide/exts.html) (current)
  - [ ] [A Guide to GHC's Extensions (2018)](https://limperg.de/ghc-extensions/)
  - [ ] [An Opinionated Guide to Haskell in 2018](https://lexi-lambda.github.io/blog/2018/02/10/an-opinionated-guide-to-haskell-in-2018/#any-flavor-you-like)
  - [x] For records: [my findings](https://github.com/fpsvogel/haskell-mooc/blob/141495e219cb8c48564de7da49ddb55d45830daa/exercises/Set5a.hs#L6-L14) plus [a note on a false compiler warning](https://github.com/fpsvogel/haskell-mooc/blob/141495e219cb8c48564de7da49ddb55d45830daa/exercises/Set5a.hs#L99-L107)
- [ ] Explore performance optimization
  - [ ] [StackOverflow answer on intermediate compiler output](https://stackoverflow.com/a/59338472)
  - [ ] [Doc on debugging the compiler](https://downloads.haskell.org/ghc/latest/docs/users_guide/debugging.html#dumping-out-compiler-intermediate-structures)
  - [ ] [Doc on code optimization](https://downloads.haskell.org/ghc/latest/docs/users_guide/using-optimisation.html)
  - [ ] [Haskell Wiki - Performance/GHC](https://wiki.haskell.org/Performance/GHC)
  - [ ] [FP Complete - Performance section in the Applied Haskell Syllabus](https://tech.fpcomplete.com/haskell/syllabus/#performance)
  - [ ] "Core" and "Asm" views in [Haskell Playground](https://play.haskell.org/saved/w9UU3xLx), plus more options in [godbolt](https://godbolt.org/)

### Exercises

- [ ] [Exercism - Haskell](https://exercism.org/tracks/haskell)
- [ ] [hw-koans](https://github.com/haskell-works/hw-koans)
- [ ] [Advent of Code](https://adventofcode.com) and Haskell solutions: [1](https://github.com/RossPaterson/advent-of-code), [2](https://github.com/glguy/advent), [3](https://github.com/Javran/advent-of-code/tree/master/src/Javran/AdventOfCode), [4](https://github.com/yarrick/advent), [5](https://github.com/Prillan/adventofcode-solutions), [6](https://github.com/Sheinxy/Advent-Of-Code), [7](https://github.com/slotThe/advent)
  - Haskell templates for Advent of Code: [1](https://github.com/mstksg/advent-of-code-dev), [2](https://github.com/Martinsos/aoc-2023-haskell-template), [3](https://github.com/samcoy3/advent-of-code-template), [4](https://github.com/lsmor/template-advent-of-code), [5](https://github.com/pabloariasal/advent-of-code-2021-haskell), [6](https://github.com/ambroslins/AdventOfCode), [7](https://github.com/bereal/AdventOfCodeHaskell)
- [ ] [HackerRank - Functional Programming track](https://www.hackerrank.com/domains/fp)
- [ ] [nested-map-reduce-traversal challenge](https://github.com/josevalim/nested-map-reduce-traversal) ([discussion](https://discourse.haskell.org/t/beautiful-functional-programming/7411), [Haskell solutions](https://github.com/josevalim/nested-map-reduce-traversal/tree/master/haskell), more Haskell solutions: [1](https://gist.github.com/TristanCacqueray/fc8fb5cbba7a0391341e73b80a90b2e8), [2](https://gist.github.com/goldfirere/ed1450872afd324ed656e2807b8dfcc0), [3](https://github.com/danielc777888/toy-problems/blob/main/nested-map-reduce-traversal/Recursion.hs), [4](https://gist.github.com/lazamar/305e8808f8975258f6acea4d20fd3405))
- [ ] [snake-fury](https://github.com/lsmor/snake-fury)

### Projects

- [ ] Make a text-based game.
  - Guides:
    - [ ] <http://jackkelly.name/blog/archives/2022/05/28/text-mode_games_as_first_haskell_projects/index.html>
    - [ ] <https://medium.com/codex/developing-a-video-game-in-haskell-e8259050e4dc>
    - [ ] <https://whatthefunctional.wordpress.com/2018/03/07/making-a-text-adventure-in-haskell-part-1/#comments>
    - [ ] <https://www.youtube.com/watch?app=desktop&v=WLYN7sUDm7Y>
    - [ ] <https://haskell-via-sokoban.nomeata.de/>
  - Examples:
    - "Haskell Program to Play the Blackjack Card Game" in [Haskell Tutorial and Cookbook](https://markwatson.com/opencontent/haskell-cookbook.pdf)
    - <https://codereview.stackexchange.com/questions/159069/haskell-text-adventure-game>
    - <https://github.com/emanuelfakh/Game_Haskell>
    - <https://github.com/rklyne/haskell-text-adventure>
    - <https://github.com/jensdanb/Pong2>
    - <https://github.com/jasonstolaruk/CurryMUD>
    - <https://github.com/Qqwy/haskell-snek>
  - See also the Haskell Wiki pages [Game Development](https://wiki.haskell.org/Game_Development) and [Applications and libraries/Games](https://wiki.haskell.org/Applications_and_libraries/Games)

### Articles

- [ ] [Haskell mini-patterns handbook](https://kowainik.github.io/posts/haskell-mini-patterns)
- [ ] [Competitive programming in Haskell](https://byorgey.github.io/blog/). See also [CPHaskell](https://github.com/anurudhp/CPHaskell).
- [ ] [The Power of Tiny DSLs](http://jackkelly.name/blog/archives/2020/04/03/the_power_of_tiny_dsls)
- [ ] [The IO Monad for People who Simply Don't Care](http://blog.sigfpe.com/2007/11/io-monad-for-people-who-simply-dont.html)
- [ ] [All About Strictness](https://tech.fpcomplete.com/blog/2017/09/all-about-strictness/)
- [ ] [Make invalid states unrepresentable](http://h2.jaguarpaw.co.uk/posts/make-invalid-laziness-unrepresentable/) and [related discussion](https://www.reddit.com/r/haskell/comments/zz87px/comment/j2ic1lk/)

### Dependent types, type theory

I probably won't get into this, but I'm saving these just in case.

- [ ] [Liquid Haskell](https://www.tweag.io/blog/2022-01-19-why-liquid-haskell/)
- [ ] [Idris docs](https://idris2.readthedocs.io/en/latest/tutorial/index.html)
- [ ] 💲[Type-Driven Development with Idris](https://www.manning.com/books/type-driven-development-with-idris)
- [ ] [Agda Wiki](https://wiki.portal.chalmers.se/agda/pmwiki.php)
- [ ] [agda2hs](https://agda.github.io/agda2hs/)
- [ ] [Learn You an Agda](http://learnyouanagda.liamoc.net/pages/introduction.html)
- [ ] 💲[Verified Functional Programming in Agda](https://dl.acm.org/doi/book/10.1145/2841316)
- [ ] [Programming Language Foundations in Agda](https://plfa.github.io/)
- [ ] 💲[Types and Programming Languages](https://www.cis.upenn.edu/~bcpierce/tapl/)

### More resources

- [awesome-learning-haskell](https://github.com/tweag/awesome-learning-haskell)
- ["Resources" section in The Haskell Guide](https://haskell-docs.netlify.app/resources/resources/)
- [Haskell Books](https://www.extrema.is/articles/haskell-books)
- [Haskell - Documentation (books, courses, etc.)](https://www.haskell.org/documentation/) -->

<!-- ## Elixir

Because it's a different take on FP: less pure and with unique advantages offered by the BEAM platform. (But these advantages are not yet completely realized, i.e. it's a work in progress, according to the talk [The Soul of Erlang & Elixir](https://www.youtube.com/watch?v=JvBT4XBdoUE).)

### Community

- [Elixir Status](https://elixirstatus.com/)

### Courses, etc.

- [ ] [Elixir School](https://elixirschool.com/en)
- [ ] [DockYard Academy curriculum](https://github.com/DockYard-Academy/curriculum)
- [ ] 💲[Elixir for Programmers](https://codestool.coding-gnome.com/courses/elixir-for-programmers-2)
- [ ] 💲[From Ruby to Elixir](https://pragprog.com/titles/sbelixir/from-ruby-to-elixir)
- [ ] 💲[Phoenix on Rails](https://phoenixonrails.com/) ($10 discount code [here](https://elixirforum.com/t/phoenix-for-rails-developers/54624/18))
- [ ] 💲[Elixir in Action](https://www.manning.com/books/elixir-in-action)

### Exercises

- [ ] [Elixir Koans](https://github.com/elixirkoans/elixir-koans)
- [ ] [Exercism - Elixir](https://exercism.org/tracks/elixir)

### Projects

- [ ] Build a [SpaceTraders](https://spacetraders.io/) Phoenix app

### More resources

- ["Learning" page on the Elixir site](https://elixir-lang.org/learning.html) -->

## FP in non-FP languages

Because my goal in learning FP is not to switch to a different stack, but to become a better programmer in the languages that I use now.

### TypeScript

- FP libraries: [Purify](https://gigobyte.github.io/purify/), [Effect](https://effect.website/), [fp-ts](https://gcanti.github.io/fp-ts/)
- [TypeScript for Functional Programmers](https://www.typescriptlang.org/docs/handbook/typescript-in-5-minutes-func.html)
- [How to Write TypeScript Like a Haskeller](https://serokell.io/blog/typescript-for-haskellers)

### Ruby

- "Functional lite": prefer immutability and avoid side effects
  - [Avoid Mutation — Functional Style in Ruby](https://www.rubypigeon.com/posts/avoid-mutation-functional-style-in-ruby/)
  - [Boundaries](https://www.destroyallsoftware.com/talks/boundaries)
  - Sandi Metz ([source](https://dev.to/sandimetz/comment/255m)): "I only have a small bit of experience with functional languages, so I don't get to have much of an opinion. I can say, however, that immutability and no side-effects are great ideas, and that I've borrowed them for my OO. My initial goal for every new object I write is that it not change, and that it not have side effects. This obviously can't suit every object, but I've been pleasantly surprised about how much can be done under these constraints, and how much the constraints simplify code."
  - Avdi Grimm ([source](https://web.archive.org/web/20201009182546/https://github.com/yct21/observatory/issues/93)): "Functional programming ideas about preferring immutability and isolating interactions with the outside world can help us avoid the worst pitfalls of procedural and object-oriented coding. But trying to program in a *'fully FP'* style in Ruby can be like paddling a kayak with a canoe paddle. Upstream. […] Your best bet for effective development is to learn to 'code with the grain' [of the language you're using]. And when you get right down to it, Ruby's grain is object-oriented."
- Hanami/dry-rb ecosystem
  - [This blog series by Tim Riley](https://www.icelab.com.au/notes/conversational-rom-rb-part-2-types-associations-and-update-commands) is a good introduction. The linked article is the last one; scroll to the bottom to see a list of all the posts in the series.
  - Learn the [Hanami](https://hanamirb.org/) framework with [Hanami Mastery](https://hanamimastery.com) and example apps found in GitHub repo searches ([1](https://github.com/search?q=hanami+example+pushed%3A%3E2022-01-01&type=repositories), [2](https://github.com/search?q=hanami+app+pushed%3A%3E2022-01-01&type=repositories), [3](https://github.com/search?q=hanami+application+pushed%3A%3E2022-01-01&type=repositories), [4](https://github.com/search?q=hanami+software+pushed%3A%3E2022-01-01&type=repositories)).
  - Explore [dry-rb](https://dry-rb.org/) gems.
