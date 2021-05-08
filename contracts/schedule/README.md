### On-chain Automatic Scheduler
- SchedulerCall contract address: `0x0000000000000000000000000000000000000802`
```
// Scheduler call the contract.
// Returns a boolean value indicating whether the operation succeeded.
function scheduleCall(address contract_address, uint256 value, uint256 gas_limit, uint256 storage_limit, uint256 min_delay, bytes memory input_data) public returns (bool);

// Cancel scheduler call the contract.
// Returns a boolean value indicating whether the operation succeeded.
function cancelCall(bytes memory task_id) public returns (bool);

// Reschedule call the contract.
// Returns a boolean value indicating whether the operation succeeded.
function rescheduleCall(uint256 min_delay, bytes memory task_id) public returns (bool);
```
