# VASTORA website + Lead Machine preview

This is a static prototype inspired by the video you shared about an AI website that helps book clients. It includes a premium public website and a separate concept dashboard called **Vastora OS — Lead Machine**.

## Run it locally
1. Extract the ZIP.
2. Open `index.html` in a modern browser.
3. Use the consultation form to create a sample enquiry.
4. Open `lead-machine.html` to see that sample enquiry appear in the preview dashboard.

For the best local experience, use VS Code with the free Live Server extension, or run `python -m http.server 8000` from this folder and open `http://localhost:8000`.

## Publish on GitHub Pages
Upload these files to the root of a GitHub repository and enable **Settings → Pages → Deploy from a branch → main → /(root)**. Both `index.html` and `lead-machine.html` are public static pages once published.

## What's included
- Premium dark/stone/gold responsive Vastora landing page.
- Kitchen, bathroom, wardrobe, living/furniture and lighting studios.
- Services, project process and consultation form.
- Demo lead storage in browser `localStorage`.
- Separate Lead Machine dashboard concept with lead pipeline, AI-agent ideas and automation blueprint.
- Responsive styling and reduced-motion support.

## Important limitations
**This is a visual/functional frontend prototype, not a production AI automation system.**
- Enquiries are stored only in the browser that submitted them. They are not sent to Vastora.
- Dashboard data is not shared between devices/users and is not private.
- The agent cards and automation rules are examples; they do not run AI or send messages.
- No real login, role permissions, database, file storage, calendar, WhatsApp/SMS, email, payment, CRM, Google review or social publishing is connected.
- Do not collect real customer data or publish confidential information through this preview.
- To make it live, build a secure backend (e.g. Supabase), server-side API integrations, staff authentication and permissions, consent rules, logging, and human approval for quotes/content. Never place private API keys in frontend JavaScript.

## Suggested production implementation sequence
1. Secure enquiry database and staff authentication.
2. Lead assignment, notification and CRM pipeline.
3. Calendar booking + confirmations/reminders.
4. Photo upload + AI-assisted scope drafting (human reviewed).
5. Approved catalogue-based quotation drafts.
6. Follow-up task scheduler and consent-based post-handover review requests.
7. Content/SEO drafting, with human approval before publication.
8. Analytics and reporting.

Images are loaded from Unsplash and fonts from Google Fonts, so an internet connection is needed for those assets. Replace placeholder imagery and brand assets with approved Vastora content before launch.
