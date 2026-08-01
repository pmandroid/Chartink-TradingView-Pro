# Privacy Policy — Chartink TradingView Pro

*Effective / Last updated: **August 1, 2026***

This Privacy Policy explains what data the **Chartink TradingView Pro** Chrome
extension ("the Extension", "we", "us") accesses, how it is used, and what
happens (and doesn't happen) to it. In short: the Extension does not collect,
store, or transmit any personal data to us or to any third party.

## 1. Summary

- We do **not** collect, sell, rent, or share any personal information.
- We do **not** run analytics, tracking pixels, or advertising scripts.
- We do **not** operate any backend server that the Extension talks to.
- All settings you configure are stored **locally on your device** (via
  Chrome's built-in `storage` API) and never leave it, except through
  Chrome's own optional account sync, which is controlled by you and Google,
  not by us.
- The Extension only runs on `chartink.com` pages.

## 2. What the Extension does

The Extension reads stock symbols that are already visible on the Chartink
page you are viewing (screener results, watchlists, related-stocks tables)
and adds a small options menu next to each one. Selecting an option opens
the corresponding page — TradingView's chart, TradingView's symbol stats
page, or Screener.in's company page — for that stock, in a new browser tab.

That's the entirety of its function. It does not read, log, or transmit
anything else from the page, and it does not run on any website other than
chartink.com.

## 3. Information we access, and why

| Data | Purpose | Where it's stored |
|---|---|---|
| Stock symbols visible on the current Chartink page | To attach the options menu to the correct row/cell | Held only in memory, in your browser tab, while the page is open. Never saved or transmitted anywhere. |
| Your extension settings (enabled/disabled state, exchange choice — NSE/BSE/Custom, "Open Top X" count, debug-logging toggle) | To remember your preferences between sessions | Locally, via Chrome's `chrome.storage.sync` API. May sync across your own signed-in Chrome browsers through your Google Account — handled entirely by Google, per your own Chrome sync settings, not by us. |

We do not collect names, email addresses, financial account information,
browsing history outside chartink.com, IP addresses, or any other
personally identifiable information.

## 4. Permissions the Extension requests

| Permission | Why it's needed |
|---|---|
| `storage` | Save your settings locally (see Section 3). |
| `contextMenus` | Add the right-click options ("Open in TradingView", "Copy Symbol", "Copy TradingView Symbol") on Chartink pages. |
| `host_permissions` — `https://chartink.com/*` | Required so the Extension can detect stock symbols and add the options menu on Chartink's own pages. No other website is accessed or read. |

## 5. Third-party websites

Clicking a menu option opens a third-party website — TradingView
(`tradingview.com` / `in.tradingview.com`) or Screener.in (`screener.in`) —
in a new browser tab. Once you're on those sites, your interaction is
governed by **their** respective privacy policies and terms, not this one.
We have no access to, and receive no information from, those sites.

The Extension is an independent, unofficial tool and is not affiliated
with, endorsed by, or sponsored by Chartink, TradingView, or Screener.in.

## 6. Data sharing and sale

We do not sell, rent, trade, or otherwise share any data with third
parties, advertisers, or data brokers, because we do not collect any data
to begin with.

## 7. Data retention and deletion

Your settings remain on your device for as long as the Extension is
installed. Uninstalling the Extension removes its locally stored settings
from your browser. Because nothing is transmitted to us, there is no
server-side copy of your data for us to retain or delete.

## 8. Children's privacy

The Extension is not directed at children under 13 (or the relevant age of
consent in your jurisdiction) and does not knowingly collect information
from children, as it does not collect personal information from anyone.

## 9. Security

Because the Extension does not transmit data to any server we control,
there is no remote database or account of yours that could be exposed in a
breach on our end. Standard Chrome extension sandboxing and Chrome's own
security model apply to locally stored settings.

## 10. Changes to this policy

If this policy changes, we will update the "Last updated" date at the top
of this page and, where required, note the change in the Extension's
Chrome Web Store listing. Continued use of the Extension after changes
take effect constitutes acceptance of the revised policy.

## 11. Contact

Questions about this policy or the Extension's data practices can be sent to:

- Email: **prashant.cse2007@gmail.com**
- Support / issues: **https://github.com/your-username/chartink-tradingview-pro/issues**

---

> **Before publishing:** replace the placeholder email and support URL
> above with your real contact details, and update the developer/company
> name if you want one listed. This document is a starting point and isn't
> a substitute for legal advice — if you plan to target users in
> jurisdictions with specific requirements (e.g. GDPR in the EU/UK, CCPA in
> California), consider having it reviewed by a lawyer.
