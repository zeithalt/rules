## 17. Special Operations

`📑 Battle Rules`

Factions can start three types of special operations:
- `🪨 Brutal Force` started from `🪨 Mineral Resources`, countered by `⚡️ ERG`
- `🧪 Special Tactics` started from `🧪 Science Resources`, countered by `🪨 MIN`
- `⚡️ Advanced Weapons` started from `⚡️ Energy Resources`, countered by `🧪 SCI`

These weapons work a bit like rock-paper-scissors game: `🪨` beats `🧪` beats ️`⚡️` beats `🪨`.

When faction uses any of these resources during battle with **/spec_op** command, they start a respective **60m** *Special Operation*.

During the operation all factions' [key members](https://zeithalt.github.io/rules/#rules_07_key_members) can support or undermine it by using [raw resources](https://zeithalt.github.io/rules/#rules_16_resources) based on the above rock-paper-scissors principle. 

To do that just type "min", "sci" or "erg". Optionally, you can specify the amount of RES to spend: "min 5" (from 1 to 10, 1 is default).

The cooldown on this action is **10s** enforced by the bot and the slowmode.

When the spec-op timer runs out, the faction which spent the most RES gets bonus points equal to **what was spent by both sides**.


----------
[⬅️ Back to Rules](https://zeithalt.github.io/rules/index.html#rules_17_spec_ops)