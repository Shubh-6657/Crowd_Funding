# Crowd-Funding

This project is a blockchain-based crowdfunding platform that allows users to donate money to projects of their choice. The funds are held in a smart contract, which can only be released if 51% of the contributors approve.

## Features

* Secure and transparent: All transactions are recorded on the blockchain, ensuring that the funds are secure and transparent.
* Refund mechanism: In case the project does not reach its funding goal, the donors will be refunded their money.
* Efficient and cost-effective: The smart contract eliminates the need for intermediaries, reducing transaction fees and speeding up the fundraising process.

## How to Use

1. To donate money to a project, simply copy the code to your local machine then run the file.
2. The smart contract will automatically record your donation.
3. If the project reaches its funding goal, the funds will be released to the project creator.
4. If the project does not reach its funding goal, the donors will be refunded their money.

## Smart Contract

The smart contract for this project is written in Solidity. The contract code is available in the `contracts` directory.

The contract has the following functions:

* `make payment(uint256 amount)`: This function allows a user to donate money to the project.
* `deadline()`: This function in used under which th amount of money that has been donated to the project should be collect on time.
* `raised amount()`: This function is ued to collect the certain amount.
* `refundFunds()`: This function refunds the money to the donors if the project does not reach its funding goal.

## Roadmap

The following are some of the features that I plan to add to this project in the future:

* Support for multiple cryptocurrencies.
* Integration with a payment gateway.
* A user-friendly interface.

## Contact

If you have any questions or suggestions, please feel free to contact me at shubhagrahari.ashta@gmail.com
