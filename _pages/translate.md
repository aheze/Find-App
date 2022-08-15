---
layout: page
title: Translate Find
include_in_header: false
page_order: 5
is_hidden: false
---

# Translate Find
Find is translated by the community. Want to help? Get started with the [Translation Dashboard](https://crwd.in/find-app)!

[![Go to Translation Dashboard]({{ '/assets/TranslationDashboard.jpg' | relative_url }})](https://crwd.in/find-app)

### Getting Started

Thanks for your interest in helping translate Find! Translations are hosted using [Crowdin](https://crowdin.com/). To contribute translations, you'll need to [sign up for an account](https://accounts.crowdin.com/login?continue=%2Ftranslate%2Ffind-app) first.

After signing up, head to the [Translation Dashboard](https://crwd.in/find-app). You should see something like this:

<kbd><img src="{{ '/assets/TranslationHome.png' | relative_url }}" width="600" alt="Translation Dashboard"></kbd>


Click whichever language you'd like to work with. You should then see 2 files:

<kbd><img src="{{ '/assets/TranslationFiles.png' | relative_url }}" width="350" alt="Translation files"></kbd>

- **Localizable.strings** contains most of the words to translate.
- **Localizable.stringsdict** contains any words that have plural forms.

Feel free to start with whichever. After selecting one, you'll see the translation editor:

<kbd><img src="{{ '/assets/TranslationSubmit.png' | relative_url }}" width="600" alt="Translation editor"></kbd>

This is where you enter your translations. When you're done, hit "Save" and I'll export it into Find's source code. That's about it!

### Translation Guide

Here's an example of what you'll see for each word to translate.

<kbd><img src="{{ '/assets/TranslationExample.jpg' | relative_url }}" width="600" alt="Translation editor example, labeled from 1 to 5"></kbd>

1. The string identifier used in the source code.
2. The default English translation.
3. Some comments that I've added for context.
4. A screenshot for reference. I'll usually add these when the word's purpose is confusing.
5. The translation that you submit.

The string identifier is named with a dot syntax.



- e.x. `Albums.AddAlbum` / "Add Album"

    - e.x. `Plural.Photos.Scanners.RecognizableLanguages`
    - You'll be able to add separate translations for `One` / `Other`









---

# News

**Update August 14, 2022**
Uploaded the first batch of strings for Find v3.0.

**Update July 30, 2022**
iOS 16 will introduce text search in Photos, which makes the current version of Find almost useless (I got sherlocked 😢).
So, I'm working on Find v3.0 right now. In about 3 weeks I'll have the base foundation done. ([Sneak peeks on my Twitter](https://twitter.com/aheze0)).
Thanks to those who've signed up already!

**Update May 22, 2022**
I'm still working on gathering all the strings in the app. I should be done in a couple days. In the meantime, join the [Discord server](https://discord.com/invite/Pmq8fYcus2)?

The translation dashboard is already set up (translations are managed through Crowdin) but I haven't uploaded anything to translate yet. You can still [sign up for an account](https://accounts.crowdin.com/login?continue=%2Ftranslate%2Ffind-app%2F6%2Fen-zhcn) though!

