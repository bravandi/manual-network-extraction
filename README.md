Web Based Interactive Directed Graph Creator (D3 Javascript)
======================

This is an extended version of directed-graph-creator developed by Colorado Reed
 (Thank you!): https://github.com/cjrd/directed-graph-creator

Interactive tool for creating directed graphs, created using d3.js. The graph can be created on a background image.

My contributions:
* added labels to the edges.
* ctrl+click to change a node label.
* background image

Operation:

* download/upload graph in JSON format
* drag/scroll to translate/zoom the graph
* shift-click on graph to create a node
* shift-click on a node and then drag to another node to connect them with a directed edge
* ctrl-click on a node to change its title
* click on node or edge and press backspace/delete to delete

<p align="center">
<img src="https://github.com/bravandi/directed-graph-creator/blob/master/sample_picture.PNG?raw=true" alt="Metacademy Logo" height="350px"/>
</p>


Run:

* `python -m SimpleHTTPServer 8000`
* navigate to http://127.0.0.1:8000

Github repo is at https://github.com/bravandi/directed-graph-creator

License: MIT/X







