# esoji

**Find, keep and tidy the photos that matter.** esoji is a Mac app that works on top of Apple Photos: search your
library in your own words, get suggestions for photos to heart and albums to make, clear out duplicates, and hide
photos of someone in one go.

### [Download esoji for Mac](https://github.com/santekotturi/esoji/releases/latest/download/esoji.dmg)

Open the download, drag esoji to Applications, then open it from Applications. It's signed and checked by Apple, so it
opens without warnings.

<p align="center"><img src="https://github.com/santekotturi/esoji/releases/download/screenshots/hero.png" width="860" alt="esoji's main window: photos of mountain sunsets in a grid, with the sidebar on the left and the chat on the right."></p>

## What it does

<table>
<tr>
<td width="50%"><img src="https://github.com/santekotturi/esoji/releases/download/screenshots/feature-search.jpg" alt="A search for sunset mountain tops"><br><b>Search in your own words</b>: “the dog on a summit”, “sunsets from the van”</td>
<td width="50%"><img src="https://github.com/santekotturi/esoji/releases/download/screenshots/feature-hearts.jpg" alt="Suggested Hearts"><br><b>Suggested Hearts</b>: your best photos you haven't hearted yet</td>
</tr>
<tr>
<td><img src="https://github.com/santekotturi/esoji/releases/download/screenshots/feature-albums.jpg" alt="Suggested Albums"><br><b>Suggested Albums</b>: trips and moments, ready to create</td>
<td><img src="https://github.com/santekotturi/esoji/releases/download/screenshots/feature-duplicates.jpg" alt="Duplicates"><br><b>Duplicates</b>: near-identical shots grouped, the best one kept</td>
</tr>
</table>

## What you need

- A Mac with Apple silicon (M1 or later) and macOS 26 or later
- About 6 GB of free space
- Your photos in Apple Photos
- Optional, for search understanding and the chat on your Mac: Apple Intelligence, turned on, on a Mac that supports it
- Optional, instead: [Claude Code](https://claude.com/claude-code) (a paid Claude plan) or
  [Codex](https://developers.openai.com/codex/cli), installed and signed in. Without any of these,
  search gives instant results and suggestions, duplicates, hiding and Morning esoji all still work.

The first time you open it, esoji asks for access to Photos, then downloads its search engine and image model
(about 3 GB). After that it reads your library in the background. You can use it right away; search gets better as it
goes, and a large library takes a few hours.

## Private by design

- **Your photos never leave your Mac.** Understanding your pictures (EmbeddingGemma 2 and Apple Vision), search,
  suggestions, duplicates and face matching all run on your Mac. No account, no analytics.
- **With Apple Intelligence, all of it can run on your Mac**: understanding photos, search, refining searches and the
  chat. It works offline after the one-time setup download.
- **Claude Code and Codex are optional and get text only.** The chat and smarter search can use Claude (Anthropic) or
  Codex (OpenAI) instead, only after you turn one on. Before anything is sent, photo ids become handles like `S3.12`,
  People names become stand-ins like `PERSON_A` (unless you choose to share names), and emails and phone numbers are
  removed. They never see your photos, thumbnails, face data or file names.
- **The assistant can't change anything.** Whichever it is, its tools run in a sandbox with no network and can only
  propose. esoji changes your library only when you press Apply. Deleting asks you first, then macOS asks again, and
  deleted photos stay in Recently Deleted for 30 days.
- **Morning esoji** (optional) is made on your Mac at night: the best new photos to heart, an album when a trip is
  over, new duplicates. Nothing is sent anywhere.

The [download page](https://santekotturi.github.io/esoji/#security) has a diagram of what stays on your Mac and what
Claude Code or Codex see.

## Updates

esoji checks for a new version at most once a day and tells you only when there is one. The check asks GitHub for
the public page of esoji's latest release, with an `esoji/<version>` User-Agent: nothing about you or your photos.
Turn it off in **Settings → Updates**, or check yourself with **esoji → Check for Updates…**. To update, download again
and replace the app in Applications. Your settings and index stay.

## Questions or problems

[Tell us here](https://github.com/santekotturi/esoji/issues/new). Please don't attach screenshots of your own photos
unless you're happy for them to be public.
