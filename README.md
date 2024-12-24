# Elixir List Modification During Enum.each

This repository demonstrates a common issue in Elixir when attempting to modify a list while iterating over it using `Enum.each`.  The example shows that direct list modification within the `Enum.each` callback does not alter the original list as expected. The solution demonstrates the use of `Enum.filter` for achieving the intended list manipulation. 

**Key Takeaway:**  Avoid modifying lists directly within `Enum.each`. Use functional approaches such as `Enum.filter`, `Enum.map`, `Enum.reduce`, etc., for more predictable and safer list manipulation.