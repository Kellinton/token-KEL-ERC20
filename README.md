
## Description

`🪙KEL Token` contract implements the ERC20 standard for a fungible token on the Ethereum blockchain. It allows users to transfer tokens, approve others to spend tokens on their behalf, and check balances and allowances.

## Features

- **ERC20 Standard**: Implements the ERC20 interface.
- **Fixed Supply**: The total supply of tokens is initialized to 10 ether (10^19 units).
- **Transfer Tokens**: Users can transfer tokens to other addresses.
- **Approve & TransferFrom**: Users can approve other addresses to spend tokens on their behalf and perform transfers using those approvals.

## Contract Functions

- `totalSupply()`: Returns the total number of tokens in circulation.
- `balanceOf(address account)`: Returns the token balance of a given address.
- `transfer(address recipient, uint256 amount)`: Transfers tokens from the sender to the specified recipient.
- `approve(address spender, uint256 amount)`: Approves the spender to withdraw tokens from the sender's account.
- `allowance(address owner, address spender)`: Returns the amount of tokens the spender is allowed to withdraw from the owner's account.
- `transferFrom(address sender, address recipient, uint256 amount)`: Transfers tokens from a specified address to another address using an allowance.

## Events

- `Transfer(address indexed from, address indexed to, uint256 value)`: Emitted when tokens are transferred.
- `Approval(address indexed owner, address indexed spender, uint256 value)`: Emitted when an allowance is set or changed.


