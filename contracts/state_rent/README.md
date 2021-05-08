
### State Rent
- StateRent contract address: `0x0000000000000000000000000000000000000800`
```
// Returns the const of NewContractExtraBytes.
function newContractExtraBytes() public view returns (uint256);

// Returns the const of StorageDepositPerByte.
function storageDepositPerByte() public view returns (uint256);

// Returns the maintainer of the contract.
function maintainerOf(address contract_address) public view returns (address);

// Returns the const of DeveloperDeposit.
function developerDeposit() public view returns (uint256);

// Returns the const of DeploymentFee.
function deploymentFee() public view returns (uint256);

// Transfer the maintainer of the contract.
// Returns a boolean value indicating whether the operation succeeded.
function transferMaintainer(address contract_address, address new_maintainer) public returns (bool);
```
