# CSS calc() Unexpected Results
This repository demonstrates a common issue with the CSS `calc()` function: unexpected results due to operator precedence and unit handling.  The `bug.css` file showcases the problem, while `bugSolution.css` provides a solution.

The problem arises when combining percentages and fixed units (like pixels) within a `calc()` expression. The order of operations and unit conversion can lead to inaccurate calculations if not handled carefully.

The solution shows how to avoid this issue by using parentheses to clearly define the order of operations and ensuring consistent unit usage throughout the expression.