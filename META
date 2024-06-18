// SPDX-License-Identifier: MIT
pragma solidity ^0.8.26;

contract META {
    uint public oddCount;

    function assertOddNumber(uint metacrafters) external {
        assert(metacrafters % 2 != 0);
        ++oddCount;
    }

    function requireOddNumber(uint metacrafters) external {
        require(metacrafters % 2 != 0, "There are EVEN number of Metacrafters");
        ++oddCount;
    }

    function revertOddNumber(uint metacrafters) external {
        if (metacrafters % 2 == 0) {
            revert("There are EVEN number of Metacrafters");
        }
        ++oddCount;
    }
}
