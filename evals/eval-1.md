# Daily Email Triage — Classification Eval Log

This file tracks the AI's classification of each triaged email against a human-labeled ground truth.

**How to label:** find the row for an email below, click the pencil icon (top right of this file on GitHub), replace `TODO` in the `HumanLabel` column with the correct category (`urgent`, `non-urgent-needs-reply`, `fyi`, or `noise`), then click "Commit changes."

**How accuracy is computed:** each run compares `AICategorization` to `HumanLabel` for all rows where `HumanLabel` is not `TODO`, and reports `correct / labeled` as a percentage. Rows still marked `TODO` are excluded from the accuracy calculation until labeled.

---

## 2026-07-07

| MessageId | Subject | Sender | AICategorization | HumanLabel |
|---|---|---|---|---|
| AAMkADQ5MzgzY2JiLTViZmUtNGFhZC1hNmQwLTMyM2M0YjQ1NjYxMQBGAAAAAAAsC3eVn--5QbycwVQtv2WSBwDSHF-C4pfgQ5l01fnR_8f4AAAAAAEMAADSHF-C4pfgQ5l01fnR_8f4AAAFrxC_AAA= | [EXTERNAL] Scam of the Week: No Call? Good Call | ScamoftheWeek@KnowBe4.com | noise | TODO |
| AAMkADQ5MzgzY2JiLTViZmUtNGFhZC1hNmQwLTMyM2M0YjQ1NjYxMQBGAAAAAAAsC3eVn--5QbycwVQtv2WSBwDSHF-C4pfgQ5l01fnR_8f4AAAAAAEMAADSHF-C4pfgQ5l01fnR_8f4AAAFrxC9AAA= | [EXTERNAL] What comes with a paid key | welcome@openrouter.ai | noise | TODO |
| AAMkADQ5MzgzY2JiLTViZmUtNGFhZC1hNmQwLTMyM2M0YjQ1NjYxMQBGAAAAAAAsC3eVn--5QbycwVQtv2WSBwDSHF-C4pfgQ5l01fnR_8f4AAAAAAEMAADSHF-C4pfgQ5l01fnR_8f4AAAFrxC8AAA= | [EXTERNAL] Ready to code? Your first repository awaits | no-reply@github.com | noise | TODO |
| AAMkADQ5MzgzY2JiLTViZmUtNGFhZC1hNmQwLTMyM2M0YjQ1NjYxMQBGAAAAAAAsC3eVn--5QbycwVQtv2WSBwDSHF-C4pfgQ5l01fnR_8f4AAAAAAEMAADSHF-C4pfgQ5l01fnR_8f4AAAFrxC5AAA= | [EXTERNAL] Colibri on Slack: New Account Details | no-reply-CleUtdXJmWHMAaq8PcPWnZMY@slack.com | noise | TODO |
| AAMkADQ5MzgzY2JiLTViZmUtNGFhZC1hNmQwLTMyM2M0YjQ1NjYxMQBGAAAAAAAsC3eVn--5QbycwVQtv2WSBwDSHF-C4pfgQ5l01fnR_8f4AAAAAAEMAADSHF-C4pfgQ5l01fnR_8f4AAAFrxC6AAA= | [EXTERNAL] Slack confirmation code: WFS-D8Q | no-reply-93IBsrXhR4FYfiIhWGy3NWn1@slack.com | noise | TODO |
| AAMkADQ5MzgzY2JiLTViZmUtNGFhZC1hNmQwLTMyM2M0YjQ1NjYxMQBGAAAAAAAsC3eVn--5QbycwVQtv2WSBwDSHF-C4pfgQ5l01fnR_8f4AAAAAAEMAADSHF-C4pfgQ5l01fnR_8f4AAAFrxC1AAA= | [EXTERNAL] Slack confirmation code: V8E-VJ6 | no-reply-AzPp863Vggmj75fkzyWrzawj@slack.com | noise | TODO |
| AAMkADQ5MzgzY2JiLTViZmUtNGFhZC1hNmQwLTMyM2M0YjQ1NjYxMQBGAAAAAAAsC3eVn--5QbycwVQtv2WSBwDSHF-C4pfgQ5l01fnR_8f4AAAAAAEMAADSHF-C4pfgQ5l01fnR_8f4AAAFrxCvAAA= | [EXTERNAL] Secure link to log in to Claude.ai \| 2026-07-06 09:21:31 | no-reply-qLZCoYDwtTKqEK2EKjpaWA@mail.anthropic.com | noise | TODO |
| AAMkADQ5MzgzY2JiLTViZmUtNGFhZC1hNmQwLTMyM2M0YjQ1NjYxMQBGAAAAAAAsC3eVn--5QbycwVQtv2WSBwDSHF-C4pfgQ5l01fnR_8f4AAAAAAEMAADSHF-C4pfgQ5l01fnR_8f4AAAFrxCtAAA= | [EXTERNAL] Secure link to log in to Claude.ai \| 2026-07-06 09:22:29 | no-reply-o5hTUxG39DqwkPhO_nRlHA@mail.anthropic.com | noise | TODO |
| AAMkADQ5MzgzY2JiLTViZmUtNGFhZC1hNmQwLTMyM2M0YjQ1NjYxMQBGAAAAAAAsC3eVn--5QbycwVQtv2WSBwDSHF-C4pfgQ5l01fnR_8f4AAAAAAEMAADSHF-C4pfgQ5l01fnR_8f4AAAFrxCsAAA= | [EXTERNAL] Gaurinadhan, track time as you work | support@myintervals.com | noise | TODO |

## 2026-07-08

| MessageId | Subject | Sender | AICategorization | HumanLabel |
|---|---|---|---|---|
| AAMkADQ5MzgzY2JiLTViZmUtNGFhZC1hNmQwLTMyM2M0YjQ1NjYxMQBGAAAAAAAsC3eVn--5QbycwVQtv2WSBwDSHF-C4pfgQ5l01fnR_8f4AAAAAAEMAADSHF-C4pfgQ5l01fnR_8f4AAAFrxDKAAA= | Post #35: What Moves Us Forward – One Year In – Learn, Change, Grow | shgoli@colibrigroup.com | noise | TODO |
| AAMkADQ5MzgzY2JiLTViZmUtNGFhZC1hNmQwLTMyM2M0YjQ1NjYxMQBGAAAAAAAsC3eVn--5QbycwVQtv2WSBwDSHF-C4pfgQ5l01fnR_8f4AAAAAAEMAADSHF-C4pfgQ5l01fnR_8f4AAAFrxDJAAA= | Marketing Hackathon Showcase – Brown Bag Session – Four AI Prototypes, Real Revenue Impact | Kevin.OConnor@colibrigroup.com | fyi | TODO |
| AAMkADQ5MzgzY2JiLTViZmUtNGFhZC1hNmQwLTMyM2M0YjQ1NjYxMQBGAAAAAAAsC3eVn--5QbycwVQtv2WSBwDSHF-C4pfgQ5l01fnR_8f4AAAAAAEMAADSHF-C4pfgQ5l01fnR_8f4AAAFrxDIAAA= | [EXTERNAL] Gaurinadhan, collaborate with your team | support@myintervals.com | noise | TODO |
| AAMkADQ5MzgzY2JiLTViZmUtNGFhZC1hNmQwLTMyM2M0YjQ1NjYxMQBGAAAAAAAsC3eVn--5QbycwVQtv2WSBwDSHF-C4pfgQ5l01fnR_8f4AAAAAAEMAADSHF-C4pfgQ5l01fnR_8f4AAAFrxDHAAA= | [EXTERNAL] Three features that quietly save you money | welcome@openrouter.ai | noise | TODO |
| AAMkADQ5MzgzY2JiLTViZmUtNGFhZC1hNmQwLTMyM2M0YjQ1NjYxMQBGAAAAAAAsC3eVn--5QbycwVQtv2WSBwDSHF-C4pfgQ5l01fnR_8f4AAAAAAEMAADSHF-C4pfgQ5l01fnR_8f4AAAFrxDGAAA= | [EXTERNAL] How to start a conversation in Slack | no-reply@email.slackhq.com | noise | TODO |
| AAMkADQ5MzgzY2JiLTViZmUtNGFhZC1hNmQwLTMyM2M0YjQ1NjYxMQBGAAAAAAAsC3eVn--5QbycwVQtv2WSBwDSHF-C4pfgQ5l01fnR_8f4AAAAAAEMAADSHF-C4pfgQ5l01fnR_8f4AAAFrxDFAAA= | [EXTERNAL] Ready for your first win with Notion? | team@mail.notion.so | noise | TODO |
| AAMkADQ5MzgzY2JiLTViZmUtNGFhZC1hNmQwLTMyM2M0YjQ1NjYxMQBGAAAAAAAsC3eVn--5QbycwVQtv2WSBwDSHF-C4pfgQ5l01fnR_8f4AAAAAAEMAADSHF-C4pfgQ5l01fnR_8f4AAAFrxDCAAA= | [EXTERNAL] Re: [Colibri-Group-Core/intern-mcp-servers] Add nandhu-umeshnath weather MCP server (v2) (PR #3) | notifications@github.com | fyi | TODO |
| AAMkADQ5MzgzY2JiLTViZmUtNGFhZC1hNmQwLTMyM2M0YjQ1NjYxMQBGAAAAAAAsC3eVn--5QbycwVQtv2WSBwDSHF-C4pfgQ5l01fnR_8f4AAAAAAEMAADSHF-C4pfgQ5l01fnR_8f4AAAFrxDBAAA= | Colibri Culture & Inclusion – Q3 Update – Thrive Together | colibri-cic@colibrigroup.com | noise | TODO |
| AAMkADQ5MzgzY2JiLTViZmUtNGFhZC1hNmQwLTMyM2M0YjQ1NjYxMQBGAAAAAAAsC3eVn--5QbycwVQtv2WSBwDSHF-C4pfgQ5l01fnR_8f4AAAAAAEMAADSHF-C4pfgQ5l01fnR_8f4AAAFrxDAAAA= | MCP Walkthrough | Adithya.Krishna@colibrigroup.com | fyi | TODO |
| AAMkADQ5MzgzY2JiLTViZmUtNGFhZC1hNmQwLTMyM2M0YjQ1NjYxMQBGAAAAAAAsC3eVn--5QbycwVQtv2WSBwDSHF-C4pfgQ5l01fnR_8f4AAAAAAEMAADSHF-C4pfgQ5l01fnR_8f4AAAFrxC-AAA= | MCP Walkthrough | Adithya.Krishna@colibrigroup.com | noise | TODO |
| AAMkADQ5MzgzY2JiLTViZmUtNGFhZC1hNmQwLTMyM2M0YjQ1NjYxMQBGAAAAAAAsC3eVn--5QbycwVQtv2WSBwDSHF-C4pfgQ5l01fnR_8f4AAAAAAEMAADSHF-C4pfgQ5l01fnR_8f4AAAFrxC_AAA= | [EXTERNAL] Scam of the Week: No Call? Good Call | ScamoftheWeek@KnowBe4.com | noise | TODO |
| AAMkADQ5MzgzY2JiLTViZmUtNGFhZC1hNmQwLTMyM2M0YjQ1NjYxMQBGAAAAAAAsC3eVn--5QbycwVQtv2WSBwDSHF-C4pfgQ5l01fnR_8f4AAAAAAEMAADSHF-C4pfgQ5l01fnR_8f4AAAFrxC9AAA= | [EXTERNAL] What comes with a paid key | welcome@openrouter.ai | noise | TODO |
| AAMkADQ5MzgzY2JiLTViZmUtNGFhZC1hNmQwLTMyM2M0YjQ1NjYxMQBGAAAAAAAsC3eVn--5QbycwVQtv2WSBwDSHF-C4pfgQ5l01fnR_8f4AAAAAAEMAADSHF-C4pfgQ5l01fnR_8f4AAAFrxC4AAA= | [EXTERNAL] Ready to code? Your first repository awaits | no-reply@github.com | noise | TODO |
