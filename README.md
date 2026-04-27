# ASR & Computational Linguistics Roadmap

Personal interactive study roadmap covering computational linguistics, ASR, and language modelling — from classical HMM/GMM systems to SOTA self-supervised models like wav2vec 2.0 and XEUS, with a dedicated thread on Indigenous language challenges.

**[View the roadmap →](https://your-username.github.io/asr-roadmap)**

## How to add or update topics

All content lives in the `TOPICS` array near the top of `index.html`. Each entry looks like this:

```js
{
  id: "unique-id",          // unique string, no spaces
  era: "classical",         // classical | hybrid | e2e | ssl | indigenous
  title: "Topic name",
  year: "2017–",
  tags: ["tag1", "tag2"],   // shown as pills in the sidebar
  desc: `Long description.

  Supports multiple paragraphs with blank lines between them.`,
  lineage: "How this connects to other topics and eras.",
  resources: [
    {
      type: "paper",        // paper | book | blog | course | tutorial | docs | resource
      title: "Title here",
      author: "Author, Year",
      url: "https://..."    // leave as "" if no URL
    }
  ]
}
```

To add a new era, add an entry to the `ERAS` array above `TOPICS`.

## How to update GitHub Pages

```bash
# Make your edits to index.html, then:
git add index.html
git commit -m "add: topic name"
git push
```

GitHub Pages rebuilds automatically — changes are live in ~30 seconds.

## Personal notes

Each topic has a notes field in the UI that saves to your browser's `localStorage`. These are private to your browser and are not stored in the repo. If you want to persist notes across devices, you could copy them into the `desc` field or add them as resources.

## Setup

See the setup instructions in the initial commit message or the guide below.
