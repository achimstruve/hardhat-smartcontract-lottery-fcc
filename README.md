# Raffle Contract and Test with Hardhat

This repository contains a Raffle contract that is capable to provide real random winners within a lottery through Chainlink node utilization. This contract leverages also timebased functions.

## Steps to enable the utilization of Chainlink nodes for random numbers

1. Get our subscription ID (SubId) for the Chainlink VRF from vrf.chain.link
2. Deploy our contract using the SubId
3. Register the contract with Chainlink VRF & it's subId (add it as consumer under the subscription)
4. Register the contract with Chainlink Keepers on https://keepers.chain.link/ (chose custom-logic, starting balance 8 LINK)
5. Run staging tests / go in production
#   h a r d h a t - s m a r t c o n t r a c t - l o t t e r y - f c c  
 