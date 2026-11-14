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
- For the chat: [Claude Code](https://claude.com/claude-code) installed and signed in, which needs a paid Claude plan.
  Without it, search, suggestions, duplicates and hiding all still work.

The first time you open it, esoji asks for access to Photos, then downloads its search engine and image model
(about 3 GB). After that it reads your library in the background. You can use it right away; search gets better as it
goes, and a large library takes a few hours.

## Private by design

**Your photos never leave your Mac.** Understanding your pictures, search, suggestions, duplicates and face matching
all happen on your Mac. esoji has no account and no analytics.

The chat and the smarter search can use Claude (by Anthropic), but only if you have Claude Code and turn it on. They
send text, never photos, and esoji shows you exactly what it sends first. Everything else works without it.

esoji changes your library only when you click: it suggests albums and hearts and you press Apply, and deleting always
asks you first, then macOS asks again. Deleted photos stay in Recently Deleted in Photos for 30 days.

## Updates

Choose **esoji → Check for Updates…** in the app. To update, download again and replace the app in Applications. Your
settings and index stay.

## Questions or problems

[Tell us here](https://github.com/santekotturi/esoji/issues/new). Please don't attach screenshots of your own photos
unless you're happy for them to be public.
