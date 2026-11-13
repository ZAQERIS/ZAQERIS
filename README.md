# ZAQERIS Ai

Independent AI research group. We train open-source foundation models from scratch so people can run them on their own computers.

## AXIOM

[AXIOM](https://huggingface.co/ZAQERIS/ZAQERIS_AXIOM) is our first public foundation model: a sparse Mixture-of-Experts language model with **79.43B** total parameters and **12.39B** active per token, trained from scratch and released under **Apache 2.0**.

After training, we compressed the weights with **ZAQERIS-M3** (sub-3-bit vector quantization) to about **29.20 GiB**, so a 79B-class model can be downloaded and run locally.

- Model card and weights: [huggingface.co/ZAQERIS/ZAQERIS_AXIOM](https://huggingface.co/ZAQERIS/ZAQERIS_AXIOM)
- Organization: [huggingface.co/ZAQERIS](https://huggingface.co/ZAQERIS)
- Architecture explorer: [huggingface.co/spaces/ZAQERIS/AXIOM-Architecture-Explorer](https://huggingface.co/spaces/ZAQERIS/AXIOM-Architecture-Explorer)
- Public chat demo: [AXIOM-Chat](https://huggingface.co/spaces/ZAQERIS/AXIOM-Chat) (being set up)

## What we work on

- Foundation models trained from scratch, not fine-tunes of someone else's base model
- Efficient Mixture-of-Experts architectures
- Compression methods that keep large models usable on local hardware
- Open weights, code and documentation under permissive licenses

## Support the work

If AXIOM or our other public releases are useful to you, you can sponsor ZAQERIS Ai on GitHub. Sponsorships help pay for compute, hosting and continued open releases.

[Support ZAQERIS on Patreon](https://www.patreon.com/c/ZAQERISAI)

## Contact

zaqeris.research@gmail.com

Based in Cairo, Egypt.
