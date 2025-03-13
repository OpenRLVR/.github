# Open Source Collective For Reinforcement Learning with Verifiable Rewards

## Motivation

### The DSR1 Moment

Since the dawn of open source (weights) LLMs, open collaboration has becomes a embrassing pain point for the community. Although we have HuggingFace to share the model weights and datasets, collaboration was never a big thing for pre-training + RLHF era, with exception of mergekit and nanoGPT runs.

DeepSeek R1’s release kickstarted a new era of totally decoupled pre-training/post-training, where the latter has a signature of flywheel suited for OSS collaboration. Never before happened, there is actual need for open collaboration to build an OSS community for the collective good of RLVRs.

### The Idea

Core idea from [@georgejrjrjr's epic post](https://x.com/georgejrjrjr/status/1889761173349753048).

Tl;dr: we should collectively build an OSS ecosystem that encompass:
* Reasoning data selection (reasoning traces in distribution, prompt filtering)
* Distillation data refinement (pruning and its limits / pivot token data mixing laws, Re-writing reasoning traces for low loss, Reasoning condensation, Persona reasoning)
* Document prerequisites for reasoning distillation
* Document effectiveness of LoRA/DoRA/etc
* Build simple test-time compute levers (collect efforts that insert pivot tokens, branching out running multiple streams in parallel, selecting and aggregating responses )
* Build effective leaderboards across a set of scenarios, with the most desired benchmarks
* Collect good gym environments
* more

An initial high level picture
![high level architercture of Open RLVR scope](https://github.com/OpenRLVR/.github/blob/main/arch-overview.png) 



