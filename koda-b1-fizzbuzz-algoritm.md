# Algoritma

## Flowchart

```mermaid
    flowchart TD
    start((start))
    init["i <-- 1"]
    check{"i <= 10"}
    check2{"i % 2 == 0"}
    increment["i++"]
    output["FizzBuz"]
    output2["i"]
    finish((("finish")))

    start --> init
    init --> check
    check -- yes --> check2
    check -- no --> finish
    check2 -- yes --> output
    check2 -- no --> output2
    output & output2--> increment
    increment --> check
```

## Pseudocode

```pseudocode
    DECLARE i : INT
    DECLARE hasil : STRING

    hasil <-- "FizzBuzz"

    FOR i <- 1 TO 10
        IF i % 2 == 0 THEN
            OUTPUT, hasil
        ELSE
            OUTPUT, i
        ENDIF
    NEXT i
```
