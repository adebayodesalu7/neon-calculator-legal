# Privacy Policy — Neon Calculator

**Last updated: 6 October 2026**

Neon Calculator ("the app") is a calculator, unit converter and currency
converter. This policy explains what the app does — and does not — do with your
information. It is written to be short because the app genuinely collects
almost nothing.

## Summary

- We do **not** require an account, sign-in, email address or phone number.
- We do **not** collect, transmit or sell personal data.
- We do **not** use advertising, analytics or crash-reporting SDKs.
- We do **not** request access to your contacts, photos, files, location,
  microphone, camera or any other sensitive permission.
- Your calculations, history and settings stay **on your device**.

## Information stored on your device

The app keeps the following locally, in memory or in app-private storage, and
never uploads it:

- the expression you are currently typing;
- your in-session calculation history;
- your selected colour theme and sound preference.

Uninstalling the app, or clearing its data from Android Settings, removes all of
it.

## Network requests

The app has exactly one reason to use the internet: **fetching currency
exchange rates** when you open the Currency converter or tap refresh.

- Requests go to a third-party rate provider over **HTTPS**.
- The request contains only a fixed base-currency code (for example `USD`).
  It contains **no device identifier, account, location or calculation data**.
- As with any internet request, the provider can see the IP address your device
  uses to connect. We do not receive, log or store that address. Please refer to
  the provider's own privacy policy for how they handle request logs.
- If the device is offline, or the provider cannot be reached, the app falls
  back to exchange rates built into the app. **No data is queued or retried in
  the background.**

The app contains **no** advertising, tracking pixels, fingerprinting, or
third-party analytics.

## Permissions

The app declares a single Android permission:

| Permission | Why |
|---|---|
| `android.permission.INTERNET` | To download the exchange rates described above. |

It requests no other permission.

## Children

The app is a general-purpose utility suitable for all ages. It does not collect
personal information from anyone, including children under 13.

## Financial disclaimer

Currency conversion is provided **for informational and educational purposes
only**. Rates are indicative, may be delayed or inaccurate, and are **not
financial, investment, tax or accounting advice**. Do not rely on the app for
transactions, trading or any decision with financial consequences. Always
confirm rates with your bank or payment provider.

## Accuracy of calculations

The calculator uses a standard expression engine evaluated on your device.
Results are provided on a best-effort basis; verify important results
independently.

## Your rights

Because the app does not collect personal data, there is nothing for us to
export, correct or delete. If you are in the EEA, UK, California or another
region with data-protection legislation, note that no processing of personal
data takes place, so no data-subject request applies. Uninstalling the app
removes all locally stored data.

## Changes to this policy

If a future version adds a feature that changes any of the above (for example
advertising, analytics or cloud sync), this document will be updated and the
"Last updated" date revised **before** that version is published.

## Contact

Questions about this policy: **<your-support-email@example.com>**

---

### Hosting this policy

Google Play requires a publicly reachable URL (not a PDF, not a file download).
The cheapest option is GitHub Pages:

1. Create a public repository, e.g. `neon-calculator-legal`.
2. Add this file as `index.md` (or `privacy.md`).
3. Enable **Settings → Pages → Deploy from branch → main /root**.
4. Use `https://<username>.github.io/neon-calculator-legal/` as the Play Console
   privacy-policy URL.

Replace the contact address above with a real, monitored mailbox before
publishing.
