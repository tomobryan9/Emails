# Daily Policy Briefing

Reference copy of the Claude Routine that emails the Tamkeen Daily Policy Briefing at 06:55 GST, Monday to Friday.

- Routine ID: `trig_01H2SuVK2P67XLz8RPs8u3o8`
- Schedule: `CRON_TZ=Asia/Dubai 55 6 * * 1-5`
- Prompt: `briefing/routine-prompt.md` (the routine stores its own copy; edit both together)
- State: deduplication reads the past 21 days of sent briefings in Gmail, so no state file is kept.
