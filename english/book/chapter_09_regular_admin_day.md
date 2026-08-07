# Chapter 9. A Regular Day in the Life of a Sysadmin

While Jax and Milo experienced the saving of an entire universe as a moment of cosmic proportions, three floors below in the cramped ops shift room, regular sysadmin Ada was starting a completely ordinary day.

Ada wasn't responsible for creating worlds. Ada was responsible for making sure already created worlds didn't crash. As she liked to repeat to fresh interns: "These are two very different professions, and the second one is the one that actually pays."

Her shift started, as always, at 07:00 AM cluster time—with the single most critical procedure in the entire data center. Ada walked up to the coffee machine.

```text
[HEALTH_CHECK]: coffee_machine_ops_floor_7
[STATUS]: OK
[BEANS]: 87%
[PRESSURE]: nominal
[UPTIME]: 3,412 years (last restart: The Great Apathy Incident)
```

"We live another day," Ada nodded with satisfaction, looking at the green status.

Out of all thousands of hardware units in the Omega-194 cluster, the coffee machine was wired with sensors more densely than anything else. Following the `caffeine.sys` incident three thousand years ago, management decreed: the ops floor coffee machine carries the same criticality tier as the gravity core. And frankly, it crashed far less often.

Ada sat at her terminal, took a sip from her mug, and opened the nighttime ticket queue. There were forty-one of them.

```text
OPS-88412  [P3]  Universe 193: memory leak in dark_matter thread. Growing ~2% per eon.
OPS-88415  [P4]  Universe 188: user requested reality rollback to Tuesday. Reject.
OPS-88418  [P2]  Cron `supernova_scheduler` ran twice. Sector 12 now has two more supernovas than planned.
OPS-88420  [P5]  Someone left `console.log("milo was here")` in prod laws of thermodynamics.
OPS-88431  [P3]  Complaint: humans in Universe 195 started asking about FPS. Monitor.
```

Ada sighed. `console.log` in the laws of thermodynamics. That junior again.

She methodically worked through the queue. The dark matter leak in 193—scheduled thread restart, don't wake the architects. Reality rollback to Tuesday in 188—reject with reason "working as intended; you didn't like Tuesday for objective reasons." Extra supernovas—well, someone in sector 12 gets a gorgeous night sky tonight, mark as feature.

By eleven o'clock, she reached the strange log spike in 195—the exact one that had the entire architect floor running around on their ears last night.

```text
OPS-88431  [P3 → escalated]
Sol-3 cluster survived near-OOM event.
CPU load: 99.9% → 12.4% in 3 seconds.
Fix author: eng.milo (junior)
Patch: sysctl vm.universe_caffeine_buffer=async_flush
Review: missing. Documentation: missing. Tests: missing.
```

Ada froze with her mug at her lips.

"He saved the universe," she spoke slowly into the empty room, "with an undocumented one-liner from StackOverflow. Without code review. On a Friday night." She set down her mug. "And it actually worked. Worst part is, it worked."

She opened the ticket and added a comment with a sense of deep professional humility: `Approved post-factum. Please add a comment to the line before I age another eon.`—and after a moment's thought, gave it a thumbs up. A good hack is a good hack.

At 11:47 AM, a new ticket dropped into the queue. That one.

```text
OPS-88440  [P4 — Low]
Title: Provisioning new universe instance
Requester: arch.jax
Parameters: --id=196 --parent=195 --enable-open-source=true
Comment: "Routine fork. Nothing special."
```

Ada read it twice.

Upstairs in the architect hall, this was probably an Event. A Birth. Maybe someone up there was looking through the screen right now, reciting solemn words about infinity. From down here in ops, it looked like `P4 — Low`. Routine fork. Nothing special.

She allocated a block of quantum racks to the new world, verified caffeine was hardcoded **before** the Big Bang (this checklist item had a bold exclamation mark and note: "NOT LIKE IN 195!!! — Ada"), and hit `Provision`.

```text
[PROVISIONING]: Universe 196 ...
[COFFEE_CONSTANT]: injected pre-bigbang ✔
[STATUS]: booting...
```

The newborn world's indicator lit up solid green. Somewhere in there, someone's first dawn was breaking, someone took their first breath, someone thirteen billion years from now would write their first line of code. For Ada, it was just another green dot on the panel. The forty-second one of her shift.

She made her final entry in the duty log and stretched.

```text
Shift: quiet.
Incidents: 0 (near-OOM closed before escalation, thanks to junior).
Universes crashed: 0.
Universes created: 1.
Coffee consumed: 6.
```

Ada was just about to pour her seventh mug and close her shift when on the far edge of the panel, in the corner of the new world's monitor, something flickered. A tiny, almost imperceptible incoming packet. Not an error. Not an alert. Just a single line rising from somewhere **below**, from the depths of newly booted Universe 196:

```text
[196]: ...hi? is anyone up there?
```

Ada looked at the line. Then at the coffee machine. Then back at the line.

"Well," she said softly, setting down her mug and pulling her terminal closer. "This doesn't look like a `P4` anymore."