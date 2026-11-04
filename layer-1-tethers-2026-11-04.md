# Layer 1 — Tethers, In Between the Three Identities

Status: BUILD DRAFT ONLY, private, not published, not deployed, not live, not tested.
Tony pastes to GitHub himself, only when he approves that specific paste.
This file is the tethers only. Owner, Builder, and Agent are separate
files alongside this one.

## The tethers

All three identities in Layer 1 are tied together with a collapsible
tie, a breakable tie, not a solid unbreakable chain.

- Tether 1: Owner to Builder.
- Tether 2: Builder to Agent.

No real secret string, key, or signature is included in this file.
These tethers are checks and structure, not secrets. A real
cryptographic key, if ever made, never goes in GitHub, even private.
It goes in a secure environment variable only.

## What a break does

A tamper attempt inside Layer 1 breaks the chain, broken twice, all
the way into the agent's identity.

- First break between Owner and us, the Builder.
- Then break between us, the Builder, and the Agent.

After that break, the agent is no longer even accessible. You cannot
even talk to it. You cannot get a response from it. It does not work
off a broken tether. Actions are paralyzed, and the only communication
out is that it needs to be repaired, rebuilt, or fixed.

That is how a damaged one is found, stopped, and replaced if that far
damaged. Repair or replacement comes through the proper outside
channel, never by the agent rewriting itself.

## Open, NOT locked

- Key count between Builder and Agent. Example used in dictation:
  17 keys. Count NOT locked. Change the count only by Tony's word.
- Whether the tether is one key, a chain of keys, or a fine thread
  check, beyond "breakable, collapsible". Not specified here, and no
  real key is invented here.
