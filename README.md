# COMP110 Worksheet 4

Please edit this README.md file with your answers to the worksheet questions.

## Question 1

### a
| A     | B     | C     | A and B and not C |
|-------|-------|-------|-------------------|
| FALSE | FALSE | FALSE | FALSE             |
| FALSE | FALSE | TRUE  | FALSE             |
| FALSE | TRUE  | FALSE | FALSE             |
| FALSE | TRUE  | TRUE  | FALSE             |
| TRUE  | FALSE | FALSE | FALSE             |
| TRUE  | FALSE | TRUE  | FALSE             |
| TRUE  | TRUE  | FALSE | TRUE              |
| TRUE  | TRUE  | TRUE  | FALSE             |

### b
| A     | B     | C     | A AND NOT \(B AND NOT C\) |
|-------|-------|-------|---------------------------|
| FALSE | FALSE | FALSE | FALSE                     |
| FALSE | FALSE | TRUE  | FALSE                     |
| FALSE | TRUE  | FALSE | FALSE                     |
| FALSE | TRUE  | TRUE  | FALSE                     |
| TRUE  | FALSE | FALSE | TRUE                      |
| TRUE  | FALSE | TRUE  | TRUE                      |
| TRUE  | TRUE  | FALSE | FALSE                     |
| TRUE  | TRUE  | TRUE  | TRUE                      |

### c
| A     | B     | C     | \(A OR NOT B\) AND \(A OR C\) |
|-------|-------|-------|-------------------------------|
| FALSE | FALSE | FALSE | FALSE                         |
| FALSE | FALSE | TRUE  | TRUE                          |
| FALSE | TRUE  | FALSE | FALSE                         |
| FALSE | TRUE  | TRUE  | FALSE                         |
| TRUE  | FALSE | FALSE | TRUE                          |
| TRUE  | FALSE | TRUE  | TRUE                          |
| TRUE  | TRUE  | FALSE | TRUE                          |
| TRUE  | TRUE  | TRUE  | TRUE                          |

### d
| A     | B     | C     | D     | A AND NOT \(B OR NOT C\) AND \(NOT A AND D\) |
|-------|-------|-------|-------|----------------------------------------------|
| FALSE | FALSE | FALSE | FALSE | FALSE                                        |
| FALSE | FALSE | FALSE | TRUE  | FALSE                                        |
| FALSE | FALSE | TRUE  | FALSE | FALSE                                        |
| FALSE | FALSE | TRUE  | TRUE  | FALSE                                        |
| FALSE | TRUE  | FALSE | FALSE | FALSE                                        |
| FALSE | TRUE  | FALSE | TRUE  | FALSE                                        |
| FALSE | TRUE  | TRUE  | FALSE | FALSE                                        |
| FALSE | TRUE  | TRUE  | TRUE  | FALSE                                        |
| TRUE  | FALSE | FALSE | FALSE | FALSE                                        |
| TRUE  | FALSE | FALSE | TRUE  | FALSE                                        |
| TRUE  | FALSE | TRUE  | FALSE | FALSE                                        |
| TRUE  | FALSE | TRUE  | TRUE  | FALSE                                        |
| TRUE  | TRUE  | FALSE | FALSE | FALSE                                        |
| TRUE  | TRUE  | FALSE | TRUE  | FALSE                                        |
| TRUE  | TRUE  | TRUE  | FALSE | FALSE                                        |
| TRUE  | TRUE  | TRUE  | TRUE  | FALSE                                        |

## Question 2

### a
![a](/LogicA.png)
### b
![b](/LogicB.png)
### c
![c](/LogicC.png)
### d
![d](/LogicD.png)
## Question 3

### a
| A     | B     | NOT \(A OR B\) |
|-------|-------|----------------|
| FALSE | FALSE | TRUE           |
| FALSE | TRUE  | FALSE          |
| TRUE  | FALSE | FALSE          |
| TRUE  | TRUE  | FALSE          |

| A     | B     | NOT A AND NOT B |
|-------|-------|-----------------|
| FALSE | FALSE | TRUE            |
| FALSE | TRUE  | FALSE           |
| TRUE  | FALSE | FALSE           |
| TRUE  | TRUE  | FALSE           |
### b
| A     | B     | NOT \(A AND B) |
|-------|-------|----------------|
| FALSE | FALSE | TRUE           |
| FALSE | TRUE  | TRUE           |
| TRUE  | FALSE | TRUE           |
| TRUE  | TRUE  | FALSE          |

| A     | B     | NOT A OR NOT B |
|-------|-------|----------------|
| FALSE | FALSE | TRUE           |
| FALSE | TRUE  | TRUE           |
| TRUE  | FALSE | TRUE           |
| TRUE  | TRUE  | FALSE          |
### c
| A     | B     | C     | \(A AND B\) OR \(A AND C\) |
|-------|-------|-------|----------------------------|
| FALSE | FALSE | FALSE | FALSE                      |
| FALSE | FALSE | TRUE  | FALSE                      |
| FALSE | TRUE  | FALSE | FALSE                      |
| FALSE | TRUE  | TRUE  | FALSE                      |
| TRUE  | FALSE | FALSE | FALSE                      |
| TRUE  | FALSE | TRUE  | TRUE                       |
| TRUE  | TRUE  | FALSE | TRUE                       |
| TRUE  | TRUE  | TRUE  | TRUE                       |

| A     | B     | C     | A AND \(B OR C\) |
|-------|-------|-------|------------------|
| FALSE | FALSE | FALSE | FALSE            |
| FALSE | FALSE | TRUE  | FALSE            |
| FALSE | TRUE  | FALSE | FALSE            |
| FALSE | TRUE  | TRUE  | FALSE            |
| TRUE  | FALSE | FALSE | FALSE            |
| TRUE  | FALSE | TRUE  | TRUE             |
| TRUE  | TRUE  | FALSE | TRUE             |
| TRUE  | TRUE  | TRUE  | TRUE             |

### d
| A     | B     | C     | \(A OR B\) AND \(A OR C\) |
|-------|-------|-------|---------------------------|
| FALSE | FALSE | FALSE | FALSE                     |
| FALSE | FALSE | TRUE  | FALSE                     |
| FALSE | TRUE  | FALSE | FALSE                     |
| FALSE | TRUE  | TRUE  | TRUE                      |
| TRUE  | FALSE | FALSE | FALSE                     |
| TRUE  | FALSE | TRUE  | TRUE                      |
| TRUE  | TRUE  | FALSE | FALSE                     |
| TRUE  | TRUE  | TRUE  | TRUE                      |

| A     | B     | C     | A OR \(B AND C\) |
|-------|-------|-------|------------------|
| FALSE | FALSE | FALSE | FALSE            |
| FALSE | FALSE | TRUE  | FALSE            |
| FALSE | TRUE  | FALSE | FALSE            |
| FALSE | TRUE  | TRUE  | TRUE             |
| TRUE  | FALSE | FALSE | TRUE             |
| TRUE  | FALSE | TRUE  | TRUE             |
| TRUE  | TRUE  | FALSE | TRUE             |
| TRUE  | TRUE  | TRUE  | TRUE             |
## Question 4

### a
|file_exists("a.txt")|file_exists("b.txt")|First Program|Second Program|
|--------------------|--------------------|-------------|--------------|
|FALSE               |FALSE               |TRUE         |TRUE          |
|FALSE               |TRUE                |TRUE         |TRUE          |
|TRUE                |FALSE               |TRUE         |TRUE          |
|TRUE                |TRUE                |FALSE        |FALSE         |

### b
|x > 7|type ( x) == int|type (x) == float|First Program|Second Program|
|-----|----------------|-----------------|-------------|--------------|
|FALSE|FALSE           |FALSE            |FALSE        |FALSE         |
|FALSE|FALSE           |TRUE             |FALSE        |FALSE         |
|FALSE|TRUE            |FALSE            |FALSE        |FALSE         |
|FALSE|TRUE            |TRUE             |TRUE         |TRUE          |
|TRUE |FALSE           |FALSE            |FALSE        |FALSE         |
|TRUE |FALSE           |TRUE             |FALSE        |FALSE         |
|TRUE |TRUE            |FALSE            |TRUE         |TRUE          |
|TRUE |TRUE            |TRUE             |TRUE         |TRUE          |

### c
|Y==0 |X==0 |First Program|Second Program|
|-----|-----|-------------|--------------|
|FALSE|FALSE|FALSE        |TRUE          |
|FALSE|TRUE |FALSE        |TRUE          |
|TRUE |FALSE|FALSE        |TRUE          |
|TRUE |TRUE |TRUE         |FALSE         |

### d
|x > 0|X > 10|y > 0|First Program|Second Program|
|-----|------|-----|-------------|--------------|
|FALSE|FALSE |FALSE|FALSE        |FALSE         |
|FALSE|FALSE |TRUE |FALSE        |FALSE         |
|FALSE|TRUE  |FALSE|TRUE         |TRUE          |
|FALSE|TRUE  |TRUE |TRUE         |TRUE          |
|TRUE |FALSE |FALSE|FALSE        |FALSE         |
|TRUE |FALSE |TRUE |TRUE         |FALSE         |
|TRUE |TRUE  |FALSE|TRUE         |TRUE          |
|TRUE |TRUE  |TRUE |TRUE         |TRUE          |
