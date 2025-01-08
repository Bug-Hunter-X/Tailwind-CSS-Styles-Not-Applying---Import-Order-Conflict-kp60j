# Tailwind CSS Styles Not Applying - Import Order Conflict

This repository demonstrates a common issue with Tailwind CSS where styles fail to apply due to incorrect CSS import order.  A conflicting CSS framework or custom styles override Tailwind's styles.  The solution highlights the importance of correct import ordering to resolve the conflict.

## Bug
The `bug.css` file shows how a conflicting CSS rule (from a hypothetical framework) can override a Tailwind class.  This results in the Tailwind class not being applied correctly.

## Solution
The `bugSolution.css` file demonstrates the correct way to import CSS files to prioritize Tailwind's styles and resolve the conflict.