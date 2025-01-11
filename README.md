# Subtle Memory Management and Delegate Issues in Objective-C

This repository demonstrates common, yet easily overlooked, memory management and delegate-related errors in Objective-C.  These issues often lead to crashes or unpredictable application behavior.  The `bug.m` file contains code exhibiting these problems, while `bugSolution.m` provides the corrected versions. 

**Key Issues Covered:**

*   **Incorrect `retain`/`release`:**  Improper handling of object ownership can lead to premature deallocation or retain cycles.
*   **Unsafe `assign` for delegates:** Assigning delegate properties without retaining them creates a risk of accessing a deallocated object.

This repository aims to help developers understand these pitfalls and write more robust, memory-safe Objective-C code.