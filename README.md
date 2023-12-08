# go-learning-notes
Notes on learning Go lang

### Pointer
#### Deferencing
- There's value `t` of Type `T` . To get the value referenced by a pointer, we need to derefence it. The `*` is called dereference operator.
- Arithmetic operations on pointer type is illegal in Go. You should dereference the type first and then apply the required arithmetic operations. `*p++` is modified to `(*p)++`
### Module in Go
- Therefore, a module by definition is a collection of Go packages stored in a file tree with a go.mod file at its root.
- Very important pointer on how to write [Go code](https://go.dev/doc/code)
## Testing in Go
What happens when you run `go test` and what are the standards
https://pkg.go.dev/testing

## Interfaces in Go
Defining an interface is just defining a bunch of methods with a name and return type.
Whenever any type defines a method with the same name and the same return type , it is said to have implemented the interaface.

Is there any benefit of using interfaces in Go, like runtime polymorphism, etc. ?
