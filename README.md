# LoopTest
The LoopTest Solidity contract demonstrates a simple loop operation where a counter is incremented 1000 times. This contract showcases basic looping in Solidity using a for loop to increment a public counter variable.

## Description
The LoopTest contract contains a single function, simpleLoop(), which runs a loop that increments the count variable 1000 times. This contract serves as a basic example of how loops work in Solidity, and can be expanded for more complex operations involving loops.

## Getting Started
### Installing
To use this contract, you can compile and deploy it using an Ethereum development environment like Remix.

Open the Remix IDE.
Create a new file with a .sol extension (e.g., LoopTest.sol).
Copy and paste the following code into the file:
solidity
Copy code
    
    // SPDX-License-Identifier: MIT
    pragma solidity ^0.8.26;

    contract LoopTest {
        uint256 public count;

        // Function to run a loop for 1000 times
        function simpleLoop() public {
            count = 0;  // Reset the counter
            for (uint256 i = 0; i < 1000; i++) {
                count += 1;  // Incrementing count
            }
        }
    }
## Executing Program
Compile the contract using the Solidity compiler in Remix. Ensure the compiler version is set to 0.8.26 or a compatible version.
Deploy the contract using the "Deploy & Run Transactions" tab.
After deploying, you can call the simpleLoop() function to reset the counter and increment the count variable by 1000.
## Help
Ensure you're using the correct compiler version (0.8.26) or a compatible one.
If the gas limit exceeds due to the loop size, you can reduce the number of iterations in the loop.
## Authors
Aakash Raj
Email: akashraj2708@gmail.com
## License
This project is licensed under the MIT License - see the LICENSE.md file for details.
