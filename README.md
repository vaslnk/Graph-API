# Graph API
A fully functional Java library that provides various classes and methods that allow users to implement graphs.

![Imgur](http://i.imgur.com/NH50uXn.jpg)

Practical examples with Methods

In order to use methods and classes from this package you need to import them in your files. If you assume that you put all the files of this package in a directory called "graph", here are some examples of importing classes from this library:
```
    import graph.LabeledGraph;
    import graph.DirectedGraph;
    import graph.DepthFirstTraversal;
```
a. Declaring Directed graph: 
```
UndirectedGraph ug = new UndirectedGraph();
```

b. Declaring Undirected graph: 
```
DirectedGraph dg = new DirectedGraph();
```

c. Adding vertices to graph. (Doesn't really matter whether we take directed or Undirected Graph).
```
        UndirectedGraph ug = new UndirectedGraph();
        ug.add();
        ug.add();
        ug.add();
        ug.add();
        ...
```
d. Adding edges to graph. In this example we will add an edge between vertices 1 and 3.
```
        DirectedGraph dg = new DirectedGraph();
        dg.add();
        dg.add();
        dg.add();
        dg.add(1, 3);
        ...
 ```
e. Removing a vertex from a graph. (Same works for DirectedGraphs too).
```
      UndirectedGraph ug = new UndirectedGraph();
      ug.add(); 
      ug.add();
      ug.add();
      ug.remove(1);
      ug.remove(3);
```
f. Removing an edge from two vertices. In this example we will remove an edge from vertices 1 and 3.
```
        DirectedGraph dg = new DirectedGraph();
        dg.add();
        dg.add();
        dg.add();
        dg.add(1, 3);
        dg.remove(1, 3);
```
