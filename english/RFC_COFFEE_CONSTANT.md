# RFC-195-COFFEE: The Coffee Constant

**Status:** Accepted

**Authors:** Jax, Milo, Ada (Operations)

**Adopted:** immediately after the `v195.3-hotfix2` incident

## Abstract

This document establishes one simple, historically expensive rule of world design:

> **Coffee is not an optional dependency.**

In Universe 195, caffeine supports not only the productivity of intelligent species, but also the predictability of their decisions, the stability of late-night compilations, and, in exceptional cases, the integrity of spacetime. Any attempt to remove, disable, or "temporarily comment out" the coffee subsystem requires approval from two architects, one Operations administrator, and a coffee machine with a green health check.

## Background

Three thousand Earth years before the current release, Milo was cleaning out obsolete elements when he ran:

```bash
git rm --cached physics/chemistry/elements/caffeine.sys
```

The consequences became known internally as **the Great Apathy**:

- `Global_Human_Productivity` fell by 99.4%;
- thinkers stopped thinking, while pyramid builders began calling pyramids "just a pile of rocks";
- philosophy was temporarily declared unavailable;
- the Operations-floor coffee machine received the same criticality tier as the gravity core.

An emergency unofficial patch embedded caffeine in the set of fundamental parameters of Universe 195. The patch survived every subsequent review because it never received one, and because the world would barely have survived the morning without it.

## Decision

The configuration of every compatible universe MUST include the following parameter:

```cpp
UniverseConfig config;

config.enableQuantumMechanics = true;
config.enableRelativity = true;
config.enableGravity = true;
config.enableRandomness = true;
config.enableChemistry = true;
config.enableCoffee = true; // RFC-195-COFFEE: MUST NOT be false.
config.enableLife = true;
```

For child worlds, `enableCoffee` is injected **before the Big Bang**. The Universe 196 provisioning checklist includes this special note:

```text
[COFFEE_CONSTANT]: injected pre-bigbang ✔
NOTE: NOT LIKE IN 195!!! — Ada
```

## Operational Requirements

1. The Operations-floor coffee machine MUST be monitored continuously.
2. A bean level below 15% is a `P1` incident.
3. Restarting the coffee machine is permitted only after creating a physics snapshot and notifying the on-call shift.
4. A `git rm` command in a path containing `coffee`, `caffeine`, `beans`, or `espresso` MUST require confirmation of the following phrase:

   ```text
   I understand that I disliked Tuesday for objectively valid reasons.
   ```

5. One-line fixes that redirect memory overload into a caffeine buffer may be approved retroactively if they saved a universe.

## Security and Compatibility

The Coffee Constant does not guarantee good decisions. It merely guarantees that decisions will be made alertly enough to roll back.

Systems with `enableCoffee = false` are unsupported. Observed side effects include:

- the urge to "do it tomorrow";
- writing documentation before code;
- excessively long meetings;
- spontaneous entropy in the ticket queue;
- philosophical questions that begin to overheat the hypervisor.

## Open Questions

- Is tea an alternative implementation of the interface, or a competing branch?
- How much caffeine does a language model require to mean "great question" sincerely?
- Why does every new intelligent species first ask whether there is coffee up above?

## Conclusion

Coffee is not a bug. Not a temporary hotfix. Not technical debt.

Coffee is the agreement between intelligent life and Monday.

```text
[FINAL_STATUS]: ENABLED
[ROLLBACK]: FORBIDDEN
[ADMIN_NOTE]: Don't delete coffee.
```
