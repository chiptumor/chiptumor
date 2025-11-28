# Wuddup!

Call me Chip.

I use Github for various projects, but I'm still getting the hang of things.

I have a whole website about me at [chiptumor.github.io](https://chiptumor.github.io/?s). Check me out!

## Project hierarchy

I'm constantly working on several projects at a time&mdash;that is, _one_ project at a time, but with another in mind.
 
Each project's dependencies are identified by an arrow pointing to it.

```mermaid
flowchart TD

chiptumor/jekyll-theme-github-wiki --> |Wiki theme| chipfucker/booru-abuse
chiptumor/jekyll-gfm-alerts --> |Alerts plugin| chiptumor/jekyll-theme-github-wiki
chipfucker/booru-abuse --> |Booru API| chipfucker/chip63
chipfucker/booru-abuse --> |Booru API| chipfucker/marlie
chipfucker/marlie --> |Templated| chiptumor/chipbot
```
