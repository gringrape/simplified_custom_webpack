# simplified_custom_webpack
make my own webpack for better understanding



## Summary of 'Build Your Own Webpack'

- What is bundler? 
- Dependency Graph
  - read .js file
  - construct  AST
  - dependency path, id mapping
  - traverse, BFS of AST
    - import statement
    - dependencies list
    - *) transpiling using babel
- Bundler
  - module -> function
    - each module must have its own scope
  - function array
  - string of code that execute each item in the function array



## References

[Ronen Amiel - Build Your Own Webpack](https://www.youtube.com/watch?v=Gc9-7PBqOC8) 