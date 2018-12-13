# Implicit-Differentiation
Most functions that we have worked with so far have been defined explicitly; that is, we've had an explicit formula for the function such as f(x)=x^3-9x+4 or y = sin(x)+ln(x). These explicit formulas clearly show the relationship between x and y by way of the formula. However, some relationships between x and y are only implied by an equation.  For example, we could solve the equation (x^2)y=4 for y to get y = 4/(x^2).  In this example, y = 4/(x^2) is the explicit formula for y, whereas (x^2)y=4 implicitly defines the relationship between x and y.

To find dy/dx for this equation, we will use our usual rules of differentiation and differentiate both sides of (x^2)y = 4 with respect to x (recognizing that dx/dx = 1).  Using the product rule to differentiate (x^2)y we arrive at (2x)(dx/dx)y + (x^2)(dy/dx), while differentaing 4 we arrive at 0.  

So (2x)(dx/dx)y +(x^2)(dy/dx) = 0, or equivalently (2xy + (x^2)(dy/dx) = 0.  Solving for dy/dx we get (x^2)(dy/dx) = -2xy, so (dy/dx) = (-2xy)/(x^2) or equivalently dy/dx = -2y/x.
