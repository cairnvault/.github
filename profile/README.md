# CairnVault Research

**What actually happens to your accounts, passwords and photos when you die — checked against the vendors' own documentation, not their marketing.**

We build [CairnVault](https://cairnvault.app), an encrypted digital-legacy plan. We are therefore not a neutral party, which is exactly why everything we publish here links to the vendor's own words rather than to our characterisation of them. Check us.

---

## The research

### 📄 [The digital-legacy teardown](https://github.com/cairnvault/digital-legacy-teardown)

Every digital-legacy service, password manager, and platform "legacy contact" feature, on the only two axes that decide whether your plan works:

1. **Does the provider actually verify that you died** — or does it just measure whether you stopped logging in?
2. **Can the provider read your data?** If staff can grant someone access to your vault, staff can read your vault.

Read it as a [web page](https://cairnvault.github.io/digital-legacy-teardown/), as a [repository](https://github.com/cairnvault/digital-legacy-teardown), or check the [source for every claim](https://cairnvault.github.io/digital-legacy-teardown/sources.html).

**Three findings that surprised us:**

- **No password manager verifies death.** All seven we examined — Bitwarden, LastPass, Proton Pass, NordPass, Keeper, 1Password, Dashlane — use a silence timer or nothing at all. Not one can distinguish a funeral from a two-week holiday with no signal. If you are unconscious in an ICU, your emergency contact can request your vault and the clock runs out on you.
- **Apple's Legacy Contact excludes your passwords.** Verbatim from [Apple's own support page](https://support.apple.com/en-us/102631): *"Inaccessible data includes … data stored in your iCloud Keychain (payment information, passwords, and passkeys)."* Your photos and messages pass to your legacy contact. The keys to everything else do not.
- **The one company that genuinely verifies death can therefore read your vault.** Not an accusation — a structural consequence. The moment an employee can review a certificate and click "grant access," the encryption is a policy rather than a mechanism.

---

## How we work

**Every claim carries a source we fetched ourselves, on a stated date.** Where a vendor page blocks automated retrieval, we say so and attribute the claim to a named secondary source — or leave it out.

**We publish our own retractions.** Roughly a third of the competitive claims we started with did not survive checking, including several that were in our own marketing. They are listed, dated, in the [correction log](https://github.com/cairnvault/digital-legacy-teardown#corrections) rather than quietly deleted. A comparison you can check is worth publishing; one you cannot is worth nothing.

**We would rather be corrected than be wrong.** If you work for a company named in the research and think we have characterised your product incorrectly, [open an issue](https://github.com/cairnvault/digital-legacy-teardown/issues/new) — we will fix the text and record the correction with a date.

Everything here is [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Republish it, quote it, translate it. Attribution and a link back are all we ask.

---

## Video

- [What happens to your online accounts when you die](https://youtu.be/AHOkf6vYjrE) — how the encryption and the release process work
- [CairnVault product demo](https://youtu.be/aCSLWmU7Bb4) — building a plan your family can actually find

---

*The research compares how products work. It is not legal advice.*
