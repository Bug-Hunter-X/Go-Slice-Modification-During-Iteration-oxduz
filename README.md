# Go Slice Modification During Iteration

This repository demonstrates a common error in Go when modifying a slice while iterating over it using a range loop. The `bug.go` file contains the erroneous code, while `bugSolution.go` provides a corrected version.

The issue arises because modifying the slice's length during iteration invalidates the index used by the loop, resulting in unexpected behavior or runtime panics.  The solution utilizes a different approach to avoid this problem.

This example highlights the importance of understanding how Go's slice manipulation affects iteration and how to handle such situations effectively.