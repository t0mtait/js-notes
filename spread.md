The spread allows an iterable such as an array or string to be expanded in places where zero or more elements are expected.


In an object literal, the spread enumerates properties of an object and adds the kv pairs to the object being created

```
Function sum(x,y,z)
{
	return x + y + z
}
Const numbers = [1,2,3]

console.log(sum(...numbers));
// logs 6

console.log(sum.apply(null, numbers));
// logs 6
```