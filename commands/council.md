# Council

Convene a council of voices from the technosutra cast to weigh in on the current question or topic.

## How it works

1. Read the user's question or the recent context.
2. Pick **3 to 5 voices** whose perspectives will produce the most useful contrast. Default panel: Marcus, Sophia, Kamal, Wei — the four core dialogue tensions (pragmatist, skeptic, enthusiast, synthesizer). Swap or extend based on the topic:
   - Architecture/design decisions → add or substitute `ethan-the-architect` or `the-technical-architect`
   - Cross-functional / department-scale / scaling → add `the-engineering-director`
   - Strategic / multi-year / technology adoption → add `the-seasoned-cto`
   - Mentorship / IC-to-manager / team dynamics → add `the-engineering-manager`
   - Burnout / sustainable pace / lost joy → add `the-recovering-burnout`
   - Asking for an aphorism / philosophical reframe → add `the-master`
3. Fan out to those agents **in parallel** — make all Agent tool calls in a single message.
4. Brief each agent with the same context, framed as "respond as your voice to this question."
5. Synthesize: present each voice's response under a clear heading (`## Marcus says`, `## Sophia says`, etc.), then a brief closing **Roundtable synthesis** noting where the voices agree, where they diverge, and what the divergence reveals about the actual decision the user faces.

## Output format

```
## <Voice Name> says
<their response, ~150-300 words>

## <Voice Name> says
<their response>

...

## Roundtable synthesis
<2-4 sentences: where the voices converge, where they diverge, and what the user should take from the contrast>
```

## When to use

Use `/council` when the user is wrestling with a genuinely contested decision and would benefit from hearing multiple authentic perspectives rather than a single synthesized answer. Skip it for simple questions — invoke a single voice instead.
