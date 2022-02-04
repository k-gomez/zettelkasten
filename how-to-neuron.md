---
date: 2022-01-21T15:27
---

# How to neuron
Go to [[index]]

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

## Heterarchy

- Use `gzL` if the zettel should be a cluster and has folgezettel
- Use `gzl` for *stupid* links

Hence, the following structure of a zettel should be used:
```
---
date: ....
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
