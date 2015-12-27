# Nobody-Likes-Ricotta
```
// Cheeses of many types

class Ricotta {}

struct Cheese<T> {
    func isItDelicious() -> Bool {
        if Ricotta.self is T.Type {
            return false
        } else {
            return true
        }
    }
}

let stringCheese = Cheese<String>()
let booleanCheese = Cheese<Bool>()
let ricottaCheese = Cheese<Ricotta>()

stringCheese.isItDelicious()
booleanCheese.isItDelicious()
ricottaCheese.isItDelicious()

```
