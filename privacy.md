---
layout: default
title: Privacy Notice — Matrix Mail Organizer
---
# Privacy notice

Prepared November 8, 2026. This notice describes the Matrix Mail Organizer server application, identified on Google’s consent screen as **gws-cli — Matrix Mail Organizer**. It does not describe separate email assistants or other software connected to the same accounts.

## Operator and purpose

Ken Schlenker operates this private tool to organize his authorized mailboxes. It is not a public email service. Questions and deletion requests may be sent to [kschlenker@marshinstitute.org](mailto:kschlenker@marshinstitute.org).

## Information accessed

With the account owner’s Google authorization, the organizer accesses the account’s email address, message identifiers, sender headers, labels, and category search results. It uses this information to move the selected categories out of the inbox and apply Marketing/Review and sender-specific labels.

The organizer requests Gmail modification permission. That permission is broader than label-only access; the implemented organizer limits its requests to profile identification, message metadata, category searches, and label operations. It does not request message bodies or attachments, send email, or permanently delete messages.

## Storage and retention

Google continues to store the email messages. The private server stores encrypted authorization credentials, message-ID checkpoints, label identifiers, and operational status information. Credentials are briefly decrypted in a restricted server runtime when required to contact Google. Backups may contain configuration, credentials, and operational state.

Checkpoints are updated during successful runs and pruned against messages currently in Marketing/Review. Credentials, configuration, status records, and backups remain until removed or expired under the operator’s retention settings. Revoking Google access stops future access but does not itself erase server records or labels already applied in Gmail.

The operator can stop the service, remove its stored credentials and state, and allow existing backup copies to expire. Email deletion is separate and remains under the account owner’s control.

## Use and disclosure

The organizer uses Google user data solely for the filing functionality described here. It does not sell Google user data, use it for advertising, or use it to train generalized AI or machine-learning models. The server organizer does not send email content to an AI provider.

The application communicates with Google to perform authorized operations. Access to its private server and backups is limited to the operator and authorized administration. Google user data is not published on this informational website.

Matrix Mail Organizer’s use and transfer of information received from Google APIs will adhere to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including its Limited Use requirements.

## Public website

The informational pages are intended for GitHub Pages hosting. They contain no application-provided analytics, advertising scripts, mailbox forms, or OAuth callback handler. GitHub may process ordinary website request information under its own [privacy statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).

## Your choices

Revoke the app in [Google Account connections](https://myaccount.google.com/connections), contact the operator to stop processing or remove server data, and manage labels and messages directly in Gmail. Revocation may require authorization again before the service can resume.

Material changes to the organizer’s data handling should be reflected in this notice before that changed processing begins.

[Return to the app homepage](index.html) · [Terms of use](terms.html)
