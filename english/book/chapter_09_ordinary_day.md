# Chapter 9. An Ordinary Day in the Life of an Admin

While Jax and Milo were living through the rescue of an entire universe as a moment of cosmic significance, three floors below—in the cramped on-call room of the Operations department—a perfectly ordinary day was beginning for administrator Ada.

Ada wasn't responsible for creating worlds. Ada was responsible for keeping the already-created worlds from falling over. That, as she liked to remind fresh interns, was "two very different jobs, and the second one is the one that actually pays."

The shift started, as always, at 07:00 cluster time—with the single most critical procedure in the entire data center. Ada walked over to the coffee machine.

```text
[HEALTH_CHECK]: coffee_machine_ops_floor_7
[STATUS]: OK
[BEANS]: 87%
[PRESSURE]: nominal
[UPTIME]: 3,412 years (last restart: The Great Apathy Incident)
```

"We live to fight another day," Ada nodded with satisfaction at the green status.

Of the thousands of pieces of hardware in the "Omega-194" cluster, the coffee machine was the one wrapped in the most sensors. After the `caffeine.sys` incident three thousand years ago, management had ruled that the ops-floor coffee machine carried the same criticality tier as the gravity core. And, frankly, it went down less often.

Ada sat at her terminal, took a sip from her mug, and opened the overnight ticket queue. There were forty-one.

```text
OPS-88412  [P3]  Universe 193: memory leak in dark_matter thread. Growing ~2% per eon.
OPS-88415  [P4]  Universe 188: user requested a rollback of reality to Tuesday. Reject.
OPS-88418  [P2]  Cron `supernova_scheduler` ran twice. Sector 12 now has two extra supernovae.
OPS-88420  [P5]  Someone left `console.log("Milo was here")` in the production laws of thermodynamics.
OPS-88431  [P3]  Complaint: people in Universe 195 have started asking about FPS. Monitor.
```

Ada sighed. A `console.log` in the laws of thermodynamics. That junior again.

She worked through the list methodically. The dark-matter leak in 193—restart the thread on schedule, don't wake the architects. The rollback-to-Tuesday request in 188—reject with the note "working as intended, you disliked Tuesday for objectively valid reasons." The extra supernovae—well, someone in Sector 12 would see a very pretty sky tonight; file it under feature.

By eleven o'clock she reached the strange spike in the 195 logs—the very one that had had the entire architects' floor in an uproar overnight.

```text
OPS-88431  [P3 → escalated]
Sol-3 cluster survived a near-OOM event.
CPU load: 99.9% → 12.4% in 3 seconds.
Fix author: eng.milo (junior)
Patch: sysctl vm.universe_caffeine_buffer=async_flush
Review: none. Documentation: none. Tests: none.
```

Ada froze with the mug at her lips.

"He saved a universe," she said slowly to the empty room, "with an undocumented one-liner off StackOverflow. No review. On a Friday night." She set the mug down. "And it worked. Worst of all, it worked."

She opened the ticket and, with a feeling of deep professional resignation, added to the comments: `Approved retroactively. Please add a comment to that line before I age another eon.`—and, after a moment's thought, gave it a thumbs-up. A good hack is a good hack.

At 11:47 a new ticket dropped into the queue. *That* one.

```text
OPS-88440  [P4 — Low]
Title: Provision a new universe instance
Requester: arch.jax
Parameters: --id=196 --parent=195 --enable-open-source=true
Comment: "Routine fork. Nothing special."
```

Ada read it twice.

Somewhere upstairs, in the architects' hall, this was probably an Event. A Birth. Maybe someone up there was staring through a screen right now, intoning solemn words about infinity. Down here, from the on-call room, it looked like `P4 — Low`. Routine fork. Nothing special.

She allocated the newborn world a block of quantum racks, verified that caffeine was baked into the constants **before** the Big Bang (this checklist item had a bold exclamation mark and the note "NOT LIKE IN 195!!! —Ada"), and pressed `Provision`.

```text
[PROVISIONING]: Universe 196 ...
[COFFEE_CONSTANT]: injected pre-bigbang ✔
[STATUS]: booting...
```

The newborn world's indicator lit up a steady green. Somewhere in there, someone's first sunrise was already breaking; someone was drawing a first breath; someone, thirteen-and-a-half billion years from now, would write their first line of code. To Ada it was just one more green dot on the panel. The forty-second of her shift.

She made a final entry in the on-call log and stretched.

```text
Shift: quiet.
Incidents: 0 (near-OOM closed before escalation, thanks to the junior).
Universes lost: 0.
Universes created: 1.
Cups of coffee: 6.
```

Ada was just about to pour a seventh cup and close out the shift when, at the very edge of the panel, in the corner of the new world's monitor, something blinked—barely perceptible. A tiny, almost invisible inbound packet. Not an error. Not an alert. Just a single line, rising from somewhere **below**, out of the depths of the freshly booted Universe 196:

```text
[196]: ...hello? is anybody there?
```

Ada looked at the line. Then at the coffee machine. Then back at the line.

"Okay," she said quietly, setting down her mug and pulling her chair up to the terminal. "*This* one, I don't think, is a `P4`."
