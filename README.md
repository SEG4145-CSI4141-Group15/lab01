# Lab 1: Interactive traffic lights

## Part 1: traffic lights for motor vehicle

The following is **one cycle**:

| # Phase | RED LED | YELLOW LED | GREEEN LED | DURATION (s)
|----------|----------|----------|-----------|------------|
| 1   | ON   |  OFF  |  OFF | 10 |
| 2   | ON   |  ON   |  OFF | 2 |
| 3   | OFF  |  OFF  |  ON  | 10 |
| 4   | OFF  |  ON   |  OFF | 3 |

## Part 2： Interactive traffic lights

The following is **one cycle**:

| # Phase | RED MOTORIST LED | YELLOW MOTORIST LED | GREEEN MOTORIST LED | DURATION (s) | RED PEDESTRIAN LED | GREEEN PEDESTRIAN LED |
|----------|----------|----------|-----------|------------|-----------|------------|
| 1   | OFF  |  OFF  |  ON | (stay on this phase until the button is pushed) | ON | OFF|
| 2   | OFF  |  ON   |  OFF | 3  | ON  | OFF |
| 3   | ON   |  OFF  |  OFF | 1  | ON  | OFF |
| 4   | ON   |  OFF  |  OFF | 10 | OFF | ON  |
| 5   | ON   |  OFF  |  OFF | 1  | ON  | OFF |
| 6   | ON   |  ON   |  OFF | 2  | ON  | OFF |
