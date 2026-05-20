# SiRA: General Agentic Planning through Simulative Reasoning with World Models

Project page for **SiRA** (Simulative Reasoning Architecture), a goal-oriented, model-agnostic architecture that instantiates **simulative reasoning** via an LLM-based world model over natural-language belief states:

- **Encoder** — maps observations into a discrete natural-language belief state.
- **Planner with World Model** — samples candidate abstract actions, predicts their consequences, and scores goal progress with a critic.
- **Actor** — grounds the selected abstract action into a concrete environment command.

Evaluated as a web-browsing agent, simulative reasoning delivers up to **124% higher task completion** than a matched reactive baseline and raises constrained-navigation success from **0% to 32.2%** over a representative open-web agent, with the advantage persisting across three qualitatively distinct task categories.

## Links

- Project page: <https://sira-simulative-reasoning.github.io>
- Paper: <https://arxiv.org/abs/2507.23773>
- Code: <https://github.com/sailing-lab/sira>

## Authors

Mingkai Deng\*, Jinyu Hou\*, Zhiting Hu, Eric P. Xing. (\*Co-First Authors)
Institute of Foundation Models · Carnegie Mellon University · UC San Diego.

## Local preview

```sh
python3 -m http.server 8000
# then open http://localhost:8000
```
