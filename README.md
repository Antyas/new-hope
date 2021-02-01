![new-hope logo](https://cdn.rawgit.com/maroun-baydoun/new-hope/gh-pages/img/github.svg)

# Esperanto tokenizer for Deno
This is a fork from https://github.com/maroun-baydoun/new-hope

----
## Esperanto?
Esperanto is a constructed language created by L. L. Zamenhof in 1887. Find out more [here](https://en.wikipedia.org/wiki/Esperanto) and check out the great [Duolingo Esperanto Course](https://www.duolingo.com/course/eo/en/Learn-Esperanto-Online).

----
## Usage

```js
import { split, tokenize } from 'https://deno.land/x/new_hope/mod.ts';

const words = split("Mi parolas Esperanton.");
const tokens = tokenize(words);
```
