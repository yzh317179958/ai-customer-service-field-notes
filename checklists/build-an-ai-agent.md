# Seven steps to build an AI agent that survives real work

A demo agent takes an afternoon. An agent that handles thousands of real cases a month is mostly work outside the model. This is the order we follow. The full write-up with the incidents behind each step: [How to build an AI agent that survives real work](https://ai.dingboai.com/en/how-to-build-an-ai-agent.html).

## 1. Pick one job

- [ ] One job, stated in one sentence ("reply to emails asking where an order is").
- [ ] A written definition of a finished case.
- [ ] The job repeats daily, has real volume, and has a system behind it to look things up in.

## 2. Connect tools, read-only first

- [ ] Every lookup a person does for this job exists as a tool the model can call.
- [ ] The first version can read and cannot change anything.
- [ ] Each tool returns a small, fixed answer. Statuses come back as one of a few fixed values, never as a sentence.
- [ ] "Nothing found" and "the lookup failed" are separate results with separate handling.

## 3. Prepare the facts before the model sees them

- [ ] The model never receives a whole thread, a whole order or a whole document.
- [ ] Input is a short list of facts: what the customer wants now, what was promised, what was done, what is missing.
- [ ] You have printed what the model actually receives and counted its size.

## 4. Write the rules once

- [ ] How the agent should think and speak lives in one text. Everything else refers to it.
- [ ] No rule exists in two places with different wording.
- [ ] Rules are principles, not ready-made sentences. A model copies example sentences word for word.

## 5. Set the approval lines

- [ ] A list, action by action: what the agent does alone, what a person approves.
- [ ] Anything that costs money or sends goods is approved by a person.
- [ ] Records are written from the version the person approved, not from the agent's first proposal.

## 6. Replay real cases before launch

- [ ] Real past cases, run without sending anything.
- [ ] Each case run twice. Model output varies between runs.
- [ ] Anything that changes over time is frozen to the moment of the original case.
- [ ] The replay cannot write or send. You checked by trying a write and seeing it fail.

## 7. Launch with review, then measure what people change

- [ ] A person reviews every output at launch.
- [ ] The agent's draft and the version that was sent are stored in separate fields.
- [ ] Edits are grouped by what changed: removed promise, added fact, replaced "no information".
- [ ] A type of reply is sent without review only after it has gone out unchanged case after case.

## When something goes wrong

- [ ] Remove first: the repeated explanation, the two rules that disagree, the step that adds nothing.
- [ ] Add a rule only if it is a general principle. A rule written for one case makes the next case worse.
