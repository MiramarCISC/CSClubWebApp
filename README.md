# SDCS Club website

A dependency-free, responsive website for the Computer Science Club at San Diego Miramar College. Open `index.html` locally to preview it.

## Update club information

Edit `index.html` directly. Meetings are listed as the second and fourth Friday of each month, 12:30–1:30 p.m. in room M-102. Update the `#meetings` section if the schedule changes. The club purpose, activities, officer names, advisor, and membership summary come from the supplied certification packet. Confirm officer changes before publishing; update names in `#people` when roles change. The Join section links to the club Discord at `https://discord.sdcs.club/` and Instagram at `https://www.instagram.com/sdcs.club/`, and gives the advisor’s Discord tag as `@ahuang`. The club purpose appears once in the About section; the hero leads with a headline and meeting details. Add confirmed project links as needed. The private membership roster and personal addresses, phone numbers, student IDs, and signatures are intentionally excluded.

The design uses the club slide screenshot as its visual reference. The SDCS logo was translated into the self-contained vector asset `assets/logo.svg`. Styling is in `assets/styles.css`, and the matching favicon is in `assets/favicon.svg`. The `CNAME` file sets the GitHub Pages custom domain to `sdcs.club`; remove or change it if the domain is not ready.

## Publish with GitHub Pages

1. Create a public GitHub repository for the club and upload these files to its root (including `.nojekyll` and `CNAME`).
2. In **Settings → Pages → Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
3. In **Settings → Pages**, confirm the custom domain `sdcs.club`. Configure the domain's DNS to point to GitHub Pages, then enable **Enforce HTTPS** after GitHub provisions a certificate. Follow GitHub's current custom domain documentation for the DNS records and verification steps.
4. If `www.sdcs.club` should also work, configure its DNS as GitHub Pages documents. Verify the domain in the GitHub organization's Pages settings to prevent domain takeover.

No Node, package install, build command, or workflow file is needed. Pull requests can review changes before merging to `main`.
