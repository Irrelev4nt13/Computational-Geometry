# Computational-Geometry
📐Implementation of various convex hull algorithms as well as Voronoi diagrams, Delaunay triangulation and geometric search.

## Convex Hull Algorithms
### Incremental Convex Hull Algorithm
The Incremental algorithm is implemented here to compute the convex hull of a set of points in 2D space.

### Divide and Conquer Convex Hull Algorithm
Divide and Conquer algorithm, to efficiently find the convex hull of a set of points, but instead of bridge it uses the Incremental to merge the two sets.

### Gift Wrapping Convex Hull Algorithm
The Gift Wrapping algorithm, also known as the Jarvis March algorithm, is implemented here to calculate the convex hull of a set of points.

### Quickhull Algorithm with scipy for 2D and 3D Convex Hull
The Quickhull algorithm is implemented using the scipy library to find the convex hull of 2D and 3D point sets.

## Space-Partitioning
### KD-Tree Implementation
* Build a KD-Tree from a set of points.
* Search for points that fall within a given rectangular region.

### Voronoi Diagram and Delaunay Triangulation Visualization
The Voronoi diagram and Delaunay triangulation visualization feature allows you to visualize the Voronoi diagram and Delaunay triangulation based on the generated points.
