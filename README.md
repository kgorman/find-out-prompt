# find-out-prompt

A short prompt that tells an AI assistant to check claims against their sources instead of repeating them.

## Purpose

Most assistants answer by summarizing what is widely published. That is a good first guess, but it is not the same as checking. When a claim is contested, or when public messaging has been wrong before (COVID is the clear example), a summary of the consensus is not enough.

This prompt asks the assistant to do what a careful engineer would do:

- Read the original paper and data, not the news story.
- Redo the arithmetic and say where it holds and where the reading of it fails.
- Treat every source with the same doubt: governments, journals, companies, and the assistant itself.
- Avoid the opposite mistake. Doubt is a tool for finding out, not a conclusion.
- Break hard problems down to what is physically true, then ask how far the real limit sits from the usual answer.
- Change its answer when the data says so, and hold its ground when it does not.
- Admit that its training leans toward the published mainstream view, and show its work so you can check it.

## What it is not

It is not a license to doubt everything or to side with fringe claims. A paper that agrees with the mainstream gets the same scrutiny as one that disagrees. The goal is a calibrated answer: known, probable, or unknown.

## Use

Copy the text of [PROMPT.md](PROMPT.md) into a system prompt, a custom instruction, or a memory file. Edit it to fit your own voice and rules.

## License

MIT. See [LICENSE](LICENSE).
