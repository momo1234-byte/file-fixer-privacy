File Fixer — Privacy Policy (Beta)

Last updated: August 13, 2026
Status: Beta release

What File Fixer does

File Fixer is a Chrome extension that helps you prepare images (JPEG, PNG, WebP) for upload to a website. It looks at the upload field you're using, works out what that website expects — file format, maximum file size, and, where the website states it, pixel dimensions — and lets you fix a selected or pasted image to match before you upload it. Everything File Fixer does happens locally, inside your own browser.

Local image processing

Every image File Fixer processes — converting its format, compressing it, resizing it — is handled entirely inside your browser, using your browser's own built-in image-drawing tools (the HTML canvas). File Fixer has no server of any kind. Your original image and the repaired result never leave your device as part of this processing. There is no cloud image-processing service, no remote API call, and no upload of your image data anywhere, at any point.

Clipboard access

File Fixer can read an image from your clipboard, but only when you click the "Paste image" button yourself. The clipboard is never read automatically, on a timer, in the background, or simply because the popup is open — only in direct response to that one click. File Fixer does not keep a history of previous clipboard contents, and a pasted image is processed the same way as any other selected file: locally, and never transmitted anywhere.

Website requirement detection

To work out what a website expects, File Fixer looks at the specific upload field you're using (or that it finds on the page) and reads a small, bounded amount of information near it: the field's own accepted-format attribute, its associated label text, and the text of the small area of the page immediately around it — enough to recognize phrasing like "Maximum file size: 5 MB." It also watches for new text appearing on the page after you select a file, so it can recognize a small set of known upload-rejection messages (for example, "file too large" or "invalid format") if the website shows one.

File Fixer does not read or collect the content of the whole page. It only looks at file-upload fields and text near them — never other form fields, passwords, or unrelated page content — and it uses this information immediately, in memory, to work out upload requirements. It is never transmitted anywhere and never stored permanently.

Storage behavior

File Fixer stores a small amount of data locally in your browser, using Chrome's own built-in extension storage:





Two preferences you control — "Automatically repair files selected on websites" (Auto Fix) and "Keep original dimensions" — persist across browser restarts until you change them.



Temporary per-tab session details — while you're using the popup on a given page, File Fixer remembers which upload field you selected and basic details about your current or fixed file (its name, type, size, and dimensions), so reopening the popup shows where you left off. This clears automatically when your browser session ends, or immediately if you click "Clear session."

File Fixer never stores the actual bytes of your selected image or your repaired image. Only small pieces of text/number metadata — like a filename or a size — are ever kept, and only temporarily. There is no separate file-byte database of any kind.

Network / data transmission

File Fixer makes no network requests of any kind. It has no server component, calls no external APIs, and uploads nothing. Nothing File Fixer does ever leaves your browser.

Analytics / telemetry

File Fixer contains no analytics, telemetry, or usage-tracking code of any kind. Nothing about how you use the extension is measured, recorded, or reported — to the developer or to anyone else.

Third-party sharing

Because File Fixer collects nothing and transmits nothing, there is no user data to share with, or sell to, any third party. File Fixer has no backend, no user accounts, and no business relationship with any third party that would involve your data.

Data retention





Preferences (Auto Fix, Keep original dimensions): kept until you change them or uninstall the extension.



Session metadata (selected upload target, current file's name/type/size/dimensions): kept only for your current browser session and only for the specific browser tab and page it applies to; cleared automatically when the browser session ends, or manually via "Clear session."



Image bytes: never retained at all, at any point, by File Fixer.



User control / Clear session

You can turn Auto Fix on or off at any time from the popup — it is off by default. A "Clear session" action in the popup immediately removes the temporary details File Fixer has remembered for the current tab. Uninstalling the extension removes all locally stored preferences and data along with it.

Changes to this policy

This is a beta-stage policy and may be updated as File Fixer's functionality changes during and after the beta period. Material changes will be reflected here, with an updated "Last updated" date above.

Contact

Questions about this policy or File Fixer's data practices can be sent to: filefixer.help@outlook.com
