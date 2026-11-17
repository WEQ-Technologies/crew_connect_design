# CrewConnect — Interactive journeys (reviewer controls Flows A–E, presets, roles) — design reference

This is a design mockup created in a visual design tool, exported as a
standalone page. Treat it as a REFERENCE MOCKUP, not production code:
the markup and inline styles carry the design's precise values — colors,
font sizes, spacing, radii, shadows, layout — which an implementation
should replicate faithfully in its own components and styling system
rather than copy wholesale.

## Contents

- `Journeys.dc.html` — the artboard (a Design Component: an `<x-dc>`
  template + a small logic class). The values to replicate live in its
  inline `style="…"` attributes and the `<helmet><style>` block.
- `Prototype.dc.html` — referenced resource
- `cc.css` — referenced resource
- `AddMode.dc.html` — referenced resource
- `AddRole.dc.html` — referenced resource
- `ApplicantDetail.dc.html` — referenced resource
- `Applicants.dc.html` — referenced resource
- `AssocLogin.dc.html` — referenced resource
- `AssocNotices.dc.html` — referenced resource
- `AssociationProfile.dc.html` — referenced resource
- `Associations.dc.html` — referenced resource
- `Calendar.dc.html` — referenced resource
- `CompleteProfile.dc.html` — referenced resource
- `Connections.dc.html` — referenced resource
- `CreateJob.dc.html` — referenced resource
- `Discover.dc.html` — referenced resource
- `DiscoverFeed.dc.html` — referenced resource
- `FollowList.dc.html` — referenced resource
- `FollowingFeed.dc.html` — referenced resource
- `ForumWall.dc.html` — referenced resource
- `InvoiceCreate.dc.html` — referenced resource
- `InvoiceDetail.dc.html` — referenced resource
- `Invoices.dc.html` — referenced resource
- `JobDetail.dc.html` — referenced resource
- `JobDigest.dc.html` — referenced resource
- `JobSearch.dc.html` — referenced resource
- `Jobs.dc.html` — referenced resource
- `ListingForm.dc.html` — referenced resource
- `LogIn.dc.html` — referenced resource
- `ModeChoice.dc.html` — referenced resource
- `MyApplications.dc.html` — referenced resource
- `MyJobs.dc.html` — referenced resource
- `MyListings.dc.html` — referenced resource
- `NoticeDetail.dc.html` — referenced resource
- `NoticeForm.dc.html` — referenced resource
- `Notifications.dc.html` — referenced resource
- `Onboarding.dc.html` — referenced resource
- `Otp.dc.html` — referenced resource
- `PosterHome.dc.html` — referenced resource
- `PosterJobDetail.dc.html` — referenced resource
- `PosterProfile.dc.html` — referenced resource
- `RoleChoice.dc.html` — referenced resource
- `RoleNav.dc.html` — referenced resource
- `SeekerHome.dc.html` — referenced resource
- `SeekerProfile.dc.html` — referenced resource
- `SetupBasic.dc.html` — referenced resource
- `SetupDone.dc.html` — referenced resource
- `SetupPoster.dc.html` — referenced resource
- `SignUp.dc.html` — referenced resource
- `Splash.dc.html` — referenced resource
- `Subscription.dc.html` — referenced resource
- `Talent.dc.html` — referenced resource
- `UserProfile.dc.html` — referenced resource
- `VendorPublic.dc.html` — referenced resource
- `Welcome.dc.html` — referenced resource
- `assets/` — files uploaded to the design (images, fonts, media)
- `support.js`, `vendor/react*.js` — the runtime that renders the
  component in a browser; not part of the design.

## Uploaded files

Images, fonts and media uploaded to the design are written once each under
`assets/` — 1 in this export — and the exported files refer to them there. A
reference a script puts together while the page runs (for example
`"/_blob/" + id`) is not rewritten and does not load from this folder.

## Viewing

Serve the folder (e.g. `python3 -m http.server`) and open `Journeys.dc.html`;
some browsers block the scripts over file://.
