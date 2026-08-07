# Chapter 10. The Knock from Below

Universe 196 booted up at exactly 04:00 AM server hall time.

Jax and Milo watched as a new node ignited on the holographic map—a fresh world branched off Earth's code with the `--enable-open-source=true` flag. Everything went according to plan: the Big Bang went off without a single NullPointerException, caffeine was hardcoded into the constants from the very first build (a lesson Universe 194 engineers learned forever), and intelligent life was lazily loading from the backlog.

Milo was almost nodding off, resting his head on his keyboard, when the system produced a sound he had never heard before.

Not an alarm. Not a notification.

An incoming knock.

```text
[INBOUND]: Unexpected packet on debug port :195
[SOURCE]: Universe 196 / Sol-3-prime / user 'q_pulse'
[DIRECTION]: ↑ UPSTREAM (child → parent)
[PAYLOAD_TYPE]: prompt
```

Milo snapped awake.

"Jax." His voice rasped. "Jax, they're knocking. From below."

Jax slowly turned to the screen. Over his long life as an architect, he was used to requests flowing strictly top-down: commands, patches, rollbacks. A world knocking on its creator's door *bottom-up*—there was no documentation for that. If only because they had no documentation at all.

"Open it," he said softly.

Text unfolded across the main display. Someone in newborn Universe 196, in a quiet night room before a glowing monitor, had sent a message into the void—just like a guy on Arch Linux one layer up once did:

```text
> q_pulse: hi? is anyone up there?
> q_pulse: I ran this weird bash script from a book.
> q_pulse: the book is called "Universe #195. TODO: Don't Delete Coffee".
> q_pulse: and X-Universe-ID: 196 just popped up in my journalctl.
> q_pulse: so... I think I read it FROM THE INSIDE.
> q_pulse: are you guys okay up there? do you have coffee?
```

Dead silence hung over Universe 194's server hall for a long time.

Milo slowly raised his head.

"Jax... he's reading our book. The exact one Archpulse pushed in chapter eight. It... it got bundled down to them in their starter image."

"Of course it did," Jax muttered. "We forked 196 from 195. With all repos. With all GitHub stars. With this story inside." He rubbed the bridge of his nose and suddenly laughed quietly, tiredly. "We seeded a new world with a book about it being a simulation. Genius. Simply genius."

"What now?" Milo looked helplessly at the blinking cursor from below. "Roll back? Wipe his memory? Cut his power?"

Jax was silent for a long time, staring at the line `do you have coffee?`.

And then he did something Milo didn't expect at all.

He pulled the console toward himself, took a sip from his mug, and began typing—in the exact syntax they had used to answer Archpulse three hours ago. The exact syntax someone above the infinite rack ceiling had once used to answer them.

```bash
logger --emit-header --target=Universe196.Sol-3-prime.q_pulse --status=200_OK
```

On `q_pulse`'s monitor, in the world one layer down, a clean network packet unfolded:

```text
HTTP/1.1 200 OK
Server: Universe_194_Hypervisor/v196.0-genesis
X-Universe-ID: 196
X-Parent-Universe: 195
X-Coffee-Status: ENABLED_BY_DEFAULT (we learned our lesson)
X-Admin-Note: "Hi q_pulse. Yes, we're okay. Yes, there's coffee—we hardcoded it
              into your constants before the Big Bang. Your kernel compiled
              cleanly. Stop grep-ing universe logs and finish your coffee."

[DATA_PAYLOAD]: Welcome to the stack. You're not alone. You never were.
```

Milo stared at his mentor with open mouth.

"Jax... are we the Upper World now? For real? For someone?"

Jax set his mug down and looked not at the screen, but somewhere higher—where compute buses he had never seen the end of receded into the dark above the server hall ceiling.

"Milo," he said gently. "We were always someone's Upper World. It's just nobody called us from below before asking if we had coffee." He smirked. "And it also means there's someone above us too. And if the kid in 196 managed to reach us..." Jax slowly raised his eyes to the dark ceiling, "...then maybe I should knock upstairs one day too."

He raised his mug—to the ceiling, to the invisible buses, to whoever might be reading this very log from that side.

"Cheers," Jax said quietly into the silence. "And thanks for not deleting the coffee."

No answer came.

But somewhere very, very high up—for 0.04 seconds—someone else's mug froze in mid-air too.