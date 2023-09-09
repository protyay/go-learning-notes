# go-learning-notes
Notes on learning Go lang

### Pointer
#### Deferencing
- There's value `t` of Type `T` . To get the value referenced by a pointer, we need to derefence it. The `*` is called dereference operator.
- Arithmetic operations on pointer type is illegal in Go. You should dereference the type first and then apply the required arithmetic operations. `*p++` is modified to `(*p)++`

## Testing in Go
---
What happens when you run `go test` and what are the standards
https://pkg.go.dev/testing
