# Privacy Policy — AtomicLLM

**Last updated: 19 July 2026**

## Summary

AtomicLLM does not collect, transmit, sell, or share any user data. The extension has no
backend server, no analytics, and no telemetry. Everything it does happens on your own
computer.

## What AtomicLLM stores

The extension saves the following locally on your device using Chrome's `storage.local` API:

- Your chat sessions and the messages inside them
- The name of the Ollama model you selected
- Your theme preference (dark / light / system)
- A flag recording whether you completed first-run setup

This data never leaves your device. It is not uploaded, backed up to any server, or
synchronised across machines. You can delete all of it at any time using **Clear All Chats**
in the extension menu, or by removing the extension.

## Where your prompts go

Prompts you type — and any page text you select and send via the right-click menu or the
selection toolbar — are sent to the Ollama server running on your own machine at
`http://localhost:11434`. This is a loopback address: the request never leaves your
computer and never reaches the internet.

AtomicLLM makes no network requests to any other host. There is no remote API, no cloud
inference, and no developer-operated server involved at any point.

## Page content

AtomicLLM includes a content script that runs on web pages so it can show a small toolbar
when you highlight text, and so it can pass text you explicitly select into the chat. The
script does not read, log, scrape, or transmit page content on its own initiative. It acts
only on text you have selected and on actions you have deliberately triggered. Any text it
handles goes only to Ollama on your own machine, as described above.

## Data sharing

We do not sell or transfer user data to third parties. We do not use or transfer user data
for any purpose unrelated to the extension's single purpose. We do not use or transfer user
data to determine creditworthiness or for lending purposes. Because no data is collected in
the first place, there is nothing to share.

## Permissions

- **storage** — save your chats and settings on your device
- **contextMenus** — add the Ask / Summarize / Explain right-click items on selected text
- **sidePanel** — show the chat in Chrome's side panel
- **activeTab** — identify the current tab when you open the panel or pull in page text
- **host permission `http://localhost:11434/*`** — talk to Ollama on your own machine

## Third-party software

AtomicLLM connects to [Ollama](https://ollama.com), which you install and run yourself.
Ollama is separate software with its own terms and privacy practices. AtomicLLM does not
send your data to the Ollama project or to any model provider — it only talks to the copy of
Ollama running locally on your computer.

## Children's privacy

AtomicLLM does not collect data from anyone, including children under 13.

## Changes to this policy

If this policy changes, the updated version will be published at this URL with a new
"Last updated" date.

## Contact

Questions about this policy: **ankitsalvi233@gmail.com**
