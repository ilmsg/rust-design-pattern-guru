# Rust Design Pattern GURU

## Singleton

[https://refactoring.guru/design-patterns/singleton/rust/example](https://refactoring.guru/design-patterns/singleton/rust/example)


    $ cargo run [Options]

    -p, --pacage [<SPEC>] Package wth the target to run
    -q, --quiet Do not print cargo log messages


**example 1:**

    $ cargo run -p singleton-safe-single -q

result:

    Final state: 1
    Final state: 2
    Final state: 3
    Final state: 4

---
**example 2:**

    $ cargo run -p singleton-lazy -q

result:

    Called 3

---
**example 3:**

    $ cargo run -p singleton-mutex

result:

    Called 3 times: [1, 1, 1]
    New single object: [3, 4, 5]

---
## Prototype

[https://refactoring.guru/design-patterns/prototype/rust/example](https://refactoring.guru/design-patterns/prototype/rust/example)

** example 1:**

prototype ในภาษา rust จะมี build-in ที่เป็น std::clone::Clone ( #[derive(Clone)] )

    $ cargo run -p prototype-buildin-clone -q

result:

    Circle 1: 10, 15, 10
    Circle 2: 10, 15, 77

---
## Factory Pattern In Rust

[https://refactoring.guru/design-patterns/factory-method/rust/example](https://refactoring.guru/design-patterns/factory-method/rust/example)

** example 1:**

