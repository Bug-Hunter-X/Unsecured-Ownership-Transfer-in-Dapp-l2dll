This repository demonstrates a common vulnerability in Dapps: insecure ownership transfer. The `bug.sol` file contains the vulnerable code, while `solution.sol` provides a corrected version.  The vulnerability allows any address to transfer ownership, bypassing the intended access control mechanism. The solution addresses this by adding a check to ensure only the current owner can transfer ownership.