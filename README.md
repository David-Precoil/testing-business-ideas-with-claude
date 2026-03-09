# Testing Business Ideas with Claude

A free Claude skill based on David J. Bland's Precoil EMT methodology — Extract, Map, Test.

Install it to run structured assumption extraction and experiment design directly inside Claude.

---

## What it does

The skill runs a guided three-phase sequence:

1. **Extract** — surfaces risky assumptions across Desirability, Viability, and Feasibility from any idea, strategy, or initiative
2. **Map** — reviews your assumption map and identifies which assumptions to test first
3. **Test** — designs an experiment brief for your riskiest assumptions

## What it does not include

The [Precoil Experiment Library](https://www.precoil.com/library) — a structured collection of tested experiment designs mapped to assumption types — is not included in this skill. The library is available separately for teams that want matched experiment designs, evidence strength ratings, and sequencing guidance.

---

## How to install

1. Download `testing-business-ideas-with-claude.zip`
2. Open [Claude.ai](https://claude.ai) and go to **Settings → Capabilities**
3. Ensure **Code execution and file creation** is enabled
4. Go to **Customize → Skills**
5. Click **"+"** → **"Upload a skill"** and upload the ZIP file

> Requires a free, Pro, Max, Team, or Enterprise Claude account.

---

## How to use

Once installed, start a new conversation and prompt:

```
Run EMT on this idea:
[describe your product, strategy, or initiative]
```

Or use any of these trigger phrases:

* "Pressure test this idea"
* "What are the riskiest assumptions here?"
* "Extract assumptions from this strategy"
* "Identify hidden risk in this initiative"

---

## Note for artifact and app builders

If you're using this skill to build a Claude-powered artifact or browser-based app, note that **image analysis in the Map phase works in claude.ai chat and Claude Code, but not in browser-based artifacts** that call the Anthropic API directly. This is a CORS restriction — the API doesn't accept image payloads from browser fetch calls.

If building a browser artifact, replace the image upload step with a drag-and-drop matrix or text-based placement input. The updated EMT artifact in this repo uses that approach.

---

## Read before installing

The full `SKILL.md` is readable above. It contains all instructions Claude follows when the skill is active — no hidden logic, no external calls, no data collection.

---

## License

This skill is released under the MIT license. The Precoil Experiment Library is a separate licensed asset and is not included here.

---

## About Precoil

Precoil helps organizations derisk major initiatives through structured business experimentation. The EMT system has been facilitated over 1,000 times across enterprise teams including Adobe, Toyota, HP, and DuPont.

[precoil.com](https://www.precoil.com) · [Experiment Library](https://www.precoil.com/library)
