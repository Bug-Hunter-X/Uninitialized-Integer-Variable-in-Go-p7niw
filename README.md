# Uninitialized Integer Variable in Go

This repository demonstrates a common issue in Go programming related to uninitialized integer variables.  In Go, variables are initialized to their zero values by default.  However, relying on this implicit initialization can lead to unexpected behavior if the variable is used before being explicitly assigned a value.

The `bug.go` file contains code that showcases this problem.  The `bugSolution.go` file offers a corrected version that avoids the issue.