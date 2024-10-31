# NextJS

# TypeScript Study Notes

## Prerequisites
Before diving into TypeScript, it's helpful to be familiar with the following JavaScript concepts:
- **Variables**: Declaring and assigning values.
- **Arrays**: Working with collections of data.
- **Objects**: Creating and manipulating objects.
- **Functions**: Defining functions for code reuse.
- **Arrow Functions**: Compact syntax for function expressions.
- **Destructuring**: Extracting values from arrays and objects.

---

## Benefits of TypeScript
TypeScript provides several advantages over JavaScript that make it especially appealing for large projects and collaborative coding.

1. **Static Typing**
   - **Statically Typed**: TypeScript enforces types at compile time, allowing early detection of potential errors.
     ```bash
	    int number = 20;
		Number = ‘a’;  (Not allowed)
     ```
   - **Dynamically Typed (JavaScript)**: In JavaScript, type-related errors are often caught only at runtime, which can lead to unexpected behavior.
     ```bash
		Let number = 10;
		Number = “a”;
		Math.round(number);
     ```
2. **Code Completion and IntelliSense**: TypeScript's type system enables code editors to provide accurate suggestions, auto-completion, and error detection, making coding faster and less error-prone.
3. **Refactoring**: Types improve refactoring tools, allowing you to confidently change code structure without breaking functionality.
4. **Shorthand Notations**: TypeScript syntax often includes shorthands that make the code cleaner and easier to understand.

---

## Drawbacks
While TypeScript has many benefits, there are a few drawbacks:
- **Compilation Requirement**: TypeScript code needs to be compiled to JavaScript before running in a browser or server environment.
- **Coding Discipline**: TypeScript requires consistent typing and code structure, which might require more initial effort and planning.

---

## Setting up the TypeScript Environment
1. **Install Node.js** (TypeScript requires Node.js to run in development).
2. **Install TypeScript** globally using npm.
   ```bash
   npm I -g typescript
   ```
3. **Compile TypeScript Code**: Compile `.ts` files to JavaScript. This will generate a `.js` file that can be run (e.g., with Code Runner). By default, TypeScript compiles to ES5.

### TypeScript Compiler Configuration
To customize TypeScript settings:
1. **Initialize TypeScript Configuration** to create a `tsconfig.json` file.
2. **Update `tsconfig.json`**: Modify configurations like `target` (JavaScript version), `strict` (strict mode), and other compiler options.

---

## Debugging Setup (Optional)
To use debugging tools, create a `launch.json` file in your `.vscode` folder and configure it for TypeScript debugging.

---

## JavaScript vs. TypeScript Types

| JavaScript Type | TypeScript Type |
|-----------------|-----------------|
| Number          | `number`        |
| String          | `string`        |
| Boolean         | `boolean`       |
| Null            | `null`          |
| Undefined       | `undefined`     |
| Object          | `object`, `any`, `unknown` |
| N/A             | `never`, `enum`, `tuple` |

---

## Type Handling in TypeScript

1. **Declaring Variables with Types**: TypeScript allows specifying types for variables, making the code more predictable.
   
3. **Arrays**: TypeScript enforces consistent types in arrays, preventing unexpected types from being added.
4. **Tuples**: Tuples allow fixed structures with specific types for each element, adding structure to arrays of known values.
5. **Enums**: Enums define a set of named constants, making the code more readable and reducing the risk of misused values.

---

## Functions
In TypeScript, you can define the types of function parameters and return types, adding clarity and reducing errors.

## Objects
Define object structures with type annotations to enforce shape and type consistency, making it easier to work with structured data.

---
