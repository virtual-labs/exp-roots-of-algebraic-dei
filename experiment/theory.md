## Algebraic Equations

An **algebraic equation** is a mathematical statement that expresses the equality between two algebraic expressions composed of variables, constants, and coefficients combined through arithmetic operations such as addition, subtraction, multiplication, and division. In numerical analysis, algebraic equations are commonly expressed in the standard polynomial form:

<img width="140" height="49" alt="image" src="https://github.com/user-attachments/assets/12bc28e8-9b0c-4e61-8da8-fdd39bd64c71" />

where \( P(x) \) is a polynomial function of the variable \( x \).

Based on the **degree of the polynomial**, algebraic equations are classified as follows:

- **Linear equation (Degree 1):**
<img width="179" height="59" alt="image" src="https://github.com/user-attachments/assets/7dd31a56-0985-4780-a6a6-bff68763fe27" />

- **Quadratic equation (Degree 2):**
<img width="299" height="58" alt="image" src="https://github.com/user-attachments/assets/94b95778-0e9f-47f3-a80b-07529cce5fab" />

- **Cubic equation (Degree 3):**
<img width="287" height="46" alt="image" src="https://github.com/user-attachments/assets/01342387-8754-4e26-aaab-5dcd36448252" />

- **Higher-degree equation (Degree \(\geq 4\)):**
<img width="219" height="46" alt="image" src="https://github.com/user-attachments/assets/b9480a73-bde4-4cbd-a0f3-8d2803c7ef2e" />

The **solutions or roots** of an algebraic equation are the values of \( x \) for which the polynomial evaluates to zero. While exact analytical solutions exist for linear and quadratic equations, higher-degree equations often require **numerical methods** such as the **Bisection Method**, **Regula Falsi Method**, **Newton–Raphson Method**, or **Secant Method** to approximate the roots.

---

## Transcendental Equations

A **transcendental equation** is an equation that involves **non-polynomial functions**, such as exponential, logarithmic, trigonometric, or inverse trigonometric functions. These equations cannot be reduced to polynomial form and therefore do not generally admit closed-form analytical solutions.

A typical transcendental equation is written as:

<img width="163" height="47" alt="image" src="https://github.com/user-attachments/assets/3164835d-4372-41af-9bf9-e135d4b94dda" />

where \( f(x) \) contains transcendental terms.

### Examples of Transcendental Equations

<img width="951" height="402" alt="image" src="https://github.com/user-attachments/assets/467a0974-7932-4f39-9afc-c461d1c0c47a" />


<img width="1041" height="458" alt="image" src="https://github.com/user-attachments/assets/a5b098b0-daef-49a5-94bc-ea90555fe4aa" />


Such equations are frequently encountered in **physics, engineering, control systems, and signal processing**, particularly in problems involving oscillatory motion, heat transfer, and system stability. Since exact solutions are rarely available, **iterative numerical techniques** are essential for approximating their roots.

---

## Numerical Perspective and Relevance

Both algebraic and transcendental equations play a critical role in **scientific computing and numerical analysis**. The objective of numerical root-finding methods is to **iteratively approximate solutions** by starting from an initial guess or interval and refining it until a specified level of accuracy is achieved.

In this experiment, numerical methods are applied to:

- Identify approximate roots of **algebraic equations of different degrees**, and  
- Determine numerical solutions for **transcendental equations**, where analytical approaches are not feasible.

Understanding the nature of the equation—whether algebraic or transcendental—is essential for selecting an appropriate numerical method and for interpreting the **convergence behavior, accuracy, and stability** of the obtained solution.
