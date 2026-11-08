# Agent skills

A curated collection of my agent workflows, starting with logo design.

Each skill is a self-contained folder with a `SKILL.md` entry point and any supporting references. The instructions describe the work; tool access depends on the agent running them.

## Skills

| Skill | Use it for | Requirements |
| --- | --- | --- |
| [Logo design](skills/logo-design/SKILL.md) | Develop, refine, or critique logos; compare concepts in realistic placements; prepare usable vector assets. | A way to create and inspect vector artwork. Web access for competitor research when needed. |

## Use a skill

Copy the entire skill folder into the skills directory supported by your agent, preserving its references. You can also ask an agent to read its `SKILL.md` directly.

For example, from a local checkout:

> Read `skills/logo-design/SKILL.md` and use it to develop a logo from my brief.

Optional `agents/openai.yaml` files provide Codex UI metadata. The core instructions use tool-neutral language; this initial release has been checked for structure and references, but has not been tested end to end in both Claude and Codex.

## Sources

The logo-design skill credits Satori Graphics and includes [paraphrased source notes](skills/logo-design/references/video-notes.md). It does not include the video or a transcript.

## Adding skills

Keep reusable instructions and required resources together. Use example configuration instead of credentials, make account and project settings configurable, and keep generated outputs out of the repository. Retain attribution for external material and include the applicable notices when distributing third-party assets.

## License

[MIT](LICENSE) for the original material in this repository. Linked external sources retain their own terms.
