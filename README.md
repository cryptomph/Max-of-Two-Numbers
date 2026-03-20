# Max-of-Two-Numbers
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract MaxNumber {
    function findMax(uint256 a, uint256 b) public pure returns (uint256) {
        return a >= b ? a : b;
    }
}
