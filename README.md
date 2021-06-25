# v-programming-language

`v new [project-name]`

```v
module main

fn main() {
	println('Hello, World!')
}
```

`v run [file]` to run 

`v run .` to run all 

`v -stats test [test-file]` to run tests 

`v -stats test .` to run all tests 

# testing 

- tests files may be ended with ` *_test.v ` and test functions started with `test_*` like:
```v
module main

fn test_guanine_to_cytosine() {
	assert to_rna('G') == 'C'
}
```
