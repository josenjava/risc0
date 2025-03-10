# Options for Proof Generation

:::info

The `stark2snark` prover currently _only_ works on x86 architecture, and so Apple Silicon is _currently unsupported_ (even via Docker).

You can find out more info in the relevant issues [here](https://github.com/risc0/risc0/issues/1520) and [here](https://github.com/risc0/risc0/issues/1749).

:::

---

To support a variety of use cases, RISC Zero allows users a variety of options for proof generation.

Users can choose between:

1. [dev-mode]: No proofs are generated, enabling rapid prototyping.
2. [Local Proving]: Proofs are generated on the user's own CPU/GPU.
3. [Remote Proving]: Proofs are generated by [Bonsai], a highly parallelized, highly performant proving service.

We recommend option 1 during development, option 2 for applications involving private inputs, and option 3 for all other applications.

[dev-mode]: ./dev-mode.md
[Local Proving]: ./local-proving.md
[Remote Proving]: ./remote-proving.md
[Bonsai]: https://bonsai.xyz
