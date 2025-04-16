# Angular Senior Developer Interview Questions

## 1. Core Angular Concepts
1. What is Angular, and how is it different from AngularJS?
2. Explain the Angular architecture.
3. What are Angular modules (`@NgModule`), and why are they important?
4. What are Angular templates, and how do they work?
5. What is the role of decorators like `@Component`, `@NgModule`, and `@Injectable`?
6. What is TypeScript, and why does Angular use it?
7. Explain the difference between **declarative and imperative programming** in Angular.
8. How does **Angular’s bootstrapping process** work?
9. What is **Change Detection**, and how does it work in Angular?
10. What is **Zone.js**, and why is it used in Angular?

## 2. Lifecycle Hooks & View Management
11. What are **Angular lifecycle hooks**? Explain their execution order.
12. What is the difference between **ngOnInit and ngOnChanges**?
13. What is the use of **ngAfterViewInit and ngAfterContentInit**?
14. When would you use **ngDoCheck** instead of **ngOnChanges**?
15. How do you clean up subscriptions in **ngOnDestroy**?
16. What is the difference between **ViewChild, ViewChildren, ContentChild, and ContentChildren**?
17. How can you manually trigger change detection in Angular?
18. What are **detached change detectors**, and how do they improve performance?

## 3. Data Binding & Directives
19. What are the four types of data binding in Angular?
20. What is **two-way data binding**, and how is it implemented in Angular?
21. Explain the difference between **structural directives** (`*ngIf`, `*ngFor`) and **attribute directives** (`[ngClass]`, `[ngStyle]`).
22. How does **trackBy** improve performance in `*ngFor`?
23. What is a **custom directive** in Angular, and how do you create one?
24. What are **pipes** in Angular, and how do they work?

##  Angular Forms (Template-driven & Reactive)
25. What are the key differences between Template-driven and Reactive forms in Angular?
26. How do you create a Reactive form using FormBuilder and FormGroup?
27. How can you apply synchronous and asynchronous validators in Reactive forms?
28. How do you dynamically add or remove form controls or form groups?
29. What are the steps to bind and validate a Template-driven form in Angular?
30. How do you track form state (touched, dirty, valid, etc.) in both types of forms?
31. How can you trigger validation messages conditionally?
32. What are some common issues and best practices when working with forms in Angular?
33. How do you submit a form and get the form values in both approaches?
34. How do you write unit tests for Reactive forms in Angular?

## 4. Dependency Injection & Services
35. What is **dependency injection (DI)** in Angular?
36. What are **service providers**, and how do they work?
37. What is the difference between **providedIn: 'root'** and **module-level providers**?
38. What is an **HTTP Interceptor**, and how do you implement one?
39. How do you use **RxJS Observables** in an Angular service?

## 5. Performance Optimization
40. What is the **OnPush change detection strategy**, and when should you use it?
41. How does **lazy loading** work in Angular?
42. What are **pure and impure pipes**, and how do they affect performance?
43. How does **Ahead-of-Time (AOT) compilation** improve performance?
44. How would you optimize an Angular application for faster rendering?

## 6. State Management & RxJS
45. What is **NgRx**, and how does it help with state management?
46. What is the difference between **BehaviorSubject, Subject, and ReplaySubject** in RxJS?
47. Explain the purpose of `switchMap`, `mergeMap`, and `concatMap` in RxJS.
48. How do you handle **error handling in RxJS Observables**?
49. What is the **async pipe**, and how does it work?
50. How do you cancel pending HTTP requests in Angular?

## 7. Routing & Navigation
51. What is **Angular Router**, and how does it work?
52. How do you implement **lazy-loaded routes** in Angular?
53. What are **Route Guards (CanActivate, CanDeactivate, Resolve, etc.)**, and how do they work?
54. How can you pass **route parameters** between components?
55. How do you handle **404 and wildcard routes** in Angular?

## 8. Security & Best Practices
56. How does Angular handle **Cross-Site Scripting (XSS) protection**?
57. How do you implement **JWT-based authentication** in Angular?
58. What is **Content Security Policy (CSP)**, and how does it apply to Angular?
59. What are **trusted types**, and how do they improve security in Angular?
60. How do you protect Angular applications against **cross-site request forgery (CSRF) attacks**?

---
## 10 Machine Coding Round Questions
1. **Create a Debounced Search Component** – Implement an input field that fetches data after 300ms delay using `debounceTime`.
2. **Build a Dynamic Form Generator** – Create a form that renders based on a given JSON configuration.
3. **Implement a Custom Directive** – Write a directive that changes background color on hover.
4. **Develop a Todo App with NgRx** – Create a CRUD-based Todo list using state management.
5. **Create an HTTP Interceptor for JWT Authentication** – Modify HTTP requests to include authentication tokens.
6. **Optimize a Large List Rendering** – Implement a virtual scroll feature for rendering large datasets.
7. **Build a Modal Component Using Content Projection** – Create a reusable modal dialog with dynamic content.
8. **Implement a Custom Pipe** – Write a pipe to format text as title case (e.g., `hello world` → `Hello World`).
9. **Create a Multi-Step Form with State Management** – Design a form that maintains state across steps.
10. **Develop a Role-Based Access Control (RBAC) System** – Implement role-based authorization using Angular guards.
