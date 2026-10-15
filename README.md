# late-payment-radar

Know who will pay you late before it hurts your cash flow.

## What it does
- Scores each customer's payment risk from their past invoices
- Shows how much money is overdue or likely to arrive late
- Writes a polite or firm reminder email, based on how late the payment is

## How to use
1. Open the live site: [https://forgemediacontact.github.io/late-payment-radar/]
2. Add your invoices, or click "Load sample data"
3. Check the risk and cash-at-risk numbers
4. Pick a customer and copy the reminder email

## Privacy
- **No server, no account.** Late Payment Radar runs entirely in your browser. I don't run a database, and I never see your data.
- **Invoice data stays on your device.** Customer names, amounts, dates and emails are saved only in your browser's local storage. Clearing your browser data, or clicking "Clear all", removes them.
- **Imports are read locally.** Excel, CSV and pasted data are processed in your browser and not uploaded anywhere.
- **Emails go through EmailJS.** When you click Send, only the reminder text and the customer's email address are passed to EmailJS (emailjs.com), which delivers the message through your own Gmail or Outlook account. EmailJS's privacy policy applies to that step.
- **Your EmailJS keys are stored in your browser.** The Public Key, Service ID and Template ID are saved locally and are not shared with me.
- **No tracking.** There are no analytics, cookies or ads.
- **Third-party libraries.** The page loads two open-source libraries (SheetJS and the EmailJS SDK) from public CDNs, which may log your IP address as normal web servers do.

Don't enter data you aren't allowed to share, and only email customers who expect to hear from you.


## Who it's for
Freelancers, shops, traders and small businesses in any country.

## Status
Early version. Feedback and ideas are welcome: please open an issue.
