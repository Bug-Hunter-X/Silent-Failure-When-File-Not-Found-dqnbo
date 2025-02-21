# Shell Script Bug: Silent File Processing Failure

This repository demonstrates a common error in shell scripts: silent failure when a file is not found. The `bug.sh` script attempts to process a file, but it does not handle the case where the file does not exist.  This results in the script failing silently, making debugging difficult.

The `bugSolution.sh` script provides a corrected version that includes robust error handling.