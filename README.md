# WhatPulse Client Translations

Welcome to the repository for translations of the WhatPulse client. We use [Qt](https://www.qt.io/) as our coding framework, which provides a way to translate the client. This repository is where we keep track of the languages and translations that are used by the client.

We welcome all contributions: new languages or modifications to existing languages.

# Contributing

There are two ways to contribute:
* Create a [PR](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request) in this repository,
* **or**, if you're not familiar with GitHub, send the file to support@whatpulse.org, and we'll add it for you.

Let's say you're creating a translation in German. Start with copying the `whatpulse.ts.template` file to a new file called `whatpulse_de.ts`. Then you have two options: open the file in a text editor, or use the Qt Linguist app.

I'd recommend Qt Linguist, as you can easily see which language strings are still to be translated. Find a standalone download here: https://github.com/lelegard/qtlinguist-installers/releases

Find more information about the Qt translation process, and the manual for Qt Linguist here: https://doc.qt.io/qt-5/linguist-translators.html

A few things to note:

* There could be HTML in the language string. This could be a link or an HTML character. They usually include `&gt;` and `&lt;` - but not limited to that. **Please keep those**.
* There could be spaces in the language string. **Please keep those** - they are there for a reason (i.e., extra spacing).
* The letter before a `&` indicates that you can use that letter as a shortcut. If possible, keep them, unless the language you're working in does not have a convenient way to do this.

# Contributors

Here's a list of incredible people that have contributed:

* **Slovak:** Richard Gráčik ([GitHub](https://github.com/TheMorc), [Twitter](https://twitter.com/morciatka))
* **Frech:** UBrain ([GitHub](https://github.com/UBrainDev))
* **German:** Finn ([GitHub](https://github.com/MoweME), [Twitter](https://twitter.com/MoweM3))
* **Swedish:** Remlej9 ([GitHub](https://github.com/Remlej9), [Twitter](https://twitter.com/Remlej9))
* **Simplified Chinese:** Geno1024 ([GitHub](https://github.com/Geno1024))
