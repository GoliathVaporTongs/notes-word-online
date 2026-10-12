# word online

A quick orientation for anyone who typed `word online` and wants to know what that actually gets you in 2024 — and where the phrase quietly splits into two different things.

![Focus Words](assets/cover.jpg)
*Focus Words — Romain Vignes (CC0). The whole point of a word processor is getting words out of your head and onto a page without the tool fighting you.*

## The two meanings hiding in "word online"

People land on this phrase from two directions, and the right answer depends on which one you meant.

The first is literal: **Microsoft Word, running in a browser.** Microsoft ships a web version of Word at Office.com. It's free with a Microsoft account, it saves to OneDrive, and it opens `.docx` files natively. If your query was `ms word web`, `microsoft word online`, or `msword online`, that's the thing.

The second is looser: **any free word processor that runs in a browser**, whether or not it's Microsoft's. Google Docs is the obvious one. So are Zoho Writer, the online build of LibreOffice (Collabora Online), and a long tail of simpler editors. If you typed `free word processor` or `word pad`, you probably meant this broader category.

Both are valid. They diverge in ways that matter once you start sharing files with other people.

## Microsoft Word on the web: what you actually get

The browser version of Word is real Word, but it's a reduced one. Microsoft keeps the desktop and web editions deliberately different, and the gap is the single most useful thing to know before you commit.

**What works well:**
- Opening, reading, and lightly editing `.docx` files. Track Changes appears in the web editor, which surprises people who assume it's stripped out.
- Comments, mentions, and threaded replies — arguably better in the browser than on desktop, because the sidebar doesn't fight the ribbon.
- Real-time co-authoring. Two people in the same paragraph, cursors visible, changes landing live.
- Autosave to OneDrive. There is no Save button in the usual sense; the file is continuously written back.

**What doesn't:**
- Mail merge, custom styles beyond the presets, some field codes, macros, and most of the advanced layout tools. If you need a table of contents with custom numbering, the web editor will look at you blankly.
- Offline editing. The browser tab needs a connection. There's limited caching, but it is not a substitute for a desktop install.
- Add-ins. The web version supports a subset.

The practical rule: **the web editor is for writing and reviewing, the desktop app is for formatting and publishing.** Most people who try to do the second job in the browser conclude that "Word online is broken" when what actually happened is that they used the wrong tool for the task.

![Just Say The Word](assets/photo.jpg)
*"Just Say The Word" — spratpics (CC BY). Whether you're in the browser or on the desktop, the file format underneath is the same `.docx`.*

## The `.docx` question, which is really the whole question

Here's the thing nobody tells you up front: **the format matters more than the editor.** A `.docx` is a ZIP archive of XML parts. It's an ECMA standard (ECMA-376) and it's genuinely open — Microsoft published the spec, and LibreOffice, Google Docs, Pages, and Collabora all read and write it.

That has a consequence people discover the hard way. When you open a `.docx` in Google Docs and then export it back to `.docx`, you don't get the same file. You get Google's interpretation of it, re-serialized. Fonts substitute, spacing shifts, page breaks move. The same is true going the other direction. Round-t through any non-native editor is lossy in ways that are hard to predict and easy to miss until someone opens the file on a different machine.

If you're sharing a document across tools, do one of these instead:
- Send a **PDF** for anything that's final. Nobody's layout survives an edit anyway.
- Keep the `.docx` in exactly one editor for the whole life of the document, and only export out at the end.
- If collaboration is the point, agree on a single platform up front. Mixed-tool editing is where "the formatting is broken" comes from, every time.

## Free options that aren't Microsoft

If your query was `free word processor` or `word pad`, here's the honest landscape.

**Google Docs** is the default for a reason. It's free, it's fast, it handles `.docx` import and export, and the collaboration model is mature. Its weakness is layout fidelity — it is not a page-layout tool and never claimed to be.

**LibreOffice Writer** is the desktop counterpart. It's a full-featured word processor, free, and it opens `.docx` more faithfully than most. If you want a local app and don't want to pay, this is the answer. There's also Collabora Online, the browser build, which you'll see inside Nextcloud and similar setups.

**Zoho Writer** is a credible web editor with a generous free tier. Less common in the West, widely used elsewhere.

**WordPad** deserves a note because it shows up in the query list. It's the ancient rich-text editor that shipped with Windows for decades. Microsoft deprecated it — it's no longer installed by default on Windows 11 and won't be updated. It reads `.docx` poorly and was never meant for real documents. If you're searching for it, you probably want LibreOffice or Word on the web instead.

## Opening a `.docx` you were sent, without installing anything

This is the most common version of the query, so here it is plainly.

1. Go to Office.com and sign in with a free Microsoft account. Any email address works, including a Gmail one.
2. Upload the file to OneDrive, or drag it straight into the Word web editor.
3. Read it, or edit it. Changes save automatically back to OneDrive.
4. To get a copy out, use **File → Save As → Download a Copy**. You'll get a `.docx` (or a PDF if you pick that) back on your machine.

If you'd rather not sign in at all, Google Docs accepts a `.docx` upload from a signed-out state in some regions but will prompt you to log in before you can save. LibreOffice, once installed, needs no account and no connection.

One gotcha worth repeating: **the free web editors are free because storage is the product.** Your document lives in someone's cloud, and the account you used is the key. If that's not acceptable for a given file, use a local app.

## What "online" costs you

The trade is consistent across every browser-based word processor: you give up depth and control, you get access from anywhere and zero install. That's a good trade for a draft, a review pass, or a document you need to share with three people who are all on different machines.

It's a bad trade for a 200-page thesis with custom styles, or anything you need to open on a plane. Knowing which one you're doing is the whole skill.

If you're here because you typed `word online` looking for a specific thing: for Microsoft's own editor, it's Office.com. For everything else, Google Docs and LibreOffice cover the overwhelming majority of what people actually need. Start with one of those, and only reach for the paid desktop app when you hit a wall the browser can't climb.

---
Photos: Romain Vignes · CC CC0 cc0; spratpics · CC BY by