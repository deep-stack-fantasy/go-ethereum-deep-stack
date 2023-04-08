# Ethereum mod: Deep Stack Fantasy

## Objective
- Get rid of `stack too deep` errors! Increase the number of allowed variables by 16 times.
- Support running modified EVM bytecodes `DupE` and `SwapE` as an extension for `DUP{1,16}` and `SWAPE{1,16}`.

## Working Progress
- [x] Support executing new `DupE` and `SwapE` instructions in private blockchain.
- [ ] Performance evaluation.
- [ ] Proposal of adding these two instructions.
- [ ] Future: zk-EVM modification, e.g., Scroll.

## License
GPL v3
