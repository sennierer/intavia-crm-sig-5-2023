## InTaVia
- H2020 project<!-- .element: class="fragment" -->
- 4 countries: Slovenia, Austria, The Netherlands and Finland<!-- .element: class="fragment" -->
- started 2020-11-01<!-- .element: class="fragment" -->
- less than 1 year to go<!-- .element: class="fragment" -->

+++

## Goals
- integrate 4 national biographical dictionaries<!-- .element: class="fragment" -->
- further enrich them (LOD & NLP)<!-- .element: class="fragment" -->
- provide a online platform for Visual Analytics on top of the data<!-- .element: class="fragment" -->

+++

## Research questions
- is it possible to integrate different prosopographical resources and create a almost homogenous resource?<!-- .element: class="fragment" -->
- can we use NLP and/or the LOD to enrich the less rich data points?<!-- .element: class="fragment" -->
- does VA provide useful means to analyse such a dataset?<!-- .element: class="fragment" -->

+++

## Techstack
- FastAPI (including pydantic for type checking)<!-- .element: class="fragment" -->
- Blazegraph as DB backend<!-- .element: class="fragment" -->
- Jinja2 for creating SPARQL templates<!-- .element: class="fragment" -->
- Redis for caching<!-- .element: class="fragment" -->
