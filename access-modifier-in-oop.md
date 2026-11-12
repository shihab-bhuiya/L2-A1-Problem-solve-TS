# Access Modifiers in TypeScript OOP

Access Modifiers control how class properties and methods can be accessed. TypeScript provides four important modifiers.

**1. public:** Accessible from anywhere. It is the default modifier.

**2. private:** Accessible only inside its own class.

**3. protected:** Accessible inside its own class and its subclasses.

**4. readonly:** Allows a property to be assigned only during initialization or in the constructor.

```typescript
class Employee {
  public name: string;
  private salary: number;
  protected department: string;
  readonly id: number;

  constructor(name: string, salary: number, department: string, id: number) {
    this.name = name;
    this.salary = salary;
    this.department = department;
    this.id = id;
  }
}
```

Access Modifiers help protect data, control access, and create better object-oriented code.