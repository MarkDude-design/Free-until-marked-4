# NEXT ROUND CFP packet — Who Is Driving?

**Prepared:** November 2, 2026 | **State:** DRAFT / NOT SUBMITTED (except any separate, independently receipted SCaLE proposal). This is a *venue-tailored* source; original `SUBMISSION.md` and canonical slides are preserved. Speaker: **Mark Terranova (MarkDude)**.

## Primary match: BSidesSF 2027 — Informational / security talk

- CFP: https://bsidessf.org/cfp
- Deadline: 2026-11-09 soft deadline; 2026-11-13 final close per https://pretalx.com/bsidessf-2027/
- Format: Propose 30m only after adding a real annotated control/failure example and a short audience test; existing source is ~20m
- Suggested public title: **Who Is Driving? Permission, Revocation, and the Return Path for AI Agents**
- Brief hook: An agent can take the wheel. What permissions did we give it, and what happens when we pull the emergency cord?

### Ready-to-paste abstract

AI-agent demonstrations emphasize what a tool can do. Security depends on who allowed it, what resources it could reach, and whether anyone can take back control. This talk starts with a bus and a crash, then uses the same simple frame to examine practical delegation: the granted capability, the boundary, the receipt, and the return path.

We distinguish a human instruction from executable authority, show why a "STOP" signal is useful only if it reaches the component that can still act, and review the risks of giving a seemingly helpful tool access beyond its job. A bounded real-world agent/tool example, with redacted evidence rather than speculation, grounds the difference between a tool doing the right thing and a system preventing the wrong thing.

The central question isn't whether a machine can drive the bus. It's who holds the brake, who can inspect the route, and what happens if the driver stops listening. Delegation without a return path is not reliable control.

### Key takeaways

- Role fit does not imply authorization.
- Stop controls must actually interrupt action, not just signal intent.
- A return path includes an auditable event trail and human revocation.

## Second match: DPE Summit 2027 — Development Productivity / platform and agents

- CFP: https://dpe.org/
- Deadline: 2026-11-13
- Suggested public title: **The Wheel and the Return Path: A Practical Model for AI Tool Permissions**

### Ready-to-paste alternate abstract

AI-assisted development can move rapidly from suggestions to actions. This talk introduces a simple working model for deciding whether a tool should receive authority: is it right for the job, can we bound and observe the action, can we revoke the permission, and can we reconstruct what happened after failure? A short example of an agent using tools demonstrates how permissions, stop conditions and receipts belong in the workflow from the beginning — rather than being added after the demo. The result is a vocabulary teams can use when handing the wheel to automation.

## Speaker bio (~60 words)

Mark Terranova (MarkDude) is a longtime Linux and open-source community participant, maker and speaker from California. His talks explore how tools change culture, and how people preserve authorship, accountability and an exit path when collaborating with AI. He brings a hands-on, playful perspective to community technology and creative practice.

## Local stage / low-polish path

Noisebridge 5MoF https://luma.com/noisebridge — five-minute crash / who drives / red cord. BALUG optional 20m.

## Reviewer notes, evidence and privacy gates

IMPORTANT: current 10-slide skeleton leaves the owner-defined return-path slot open. A concrete stop/revocation demo, source evidence and 30m length are required for BSidesSF. Do not assert a tested mechanism without reading actual logged tests. The talk remains DISTINCT from Bus B, the message-carrier talk.

## Next action

Quickest stage: Noisebridge lightning. High-value conference: BSidesSF soft Nov 9 / final Nov 13, conditional on technical demonstration and 30m expanded outline.

**Submission controls:** A committed proposal is not a sent/submitted proposal. Obtain actual portal confirmation/ID or recorded organizer email before updating status. Verify CFP requirements, rights for streamed/CC-BY media, and whether a given public repo links to assets that are genuinely releasable. Do not expose private histories or ungated names.

### CFP source checked Nov 2, 2026

- https://bsidessf.org/cfp
- https://dpe.org/
