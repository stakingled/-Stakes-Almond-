Almond
ERC-20 / BEP-20 Advanced Staking
Advanced Staking for Standard ERC-20 / BEP-20 tokens

What is Almond Smart Contract?

The Stakes Smart Contracts allow ERC-20 / BEP-20 token holders to be able to create a Stake and gain interest, based on a predefined APY.

Almond's smart contract allows its users to stake a token and accrue interest on the staked token and additionally accrue interest on a secondary token.
Features

Administrator user can define the parameters of the contract:

    The first ERC-20/BEP-20, which is used to stake
    A secondary ERC-20/BEP-20 token to accrue interest
    APY: annual interest rate for the first token (optional), calculated per second
    APY 2: the APY for the secondary token. You can offer interest in both tokens, the main staked token and the secondary token
    Maturity: users can claim rewards only if they remain staked for at least this number of days
    Minimum amount to create a stake

Architecture

Imagine a site owner who has a token for a particular project and wants to give away interest in a secondary token. The owner can create a stake contract, define an annual interest rate for both tokens and approve some funds for the contract.

Then the token holders can create Stakes, depositing an amount of tokens in the contract and accumulating interest on both tokens, once the Stake is finished, the token holders will receive their original amount plus the interest earned on both assets. A penalty may be applied if stakes are ended before a pre-defined expiration period.

