# Type Narrowing in TypeScript

Type Narrowing is a TypeScript feature that helps identify the specific type of a variable within a condition. It allows us to safely work with union types.

There are three common ways to perform type narrowing:

**1. typeof Operator**

Used to check primitive types such as string, number, and boolean.

```typescript
function printValue(value: string | number) {
  if (typeof value === "string") {
    console.log(value.toUpperCase());
  } else {
    console.log(value * 2);
  }
}
```

**2. instanceof Operator**

Used to check whether an object belongs to a particular class.

**3. in Operator**

Used to check whether a property exists inside an object.

Type Narrowing makes TypeScript code safer, clearer, and easier to maintain.