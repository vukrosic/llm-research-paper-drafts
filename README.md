# Six Language-Model Research Paper Drafts

Vuk Rosić · **Join: [AI Research School](https://www.skool.com/become-ai-researcher-2669)**

Six near-finished research papers on language models: optimizers, attention, linear attention and embeddings. Each folder has the paper (PDF, Markdown and HTML), the results, the code and a script to reproduce the runs. You can take any of them, extend the experiments and write it up for a conference such as ICML 2027. Code under the MIT licence.

> [!IMPORTANT]
> Don't just generate a paper and submit it. It will be rejected. Spend about a month researching and improving it.

| # | Paper | Read |
|---|---|---|
| 1 | Helping Rare Words in Language Models: Similar Words Share Part of the Last-Layer Vector Used to Predict Them, with Groups the Model Finds Itself | [PDF](01-rare-words-shared-output-vectors/paper.pdf) · [Markdown](01-rare-words-shared-output-vectors/PAPER.md) · [code](01-rare-words-shared-output-vectors) |
| 2 | Hypergradient Descent on the Muon Optimizer: Can One Language-Model Training Run Replace Trying Many Learning Rates in Separate Runs? | [PDF](02-muon-hypergradient-learning-rate/paper.pdf) · [Markdown](02-muon-hypergradient-learning-rate/PAPER.md) · [code](02-muon-hypergradient-learning-rate) |
| 3 | Linear Attention Forgets Facts From Its Input Mostly Because It Writes Back Every Answer It Looks Up | [PDF](03-linear-attention-skip-lookups/paper.pdf) · [Markdown](03-linear-attention-skip-lookups/PAPER.md) · [code](03-linear-attention-skip-lookups) |
| 4 | Following Chains of Facts in the Prompt: One Modified Attention Head per Layer Follows One Link, Even When Training Checks Only the Final Answer | [PDF](04-attention-chain-following-heads/paper.pdf) · [Markdown](04-attention-chain-following-heads/PAPER.md) · [code](04-attention-chain-following-heads) |
| 5 | Following Long Chains of Facts in the Prompt: An Attention Head That Doubles Its Jump Every Layer Follows 7 Links With 3 Layers and 31 With 5 | [PDF](05-attention-pointer-doubling/paper.pdf) · [Markdown](05-attention-pointer-doubling/PAPER.md) · [code](05-attention-pointer-doubling) |
| 6 | Value Embeddings: Inside a Language Model's Attention, One Learned Vector per Word Beats One per Two-Word Sequence Until the Sequence Has Been Seen About 100 Times in Training | [PDF](06-value-embeddings-word-vs-pair/paper.pdf) · [Markdown](06-value-embeddings-word-vs-pair/PAPER.md) · [code](06-value-embeddings-word-vs-pair) |

Each paper's related-work section lists the closest published work. Check it again before you submit, because the field moves fast.
