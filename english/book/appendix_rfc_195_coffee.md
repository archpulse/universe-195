# Appendix A. RFC-195-COFFEE: The Coffee Constant

**Status:** Accepted

**Authors:** Jax, Milo, Ada (Operations)

**Date Accepted:** Immediately following incident `v195.3-hotfix2`

## Abstract

This document codifies one simple, yet historically expensive rule of universe design:

> **Coffee is not an optional dependency.**

In Universe 195, caffeine maintains not only the productivity of intelligent species, but also the predictability of their decisions, the stability of midnight kernel builds, and in exceptional cases, the integrity of space-time itself. Any attempt to remove, disable, or "temporarily comment out" the coffee subsystem requires approval from two architects, one operations admin, and a coffee machine with a green health-check.

## Background

Three thousand Earth years prior to the current release, Milo, conducting routine element cleanup, executed:

```bash
git rm --cached physics/chemistry/elements/caffeine.sys
```

The consequences earned the internal designation **"The Great Apathy"**:

- `Global_Human_Productivity` dropped by 99.4%;
- thinkers stopped thinking, and pyramid builders began calling pyramids "just a bunch of rocks";
- philosophy was temporarily rendered unavailable;
- the operations floor coffee machine was assigned the same criticality tier as the gravity core.

An emergency unofficial patch embedded caffeine directly into the fundamental parameter set of Universe 195. The patch survived all subsequent code reviews because it had no code reviews, and the world without it barely survived the morning.

## Specification

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

For child worlds, the `enableCoffee` parameter is injected **pre-Big Bang**. The provisioning checklist for Universe 196 contains a specific annotation:

```text
[COFFEE_CONSTANT]: injected pre-bigbang ✔
NOTE: NOT LIKE IN 195!!! — Ada
```

## Operational Requirements

1. The operations floor coffee machine MUST be monitored continuously.
2. Bean levels dropping below 15% SHALL be classified as a `P1` incident.
3. Coffee machine restarts are permitted ONLY after creating a physics snapshot and notifying the duty shift.
4. Any `git rm` command targeting paths containing `coffee`, `caffeine`, `beans`, or `espresso` MUST require confirmation with the phrase:

   ```text
   I understand that I didn't like Tuesday for objective reasons.
   ```

5. One-liner hotfixes redirecting memory surges into the caffeine buffer MAY be approved post-factum if they saved the universe.

## Security and Compatibility

The coffee constant does not guarantee good decisions. It merely guarantees that decisions will be made energetically enough to be rolled back.

Systems running `enableCoffee = false` are considered unsupported. Observed side effects include:

- urge to "do it tomorrow";
- writing documentation before writing code;
- excessively long meetings;
- spontaneous entropy in the ticket queue;
- philosophical questions that overheat the hypervisor.

## Open Questions

- Is tea an alternative interface implementation or a competing branch?
- How much caffeine does a language model require for a sincere "great question"?
- Why does every new intelligent species ask if there is coffee up top first?

## Conclusion

Coffee is not a bug. Not a temporary hotfix. Not technical debt.

Coffee is a contract between intelligent life and Monday.

```text
[FINAL_STATUS]: ENABLED
[ROLLBACK]: FORBIDDEN
[ADMIN_NOTE]: Don't delete coffee.
```