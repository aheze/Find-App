---
layout: page
title: Translate Find
include_in_header: false
page_order: 5
is_hidden: false
---

# Translate Find

OpenFind is not currently accepting translations. However, you can help translate [Find](https://getfind.app/), OpenFind's successor!

***Find** is currently closed source.*

--

Find is translated by the community. Want to help? Get started with the [Translation Dashboard](https://crwd.in/find-app)!

[![Go to Translation Dashboard]({{ '/assets/TranslationDashboard.jpg' | relative_url }})](https://crwd.in/find-app)

### Getting Started

Thanks for your interest in helping translate Find! Translations are hosted using [Crowdin](https://crowdin.com/). To contribute translations, you'll need to first [sign up for an account](https://accounts.crowdin.com/login?continue=%2Ftranslate%2Ffind-app).

After signing up, head to the [Translation Dashboard](https://crwd.in/find-app). You should see something like this:

<kbd><img src="{{ '/assets/TranslationHome.png' | relative_url }}" width="600" alt="Translation Dashboard"></kbd>


Click whichever language you'd like to work with. You should then see 2 files:

<kbd><img src="{{ '/assets/TranslationFiles.png' | relative_url }}" width="350" alt="Translation files"></kbd>

- [**Localizable.strings**](https://crowdin.com/translate/find-app/6) contains most of the words to translate.
- [**Localizable.stringsdict**](https://crowdin.com/translate/find-app/8) contains any words that have plural forms.

Feel free to start with whichever. After selecting one, you'll see the translation editor:

<kbd><img src="{{ '/assets/TranslationSubmit.png' | relative_url }}" width="600" alt="Translation editor"></kbd>

This is where you can enter translations. When you're done, hit "Save" and I'll review it. That's about it!

### Translation Guide

Here's an example of what you'll see for each word to translate.

<kbd><img src="{{ '/assets/TranslationExample.jpg' | relative_url }}" width="600" alt="Translation editor example, labeled from 1 to 5"></kbd>

1. The string identifier used in the source code.
2. The default English translation.
3. Some comments that I've added for context.
4. A screenshot for reference. I'll usually add these whenever a word's purpose is really confusing.
5. The translation that you submit.

The string identifier uses dot syntax and represents where the word appears in the app.


> Some words like "Add" or "Cancel" appear all over the place, so they'll be prefixed with `Shared` (e.x. `Shared.Add`).

If you need extra context or have any questions, ping me in the [`#general-find`](https://discord.gg/KjY6AjjSSf) channel in the Discord server.


### Variables

Some sentences have nested variables that are populated on-the-fly. For these, just include the original variable token in your translated string.

<kbd><img src="{{ '/assets/TranslationTemplates.png' | relative_url }}" width="600" alt="Sentence containing a variable, highlighted in green"></kbd>


### Plural words

Phrases like `x followers` need to account for cases where `x` is one. These types of sentences are stored in [**Localizable.stringsdict**](https://crowdin.com/translate/find-app/8) and their identifiers will always start with `Plural`.

<kbd><img src="{{ '/assets/TranslationPlural.png' | relative_url }}" width="600" alt="Sentence containing a variable, highlighted in green"></kbd>

Here you can enter separate translations for `One` or `Other` forms.

> Note: There's a bunch of `%#@variable@` template strings that I couldn't get rid of. You can ignore them.

### Resources

- [Discord server](https://discord.gg/KjY6AjjSSf) — ask anything.
- [Twitter DMs](https://twitter.com/aheze0) — if you have anything you'd like to discuss with me, I'm here.
- [Email](mailto:aheze@getfind.app) — I'm always open to emails!

---

### News

#### Update August 14, 2022:
Uploaded the first batch of strings for Find v3.0.

#### Update July 30, 2022:
iOS 16 will introduce text search in Photos, which makes the current version of Find almost useless (I got sherlocked 😢).
So, I'm working on Find v3.0 right now. In about 3 weeks I'll have the base foundation done. ([Sneak peeks on my Twitter](https://twitter.com/aheze0)).
Thanks to those who've signed up already!

#### Update May 22, 2022:
I'm still working on gathering all the strings in the app. I should be done in a couple days. In the meantime, join the [Discord server](https://discord.com/invite/Pmq8fYcus2)?

The translation dashboard is already set up (translations are managed through Crowdin) but I haven't uploaded anything to translate yet. You can still [sign up for an account](https://accounts.crowdin.com/login?continue=%2Ftranslate%2Ffind-app%2F6%2Fen-zhcn) though!

