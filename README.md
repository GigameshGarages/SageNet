# Introduction
Multi Dimensional Money Streaming Vaults, Escrows and Yields on Bitcoin Cash Protocol 

# Context
- Inspired by the  “Streaming Money,” lecture of Andreas Antonopolous which is all about the spatio - temporal dimensions.

# Concepts
- Money streaming represents the idea of continuous payments over a finite period of time.
- Block Numbers are used as a proxy of time to continuously update balances.

# Workflow
- A provider sets up a money streaming contract.
- A prospective payer can interact with the contract and start the stream right away by depositing the funds required for the chosen period.
- The payee is able to withdraw money from the contract based on its ongoing solvency
- payment rate * stream factor (current block height - starting block height)
- The stream terms (payment rate, length, metadata) can be updated at any time if both parties pledge their signatures.
- The stream can be stopped at any point in time by any party without on-chain consensus.
- If the stream period ended and it was not previously stopped by any party, the payee is entitled to withdraw all the deposited funds.

# Components
- Money Streaming Timer Tokens
- Money Streaming Strategy Vaults
- Money Streaming Yeild Farming
- Money Streaming Indexed Oracles
