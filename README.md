# Frontend Developer challenge

![recruitment.png](https://s22.postimg.org/8cp8tc3rl/challange_en.png)

## The task

You need to create graph editing and pathfinding web-based application.

## Spec

- Editor area must be adaptable to viewport size
- By clicking on workspace area user enter in create or edit mode
- Create mode is triggered when user click on empty area
  - Settings of tool are determined by toolbox which presents as a floating window
- Edit mode is triggered when user clicks on existing object
  - Toolbox must handle current object properties
  - There are two types of objects: nodes and edges
  - User must be able to create, move, modify and delete objects
  - Edge can be added only between two nodes
  - Deletion of node leads to deletion of all adjoining edges
- There must be an option to mark node as start or end point of a route
  - When two nodes are marked, the optimal path must be calculated and highlighted
  - Calculation results must be put in a cache
  - As optional feature direction of the route can be animated

## Requirements

The only programming language is JavaScript.
Application source code must be published on one of public source code hosting.
The application must be deployed to a cloud.
There must be a _README.md_ with instructions how to configure and run it.
You free to use tools and frameworks of your choice.
Quality is preferable to the count of features.
All kind of automation including QA is a huge advantage.

Good luck!
