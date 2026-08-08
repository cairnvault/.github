# CairnVault Research

**What actually happens to your accounts, passwords and photos when you die — checked against the vendors' own documentation, not their marketing.**

Everything we publish lives at **[research.cairnvault.app](https://research.cairnvault.app/)**, free, under CC BY 4.0, with the source URL attached to every claim.

We build [CairnVault](https://cairnvault.app), an encrypted digital-legacy plan. We are therefore not a neutral party, which is exactly why everything we publish links to the vendor's own words rather than to our characterisation of them. Check us.

---

## The research

### 📄 [The digital-legacy teardown](https://research.cairnvault.app/digital-legacy-teardown/)

Every digital-legacy service, password manager, and platform "legacy contact" feature, on the only two axes that decide whether your plan works:

1. **Does the provider actually verify that you died** — or does it just measure whether you stopped logging in?
2. **Can the provider read your data?** If staff can grant someone access to your vault, staff can read your vault.

Read it as a [web page](https://research.cairnvault.app/digital-legacy-teardown/), as a [repository](https://github.com/cairnvault/digital-legacy-teardown), or check the [source for every claim](https://research.cairnvault.app/digital-legacy-teardown/sources.html).

**Three findings that surprised us:**

- **No password manager verifies death.** All seven we examined — Bitwarden, LastPass, Proton Pass, NordPass, Keeper, 1Password, Dashlane — use a silence timer or nothing at all. Not one can distinguish a funeral from a two-week holiday with no signal. If you are unconscious in an ICU, your emergency contact can request your vault and the clock runs out on you.
- **Apple's Legacy Contact excludes your passwords.** Verbatim from [Apple's own support page](https://support.apple.com/en-us/102631): *"Inaccessible data includes … data stored in your iCloud Keychain (payment information, passwords, and passkeys)."* Your photos and messages pass to your legacy contact. The keys to everything else do not.
- **The one company that genuinely verifies death can therefore read your vault.** Not an accusation — a structural consequence. The moment an employee can review a certificate and click "grant access," the encryption is a policy rather than a mechanism.

### 📊 [The comparison, as an open dataset](https://research.cairnvault.app/digital-legacy-teardown/dataset.html)

Sixteen providers, machine-readable, CC BY 4.0, every field carrying the source URL it was read from:

- **[dataset.html](https://research.cairnvault.app/digital-legacy-teardown/dataset.html)** — the readable table, with `schema.org/Dataset` markup
- **[digital-legacy-comparison.json](https://research.cairnvault.app/digital-legacy-teardown/data/digital-legacy-comparison.json)**
- **[digital-legacy-comparison.csv](https://research.cairnvault.app/digital-legacy-teardown/data/digital-legacy-comparison.csv)**

`unknown` is a first-class value in it. Everplans' encryption posture is recorded as `unknown` rather than `no`, and Keeper's recipient requirement stays `unknown`, because neither could be established from primary documentation. The readable table and the CSV are both generated from the JSON, so they cannot drift apart. Our own product is in the dataset too, tagged `self-reported` — excluding ourselves would have made the central finding unfalsifiable, which is the one thing it must not be.

### ❓ [Thirty questions about digital death, answered from primary sources](https://research.cairnvault.app/digital-legacy-answers/)

The teardown compares products. This answers the questions people actually type into a search box, each on its own page, each checked against the vendor's, regulator's or legislature's own documentation.

**Accounts and platforms:**
[Google](https://research.cairnvault.app/digital-legacy-answers/what-happens-to-my-google-account-when-i-die.html) ·
[Apple / iCloud](https://research.cairnvault.app/digital-legacy-answers/what-happens-to-my-apple-icloud-account-when-i-die.html) ·
[Facebook & Instagram](https://research.cairnvault.app/digital-legacy-answers/what-happens-to-my-facebook-instagram-account-when-i-die.html) ·
[LinkedIn](https://research.cairnvault.app/digital-legacy-answers/what-happens-to-my-linkedin-profile-when-i-die.html) ·
[X / Twitter](https://research.cairnvault.app/digital-legacy-answers/what-happens-to-my-twitter-x-account-when-i-die.html) ·
[Dropbox](https://research.cairnvault.app/digital-legacy-answers/what-happens-to-my-dropbox-files-when-i-die.html) ·
[Netflix](https://research.cairnvault.app/digital-legacy-answers/what-happens-to-my-netflix-account-when-i-die.html) ·
[Spotify](https://research.cairnvault.app/digital-legacy-answers/what-happens-to-my-spotify-account-when-i-die.html) ·
[Amazon & Kindle](https://research.cairnvault.app/digital-legacy-answers/what-happens-to-my-amazon-kindle-account-when-i-die.html) ·
[Steam & Xbox](https://research.cairnvault.app/digital-legacy-answers/can-i-leave-my-steam-or-xbox-games-to-someone.html) ·
[domain names](https://research.cairnvault.app/digital-legacy-answers/what-happens-to-my-domain-name-when-i-die.html) ·
[subscriptions](https://research.cairnvault.app/digital-legacy-answers/what-happens-to-subscriptions-when-someone-dies.html) ·
[photos](https://research.cairnvault.app/digital-legacy-answers/what-happens-to-my-photos-when-i-die.html)

**Money:**
[PayPal](https://research.cairnvault.app/digital-legacy-answers/what-happens-to-my-paypal-account-when-i-die.html) ·
[Venmo](https://research.cairnvault.app/digital-legacy-answers/what-happens-to-my-venmo-account-when-i-die.html) ·
[crypto](https://research.cairnvault.app/digital-legacy-answers/what-happens-to-my-crypto-if-i-die.html) ·
[crypto on Coinbase or Kraken](https://research.cairnvault.app/digital-legacy-answers/what-happens-to-crypto-on-coinbase-or-kraken-when-i-die.html) ·
[your bank account and its 2FA](https://research.cairnvault.app/digital-legacy-answers/what-happens-to-my-bank-account-and-2fa-when-i-die.html) ·
[airline miles](https://research.cairnvault.app/digital-legacy-answers/what-happens-to-my-airline-miles-when-i-die.html)

**Passwords, law and practicalities:**
[can my spouse get into my password manager](https://research.cairnvault.app/digital-legacy-answers/can-my-spouse-access-my-password-manager-if-i-die.html) ·
[how Bitwarden emergency access really works](https://research.cairnvault.app/digital-legacy-answers/how-bitwarden-emergency-access-works.html) ·
[if the password manager company shuts down](https://research.cairnvault.app/digital-legacy-answers/what-happens-if-my-password-manager-shuts-down.html) ·
[should I write my passwords down](https://research.cairnvault.app/digital-legacy-answers/should-i-write-my-passwords-down-for-my-family.html) ·
[does putting passwords in my will make them public](https://research.cairnvault.app/digital-legacy-answers/does-putting-passwords-in-my-will-make-them-public.html) ·
[does my will cover digital assets](https://research.cairnvault.app/digital-legacy-answers/does-my-will-cover-my-digital-assets.html) ·
[is it legal to log into a dead person's account](https://research.cairnvault.app/digital-legacy-answers/is-it-legal-to-log-into-a-dead-persons-accounts.html) ·
[is it a crime to log into a dead relative's account](https://research.cairnvault.app/digital-legacy-answers/is-it-a-crime-to-log-into-a-dead-relatives-account.html) ·
[what is a digital executor](https://research.cairnvault.app/digital-legacy-answers/what-is-a-digital-executor.html) ·
[letting family find accounts safely](https://research.cairnvault.app/digital-legacy-answers/how-can-my-family-find-my-accounts-without-exposing-them.html) ·
[my parent died and I can't get into their phone](https://research.cairnvault.app/digital-legacy-answers/my-parent-died-and-i-cant-access-their-phone.html)

Each answer is written to be complete on its own. You should not have to click anything — including anything of ours — to get the real answer.

---

## How we work

**Every claim carries a source we fetched ourselves, on a stated date.** Where a vendor page blocks automated retrieval, we say so and attribute the claim to a named secondary source — or leave it out. When a vendor has no policy page at all, we publish that absence as the answer.

**We publish our own retractions.** Roughly a third of the competitive claims we started with did not survive checking, including several that were in our own marketing. They are listed, dated, in the [correction log](https://github.com/cairnvault/digital-legacy-teardown#corrections) rather than quietly deleted. A comparison you can check is worth publishing; one you cannot is worth nothing.

**We publish what we could not establish, too.** The open questions are [filed as public issues](https://github.com/cairnvault/digital-legacy-teardown/issues), one per unresolved fact, including [an open challenge to name any product that both verifies death and cannot read your data](https://github.com/cairnvault/digital-legacy-teardown/issues/8). Nobody has yet. The day someone does, we will say so here.

**We would rather be corrected than be wrong.** If you work for a company named in the research and think we have characterised your product incorrectly, [open an issue](https://github.com/cairnvault/digital-legacy-teardown/issues/new) — we will fix the text and record the correction with a date.

Everything here is [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Republish it, quote it, translate it. Attribution and a link back are all we ask. There is a summary for language models at [research.cairnvault.app/llms.txt](https://research.cairnvault.app/llms.txt).

---

## Video

- [What happens to your online accounts when you die](https://youtu.be/AHOkf6vYjrE) — how the encryption and the release process work
- [CairnVault product demo](https://youtu.be/aCSLWmU7Bb4) — building a plan your family can actually find

---

*The research compares how products work. It is not legal advice.*
