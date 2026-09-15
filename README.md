# Your life, in five files

A starter template for a small "context" system: a handful of plain-text files, kept in one place, that describe who you are, the people in your life, what you have going on, and what you've decided. An AI assistant reads them at the start of every conversation, so its answers fit your actual situation instead of being generic.

You don't fill the files in yourself. The assistant interviews you and fills them in. The instructions for that are in GUIDE.md, written for the assistant to read.

## How to start (phone or computer)

You need one thing: ChatGPT on the paid plan (Plus), or Claude on its paid plan (Pro). Everything else, including a GitHub account if you don't have one, gets set up during the conversation while you watch and approve.

Where you are: this page is on GitHub, a website for keeping files. The list at the top of the page is the files in this template; the text you're reading sits underneath it.

1. Open [PROMPT.md](PROMPT.md): tap that link, or scroll up to the list of files at the top of this page and tap its name there. A short page opens with a grey box on it. Tap the copy icon in the top corner of the box; if you don't see one, press and hold the text, choose Select All, then Copy. Nothing to download, attach, or edit.
2. Open ChatGPT or Claude and start a new chat. On ChatGPT, two settings: at the top, tap Work (not Chat); at the bottom of the message box, set the model picker to Medium (not Instant). On Claude, there's nothing to set. Paste the message and send.
3. Follow along. It reads the guide from this page, asks your first name, helps you make a GitHub account if you need one, creates your own private copy of these files (ChatGPT in a browser you watch, where you log in and approve; Claude through its GitHub connection, which you approve once), then interviews you and fills the files in. Plan on two or three sittings; you can stop any time.

If you'd rather set up the repository yourself first: open https://github.com/new?template_owner=AronCorp&template_name=ai-context-template (the form behind this page's "Use this template" button, which only shows on a computer, not on a phone), name it your first name followed by -life-context (for example maria-life-context), choose Private, and tell the assistant it already exists. If the links don't open for you, the ZIP route is at the bottom of PROMPT.md.

Why the two ChatGPT settings: Work is the mode that can read pages and use a browser; Chat can't. And the setup is a long list of instructions to follow carefully; Instant is built for speed and follows long instructions loosely, Medium holds them. Instant is fine later for quick everyday questions.

## What to expect

- It opens with a five-minute picture game, then asks about your days and your people rather than your goals; most of us describe our days well and our goals badly. It tells you what it thinks that adds up to, and you correct it.
- The interview comes in four short rounds, and you get a finished file at the end of each one. Each question says what shape of answer it wants (one per line, a sentence or two). Answer in your own words, ramble if you like; it does the tidying. Say "skip" to any question you don't want to answer.
- Coming back after a break: it writes where you got to into your own files. If the same chat is still open on your phone, just carry on in it. Otherwise, open PROMPT.md again (the same link that brought you here), copy the box, start a new chat with the same settings, paste, and when it asks, say you already have a repository. It reads where you left off and carries on. It's the same chat on your phone and your computer; if it hasn't appeared on the other one yet, close and reopen the app.
- On ChatGPT, when a step needs clicking on a website, it opens a browser you can watch. It stops and asks before it saves or submits anything, and hands the browser to you for logins and sign-ups: you type your own email and password, and it never sees them. GitHub also checks it's you when you log in: a code by email, a code from an authenticator app, or, if you have the GitHub app on your phone, a notification asking for a two-digit number that the assistant tells you. That's normal, not a problem. If it hits an "I'm not a robot" check, that's yours too. On Claude there is no browser: it reads and writes your files through its GitHub connection, which you approve once in its settings, and for the GitHub sign-up it gives you the link and tells you what each screen asks for.
- You don't have to open GitHub yourself. The assistant makes each change itself, ChatGPT in a browser you can watch, Claude through its connection, then reads the file back and tells you what it saved. The files are yours to look at any time, and if a save ever goes wrong, every file has a "History" button that brings back the previous version; the assistant can do that for you too.
- Once setup is done, the four phrases in [COMMANDS.md](COMMANDS.md) are the whole job: "save it", "hand off", "wrap up", "reset the week". One question, "what can you do for me?", is where the payoff comes from. New day, new chat; on ChatGPT, Work at the top, Medium at the bottom.
- If you have two chats going at once, let one finish saving before the other one saves. Two chats writing the same file at the same time will overwrite each other.
- While you're on GitHub, it asks whether, on top of the notes it keeps in your files, you also want to keep the full text of your AI chats. Say yes and it makes a second private folder for them at the same time, your archive; say no and you can add it later.
- The moment you'll feel it working: a few weeks in, when you ask something ordinary and the answer already accounts for your situation without you explaining it again.

## What you do with it

The files pay off in ordinary questions, once the answers already know your situation. Some that work from the first week:

- "What's on this week?" It reads your list, lays the week out, and asks what to drop.
- "I'm seeing (name) tomorrow. What should I remember?" It knows who they are to you and what's going on with them.
- "That repair has been waiting for months. Plan it around my weekends." It knows your weekends and what limits the job.
- "Write to (the landlord, the school, a client) about (the thing). You know the history." A message in your voice, with the facts right.
- "I'm weighing (a choice). Give me the options." Laid out the way you asked to be talked to.
- Something changed? Say it. It asks whether to update the file, and next time the change is already known.

When you don't know what to ask, ask "what can you do for me?" It reads your files and offers three things it could do right now, each drawn from something you told it; pick one. At the end of setup it also sets up two reminders, one in the evening asking whether anything from today needs wrapping up or handing off, and one on your reset day, as scheduled reminders in ChatGPT or Claude, or as two alarms on your phone.

## What's inside

- [GUIDE.md](GUIDE.md): the instructions for the assistant. What this is, the interview, the setup steps, the rules, and the mistakes the template exists to prevent.
- [PROMPT.md](PROMPT.md): the short message you paste into ChatGPT or Claude to start.
- [PROJECT-INSTRUCTIONS.md](PROJECT-INSTRUCTIONS.md): a block you paste into your Project's instructions, in ChatGPT or Claude, so every chat starts from your files.
- [COMMANDS.md](COMMANDS.md): the four phrases and the one question you'll use day to day, on one page.
- profile.md, people.md, areas.md, now.md, log.md: the five files, empty, with headings.
- inbox/: a folder for raw material waiting to be folded into the five files.
- skills/: the step-by-step procedures behind "hand off" and "wrap up", for the assistant.

## Other assistants

The setup steps are written for ChatGPT and Claude; the guide says which does what. The five files, the rules and the interview work with any assistant that can read a GitHub repository or an uploaded file; only the buttons differ.

## Credits and license

Released by Aron Corp. Written by Nicholas Aron, with Claude (Anthropic) as the drafting and research partner.

This is free for anyone to use, copy, change, and build on, for personal or commercial purposes, under the MIT license (see LICENSE). Nothing is owed back. If it turns out to be useful to you, if your AI's answers get better and your days get a little easier because of it, a link to this page or a mention that it was part of how you learned would be truly appreciated: https://github.com/AronCorp/ai-context-template
