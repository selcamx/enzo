# Changelog

All notable changes to **Enzo for Mac** (`v2.0.0` and later). Every release is signed, Apple-notarized, and delivered automatically inside the app.

- Full web release notes (including historical Chirp 1.x builds): [tryenzo.ai/releases](https://tryenzo.ai/releases)
- Signed DMG downloads: [GitHub Releases](https://github.com/selcamx/enzo/releases)

---

## [v2.0.9](https://github.com/selcamx/enzo/releases/tag/v2.0.9) — 2026-11-20

### New

- **Ghost mode.** Presenter mode is now Ghost mode, and it turns on by itself during a call. It hides Enzo’s windows as well as the notch while you share your screen, and Settings lets you choose During calls, Always or Off.
- **Stats and month view on Speak.** Speak now has a Stats button and a month picker with activity bars for every day. Click the chart icon in Speak’s top bar to see your dictated words and the time talking saved over typing, step back month by month through your Library, or click any day’s heading to jump to another date.
- **Routines side by side.** Routines now open right beside the list instead of in a pop-up over it. Changes save as you make them, past answers read in place one at a time, Cards and reminders live on the page, and deleting has Undo right in the row.
- **Meeting notes in your language.** Notes after a meeting are now written in the language the meeting was held in. Before, a meeting held in another language still got its summary and bullets in English.

### Improved

- **People and voice profiles.** People now focuses on each person’s voice profile, role, note and confirmed meetings, with Needs review at the top when Enzo has a voice to check and Other voices folded at the bottom. Open Samples on anyone’s profile to listen to or remove individual clips, or reset their voiceprint while keeping their name and transcripts, and Undo now takes back a newly named voice too.
- **Faster across the app.** Reopening Enzo’s window, opening a long chat, searching long transcripts in Speak and clicking through a heavy day in Recall all respond right away instead of stalling or scrolling down from the top. Dictation pastes right after you stop, and recording indicators and screen reading do much less background work while you work.
- **Cleaner transcripts and speaker turns.** Dictation and meetings join pauses more cleanly without stray periods or lowercase starts, break longer stretches into natural paragraphs by topic, and cut speaker echo more reliably on calls.
- **The island.** In Island style, Enzo rests as three small rounded squares that wake smoothly into the waveform when you hover or speak and settle back without a flicker. Open panels have cleaner corners and margins, dragging works across the whole pill and while open, and Settings › Appearance adds a Hide when not in use switch.
- **Steps and recordings in Chat.** When you ask a question, Chat says what it’s going to do first, fills in one step after another, and lets you click a Recall or recording step to open what it read. A recording’s card in Chat now keeps Notes and Transcript as two pages in one place.
- **Settings and Permissions.** Settings now gives Permissions its own page, groups Models cleanly, simplifies Storage, puts Quiet hours and Work hours in General, and moves What Enzo knows onto Privacy.
- **Setup on a new Mac.** Setup asks for permissions right on the Dictation, Meetings and Recall pages as you try them, replays four real questions in Chat, and keeps model downloads in one card in the sidebar.
- **Interrupted recordings in Speak.** Recordings cut off by a crash or a forced quit now land straight in Speak and transcribe automatically on the next launch, instead of waiting in a separate Recovery dialog in Settings.
- **Unlimited dictation on Plus.** Plus now includes unlimited dictation, 180 meeting minutes a week and 5× Free’s AI, and Pro steps up to 20× Free’s AI with unlimited meetings. Scheduled routines run on Plus and Pro while Free can try any routine on demand, plan cards open on monthly pricing with six one-line rows on every plan, and Usage keeps to three clean columns.

### Fixed

- **Call audio on headphones.** On some calls, like Microsoft Teams on headphones, a meeting could start while hearing only your microphone. Enzo now joins the microphone the call is using and says “Only your side · Allow Call audio in Settings” in the notch whenever call audio isn’t coming through.
- **Help search box on first open.** The first time Help opened, its search field could overlap the window buttons in the top-left corner. Now it opens below them every time, and the guide matches all of 2.0.9’s pages and shortcuts.
- **Hover tips showing by themselves.** Opening a page or scrolling could pop up a hover tip on whatever landed under the pointer. Tips now appear only after you move the pointer onto a control.

### Removed

- **Activity page, package tracking and Storage Recovery.** The Activity page and automatic tracking of packages, bills and renewals are gone, and anything they kept on your Mac is cleared. Replies you owe and upcoming dates stay on Chat’s first screen, routine answers stay in Routines, Enzo’s recent work moves under Totals on Recall, cut-off recordings recover straight in Speak, and Speak, Recall, Routines and Connections are now ⌘1 to ⌘4.
- **Feedback questions in the app.** Enzo no longer asks “Were these notes right?” under meeting notes, or asks what went wrong when you turn off a routine or cancel connecting an app.

---

## [v2.0.8](https://github.com/selcamx/enzo/releases/tag/v2.0.8) — 2026-11-15

### New

- **Your limits at a glance.** The sidebar, the notch and the menu bar now show your three limits the same way. Solo, Meet and AI each have their own bar, so you can see which one is closest without opening anything. When one gets close, the sidebar names it, like “400 words left”, and hovering shows what each one counts. Quick settings in the notch now has a card for your plan, and a click on it opens Usage.
- **One AI limit a week.** AI now has one limit a week, in place of a 5-hour session on top of the week. You can work with Chat in long stretches without waiting for a session to come back. Everyone’s AI use for this week starts again from zero.
- **Updates when Enzo starts.** Enzo now checks for a new version every time it starts, not only every six hours. A new version downloads in the background and waits for a restart, as before, and nothing pops up while you work. With automatic updates turned off, it doesn’t check.
- **Keys you can spot.** Shortcuts now show each key on its own little key, apart from the words. That’s in hover tips, Settings › Shortcuts, Search, People, setup and the notch. Return looks like the key on your Mac, with a square corner.

### Improved

- **Usage page.** The Usage page now opens with Solo, Meet and AI side by side. Each one leads with what’s left in its own unit, like “3,700 words left” or “38 min left”, then its bar and how much is used. Pro shows No limit for words and minutes.
- **Hover tips.** Hover tips are a little larger, with a clearer edge, so they’re easier to read on a white page. A tip on a control that changes, like Chat’s effort, now changes with it.
- **Effort in Chat.** Chat’s effort tip now names the level and says what it does on a second line. Low says it steps up to Medium for recaps and reviews, which it always did.

### Fixed

- **Words left.** Close to a weekly limit, the words left were rounded to the nearest hundred, so 40 left read “0 words left” and 1,050 read “1,100”. Now it never says more than are left, and under 100 it’s exact.
- **Effort tip in the wrong place.** In Chat, the effort tip could sit off to one side of its dots, and a click hid it until you moved away and back. It stays over the dots now.

---

## [v2.0.7](https://github.com/selcamx/enzo/releases/tag/v2.0.7) — 2026-11-14

### New

- **A welcome when you subscribe.** Coming back from checkout, Enzo now welcomes you to your plan in a pop-up. It says “Welcome to Plus” or “Welcome to Pro” over the window, with what the plan has, after “Confirming your payment” while your account catches up, which it now checks every few seconds. The page on tryenzo.ai that checkout returns to says the same.
- **Ask for a refund in Billing.** For 14 days after your first payment, Billing now shows a Refund row under Cancel plan. It says the date a full refund is good until. Ask for a refund shows the amount and what changes, then starts an email to us.

### Improved

- **Weekly limits.** A weekly limit now holds. Once the week’s dictated words are used, the record key doesn’t start a dictation, and once the week’s meeting minutes are used, a meeting doesn’t start and a call isn’t offered. The notch says how long until they’re back, like “Out of words for 4 days 19 hr”, and a click opens the plans. A meeting under way is never cut short, and the one that reaches the limit still gets its transcript and notes. Before, a dictation past the limit was saved without being typed and a meeting’s notes waited for the week. Free has 5,000 words and 60 meeting minutes a week, up from 50. Plus has 30,000 and 360, up from 300. Pro has no weekly limit on either.
- **Plan cards.** The plan cards now list the same five things in the same order on every plan: words a week, meeting minutes a week, AI, what Chat answers from and how often your inbox is watched. The plans are named for how much they’re for: getting started, everyday work and all-day work.
- **Usage page.** The Usage page now keeps the count when a limit is close or used, like “4,100 of 5,000 words”, and says “100% used” in place of “All used”. A limit that’s close or used shows what the next plan has, with a See plans button. The AI limit that resets through the day is called the 5-hour session everywhere.
- **Changing your plan.** Cancel plan and Resume now ask in Enzo’s own pop-up, with what happens and when on separate lines, like “Plus stays until Dec 13”. A plan that ended and a payment that didn’t go through are said once in the same pop-up, with See plans or Update card. Delete account asks before it starts its email.
- **Questions in Enzo’s look.** Questions that used to come up in a grey macOS sheet now come up in Enzo’s own card: deleting or renaming a conversation, signing out of a connection, turning on cloud AI and recording without call audio. The card that turns Recall on is a short pop-up of four lines in place of a long page. Buttons across the app are worded alike.
- **Live transcript in the notch.** The live transcript in the notch is one card with the bar under it, so nothing moves when you switch between Live and Chat. Each finished turn shows how long it ran beside its start, like “0:55 · 9s”, in a quieter grey.

### Fixed

- **What’s new.** In What’s new, the Improved, Fixed and Removed rows wrapped at half the card’s width and the last rows were cut off under the buttons. They run the full width now and all show.

### Removed

- **“What held you back?” on Billing.** Billing no longer asks why you left a checkout.

---

## [v2.0.6](https://github.com/selcamx/enzo/releases/tag/v2.0.6) — 2026-11-13

### New

- **Chat offers the next step.** When an answer turns up something to do, Enzo now offers it with one button under it. A reply you owe, a promise someone made you or a date you could miss becomes a question like “Remind you Friday at 9:00 AM?”, with what it will add shown under it. Nothing happens until you click, Not now takes the question away, and from the message box ⌘↩ accepts and ⌘. declines.
- **A shorter setup.** Setup is now seven pages that show you how Enzo works instead of describing it. Permissions asks only for the two things dictation needs before you go on, Meetings replays a call on the notch so you see the three ways a meeting starts, and Chat ends in a real card. Downloads show as four rows named by what they do, and say Ready when they’re in.
- **Transcripts inside Chat.** A recording’s transcript now opens inside its card in Chat instead of on another page. Click Transcript on the card that leads a chat about a recording and the words unfold under it, above a meeting’s notes. Double-click a word to play from there. Copy and Open in Speak sit underneath.
- **Sign in from your browser.** On a new Mac, Enzo can now sign you in with the account you made on tryenzo.ai. Continue in browser opens the site, and Open Enzo there brings you back signed in, so you don’t sign up and then log in again. If you’d rather sign in inside the app, that’s one click under the button.

### Improved

- **Live recordings.** A live transcript in the notch and on Speak now looks like a saved one. Each speaker keeps one color everywhere, your own words are white, new words fade in, and the scroll bar stays away while the transcript follows along. Speak’s card for a recording in progress matches the saved cards under it.
- **Recall.** Everything on the Recall page now opens in one reader beside your day. Click a stretch, a visit or an app and the reader shows what was open and the text Recall read there; click a recorded call or a dictation and it shows what was said, with Play. Each stretch now names what was open in it, and a strip above the list shows the day at a glance. The day reads oldest first and today opens at its latest stretch, with Newest first in the More menu, and the page’s two views are Timeline and Totals.
- **Done this week.** Activity’s Done this week now counts only what Enzo made for you, like notes, follow-ups and drafts. Message checks that found nothing, calendar reads and recording titles sit together under one line, which opens to show each. Chat’s home counts what was done for you by the same rule.
- **Drafts in Chat.** Ask Enzo to change a draft and it becomes Version 2 in the same place, with the earlier one folded to a line you can open. Every card now stays under the answer that made it, and a finished one folds to a line like “Added to Reminders · Friday 9:00 AM”.
- **Keeping a dictation Solo.** When a second voice is about to turn your dictation into a meeting, the notch now says “Meeting in 3 s · ⌘Esc to keep Solo”. Press it up to three seconds late and the recording goes back to Solo with nothing lost. The key used to be Esc, which also pressed Esc in the app you were typing in.
- **People.** A card on People that asks Who’s this? can now be closed again, and a row under Heard once is answered right where it opens. The names a voice could be drop down from the name field as a menu, the confidence tags match the Library’s badges, and Add from Contacts is gone from the page.
- **Connections.** Chat finds more in your Mac’s apps and tells you when it couldn’t see everything. Apple Mail searches the whole period you ask about instead of its newest 2,000 messages, Folders puts files named with your words first, and Calendar leaves out cancelled meetings and invitations you declined.
- **Files on Chat’s home.** Adding a file to Chat’s home now keeps you on the home until you send your question. The quick asks are one row of buttons at the message box, and with a picture or a document in the box they offer what fits it.
- **Usage card.** The sidebar’s usage card now leads with the limit you’re closest to: how much is used, its bar and when it resets.
- **Settings with the sidebar hidden.** With the sidebar hidden, a Settings page’s title now opens the list of pages, in place of a system pop-up that looked out of place.

### Fixed

- **Static in recordings.** Recordings made in 2.0.6 with a MacBook’s built-in microphone played back with static, and their transcripts were made from the same sound. That’s fixed for every recording from here on. Recordings saved in 2.0.6 keep the static.
- **Messages.** A conversation with one person on both iMessage and text messages was read as two halves, so Chat could list a reply as owed after you had sent it, and messages in Recently Deleted could turn up in a search. Both are fixed.
- **One package, several rows.** Activity could list one package several times when its shipping mail was open in a browser with no order number in view, because each look started a new one. A package seen on screen is now listed once its order or tracking number is in view, and the rows started without one are removed.
- **Icon on macOS 26.** On macOS 26, Enzo’s icon looked soft. It’s now the layered kind of icon macOS 26 draws itself, instead of a picture macOS shrinks and redraws, and it follows the Dark, Clear and Tinted icon styles. On macOS 15 it now has Apple’s own corner shape and a light edge.
- **A message left over the notch.** Opening the notch while a message showed under it left the message’s words lying over the page. They’re cleared now.

### Removed

- **Rating an answer.** The thumbs-down under a Chat answer is gone.
- **Create Summary on Recall.** The Recall page no longer creates an AI summary of a day. The Chat button asks about the day, and a day with a saved summary still shows it.

---

## [v2.0.5](https://github.com/selcamx/enzo/releases/tag/v2.0.5) — 2026-11-10

### New

- **An island for Enzo.** Enzo can now live on a small island at any edge of your screen instead of in the notch. Pick Island in the notch’s Quick settings or in Settings › Appearance › Where Enzo lives, then drag it to any of eight spots. It opens into the same pages as the notch, which helps when another app wants the notch too.
- **Pick your microphone.** You can now choose which microphone Enzo records from, and change it during a recording. Quick settings and Settings › Recording list every microphone connected to your Mac, and an open recording has a microphone icon that lists the same ones. Automatic stays the default.
- **See what Enzo knows.** Settings › Data now lists what Enzo knows about the people and companies you deal with. Open someone to see who they are, the mail you’ve exchanged, your last meeting and what’s open, with where each line came from. Forget removes someone who isn’t on People, with everything about them, and the list is part of Export and Delete.
- **Updates that stay out of your way.** After an update, a card in the sidebar says which version you’re on and opens What’s new. Nothing opens by itself any more. What’s new shows the highlights in a small pop-up, About is the same panel wherever you open it, and a restart to update waits until your recording is done.

### Improved

- **Effort as three dots.** Chat’s effort level now shows as three dots in the message field instead of a word: one lit for Low, two for Medium, three for High. Click the dots to change it.
- **Headphones and calls.** A recording now starts on your Mac’s own microphone, so a dictation never waits a second for a headset to wake. When a call is using your headset’s microphone, Enzo joins it with no gap and comes back when the call ends.
- **Long turns in a meeting.** When one person talks for minutes, their words are now split into blocks at the end of a sentence, each with its time, instead of one block of hundreds of words. Meetings saved before keep their blocks until you transcribe them again.
- **Buttons and motion.** Buttons now look the same across the app, dark for the main action and light beside it. Usage bars glide to a new value, pages arrive the way Chat does, Recall’s chart draws in when you open a day, and the fox above Chat’s greeting swishes its tail on a new chat. It all holds still with Reduce Motion on.
- **Setup.** Setup’s last page now waits for the dictation download and shows how far along it is, with Open Enzo now if you’d rather not wait. If you skipped your first dictation, setup invites you back once your key works.
- **Hover help on the notch.** While you record, the notch’s hover help now names Right ⌘ for asking about the recording. If you don’t want the help, turn it off in Settings › Appearance › Hover help.

### Fixed

- **Bluetooth headphones.** A recording started with Bluetooth headphones on could blink the microphone dot for several seconds, capture nothing and end as “No speech detected”. That’s fixed.
- **Words missing from a call.** On a call, when someone started three sentences in a row the same way, like “I don’t know”, only the first was kept. Now all of them are.
- **Speaker names on calls.** A recording that became a meeting because a call started showed who spoke when but named nobody. It now names the speakers however the meeting began.
- **A double-click that lost a dictation.** Double-clicking the notch to stop a recording could throw away the dictation you had just made, because the second click cancelled it. The second click is now ignored.
- **Punctuation in long dictations.** A long dictation could get a period before a lowercase word, or no period before a capital, where two stretches of speech met. Those joins now agree.
- **Voices on People.** Undoing a Yes on someone’s voice could be confirmed again a moment later, and a deleted person’s meetings could come back as a voice with no name. Both are fixed.
- **The wrong company on a person.** If a contact had a second address, say at a university, everyone at that university could be listed as working at the contact’s company. A line you marked Not right could also come back after you deleted a recording. Both are fixed.

---

## [v2.0.4](https://github.com/selcamx/enzo/releases/tag/v2.0.4) — 2026-11-09

### New

- **Chats about a recording.** A chat about a recording now opens with the recording itself: its name, when it was, who spoke, a play button and the transcript, with a meeting’s notes right under it. The chat takes the recording’s name, a small waveform marks it in the sidebar and on its tab, and a question you asked during the meeting says when, like “During the meeting · 1:55”.
- **People pages that know the person.** Link someone’s Contacts card to their page in People, and the page shows what’s open between you, like mail and texts waiting on a reply or what you’re waiting on from them, and when you next meet. What Enzo knows lists what it picked up about them on your Mac from your mail, invitations, meetings and contacts, like “Product Designer at Harbor”. Not right or Remove takes a line away for good, and Chat reads the whole page when you ask about someone.
- **Work, Personal and School.** In Connections, give each Mail account, calendar and Messages an area, and Activity lets you show All, Work, Personal or School. Work hours, in Settings › Notifications › Quiet, keep news from Work out of the notch outside the hours you set, 9 to 6 on weekdays to start.
- **Add to an answer while Chat reads.** Send a few more words while Chat is still reading for an answer, and they join that answer instead of waiting their turn. Your message says “Adding to this answer” until Chat takes it in.

### Improved

- **One Record button.** Speak now has a single Record button, which starts a Solo recording. Rest the pointer on it and Meet slides out beside it for a meeting.
- **A plainer menu bar menu.** Enzo’s menu bar menu is now a standard Mac menu in four groups, with checkmarks instead of icons. It names your closest limit once you’ve used 80% of it, and Record a Meeting is gone, since Enzo offers to record a call when it starts.
- **Files in Chat.** Files you add to a question now show as quiet lines with their kind’s icon and name, and when space runs short, several pictures fold into one line like “4 pictures”. Drag a file in and you see where it will land, in the window and in the notch.
- **Limits, said once.** The sidebar’s usage meter now says what it means at the end of its bar: how much you’ve used, then from 80% what’s left, like “400 words left”, and once it runs out, when Chat is back. When Chat’s allowance is spent, the box says so once: “Session limit reached · back in 3h 57m”.
- **Recording settings.** Recording settings are now grouped into Audio, Solo and Calls, and every row fits on one line. The countdown when someone else starts talking in a Solo recording has its own switch, so you can turn it off and still have calls become meetings.
- **Billing.** Update now sits on your card’s row. A receipt shows its tax when you point at it, like “$10.00 + $0.81 tax”, and a refund now counts everything that came back to your card, tax included.
- **Privacy.** Chat now opens a link in an answer only when it’s a secure link to a site the answer itself used. After a dictation, a password you had copied is no longer put back on the clipboard, so your password manager can still clear it, and clipboard managers no longer keep your dictations. When Chat looks at your screen, login codes are hidden from it.

### Fixed

- **Long questions in Chat.** A question that read a lot, like “what did I work on this week?”, could fail with an error just as Chat started writing, after all its reading. It now writes the answer. Chat also keeps going when it trips over one step, instead of ending the question.
- **An answer that rewrote itself.** A recap like “what did I work on today?” could appear in full, vanish, and be replaced by a different answer a few seconds later. Now you see one answer.
- **Forgetting on time.** Recall could miss forgetting on schedule while you were signed out, and a deleted person’s voiceprint could stay in People’s files until later saves covered it. Both now go when they should.
- **The word lit on a People line.** Playing a line on someone’s People page stopped lighting the word being heard. It lights up again.

---

## [v2.0.3](https://github.com/selcamx/enzo/releases/tag/v2.0.3) — 2026-11-05

### New

- **Words and minutes across your Macs.** If you use Enzo on more than one Mac, the words you dictate and the minutes you record now add up across all of them, as Chat’s AI use already did, so your plan’s weekly limits cover your Macs together. Usage says “Counted across all your Macs.”
- **Hold to switch Solo and Meet.** Rest the pointer on a recording’s Solo or Meet label, on the Live page or Speak’s recording card, and the other type slides out beside it. Hold it for half a second and a ring fills round its dot, then the label rolls over to the new type. A quick click only says “Hold to switch”, so a recording can’t change type by accident.
- **How close you are to a limit.** A thin line above your account in the sidebar now fills toward whichever limit you’ve used most: AI this session, AI this week, dictated words or meeting minutes. From 80% it names that limit and says when it’s back, like “resets in 1h 40m”. Point at it to see every limit.
- **Calls in Safari and Firefox.** Recording settings now has Calls in Safari and Firefox, under Read the call’s window, so Enzo can read a Google Meet call in Safari without Recall turned on. It stays off until you turn it on, and it reads call windows only.
- **Credit for what you report.** When you send a bug report or a feature request, you can tick “Credit me as” with your first name, and its public GitHub issue says who sent it. We’ll let you know when it’s fixed or ships. Diagnostics you attach now come to us privately and never appear on the issue.

### Improved

- **When a second voice joins.** When someone else starts talking in a Solo recording, the notch now counts down “Meet in 3 s” and then makes it a meeting, instead of waiting for ⌘↩. Press Esc or click Keep Solo before then to keep it Solo, and ⌘↩ stays with the app you’re in.
- **Corner cards.** A card in the corner now opens into what it has to say, with its actions as words underneath, like Open notes, Copy notes and Options. A routine’s card shows the start of its answer, and its Options can pause the routine or open it to change. A card waiting its turn also holds back when you start recording, a call or a presentation, and a mirrored display or a full-screen slideshow or video counts as presenting.
- **More room in the window.** The Enzo name now sits in the title bar, so the sidebar starts with New chat, with Search right under it. Search shows the moment you open it. With the sidebar hidden, the page’s left edge bows in as your pointer comes near, and touching the bow opens the sidebar.
- **See when Chat is working.** A chat’s tab shows a spinning ring while Chat answers, and a dot stays on a tab you’re not on until you see its new answer. In the notch, a gray arc turns inside the Dot while Chat works and closes into the green Dot when the answer lands. Tab icons now match the sidebar’s.
- **Settings and Help.** Settings’ pages have new icons and sit in three groups, Data is now Storage, and Plan is now Billing. The account menu gathers Guides, Shortcuts, Feedback and About into one Help screen, and every Help menu has Contact Support for a private question, even with no Enzo window open. Help itself is rewritten with one idea per section.
- **Billing.** The Billing page now puts Cancel plan under your plan, shows your card’s brand, last four digits and expiry, and lists receipts as a table of plan, date, status and amount. Click a receipt to open its PDF.
- **Where a dictation’s sentences break.** A long run-on sentence is now split where a new thought starts, like before “and I” or “so we”, instead of at its longest pause, so a paragraph no longer ends mid-phrase. A dictation that trails off now ends with a period, or a question mark when it was a question. Your words never change.
- **Recording cards.** A meeting card’s top row now matches a solo card’s, with the speakers’ names first, then Chat, Copy and Tag. On a recording’s page, Live and Chat sit at the right just before Copy or Send, so the switch stays put. A recording’s hover help now shows at once, in the tip above its timeline.

### Fixed

- **The word you double-clicked.** Double-clicking a word to play from it briefly lit the word before it, most noticeably on AirPods. Now only the word you clicked lights up.
- **Stray marks in meeting summaries.** A notes-ready card or a meeting brief could show “Summary**” or “Decisions None Action items None”. They now show only the summary’s words.
- **Briefs and your AI usage.** Free’s plan card said meeting briefs came out of its weekly AI usage. Briefs are made on your Mac and never did, and the card now says so.
- **Enzo’s icon on macOS 26 and later.** Enzo’s icon looked blurry when you switched apps with Command-Tab. macOS now draws it like any other app’s icon, so it’s sharp, and it stays light whichever theme you pick.

---

## [v2.0.2](https://github.com/selcamx/enzo/releases/tag/v2.0.2) — 2026-11-04

### New

- **Chat shows its work.** While it answers, Chat says in a sentence what it’s about to do and shows each step as it happens, with the sites it reads, then folds them away once the answer arrives.
- **Sources you can see.** Each source in an answer is now a small pill beside what it supports, naming the site, with its pages when you point at one. Answers no longer end in a typed list of links, Chat keeps its sources until you delete the chat, and tables show as tables.
- **Tell Enzo how it went.** Short questions now come up right where something happened, never as a pop-up and never while you’re recording: whether a meeting’s notes were right, what wasn’t right in a Chat answer (“Not what I needed”, beside Copy), what stopped an app from connecting, why you turned off a routine, and what held you back from a plan you didn’t buy. You get one a day at most, and ✕ stops a question for good.
- **Ask for the apps you want.** Apps marked Coming soon in Connections now have “I want this”, and you can name an app Enzo doesn’t list. Enzo emails you when one you asked for is ready.
- **Daily counts on your account.** Your account now gets a daily count of words dictated and meeting minutes recorded. Usage statistics now also count how dictation and routines went, such as a paste that failed or a routine turned off. Numbers only, never what was said or what a routine asks. Turning off Share anonymous usage statistics stops all of it.

### Improved

- **Limits by the month.** Plan cards now give each weekly limit as a month too: 20,000 words and 200 minutes on Free, 120,000 and 1,200 on Plus. The limits themselves are still weekly, and Usage now says recording is counted on each Mac.
- **How soon a recording is ready.** Recording cards and Speed on your Mac now say how soon after you pressed stop the transcript was ready, like “Ready in 140 ms”, instead of a number like “7× realtime” that mostly measured how long you talked. A card’s details also read in one order now: how it was recorded, a dictation’s pace or a meeting’s people (point at them to see who talked how much), how soon it was ready, and what Enzo’s AI wrote. Speed’s chart starts fresh with your next recording.
- **Long dictations.** Even an hour of dictation is now ready about a quarter of a second after you stop, where it used to take two, because Enzo works out its paragraphs while you talk. The paragraphs are shorter too: 80 words at most, with a run-on sentence split at its longest pauses. Your words never change.
- **Naming a voice.** When Enzo asks who a voice is, Video or audio, Don’t know them and Later now sit beside the name. Clicking the name lists your people, likeliest first, with how likely each one is, and Enzo warns before you add a voice to someone it probably isn’t.
- **The notch’s waveform in more places.** Speak’s recording card and dictating a question into Chat now show the notch’s own waveform, and when you finish dictating, it settles into the notch’s working sweep instead of a spinner.
- **Empty pages, painted.** While Library, People, Chats, Recall or Activity is empty, its fox scene now fills the page behind the words instead of sitting small above them. Activity has a new one, the fox keeping watch.
- **Quieter Activity.** Texts from unknown senders, the kind Messages files under Unknown Senders, no longer show up in Activity, and Pick up where you left off is gone from it.
- **Small signs that something worked.** Copy turns into a check, setup’s checks land as each step finishes, and a ticked meeting to-do or a Done in Activity shows its check before the row moves. The sidebar’s icons move a little when you point at them, and Activity’s bell rings when something new needs you.

### Fixed

- **A call could crash.** If one side of a call said a word and then stayed quiet for about 20 seconds, Enzo could crash and end the recording. It no longer does.
- **A sentence after a pause.** After a pause of a couple of seconds, a thought trailing off could run into the next one with a capital and no period, like “you know um What can we do”. Enzo now hears both sides of the pause together, so this rarely happens.
- **Split words.** Where Enzo joins the pieces of a recording, a word could come out in two (“pro perly”) or a period could stand alone between words. Words now stay whole.
- **Usage limit after the reset.** Chat could keep saying you’d reached your usage limit after it had already reset, until you opened Usage. Now the notice clears when the limit resets.
- **Dates in a question.** Asking something like “why so much rain the last few days” turned it into a question about only your own history, and a range like “October 22 through October 28” read just the first day. Now Chat looks wherever the answer is, across every day you named.
- **Countdowns for re-transcribing.** Re-transcribing a recording, or finishing one Enzo didn’t get to before it quit, showed a countdown far too short once you’d made a few recordings. Each is now timed from earlier runs of its own kind.
- **No answer over a citation.** A few web answers stopped with an error instead of the answer when Chat cited a page it hadn’t read. Now it’s told exactly which sources it can cite, so it finishes.
- **A clicked bullet went blank.** Clicking a bullet in a Chat answer could leave it blank as the message box took focus. It stays drawn now.

---

## [v2.0.1](https://github.com/selcamx/enzo/releases/tag/v2.0.1) — 2026-11-01

### New

- **A second account on your Mac.** Each Enzo account on a Mac login now has its own recordings, chats, People, Recall and connected apps. Sign in with another and Enzo asks before starting fresh; the first account’s history is set aside until it signs in again.
- **One Free account per Mac login.** A second account on the same Mac login needs Plus or Pro. Someone sharing your Mac gets their own Free account with their own Mac user.

---

## [v2.0.0](https://github.com/selcamx/enzo/releases/tag/v2.0.0) — 2026-11-01

### New

- **Chirp is now Enzo.** Same dictation and meetings, now with an assistant that knows your work. Enzo is a new app that starts fresh, with a free account. Chirp keeps working as it is, but it won’t get any more updates.
- **Chat.** Ask about your meetings, your recordings and what you worked on, even while a call is still recording, and get an answer that shows where it came from. Open it from the notch or the main window, and set how much effort it takes with a slider.
- **Notes after your meetings.** Meetings are transcribed as they happen, so soon after one ends Enzo has written up what was decided and what you owe. Plus and Pro write them after every meeting. On Free they start on too, within your weekly AI usage.
- **Briefs and follow-ups.** Before a call, Enzo tells you what is still open with the same people, and after it, drafts the replies you promised. Every plan has them, out of its AI usage.
- **Work Enzo does on its own.** Enzo plans your morning, finds the mail and chats that need a reply or are due, and asks your routines’ questions on a schedule. Settings shows everything it sends to its AI by itself. Every plan has it, out of its AI usage.
- **Packages, bills and dates.** Enzo finds deliveries, returns, renewals, bills, school work and appointments in your mail and lists them in Activity. It reads that mail on your Mac and sends nothing. On Plus and Pro, ask Chat to keep track of anything else that comes by mail.
- **Connected apps.** Connect Apple Calendar, Reminders, Contacts, Mail, Notes and Messages, and folders on your Mac or in the cloud. Chat answers from all of them, including every account you’ve added to Mail and Calendar. More apps are coming.
- **Recall.** Turn it on and Enzo remembers what you worked on, grouped into the stretches of your day, so you can ask about it later. On Plus and Pro, Enzo names each stretch by what you did. It starts off, stays encrypted on your Mac, and you can pause it, keep apps out or delete it any time.
- **People.** Voices are now People. Name someone once and Enzo recognizes them in later meetings, and Chat knows who said what.
- **Free, Plus and Pro.** Free has 5,000 dictated words and 50 meeting minutes a week, and recordings always save. Plus has 30,000 and 300, answers from all your history, keeps track of what you ask and names your day in Recall. Pro has no limit on either and 3× Plus’s usage, and both come with a 14-day money-back guarantee.

---
