# Automotive Software communities as a Sankey Diagram

Attempt to visualize relationships/"artifact flow" between the different automotive software communities.
There is no claim to completeness or correctness, or even usefulness.

[Sankey-style SDV map](https://anotherdaniel.github.io/sdv-sankey/)

## Code origins

The majority of the javascript code is lifted from [oberservable/d3](https://observablehq.com/@d3/sankey@278)

Idea for this scenario is to have a very simple, minimal diagram-generating web page that allows for experimenting with the usefulness of a Sankey-style visualization for the subject matter.

## Running

Any web server should do - minimal and lightweight:

- install npm and npx
- in the directory where the html and csv files are located, run `npx serve`
- point your browser at localhost:3000

## Working with the data

This is also very simple - open data.csv in your favorite editor, and begin editing. Reload the browser page to see your changes.

&nbsp;

---

__Author__: Daniel Krippner (dk.mailbox@gmx.net)

__License note__: code origin is documented in `index.html`. The repository license applies to any new or modified content, where applicable.
