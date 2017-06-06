## Managing Multiple SaltStack Environments for Fun & Profit


## Abstract


One of the power features of SaltStack is the ability to segment Salt states into separate environments, minions can then be setup to only receive their states from specific environments. The most common use case for using multiple environments in Salt is to provide multiple versions of states, for example development and production environments. This can be extended to support other use cases, such as providing different environments for different projects or different clients. In this talk we’ll explore a real world solution that will allow us to sanely support & manage multiple Salt environments. We’ll look at various approaches that didn’t work and why, and then at the final approach which uses various features of Salt to solve the problem.

## Gareth J. Greenaway
