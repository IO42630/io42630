### [git.plexworlds.com](http://git.plexworlds.com)

(non-public - request user:password via contact@olexyn.com)



### `min` repos

- overview of `min` repos and what they are used for:
  - [`min-root`](https://github.com/IO42630/min-root)
    - to be used in `pom.xml` -> `<parent>` of "plain" jdk projects
  - [`min-root-spring`](https://github.com/IO42630/min-root-spring)
    - to be used in `pom.xml` -> `<parent>` of "spring" projects
  - [`min-bom`](https://github.com/IO42630/min-bom) 
    - bom-pom
    - to be used in `pom.xml` -> `<dependencyManagement>`
  - [`min-log`](https://github.com/IO42630/min-log)
    - pretty log printing
    - to be used in apps where we rely on the log for visualizing state
  - [`min-prop`](https://github.com/IO42630/min-prop)
    - wraps  `java.util.Properties` for convenience
    - to be used whenever we want agnostic handling of `.properties` files
