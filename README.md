# <img src="engena-logo.png" alt="Engena - NGN Token">

**NGN Token** is the utility token of the energy community management system of **Engena**.

It's an ERC20 standard Token (based on OpenZeppelin v.3.1.0), including:

 * ability for holders to burn (destroy) their tokens;
 * ability for holders to pledge (lock over another account) their tokens;
 * ability of creating escrow wallets for the deposit of tokens (intended for new plant projects);
 * a contributor role that allows to deposit tokens on escrow wallets;
 * ability for users to view their token balance in gross form (all tokens owned) and in net form (all available tokens, i.e. tokens owned minus those pledged to third parties);
 * an owner address that can manage the admin role;
 * an admin role that allows to manage other roles;
 * a notary role that allows to finalize the transfer of pledged token and to unlock token transfers from escrow wallets;
 * a banker role that allows for others' tokens management (transfer, burning, allowance);
 * a minter role that allows for token minting (creation).
 
