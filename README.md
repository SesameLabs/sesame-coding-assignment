# Sesame Coding Assignment

### Build a Questing Platform

Welcome to Sesame’s coding challenge, in which you will build a Questing Platform ([https://bit.ly/sesame-coding](https://bit.ly/sesame-coding)) that rewards people with coupon codes for owning USDC.


**Product Requirements**

- The user should be able to sign in on the webpage with their MetaMask wallet
- Once they have connected their wallet, they will see a Quest which asks them to verify they own USDC (0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48) in their wallet. There will be a Buy USDC button (that simply links out to Uniswap) and a Verify button (that verifies if the user has successfully bought USDC). If the user owns USDC already in their wallet, the Verify button should still work.
- Once the user successfully verifies that they own USDC they should see a coupon code. For the purposes of this project, the coupon code can be a random 10 digit alphanumeric string.
- The user’s state (whether they have verified, which coupon code they have received, etc) should be stored in a DB so that it persists if the user signs in with their wallet again or even on server restart. Multiple different users should be able to use this product at the same time.
- The Quest details (title, description, cover image uri, USDC contract address, etc) and any API keys should be easily settable in a .config OR .env file
- The UI is not the primary focus of this assignment however it needs to be good enough and fully functional. Here is roughly how it should look like: [https://bit.ly/sesame-coding](https://bit.ly/sesame-coding)

**References**

- Our dummy quest ([https://sesamelabs.xyz/sesame/quests/sesame-labs-coding-assignment/](https://sesamelabs.xyz/sesame/quests/sesame-labs-coding-assignment/)) can be used for reference for how the flow and the verification should work. Feel free to use that as reference when designing your solution.

**Directions**

- Take about 8 hours to work on this assignment. Please complete this exercise yourself, however feel free to Google and use other references.
- Please create a new GitHub repository to start working on this project. Do not fork this repo, since private forks aren't possible in Github. Add a detailed README that provides easily understandable instructions on how to run your code on local machine.
- Please host your app somewhere where it is publically available and share it with your submission.
- This will be followed by a 45 min interview where you will be asked to explain your decisions and asked to describe about challenges and opportunities with your solution
- In addition to correctness, we will be evaluating based on code structure, readability, and extensibility. It does not need to be over-engineered, however should be solid production level code.
- Please reach out if you have any questions.
