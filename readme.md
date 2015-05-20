
Babel
  - fetch, including streams

Store
  - one big store for big component (not small ones) (Aartem Tretyak)
  - store as a Domain entity
  - compose both prev variants

Webpack
 - bundle (image is a part of component)
 - modules, including ES6 modules
 - multi entry points
   - build shared between entry 1, entry 2
   - build entry 1, entry 2
 - Hot reload API

react lifecycle <- we can diff here by ref

immutable data structures (immutable.js?)

Many mutators problem

export function touchAndPrint{
  var data = {key: "value"};
  touchFn(data);
  console.log(data.key);// <- data changed ???
}


react adds data attribute

The hash array mapped trie - индекс не хранится в самом графе, вычисляется до самой вершины
Directed async graph - DAG
react from ALF-er https://github.com/ALF-er/reactjs-and-cutting-edge-stack/tree/presentation
