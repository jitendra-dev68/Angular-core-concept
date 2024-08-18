# Core Angular Concepts

## 1. Component Lifecycle
- **Lifecycle Hooks:**
  - `ngOnInit`, `ngOnChanges`, `ngAfterViewInit`, etc.
  - Understand the purpose and proper usage of each lifecycle hook.
  - Learn how to manage component initialization, updates, and teardown effectively.

## 2. Data Binding
- **Two-way Binding:**
  - Using `[(ngModel)]` for two-way data binding between components and templates.
- **Property and Event Binding:**
  - Understand one-way data flow with property binding `[property]`.
  - Capture and respond to events using event binding `(event)`.
- **Component Communication:**
  - Use `@Input()` to pass data from parent to child components.
  - Use `@Output()` to emit events from child to parent components.

## 3. Directives
- **Structural Directives:**
  - Control DOM structure with `*ngIf`, `*ngFor`, `*ngSwitch`.
- **Attribute Directives:**
  - Dynamically modify element properties and behavior using `ngClass`, `ngStyle`.
- **Custom Directives:**
  - Create reusable custom directives for encapsulating common behavior.

## 4. Services and Dependency Injection
- **Creating Services:**
  - Build Angular services to encapsulate business logic and shared functionality.
- **Dependency Injection (DI) System:**
  - Understand Angular's DI mechanism for injecting dependencies into components and services.
- **Service Scopes:**
  - Differentiate between singleton services and component-scoped services.

## 5. Routing
- **Setting Up Routes:**
  - Configure routes using `RouterModule`.
  - Understand basic and nested routes.
- **Lazy Loading:**
  - Implement lazy loading for modules to improve application performance.
- **Route Guards:**
  - Protect routes using `CanActivate`, `CanDeactivate`, `CanLoad` guards.
- **Route Parameters:**
  - Handle route and query parameters for dynamic routing.

## 6. Forms
- **Form Types:**
  - Choose between template-driven and reactive forms based on use cases.
- **Form Validation:**
  - Implement form validation using Angular’s built-in validators or custom validators.
- **Form Controls:**
  - Manage form data using `FormGroup`, `FormControl`, and `FormBuilder`.

## 7. HTTP Client
- **Making HTTP Requests:**
  - Perform HTTP requests using `HttpClient` service.
- **Handling Observables:**
  - Manage asynchronous data streams returned by HTTP methods.
- **Interceptors:**
  - Implement interceptors to modify HTTP requests and responses globally.

## 8. RxJS
- **Core Concepts:**
  - Grasp the basics of Observables, Operators, and Subjects.
- **Common Operators:**
  - Utilize operators like `map`, `filter`, `switchMap`, `mergeMap`, `forkJoin`.
- **Error Handling:**
  - Implement error handling strategies within RxJS observables.

## 9. Angular CLI
- **Common Commands:**
  - Use Angular CLI commands (`ng generate`, `ng build`, `ng serve`) for project management.
- **Workspace Structure:**
  - Understand the Angular workspace and its configurations.
- **Libraries:**
  - Create and manage Angular libraries within a workspace.

## 10. Performance Optimization
- **Build Optimization:**
  - Implement Ahead-of-Time (AOT) compilation and tree shaking to reduce bundle sizes.
- **Lazy Loading:**
  - Improve load times by lazy loading modules and components as needed.
- **Change Detection:**
  - Optimize change detection strategies, such as using `OnPush`.
- **Bundle Analysis:**
  - Analyze and reduce the bundle size for better performance.

## 11. Testing
- **Unit Testing:**
  - Write unit tests for components, services, and pipes using Jasmine and Karma.
- **End-to-End Testing:**
  - Conduct end-to-end tests using Protractor or Cypress.
- **Testing Asynchronous Code:**
  - Handle asynchronous operations in tests using `fakeAsync`, `tick`, and other utilities.
