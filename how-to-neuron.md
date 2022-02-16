---
date: 2022-01-21T15:27
tags:
    - tutorial
---

# How to neuron

## Keys

- Search all zettels: `gzz`
- Search backlinks in current zettel: `gzb`
- Search uplinks in current zettel: `gzu`
- Create new zettel: `gzn`
- Search content in all zettels: `gzs`
- Insert ID of prev. visited zettel: `gzl`
- Insert ID of prev. visited zettel and folgezettel: `gzL`
- Open zettel under cursor: `<CR>` (enter in my case)
- Show help: `gz?`

## Heterarchy / Overview

- Use `gzL` if the zettel for index and structural notes
- Use `gzl` for *normal* links between zettels
- Make use of tags. But do not use **more than 3 tags** on one zettel

Hence, the following structure of a zettel should be used:
```
---
date: ....
tags:
  - tag1
  - tag2
---

# Title of the zettel

Parent: link (gzl) to parent 

## Content section 1

Some content

- reference (gzL) if there is sub-content with folgezettel

## Content section 2 

Some more content

- reference (gzL) if there is sub-content with folgezettel
```
