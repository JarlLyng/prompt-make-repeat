# Prompt. Make. Repeat.

A two-hour workshop from **Future Product Days 2026**, Copenhagen.
Everything you need to run the loop again on your own is on this page.

> I didn't just learn something about AI.
> I made something I didn't think I could make that quickly.

[Download the slides (PDF, 1.2 MB)](prompt-make-repeat.pdf) — all 50, from the two-hour version.

---

## The loop

**Prompt → Make → Inspect → Change. And then repeat.**

Most people do the first two. The workshop is about the last two.
Run it once and you have a demo. Run it twice and you have a way of working.

---

## Five moves

| | | |
|---|---|---|
| **01** | Brief | Half a page. Written once, reused everywhere. |
| **02** | Prompt | Forbid the deliverable. Make it ask. |
| **03** | Make | Expect the first one to be bad. |
| **04** | Inspect | Yourself, then through someone else's eyes. |
| **05** | Change | One thing. Then go again. |

---

## 1 · The brief

Half a page. One document, one writer, everyone else talking. No AI for this
part: the brief has to be yours, not the model's.

Five fields:

- **Who is it for**
- **What must it do**
- **What words do we use**
- **What must it never do**
- **How do we know it worked**

Keep it thin. A thin brief is more useful than a thorough one, because the gaps
are what you learn from.

---

## 2 · The prompt

The whole trick is forbidding the deliverable. Ask for an app and you get an app
in ten seconds. Generic, not yours, and now you are arguing with something that
already exists.

```text
Build nothing yet.

You are an experienced product designer.
Here is what we want to make: [our brief]

1. Ask me the five questions you'd ask
   before building. One at a time.
2. Then tell me what you'd get wrong
   if you started now.
3. Only when I say go: build the
   smallest version we can look at.
   Make it look like a real product,
   not a demo. Pick a typeface and a
   palette and commit to them.
```

**Why each line is there**

- *Build nothing yet* breaks the default. Without it you get an app.
- *One at a time* forces a conversation instead of a delivery.
- Step 2 is where it tells you your brief was thin.
- The styling line is not vanity. Without it you get grey boxes, and grey boxes
  do not feel like something you made.

Answer at least one of its questions sloppily on purpose. You want it to push back.

---

## 3 · The role switch

After you have built something, stay in the same chat and make it change sides.
No new conversation, no link to paste: it already has your product.

```text
Stop being the designer.

You are now: [a specific person in a
specific situation who would use this].

Forget what we were trying to do.
React to what is actually there.

Answer in the first person:
a reaction, not an analysis.

1. What's the first thing you think?
2. What do you think is NOT here?
3. What would you tell a colleague?
4. One to ten: do you trust this?
   And why not ten?
```

*Forget what we were trying to do* is doing the heavy lifting. Without it, the
model keeps defending the intention it helped you write.

Question 2 is the one that hurts, and the one worth using.

**One caveat, said plainly:** this does not simulate your users. It simulates an
average of how people write about being a user. That is not the same thing, and
it is still useful.

---

## 4 · When you get stuck

```text
I am stuck. Ask me one question that will get me moving again.
```

---

## Tools

The choice matters less than you think. Any of these will do the work:

- **A chatbot that builds:** Claude, ChatGPT, Gemini, Copilot
- **A UI generator:** Google Stitch, Figma Make
- **Any of them plus** *"give me the whole thing as one self-contained HTML file"*

That last one is the floor. It works everywhere, it works offline once the file
is downloaded, and it is not a consolation prize.

If you already pay for Lovable, v0, Bolt or Cursor, use those. Just watch the
credits: free tiers run out mid-build.

---

## One thing to try on Monday

Take the next thing you would normally describe in a document, and build a bad
version of it first. Then have the conversation.

The thinking does not happen before version one. It happens between one and two.

---

## Why this matters

We used to describe concepts and argue about what each of us had pictured. The
best describer won the meeting, and nobody knew whether it would work.

Now you build it first, badly, in fourteen minutes, and then the conversation
starts, about something real that everyone is looking at.

The bottleneck used to be production. Now it is judgement: knowing what to ask
for, and telling whether what came back is any good. That is your job, and it
did not get smaller.

---

## The price

A prototype that demos perfectly and does not work is the new failure mode, and
it is expensive, because everyone in the room believed it.

Before you show anyone: ask yourself what it would fail at in real life, if
someone actually used it. Not what is missing. What would fail.

---

## Who made this

**Jarl Lyng.** Designer and developer in Copenhagen.
Fifteen years on large, complicated digital projects at [Forte Advice](https://forteadvice.com).
And a ton of stupid, crazy, hopefully funny and quirky ones.

[iamjarl.com](https://iamjarl.com) · [Made by Human](https://iamjarl.madebyhuman.com)

---

*No AI was harmed during this workshop. I hope.*
