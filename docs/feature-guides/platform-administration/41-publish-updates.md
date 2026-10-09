# 41. Publish platform updates — administrators

**Audience:** authorized SPAWN platform administrators. This is not a self-service news submission tool for every project owner.

**Open:** the SPAWN admin area → **News & announcements**. You need the appropriate platform admin account. This guide explains the workflow; it does not grant access or publish anything automatically.

## Create and review a draft

1. Choose **New update**.
2. Enter the **Title**, **Short summary** and **Category**.
3. Choose the appropriate **SPAWN artwork** so the article follows the existing site branding.
4. Write the **Article** in Markdown: explain what changed, who it affects and the actions readers can take.
5. Include accurate official links, limits and any time-bounded offer terms. Avoid announcing an unshipped feature as available.
6. Use **Show article preview** to inspect headings, links and readability.
7. Choose **Save draft** before publishing a new record.

Use the provided artwork selector for the article image. The current reader does not render inline Markdown images in the body, so do not rely on an embedded image there to communicate essential instructions.

## Publish and optionally notify Telegram

1. Reopen the saved draft and make the final review.
2. Decide whether it should notify the official Telegram community. The notification option is separate and defaults off.
3. Use **Publish to site**, or the offered **Publish & notify Telegram** action when notification is selected.
4. Open the public article URL and confirm its title, summary, image and body.
5. If a notice was requested, inspect its delivery status and the intended official destination.

This notice is a platform announcement, not a token Buy Bot alert. Do not assume it posts into every project group.

## Edit or withdraw

Use **Save changes** for edits to an existing article. Editing an already announced article does not automatically resend its Telegram notice. Use **Unpublish** when an article should no longer be publicly available; this does not automatically remove a message already delivered to Telegram.

## Notification troubleshooting

| Status/problem                     | Correct action                                                                                            |
| ---------------------------------- | --------------------------------------------------------------------------------------------------------- |
| Published without notice           | Use **Send Telegram notice** if it is still appropriate and the control is available.                     |
| Explicit Telegram rejection        | Correct the reported cause and use **Retry Telegram notice** when offered.                                |
| Delivery outcome uncertain         | Check the destination first. Do not blindly resend, because the original may already have arrived.        |
| Draft absent from public site      | Expected: drafts are private until publication.                                                           |
| Published article not found        | Confirm its published state and exact public slug; refresh the list.                                      |
| Notice differs from edited article | Existing Telegram messages do not automatically become newly sent announcements when the article changes. |

**Success:** the article is publicly readable and any requested notice has a checked delivery outcome. Keep the public [reader guide](../platform-information/33-news-updates.md) distinct from these administrator steps.

***

[Guide home](../README.md) · [Troubleshooting](../reference-and-support/38-troubleshooting.md) · [Get help](../reference-and-support/39-support-and-safety.md)
