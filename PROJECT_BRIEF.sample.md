# Project Brief — Photographer Portfolio & Client Gallery Platform
Fill in what you know; leave unknowns blank.

*Filled as a worked example from the founder's prompt. 
Items marked "(inferred)" are recommendations to confirm with the founder; all other content is drawn from the prompt.*

## Idea
- **Working name:** "GalleryFlow"
- **Explain the idea in your own words:** 
	A SaaS platform where photographers deliver photos to clients through branded galleries and showcase their portfolio, with a built-in loop that brings new leads. 
        It replaces the plain Google Drive link most photographers use today.
- **Inspiration and desired outcome:** 
	Photographers currently send unbranded Google Drive/Dropbox links. 
	The desired outcome is a professional, branded client-delivery experience that doubles as a portfolio and lead-generation channel.

## Problem and customers
- **Problem you believe exists:** 
	Photographers deliver work via plain, unbranded cloud links with no client experience and no way to capture leads from people viewing the photos.
- **Who experiences it?** 
	Professional photographers (wedding, portrait, event, commercial, family) who deliver photo galleries to clients.
- **Current workaround:** 
	Google Drive / Whatsapp / Dropbox / WeTransfer links, sometimes with a separate portfolio site.
- **Geography/market:** 
	Online - India, Germany.
- **Who might pay? 
	Photographers via subscription (SaaS pricing tiers)

## Product hypothesis
- **Proposed solution:** 
	A Next.js + TypeScript application.
	Has authenticated photographer accounts, branded client galleries, a public portfolio, private originals with controlled previews in object storage, and favourites/inquiries for lead capture.
- **Main value:** 
	Professional branded photo delivery + portfolio showcase + built-in lead loop, replacing unbranded file links.
- **Potential differentiation:** 
	Combines client delivery, portfolio, and lead generation in one minimal platform (most tools do only one or two of these).
- **Example user scenario:** 
	A wedding photographer uploads a gallery, shares a branded link with the couple; the couple views previews, marks favourites, and submits an inquiry via WhatsApp/booking CTA — turning a delivered gallery into a new lead.

## Business hypothesis
- **Possible business model/revenue:** 
	SaaS subscription (freemium + paid tiers by storage/galleries/clients).
- **Known competitors/alternatives:** 
	Pixieset, ShootProof, Pic-Time, SmugMug; Google Drive, Dropbox, WeTransfer (workarounds).
- **Pricing thoughts:** 
	Not specified.
- **Existing customer access or validation:** 
	Not specified.

## Constraints and preferences
- **Budget/timeline:** 			Not specified.
- **Skills or technologies you know/prefer:** Next.js + TypeScript (explicit in Phase 1, task 1).
- **Hosting/provider preferences:** 	Not specified (inferred: Vercel/cloud platform suited to Next.js).
- **Integrations:** 			Object storage (private originals + previews), WhatsApp (contact/booking CTA).
- **Legal/privacy/industry constraints:** 	Privacy page, terms page, copyright/takedown page required (explicit, Phase 1 task 8).
- **Things you do not want:** 		Unbranded/plain file-link delivery (the Google Drive experience).

## Configuration (can decide with agent)
- **Depth:** 			Lean (inferred: Phase 1 is an MVP foundation; start Lean, move to Comprehensive if needed)
- **Project type(s):** 		SaaS and subscription products
- **Agent:** 			Mixed — OpenCode / Claude Code / Other
- **Technology decision approach:** [To be decided — compare options with founder before approving]
- **Research expectations:** 	[To be decided — market/competitor research before build]

## Open thoughts
- **Features :** 
	Auth & protected dashboard; 
	data model (users, photographer_profiles, galleries, photos, favourites, inquiries); 
	sign-up/sign-in/sign-out/session handling; 
	profile setup (display name, logo/avatar, WhatsApp, booking CTA); 
	private originals + controlled preview images in object storage; 
	environment config + error logging; 
	privacy/terms/copyright-takedown pages.
- **Risks/concerns :** 
	(inferred)object-storage costs, image security/leakage of originals, auth/session security, copyright handling.
- **Other context:** 
	Design direction is simplicity and minimalism (photos first, minimal chrome, neutral palette with a single accent).

## Founder decisions
Leave for decisions made during discovery. Agent must not pre-fill decisions.
