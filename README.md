# LUNR, ELASTICLUNR, ELM

Example project which shows how to use ports in elm with a js library. 

This demo indexes the full text of Moby Dick, with each paragraph in a separate record. You can find good search terms by looking [here](https://www.gutenberg.org/files/2701/2701-h/2701-h.htm).

The search libraries:

* [LUNR](https://lunrjs.com/)
* [ELASTIC LUNR](http://elasticlunr.com/)

The Demos:

* [LUNR DEMO](https://tommymessbauer.github.io/elm-ports-lunr/docs/lunr/index.html)
* [ELASTIC LUNR DEMO](https://tommymessbauer.github.io/elm-ports-lunr/docs/elasticlunr/index.html)


# GET STARTED

This repo should be cloned, then renamed/re-initialized for use in a component.

```bash
git clone git@github.com:tommymessbauer/elm-ports-lunr.git your_folder
cd your_folder
yarn run reinstall
yarn run start
```

After starting, a local dev server with HMR will be running at localhost:3000. Both examples are available at these urls.

* [http://localhost:3000/lunr/](http://localhost:3000/lunr/)
* [http://localhost:3000/elasticlunr/](http://localhost:3000/elasticlunr/)


