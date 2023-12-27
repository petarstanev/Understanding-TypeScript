SECTION 1
HTML script defer - script executed after page is loaded
! aways returns an elementJ: document.getElementById("num2")! as HTMLInputElement;
Babel is used in native JS but can also be used in TS to use features on older browser versions.

SECTION 2
object and {} are the same
Tuple is an array with specific array where we set the type of each element
Enum usually with Capital letter values with all caps
Enum if we set value to one 5 the other values increase 6,7,...
Literal types are types that have type and specific version for example test: 'as-number' | 'as-string'
Type Alias/ Custom type is a type that may combine other types: type Combine = string | number. 
Undifined and Void are different types. Void is function that has no return type, undefined is a function that returnes an empty return;
Function can be used as a type that can be assign to a property let a: Function;
To set sepcific function input and output we can use this: let m: (a: number, b: number)=> number;
Call back functions can receive a method that returns something even if the argument they are passed does NOT expect a return: const test = () => true;
const hello = (cb:()=>void) =>{
  return cb;
}
hello(test);
Unknown is a type that we can assign anything to it but we can NOT assign it to other type.
let vAny: any = 10;          // We can assign anything to any
let vUnknown: unknown =  10; // We can assign anything to unknown just like any
let s1: string = vAny;     // Any is assignable to anything 
let s2: string = vUnknown; // Invalid; we can't assign vUnknown to any other type (without an explicit assertion)
unknown is like a parent for all other types, any is like I don't care what is the type.

type never is used when we want explicitly a method to not return anything (not void which is default). It is usefull when we throw an exception or we have an inifinty loop.

SECTION 3