## 3.

>1
```
package main

import "fmt"

func main() {
    fmt.Print("Enter a number: ")
    var input float64
    fmt.Scanf("%f", &input)

    output := input * 0.3048

    fmt.Println(output,"fut")
}
```
>2
```
package main

import "fmt"
import "sort"

func main() {
    x := []int{48,96,86,68,57,82,63,70,37,34,83,27,19,97,9,17,}
    sort.Ints(x)
    fmt.Println(x[0])
}
```
>3

```
package main

import "fmt"
import "strconv"


func main() {

delenie_na_tri := []string{}
a := 3

for i := 1; i < 101; i++{
  if i % a == 0 {
  k:=strconv.Itoa(i)
  delenie_na_tri = append(delenie_na_tri, k)}
  }
fmt.Println(delenie_na_tri)
}
```
