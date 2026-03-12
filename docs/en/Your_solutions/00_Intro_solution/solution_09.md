To find the dimensions of the rectangle with the maximum area under the curve $y = 3 - x^2$ in the first quadrant, we can use optimization techniques from calculus.

### 1. Define the Rectangle and Variables

In the first quadrant, the rectangle is bounded by the $x$-axis, the $y$-axis, and the curve $y = 3 - x^2$. Let one vertex of the rectangle be at the origin $(0,0)$ and the opposite vertex be a point $(x, y)$ that lies on the curve.

* **Width** of the rectangle $= x$
* **Height** of the rectangle $= y = 3 - x^2$

### 2. Set Up the Area Function

The area $A$ of a rectangle is the product of its width and height:


$$A = x \cdot y$$

Since $y = 3 - x^2$, we can express the area entirely in terms of $x$:


$$A(x) = x(3 - x^2)$$

$$A(x) = 3x - x^3$$

### 3. Find the Critical Points (Derivative)

To find the maximum area, we take the derivative of $A(x)$ with respect to $x$ and set it to zero:


$$A'(x) = \frac{d}{dx}(3x - x^3)$$

$$A'(x) = 3 - 3x^2$$

Now, solve for $x$ when $A'(x) = 0$:


$$3 - 3x^2 = 0$$

$$3 = 3x^2$$

$$x^2 = 1$$

$$x = 1 \quad (\text{Since } x \text{ must be positive in the first quadrant})$$

### 4. Verify the Maximum

To confirm that $x = 1$ gives a maximum, we can use the **Second Derivative Test**:


$$A''(x) = -6x$$


At $x = 1$, $A''(1) = -6(1) = -6$. Since the second derivative is negative, the function is concave down, confirming that $x = 1$ is a **local maximum**.

### 5. Calculate the Dimensions

Now that we have the width ($x$), we find the height ($y$):


$$y = 3 - x^2$$

$$y = 3 - (1)^2$$

$$y = 2$$

### Final Result:

The dimensions of the rectangle that maximize the area are:

* **Width ($x$):** 1
* **Height ($y$):** 2

(The maximum area is $1 \times 2 = 2$ square units.)
