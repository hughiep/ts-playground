# Typescript

## Keywords

### Static Typing

- Static typing is a way to enforce type constraints at compile time.

### Non-exception Failures

- Non-exception failures are failures that are not handled by exceptions, but are instead handled by the type system.
- For example, if you try to access non existed property of an object in Typescript, it will throw a compile time error. JavaScript will not throw any error.

### Type for tooling

- Typescript is a superset of JavaScript, so it can be used in place of JavaScript. Code editors can use the type information to provide better code completion and error checking.

### tsc

- tsc is the TypeScript compiler. It compiles TypeScript code to JavaScript code.

### Emitting with errors

- Emitting with errors means that the TypeScript compiler will still generate JavaScript code even if there are errors in the TypeScript code.

### Explicit Types

- Explicit types are types that are explicitly declared in the code. For example, `let x: number = 10;` declares a variable `x` with type `number`. Without explicit types, TypeScript will infer the types based on the values.

### Ereased Types

- TypeScript types are erased during compilation. This means that the type information is not available at runtime.
- Type annotations never change the runtime behavior of your program.

### Downleveling

- Downleveling is the process of compiling TypeScript code to an older version of JavaScript. For example, you can compile TypeScript code to ES5 or ES3.

### Strictness

- Strictness is a set of compiler options that enforce stricter type checking rules. For example, `strictNullChecks` option enforces null checks.
- Strictness can be enabled by setting `strict` option to `true`.

### noImplicitAny

- `noImplicitAny` is a compiler option that prevents TypeScript from inferring the `any` type. If `noImplicitAny` is set to `true`, you must explicitly declare the types of variables.

### strictNullChecks

- `strictNullChecks` is a compiler option that enforces strict null checks. If `strictNullChecks` is set to `true`, you must explicitly handle `null` and `undefined` values.
