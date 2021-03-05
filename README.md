# icviewer

You need to generate [ELK Graph](https://www.eclipse.org/elk/documentation/tooldevelopers/graphdatastructure.html) from Firrtl file through [layered-firrtl](https://github.com/easysoc/layered-firrtl).

If you want to see the ELK Graph directly, you can use [this](https://rtsys.informatik.uni-kiel.de/elklive/elkgraph.html) online service, it's open source https://github.com/kieler/elk-live .

This project can rendering [Sprotty Graph](https://github.com/eclipse/sprotty) files as an interactive diagram to represent Chisel generated Firrtl circuits.  It is used as an external renderer for the IntelliJ [easysoc-diagrammer](https://plugins.jetbrains.com/plugin/16255-easysoc-diagrammer) plugin.  

It is highly recommended to using the [IntelliJ plugin](https://plugins.jetbrains.com/plugin/16255-easysoc-diagrammer) to view your circuit. It supports interactive viewing of the sub-modules by double-click. In addition, it supports back navigation, zoom view, export SVG format and other functions.