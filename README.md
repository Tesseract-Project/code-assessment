# Tesseract Code Assessment

### Coding Task

Given a predeployed ERC20 coin contract behind an upgradeable proxy - [USD Coin (PoS)](https://mumbai.polygonscan.com/token/0x0fa8781a83e46826621b3bc094ea2a0212e71b23)

* Create a contract `TesseractProxy` that includes a function `tesseractApprove` which takes `sigR`, `sigS`, `sigV`  as parameters and calls `executeMetaTransaction` with `approve` function signature \(signature **MUST** be generated inside `TesseractProxy`\). 
*you can choose any arguments for `approve` function.*
* Generate necessary parameters \(`sigR`\,`sigV`\,`sigS`\) on front\-end side by signing typed data\. and send them to our function `tesseractApprove` inside `TesseractProxy` contract.


### Tech stack

* Solidity
* Ethers.js
