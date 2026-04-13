# BlockInfo.sol
Really interesting way to see it.
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract BlockInfo {
    function getBlockTime() public view returns (uint256) {
        return block.timestamp;
    }

    function getBlockNumber() public view returns (uint256) {
        return block.number;
    }
}
Update logic for better performance
Refactor code for readability
Add new feature
Remove unused code
Improve error handling
Add input checks
