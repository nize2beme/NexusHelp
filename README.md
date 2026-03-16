## Player Commands

### Getting Started

| Command | Cost | Description |
|---|---|---|
| `!join` | free | Required before using any economy commands. Grants 100 C0IN starter bonus. |
| `!join @referrer` | free | Join and credit a referrer — you get 100 C0INs, they get 200 C0INs. Bonuses scale with the economy. |

---

### Core Economy

| Command | Cost | Description |
|---|---|---|
| `!mine <CODE>` | free | Claim mining reward. Requires rotating code shown on overlay. Base 50 C0INs + 15 per level. 5-min cooldown. |
| `!invest` | 200+ | Upgrade mining level (max 10). Cost increases 150 C0INs per level. |
| `!specialize deep/speed/lucky` | 2,000 | Choose a mining specialization at level 5+. One-time choice. |
| `!stake <amount>` | free | Move liquid C0INs to your hack-proof vault. |
| `!unstake <amount>` | free | Move vault C0INs back to liquid (5-min cooldown). |
| `!daily` | free | 23h cooldown. Streak rewards: 100 → 175 → 350 → 1,000 C0INs. |
| `!checkin` | free | 4h cooldown. 50–150 C0INs. |
| `!weekly` | free | 72h cooldown. 600–1,500 C0INs + Crypt0 bonus at 2/4/8-week streaks. |
| `!wallet` | free | Your balance, vault, Crypt0 holdings, level, shields, streaks. |
| `!stats [@user]` | free | Full career stats. Omit `@user` for your own stats. |
| `!top` | free | Top 5 leaderboard (rich / hackers / miners). |
| `!rig buy/upgrade` | varies | Purchase or upgrade a Mining RIG for automated passive mining income. Max level 10. |
| `!help` | free | Full command list — whispered privately (public @-reply fallback on Twitch). |

**Mining Specializations** (requires Mining Level 5 + 2,000 C0INs):

| Style | Yield | Cooldown |
|---|---|---|
| `deep` | 2× base | 8 min |
| `speed` | 0.7× base | 3 min |
| `lucky` | 1× base | 5 min (10% chance for 5× jackpot) |

---

### Hacking

| Command | Cost | Description |
|---|---|---|
| `!hack @user` | 100 | 45% chance to steal 20% of their liquid balance. |
| `!stealth @user` | 200 | Silent hack (no feed message). Steals 10% on success. |
| `!investhack` | 200+ | Upgrade hack level (max 5). Increases hack success rate. |
| `!hacktype` | 500 | Switch hack style (requires Hack Level 3+). |
| `!trap` | 150 | Set a 1h trap. Returns 50% of any incoming hack cost to attacker. |
| `!bait` | 75 | Set a 30-min fake balance bait. Triggers counter-hack. |
| `!insure` | 100 | 1h insurance. Returns 40% of any stolen amount on a failed hack defense. |
| `!vaultcrack @user` | 300 | 15% chance to steal 15% from their vault (bypasses stake protection). |
| `!shield` | 150 | 30-min hack immunity. Stackable — multiple purchases extend duration (8h max cap). |
| `!investdefense` | 200+ | Upgrade defense level (max 10). Each level reduces incoming steal by 2% (5% floor). Cost: 200 + 175 per level. |
| `!trojan @user` | 250 | Plant a trojan — 35% base success (scales with hack level). Drains ~20% of target's coins over 72 hours. |
| `!cleantrojan` | free | Remove an active trojan from yourself. |
| `!hackprestige` | 2,000 | At max hack level (10), reset to level 1 for a permanent +5% steal bonus. Stacks up to 60% max steal. |
| `!abounty @user <amount>` | amount | Admin-style anonymous bounty — source is hidden. |
| `!bounty @user <amount>` | amount | Public bounty. Anyone who hacks the target claims it (min 50). |

**Hack Styles** (switched with `!hacktype`, requires Hack Level 3+):

| Style | Effect |
|---|---|
| `ransomware` | On successful hack, target must `!pay` back 50% within 2 min or lose it. |
| `cryptojack` | Instead of stealing coins, redirect target's next 3 `!mine` rewards to you. |
| `wipe` | Lower steal % but destroys 10% of target's lifetime earned (cosmetic unlock threat). |

**Immunity:** New players are immune for 30 minutes **or** until they've earned 500 C0INs (whichever comes first).

**Post-Hack Shield:** After being successfully hacked, the victim automatically receives a 2-minute shield to prevent pile-on attacks from multiple hackers.

---

### Raids & Social

| Command | Cost | Description |
|---|---|---|
| `!raid @user` | 75 | Open a 30s raid window. Others can `!join` to split the loot. |
| `!join` | 75 | Join the active raid. |
| `!duel @user <amount>` | amount | Challenge to a 50/50 coin flip. Target has 60s to `!accept`. |
| `!offer @user <amount>` | amount | Offer C0INs to a player. They have 60s to `!accept`. |
| `!accept @user` | free | Accept a pending duel or trade offer. |
| `!flex <amount>` | amount | Burn coins for a "Whale" badge on the leaderboard + feed shoutout (30 min). Min 500. |
| `!mystery` | 100 | Random outcome: 1–5× payout, free shield, or small loss. |
| `!predict up/down <amount>` | amount | Bet on Crypt0 price direction. 5-min window. 1.8× payout. |
| `!redeem <CODE>` | free | Redeem a code drop. Everyone who types it within the window wins. |
| `!verify <CODE>` | free | Verify you're watching. +75 C0INs + 1.5× passive for 30 min. |
| `!heist <amount>` | amount | Start a group heist (100-5,000 C0INs buy-in). Need 3+ crew within 60s. |
| `!heist join` | buy-in | Join an active heist. Success = 3× buy-in; failure = lose buy-in. |

---

### Shop & Cosmetics

| Command | Description |
|---|---|
| `!shop` | View available titles and their prices/requirements. |
| `!equip <title>` | Equip a purchased title. Shown on the leaderboard. |

**Available Titles** (price = lifetime earned required — you must have earned at least this much to unlock):

| Title | Price / Lifetime Earned Required |
|---|---|
| 😎 Chad | 500 |
| 💻 Hacker | 1,500 |
| 👻 Ghost | 1,500 |
| ⭐ VIP | 5,000 |
| 💰 Baron | 10,000 |
| ₿ Crypto | 25,000 |
| 🔥 Legend | 50,000 |
| 💎 Diamond | 100,000 |
| ⚡ Glitch | 75,000 | **Animated** — glitch effect |
| 🔮 Plasma | 125,000 | **Animated** — rainbow gradient |
| 🌋 Inferno | 200,000 | **Animated** — fire glow |

---

## Market & Trading

Crypt0 (Ͼ) is the in-game cryptocurrency. Its price fluctuates continuously based on a random walk simulation with configurable volatility, event shocks, and player sentiment.

| Command | Description |
|---|---|
| `!buy <amount>` | Buy Crypt0 with C0INs at the current market price. |
| `!sell all` / `!sell <amount>` | Sell Crypt0 back to C0INs. |
| `!long <collateral> [leverage]` | Open a leveraged long position (price goes up = profit). Max 40× leverage. |
| `!short <collateral> [leverage]` | Open a leveraged short position (price goes down = profit). Max 40× leverage. |
| `!close` | Close your open leveraged position. |
| `!stoploss <percent>` | Set a trailing stop-loss (5-50%) on your open position. Auto-closes if price drops this % from peak. |
| `!portfolio` | View your Crypt0 holdings, open position, and unrealized P&L. |
| `!limit buy <amount> at <price>` | Place a limit buy order. Executes when price drops to target. |
| `!limit sell <amount> at <price>` | Place a limit sell order. Executes when price rises to target. |
| `!orders` | View your pending limit orders. |
| `!cancel` | Cancel your pending limit order. |

**Vault yield tiers** (compound each passive tick):

| Staked | Yield per tick |
|---|---|
| > 20,000 C0INs | 0.25% |
| > 5,000 C0INs | 0.15% |
| Any amount | 0.10% |

---

## Hacking System

Hack success rate improves with `!investhack` levels (max 5). Hacks that fail still cost 100 C0INs. Hacks against the same player have a 60-second cooldown.

**Hack outcome modifiers:**
- Target has `!shield` → hack is blocked entirely
- Target has `!trap` → attacker loses 50% of their hack cost back
- Target has `!bait` → attacker triggers a trap counter-hack
- Active **Guild War** → hack steal % is doubled between warring guilds

The overlay shows the "Most Wanted" player (current #1 hack target) in the header ticker with a 💀 skull indicator.

---

## Guild System

| Command | Cost | Description |
|---|---|---|
| `!guild create <Name> <TAG>` | 500 | Create a guild. You become leader. TAG is 2–5 chars. |
| `!guild invite @user` | free | Invite a player (they accept with `!guild accept`). |
| `!guild accept` | free | Accept a pending guild invite. |
| `!guild decline` | free | Decline a pending guild invite. |
| `!guild leave` | free | Leave your current guild. |
| `!guild kick @user` | free | Leader only. Remove a member. |
| `!guild deposit <amount>` | amount | Move C0INs from your balance to the shared guild vault (min 50). |
| `!guild withdraw <amount>` | free | Leader only. Withdraw from guild vault to your balance. |
| `!guild war <GuildName>` | 300 | Declare 24h war. Guild members deal 2× steal on hacks vs. war enemy. |
| `!guild info` | free | Show guild name, tag, vault, members, and active war status. |
| `!guild bounty @enemy <amount>` | amount | Place a bounty from the guild vault. Anyone who hacks the target collects it. |

- Max 5 members per guild.
- Guild tag `[TAG]` appears next to the player's name on the leaderboard.
- Guild vault is immune to individual hacks but can be targeted by coordinated `!vaultcrack` attacks.
- Guild wars auto-expire after 24 hours with a feed notification.

---

## Quests

Type `!quests` to see your active daily and weekly objectives.

**Daily Quests** (reset every 23 hours):

| Quest | Goal | Reward |
|---|---|---|
| Mine 5 times | 5 `!mine` uses | +200 C0INs |
| Win 2 hacks | 2 successful `!hack` | +350 C0INs |
| Win a prediction | 1 correct `!predict` | +250 C0INs + 0.05 Ͼ |
| Check in once | 1 `!checkin` | +150 C0INs |

**Weekly Quests** (reset every 72 hours):

| Quest | Goal | Reward |
|---|---|---|
| Reach a 5-hack streak | 5 consecutive wins | +1,000 C0INs |
| Earn 3,000 C0INs | Cumulative earning | +800 C0INs + 0.2 Ͼ |
| Trade 1,000 C0INs of Crypt0 | Buy or sell volume | +600 C0INs |

Quest progress is tracked server-side. Rewards are auto-claimed when you type `!quests` and a quest has been completed.

---

## Season & Prestige

| Command | Description |
|---|---|
| `!season` | Show current season, days remaining, and your season rank. |
| `!prestige` | Voluntarily reset balance to 0 in exchange for a permanent `[S#]` prestige badge. Requires 50,000 lifetime C0INs earned. |

- Season Hall of Fame records the top 3 finishers at season end.
- The Hall of Fame panel is visible on the overlay.
- Prestige badges persist across seasons and are visible on the leaderboard.

Seasons auto-end after 14 days (`seasonDurationMs`) and a new season starts automatically. Mods can also manually end seasons with `!admin season end`.

---

## Automated Events

All events fire automatically on a randomized timer (base interval ± variance jitter). No streamer input needed.

| Event | Interval | Effect |
|---|---|---|
| 🪂 Airdrop | ~8 min | Random active viewer receives 200–500 C0INs |
| ⚡ Mining Surge | ~15 min | `!mine` yields doubled for 5 minutes |
| 🎟 Code Drop | ~12 min | 6-char code appears on screen for 60s — everyone who redeems wins |
| 💰 Bounty Hunt | ~18 min | System places a 500 C0IN bounty on the #1 player |
| 🏷 Flash Sale | ~40 min | Shield and invest costs halved for 5 minutes |
| 🏹 Hacker Bounty | ~20 min | System places bounty on the most active hacker |
| 👁 Watch Verify | ~25 min | 4-digit code on screen — viewers who type `!verify CODE` get 75 C0INs + 1.5× passive for 30 min |

**Stream Raid** (triggered externally): When another streamer raids the channel, the raider earns C0INs (base 1,000 + 15 per viewer, capped at 10,000). Their viewers who type in chat within 2 minutes each get 250 C0INs (23h cooldown per viewer).

**Bits & Subs Hype** (triggered externally): When a viewer cheers bits or subscribes, all active viewers earn a share of the reward pool and the Crypt0 market gets a hype boost. Cheers: 1 C0IN per bit split among active viewers. Subs: 500 C0INs pool. Gift subs: 750 C0INs pool.

The overlay's **Next Events** bar shows the 4 soonest upcoming events with live countdowns.

---
