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

# Testing a Translation

Starting WhatPulse v5.5, you can run the client via the below manner making it use a local translation file. First you need to "release" your translate, which creates `.qm` file. In Qt Linguist, the File menu has a `Release As` action, where it'll create the `.qm` file and ask you where to save it. Once it's saved, run the WhatPulse client via the command line.

*Adjust the path to the WhatPulse client and translation .qm file as needed*

## macOS
1. Open a Terminal.app window
2. Run: `/Applications/WhatPulse/WhatPulse.app/Contents/MacOS/WhatPulse --translationfile /path/to/your_whatpulse_translation.qm`

## Windows
1. Open a Command window
2. Run: `C:\Program Files\WhatPulse\WhatPulse.exe --translationfile C:\path\to\your_whatpulse_translation.qm`

You'll see logs appear in the command terminal, which will say something about the translation file and using it. Something like this:

```
21-08-2023 12:26:22.735  INFO Using a custom translation file:  "/Users/martijn/WhatPulse/client/languages/whatpulse_de.qm"
```

The logs will also tell you if there's something wrong with the translation file.

# Contributors

<table>
<tr>
    <td align="center" style="word-wrap: break-word; width: 150.0; height: 150.0">
        <a href=https://github.com/smitmartijn>
            <img src=https://avatars.githubusercontent.com/u/6500836?v=4 width="100;"  alt=Martijn Smit/>
            <br />
            <sub style="font-size:14px"><b>Martijn Smit</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 150.0; height: 150.0">
        <a href=https://github.com/Geno1024>
            <img src=https://avatars.githubusercontent.com/u/6427392?v=4 width="100;"  alt=Y. Z. Chen/>
            <br />
            <sub style="font-size:14px"><b>Y. Z. Chen</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 150.0; height: 150.0">
        <a href=https://github.com/Remlej9>
            <img src=https://avatars.githubusercontent.com/u/47269799?v=4 width="100;"  alt=Remlej9/>
            <br />
            <sub style="font-size:14px"><b>Remlej9</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 150.0; height: 150.0">
        <a href=https://github.com/urbainn>
            <img src=https://avatars.githubusercontent.com/u/47057465?v=4 width="100;"  alt=Urbain/>
            <br />
            <sub style="font-size:14px"><b>Urbain</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 150.0; height: 150.0">
        <a href=https://github.com/TheMorc>
            <img src=https://avatars.githubusercontent.com/u/13377926?v=4 width="100;"  alt=Richard Gráčik/>
            <br />
            <sub style="font-size:14px"><b>Richard Gráčik</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 150.0; height: 150.0">
        <a href=https://github.com/AA0000-33>
            <img src=https://avatars.githubusercontent.com/u/22997509?v=4 width="100;"  alt=#AA0000/>
            <br />
            <sub style="font-size:14px"><b>#AA0000</b></sub>
        </a>
    </td>
</tr>
<tr>
    <td align="center" style="word-wrap: break-word; width: 150.0; height: 150.0">
        <a href=https://github.com/Stardisk>
            <img src=https://avatars.githubusercontent.com/u/24385735?v=4 width="100;"  alt=Stardisk/>
            <br />
            <sub style="font-size:14px"><b>Stardisk</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 150.0; height: 150.0">
        <a href=https://github.com/Radotornado>
            <img src=https://avatars.githubusercontent.com/u/16245632?v=4 width="100;"  alt=Radoslav Mandev/>
            <br />
            <sub style="font-size:14px"><b>Radoslav Mandev</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 150.0; height: 150.0">
        <a href=https://github.com/jinai>
            <img src=https://avatars.githubusercontent.com/u/7669687?v=4 width="100;"  alt=jinai/>
            <br />
            <sub style="font-size:14px"><b>jinai</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 150.0; height: 150.0">
        <a href=https://github.com/Inktest>
            <img src=https://avatars.githubusercontent.com/u/40661903?v=4 width="100;"  alt=Ink/>
            <br />
            <sub style="font-size:14px"><b>Ink</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 150.0; height: 150.0">
        <a href=https://github.com/edermachado>
            <img src=https://avatars.githubusercontent.com/u/1864475?v=4 width="100;"  alt=Éder Magalhães Machado/>
            <br />
            <sub style="font-size:14px"><b>Éder Magalhães Machado</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 150.0; height: 150.0">
        <a href=https://github.com/ksetlak>
            <img src=https://avatars.githubusercontent.com/u/9848795?v=4 width="100;"  alt=Krzysiek Setlak/>
            <br />
            <sub style="font-size:14px"><b>Krzysiek Setlak</b></sub>
        </a>
    </td>
</tr>
<tr>
    <td align="center" style="word-wrap: break-word; width: 150.0; height: 150.0">
        <a href=https://github.com/MoweME>
            <img src=https://avatars.githubusercontent.com/u/20139023?v=4 width="100;"  alt=Finn/>
            <br />
            <sub style="font-size:14px"><b>Finn</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 150.0; height: 150.0">
        <a href=https://github.com/Miracle0565>
            <img src=https://avatars.githubusercontent.com/u/53522776?v=4 width="100;"  alt=Miracle0565/>
            <br />
            <sub style="font-size:14px"><b>Miracle0565</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 150.0; height: 150.0">
        <a href=https://github.com/CorruptComputer>
            <img src=https://avatars.githubusercontent.com/u/5573038?v=4 width="100;"  alt=Nickolas Gupton/>
            <br />
            <sub style="font-size:14px"><b>Nickolas Gupton</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 150.0; height: 150.0">
        <a href=https://github.com/suliveevil>
            <img src=https://avatars.githubusercontent.com/u/35763237?v=4 width="100;"  alt=suliveevil/>
            <br />
            <sub style="font-size:14px"><b>suliveevil</b></sub>
        </a>
    </td>
</tr>
</table>

