# Open in Outlook

One static page. A link to it carries the id of a mail and the mailbox after the `#`:

    https://<host>/outlook-open/#m=<mail id>&a=<mailbox address>

The page hands over to the Outlook app (`ms-outlook://emails/message/<mail id>?account=<mailbox address>`) and offers Outlook on the web as the other way. On a Mac it goes to Outlook on the web at once: Outlook for Mac reads a different link grammar and cannot find the mail from this one. It exists because chat apps accept only web links.

What follows the `#` is never sent to the server. The page opens nothing but a mail in Outlook.
