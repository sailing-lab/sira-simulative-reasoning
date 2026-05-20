# SiRA: General Agentic Planning through Simulative Reasoning with World Models

Project page for **SiRA** (Simulative Reasoning Architecture), a goal-oriented agent architecture that augments reactive policies (System I) with explicit **simulative reasoning** (System II) through a world model:

- **Encoder** — maps observations into a discrete natural-language belief state.
- **Planner with World Model** — samples candidate abstract actions, predicts their consequences, and scores goal progress with a critic.
- **Actor** — grounds the selected abstract action into a concrete environment command.

Instantiated as a web-browsing agent, SiRA delivers up to **124% higher task completion** than a matched reactive baseline and raises constrained-navigation success from **0% to 32.2%** over a representative open-web agent, with the advantage persisting across three qualitatively distinct task categories.

## Links

- Project page: <https://sira-simulative-reasoning.github.io>
- Code: <https://github.com/sailing-lab/sira>

## Authors

Mingkai Deng\*, Jinyu Hou\*, Zhiting Hu, Eric P. Xing. (\*Co-First Authors)
Institute of Foundation Models · Carnegie Mellon University · UC San Diego.

## Local preview

```sh
python3 -m http.server 8000
# then open http://localhost:8000
```
