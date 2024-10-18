# rust-design-pattern-guru

## singleton

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

