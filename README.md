# Testing Business Ideas with Claude

Run the **Extract → Map → Test (EMT)** system inside Claude to surface
the riskiest assumptions behind a **new initiative, product concept, or
strategic bet** before committing budget, teams, or development
resources.

**Created by David J. Bland**\
Co‑author of *Testing Business Ideas* and creator of the **Precoil EMT
System**.

⭐ If this skill is useful, please star the repo so others can find it.

---

## Example EMT Output (Condensed)

**Idea being tested**\
"Add an AI feature that predicts health issues for cats to our wearable
cat health monitoring device for \$15/month, starting with existing
customers in San Francisco."

### Extract

**Desirability** - Cat owners want predictive insight into their pet's
health. - AI predictions would feel meaningfully better than existing
alerts.

**Viability** - Enough customers will pay **\$15/month** to justify the
investment. - The pilot cohort is large enough to generate meaningful
conversion data.

**Feasibility** - Existing sensor data is sufficient to train a reliable
prediction model. - Predictions can be validated quickly enough to build
trust.

### Map

**Highest‑Risk Assumption**\
AI predictions align with health concerns cat owners already worry
about.

**Risk Type**\
Desirability

### Test

**Experiment**: Customer Interview\
Goal: Validate whether predicted conditions match real owner concerns.

**Pass signal** - 70%+ of predicted conditions are named unprompted or
rated highly relevant.

---

## What the Skill Does

The skill runs a guided sequence:

1.  **Extract** -- surfaces assumptions across Desirability, Viability,
    and Feasibility\
2.  **Map** -- identifies the highest‑risk assumptions to test\
3.  **Test** -- generates an experiment brief to reduce uncertainty

Output typically includes:

-   a structured assumption map\
-   prioritization of the biggest risks\
-   a clear experiment brief

---

## Who This Is For

While EMT originated in startup experimentation practices, it is widely
used by **product, innovation, and strategy teams inside established
organizations** to evaluate initiatives before committing significant
resources.

Useful for:

-   product leaders evaluating new initiatives
-   innovation and strategy teams pressure‑testing concepts
-   corporate venture or incubation teams
-   consultants facilitating assumption mapping
-   organizations introducing structured experimentation

---

## Used in Practice

The EMT system behind this skill has been facilitated in **1,000+
experimentation sessions** with teams inside established organizations.

Organizations where the approach has been applied include teams at:

Adobe · Toyota · HP · DuPont and more...

---

## What it does not include

The **Precoil Experiment Library** is not included in this skill.

The library contains **50+ experiment designs mapped to assumption
types** and helps teams choose the fastest experiment to produce
evidence.

Explore the library:\
https://www.precoil.com/library

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

---

## Read before installing

The full `SKILL.md` is readable above. It contains all instructions Claude follows when the skill is active — no hidden logic, no external calls, no data collection.

---

## License

This skill is released under the MIT license. The Precoil Experiment Library is a separate licensed asset and is not included here.

---

## About Precoil

Precoil helps organizations derisk major initiatives through structured business experimentation. The EMT system has been facilitated over 1,000 times across enterprise teams including Adobe, Toyota, HP, and DuPont.

[Precoil.com](https://www.precoil.com) · [Experiment Library](https://www.precoil.com/library)
