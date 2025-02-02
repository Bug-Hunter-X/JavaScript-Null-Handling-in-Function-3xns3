# JavaScript Null Handling Bug

This repository demonstrates a common, yet subtle, bug in JavaScript related to how null values are handled within a function. The `foo` function is designed to add two numbers but returns null if either input is null. While seemingly straightforward, this can lead to unexpected behavior and errors in various scenarios.

The solution provided addresses this by treating null values as 0, offering a more robust and flexible solution.

## Bug
The bug lies in the immediate return of null if either input is null. This behavior is not always desirable, as it might result in the failure of downstream processes that rely on consistent numerical results. 