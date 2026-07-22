# PCST-Graphs
Co-citation networks of pitch-class set theory literature, divided by decade.

## Purpose

This repository accompanies the research project *Graphing Authority: A Scientometric History of Pitch-Class Set Theory*. It contains the pilot implementation used to validate the methodology described in the proposal. Specifically, it provides the co-citation networks constructed for the 1960s and the 1970s, together with the files required to inspect and reproduce the graph structures.

## Repository contents

* [`1960s.xml`](./1960s.xml) – co-citation network for the 1960s
* [`1970s.xml`](./1970s.xml) – co-citation network for the 1970s
* documentation

## Preview

![1960s](Images/1960s.jpg "The 1960s")

*Figure 1. Co-citation network for the 1960s.*

![1970s](Images/1970s.jpg "The 1970s")

*Figure 2. Co-citation network for the 1970s.*

## Software

The graphs are stored in GraphML/XML format and can be opened directly with yEd Graph Editor (recommended), Gephi, or other GraphML-compatible software.

## What the graphs represent

Nodes correspond to cited publications. Edges represent co-citation relationships. Edge weights indicate the number of articles citing the two works together.

These graphs constitute a pilot implementation demonstrating the methodology described in the accompanying research proposal.

## Citation

If referring to these materials, please cite the accompanying research project and this repository.
