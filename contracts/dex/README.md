
### SetheumDex
- SetheumDex contract address: `0x0000000000000000000000000000000000000803`
```
// Get liquidity of the currency_id_a and currency_id_b.
// Returns (liquidity_a, liquidity_b)
function getLiquidity(address tokenA, address tokenB) public view returns (uint256, uint256)

// Swap with exact supply.
// Returns (target_amount)
function swapWithExactSupply(address tokenA, address tokenB, uint256 supplyAmount, uint256 minTargetAmount) public view returns (uint256)
```
