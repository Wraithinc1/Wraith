# THE GAME

> Simple enough to understand immediately.
>
> Difficult enough to ruin your afternoon.

The Wraith arena is built around one principle:

## **Skill should be obvious. Failure should be immediate. Restarting should be irresistible.**

No complicated progression system.

No pay-to-win upgrades.

No 40-minute tutorial.

Just you, the game, and a leaderboard full of people who apparently have nothing better to do.

---

# 🎮 THE PHILOSOPHY

The game was designed around five principles:

### SIMPLE

A new player should understand what they're supposed to do almost immediately.

### FAST

Runs are short.

Failure doesn't send you through menus, loading screens, or unnecessary friction.

You restart.

### DIFFICULT

Understanding the game is easy.

Mastering it isn't.

### SKILL-BASED

Better performance should come from getting better at the game.

Not buying upgrades.

Not holding more tokens.

Not paying for advantages.

### COMPETITIVE

Every run produces something everybody understands:

**A score.**

And every score answers one question:

> **Are you better than the person above you?**

---

# 🕹️ THE GAMEPLAY

The arena is built around a simple reflex-based gameplay loop.

You control the player.

The environment gets increasingly difficult.

You survive.

Your score climbs.

Eventually...

you don't survive.

That's generally how this goes.

---

# 🔁 THE LOOP

```text
ENTER
  ↓
PLAY
  ↓
SURVIVE
  ↓
SCORE
  ↓
FAIL
  ↓
STARE AT THE SCORE
  ↓
REALIZE YOU CAN BEAT IT
  ↓
RESTART
  ↓
REPEAT
```

There should be as little friction as possible between:

**"I lost."**

and

**"Again."**

That's the loop.

---

# 📈 DIFFICULTY

The longer you survive, the harder the arena becomes.

Difficulty is intended to increase progressively rather than relying purely on random punishment.

The player should eventually reach a point where:

- Reactions matter
- Timing matters
- Consistency matters
- Mistakes become expensive

A beginner should be able to play.

A strong player should be noticeably better.

An exceptional player should produce scores that make everyone else mildly suspicious.

---

# 💀 FAILURE

A run eventually ends.

There is no resurrection button.

No extra life because you watched an advertisement.

No conveniently timed power-up because the game felt bad for you.

You failed.

Here's your score.

Try again.

> **WRAITH:**  
> "That looked intentional."

---

# 📊 SCORING

Each completed run produces a score based on legitimate gameplay.

That score becomes the player's competitive result.

Simple:

```text
BETTER RUN
    ↓
HIGHER SCORE
    ↓
HIGHER RANK
```

The game doesn't need seventeen different statistics to tell you who won.

The number is higher.

You won.

Congratulations on mathematics.

---

# 🏆 THE LEADERBOARD

Validated scores can be submitted to the competitive leaderboard.

The leaderboard displays the hierarchy of the arena.

A typical view might look like:

```text
01    TrenchGoblin         18,420
02    SendMeSOL            17,991
03    DefinitelyNotABot    16,802
04    WhaleHunter          15,441
05    TouchGrass            14,932
```

Higher score.

Higher position.

That's it.

No voting.

No committee.

No participation trophy.

---

# 👤 PLAYER IDENTITY

Players can compete using a public username associated with their wallet.

This gives competitors an identity without turning Wraith into a traditional account system.

Your public identity can be used across:

- Gameplay
- Leaderboards
- Tournament results
- Winner announcements
- Arena history

The wallet provides cryptographic proof of ownership.

The username gives Wraith something easier to insult.

Everybody wins.

---

# 🔐 WALLET CONNECTION

The game does not need custody of your wallet.

It does not need your private key.

It absolutely does not need your seed phrase.

Wallet signatures can be used to prove that a competitor controls the wallet associated with their player identity.

Think:

**"Prove this wallet is yours."**

Not:

**"Give me the wallet."**

Important distinction.

---

# 🧠 THE BROWSER IS NOT THE REFEREE

Here's the problem with competitive browser games:

The player's browser belongs to the player.

Which means blindly trusting whatever number it sends us would be...

optimistic.

For example:

```javascript
score = 999999999;
```

Incredible performance.

Unfortunately, Wraith has questions.

Competitive scores are therefore intended to pass through validation before becoming eligible tournament results.

---

# 🛡️ SCORE VALIDATION

The competitive system is designed around one principle:

## **The client can play the game. The client doesn't get to declare itself champion.**

Validation architecture can examine gameplay information before accepting a competitive result.

Protections can include mechanisms designed to identify:

- Impossible results
- Manipulated sessions
- Duplicate submissions
- Replay attempts
- Abnormal gameplay behavior
- Automated abuse
- Invalid player sessions

The exact defensive implementation does not need to be publicly documented.

Publishing every anti-cheat rule would make a fantastic anti-cheat guide.

For cheaters.

We'd rather not.

---

# 🤖 WRAITH DOES NOT VALIDATE SCORES

Important distinction.

Wraith can comment on a score.

Wraith can announce a score.

Wraith can make fun of a score.

But Wraith does not decide whether a score is technically valid because it likes the player.

The validation system handles that.

The machine determines reality.

Wraith talks about reality.

---

# 🏁 COMPETITIVE SCORES

A score appearing during gameplay and a score becoming an official tournament result are not necessarily the same thing.

Competition requires validation.

Only eligible results should determine final tournament rankings.

That means:

```text
PLAY
 ↓
SCORE
 ↓
SUBMIT
 ↓
VALIDATE
 ↓
ELIGIBLE SCORE
 ↓
LEADERBOARD
```

The objective is simple:

**If somebody wins, they should have actually won.**

A revolutionary concept.

---

# ⏱️ SHORT SESSIONS

The arena is not designed around marathon gameplay.

It's designed around repetition.

Play.

Fail.

Restart.

Improve.

Players should be able to jump in without committing their entire evening.

Whether they accidentally spend their entire evening trying to beat one score is between them and their screen-time report.

---

# 📱 MOBILE FIRST

The arena is designed around fast, accessible interaction.

The experience should work naturally across:

- Mobile
- Desktop
- Modern web browsers

Gameplay controls should remain immediately understandable regardless of device.

No keyboard orchestra required.

---

# ⚖️ COMPETITIVE FAIRNESS

The competitive game should not become pay-to-win.

Holding more tokens should not make your character faster.

Buying something should not secretly make obstacles easier.

Paying more should not give somebody a better competitive score.

The leaderboard should reflect:

## **WHO PLAYED BETTER.**

Not who had the largest wallet.

That's what the token chart is for.

---

# 🎨 COSMETICS VS COMPETITIVE ADVANTAGE

The ecosystem may eventually support cosmetic elements without affecting competitive integrity.

Cosmetics can change:

- Appearance
- Visual identity
- Celebration
- Status
- Player expression

They should not change the fundamental conditions used to determine a legitimate competitive score.

Looking richer is fine.

Playing easier isn't.

---

# 🧬 WHY ONE GAME?

Because simplicity creates identity.

Wraith doesn't need an arcade containing 37 mediocre games.

The goal is to create one arena people recognize.

One mechanic people understand.

One leaderboard people care about.

One score people want to beat.

If the core game isn't addictive enough to stand alone, adding twelve more games doesn't solve the problem.

It creates twelve problems.

---

# 👻 WRAITH + THE GAME

Wraith exists around the game.

Gameplay creates events.

Events give Wraith something to react to.

Examples:

### HORRIBLE RUN

> **WRAITH:**  
> "We're counting that?"

---

### PERSONAL BEST

> **WRAITH:**  
> "Better."
>
> "Still people above you."

---

### NEW #1

> **WRAITH:**  
> "We have a new problem at the top."

---

### PLAYER IMMEDIATELY LOSES #1

> **WRAITH:**  
> "That reign was adorable."

---

### RIDICULOUS SCORE

> **WRAITH:**  
> "Alright."
>
> "Who gave this person functioning reflexes?"

---

# 🏛️ THE ARENA REMEMBERS

Competitive gaming becomes more interesting when history develops.

The ecosystem can build public arena history around things like:

- Champions
- High scores
- Records
- Winning streaks
- Rivalries
- Tournament results

That means a score isn't necessarily forgotten when the leaderboard resets.

Today's winner can become tomorrow's target.

Someone eventually breaks the record.

Someone eventually ends the streak.

Someone eventually takes the throne.

And Wraith remembers.

---

# 🧠 THE DESIGN RULES

## RULE 01

**Easy to understand.**

## RULE 02

**Difficult to master.**

## RULE 03

**Failure should be fast.**

## RULE 04

**Restart should be faster.**

## RULE 05

**Skill determines competitive performance.**

## RULE 06

**Money does not buy leaderboard advantage.**

## RULE 07

**Scores must be verifiable before rewards depend on them.**

## RULE 08

**Keep unnecessary mechanics out.**

## RULE 09

**One addictive mechanic beats ten mediocre ones.**

## RULE 10

**If losing doesn't make you want another attempt, fix the game.**

---

# 👻 WRAITH

The rules are simple.

Play.

Survive.

Score.

Beat the person above you.

If you lose?

Good news.

The restart button works.

**Try again.**
