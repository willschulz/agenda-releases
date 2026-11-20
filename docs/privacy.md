---
title: Agenda privacy
---

# Agenda privacy

Agenda is a local-first app. Its developer runs no servers for it and
collects no data about you or your use of it.

- **Your board stays on your devices.** On the Mac, projects, todos, and
  notes are stored in a database in your user Library. If you use Agenda for
  iPhone or iPad, they sync through your own private iCloud database, which
  only your Apple ID can read. The developer can't see it.
- **No accounts, analytics, tracking, or ads.**
- **AI features run on your device.** Suggested titles and Pulse insights use
  Apple's on-device models where available. Agenda makes no calls to
  third-party AI services.
- **Optional AI-usage tracking** reads the token counts that coding tools on
  your Mac already record (never prompt text) and keeps them in your local
  database.
- **Network use.** The Mac app checks for updates at
  `willschulz.github.io`. Like any web request, this shows GitHub, which
  hosts the update feed, your IP address and Agenda's version. Nothing else
  is sent. Agenda's local agent API listens only on your own Mac
  (`127.0.0.1`), so other computers can't reach it.
- **Problem reports** open a GitHub issue form in your browser with Agenda's
  version and basic diagnostics filled in. Nothing is sent unless you submit
  the form, and logs are never attached. Issues on GitHub are public, so
  don't include private project names or notes.

Questions about privacy: open an issue at
[github.com/willschulz/agenda-releases/issues](https://github.com/willschulz/agenda-releases/issues).
