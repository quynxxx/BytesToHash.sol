# BytesToHash.sol
BytesToHash.sol
pragma solidity ^0.8.20;
contract BytesToHash {
    function hash(bytes memory data) public pure returns(bytes32){
        return keccak256(data);
    }
}
