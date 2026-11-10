# Automated site review: `www.peregrineadvisors.com`

25 pages of `https://www.peregrineadvisors.com`, read on 2026-11-10 by Suite Builder's crawler in a real browser, logged out, as a first-time visitor sees them. Nothing was sent, bought or signed in to. This review reads the public site as it is served. It also observes the site's own security guards, as a visitor's browser sees them. It sends nothing and attacks nothing.

## Links that need a look (2)

Each of these links answered an error or did not answer. A person is to look at every one, whatever the site means by it: nothing here is cleared by a rule. A link leaves this list only when the team lists it, with the status it answers, in the suite's expected-links block.

- `/health-informatics` answered 404; linked from /services; broken (SITE-02)
- `https://www.whitehouse.gov/briefing-room/statements-releases/2024/03/28/fact-sheet-vice-president-harris-announces-omb-policy-to-advance-governance-innovation-and-risk-management-in-federal-agencies-use-of-artificial-intelligence/` answered 404; linked from /blog/u6fz5u6th0zm9dlo8fkcqdejooxjst; broken (SITE-33)

**5 major, 5 minor.** Major: lets a visitor or a search engine down now. Minor: worth fixing. Info: said for the record; counts against nothing. Each finding lists every page the read saw it on.

## What this review checked

Of 40 checks, 37 ran on this crawl; 3 could not be confirmed.

<details>
<summary>The checks, by kind</summary>

Pages and links (11 of 11 ran)
- Pages that answer an error yet draw content
- Links that answer an error
- Links that redirect before they arrive
- Page titles that are shared or missing
- An address that cannot exist but answers as a page
- Chains of redirects
- Images that do not load
- Links that send visitors from https to http
- Links to other sites that lead nowhere
- Links that answer an error on purpose
- Links to other sites that did not answer the crawler

Markup, accessibility and search (13 of 13 ran)
- Links and buttons with nothing for a screen reader to say
- Form fields without a label
- Images with no address
- Placeholder text left on pages
- The viewport setting for phones
- Canonical links that point somewhere else
- Images without alt text
- The language each page declares
- The main heading of each page
- Links to a part of the page that is not there
- Descriptions for search results
- The year in the copyright notice
- Form fields whose only label is a placeholder

Loading and speed (4 of 7 ran)
- Scripts, style sheets and data requests that fail to load
- Errors thrown by the site's own scripts
- Pages slow to answer or to load
- Requests over plain http from an https page
- Requests to other sites' hosts that fail: not confirmed
- Pages that did not finish loading: not confirmed
- Other sites' scripts and style sheets that failed for the crawler: not confirmed

The site's own addresses, certificate and headers (9 of 9 ran)
- Addresses of the site that do not answer
- Response headers that browsers act on
- Server software and version announced in headers
- The certificate's end date, name and trust
- Whether the http address sends visitors to https
- The sitemap
- A contact for security reports (security.txt)
- One site answering at two names
- The certificate chain, as the crawler's machine sees it

Not confirmed: the crawl file records what such a check saw only when it saw something, so it cannot show whether the check ran and found nothing, or did not run.

</details>

## major SITE-02 1 broken link: the site links to an address that answers an error

**Why it matters.** A visitor who follows one of these links reaches an error instead of the page promised.

**Likely fix.** Point each link at a page that exists, or bring the page back \(or redirect its old address to where it went\).

<details open>
<summary>1 link</summary>

- `/health-informatics` answered 404; linked from /services

</details>

## major SITE-07 At least 19 links and buttons on 1 page have nothing for a screen reader to say

**Why it matters.** A blind visitor hears only "link" or "button", with no idea where it goes or what it does; accessibility law \(the ADA, the European Accessibility Act\) counts it, and so do automated accessibility audits.

**Likely fix.** Give each one words: visible text, an aria-label, or an alt on the image inside it \(an icon link to a cart: aria-label="Cart"\).

<details open>
<summary>5 links and buttons</summary>

- `/who` \`\<a `` href="https://www.analytica.net/">` ``
- `/who` \`\<a `` href="https://aminadconsulting.com">` ``
- `/who` \`\<a `` href="https://www.acquisconsulting.com">` ``
- `/who` \`\<a `` href="https://xtrategyllp.com">` ``
- `/who` \`\<a `` href="https://www.accenture.com/us-en/industries/afs-ind…` ``

</details>

## major SITE-33 1 link to another site leads nowhere: the page is gone

**Why it matters.** Sites move and close: a visitor who follows one of these links meets an error page, or nothing at all, on someone else's site, reached from this one.

**Likely fix.** Point each link at where the page lives now, or take it out. The suite's link report asks every one again on each run, and fails when one that answered stops.

<details open>
<summary>1 link</summary>

- `https://www.whitehouse.gov/briefing-room/statements-releases/2024/03/28/fact-sheet-vice-president-harris-announces-omb-policy-to-advance-governance-innovation-and-risk-management-in-federal-agencies-use-of-artificial-intelligence/` answered 404; linked from /blog/u6fz5u6th0zm9dlo8fkcqdejooxjst

</details>

## major SITE-21 The site's own scripts throw 1 error on 22 pages

**Why it matters.** An error nothing catches stops the script that threw it: whatever it was doing \(a form's checks, a cart, tracking\) is left undone. Visitors never report it; it is seen only in the browser's console.

**Likely fix.** Open the page with the browser's developer tools, read the console, and fix each error at the line it names.

<details open>
<summary>1 error</summary>

- `/` Cannot use import statement outside a module, on 22 pages: /, /contact, /accomplishments and 19 more

</details>

## major SITE-26 The site's certificate expires on 2026-12-08, in 28 days: then browsers warn every visitor away

**Why it matters.** A browser shows a full-page security warning in place of a site whose certificate has expired, is for another name, or is not trusted; most visitors leave, and search engines and payment providers treat the site as unsafe.

**Likely fix.** Renew the certificate before it ends, and have it renew itself \(Let's Encrypt, or the host's automatic certificates\); make sure it names every address the site answers on.

<details open>
<summary>1 detail</summary>

- `/` the certificate expires on 2026-12-08, in 28 days

</details>

## minor SITE-17 17 pages have no description for search results

**Why it matters.** Search results show the description under the title; without one, the search engine picks a line of the page, often the menu or a cookie notice.

**Likely fix.** Give each page a \<meta name="description"\> of a sentence or two saying what it offers.

<details>
<summary>17 pages</summary>

- `/` no meta description
- `/contact` no meta description
- `/accomplishments` no meta description
- `/cart` no meta description
- `/who` no meta description
- `/services` no meta description
- `/our-work` no meta description
- `/blog` no meta description
- `/blog/tag/BSA%2FAML` no meta description
- `/blog/tag/Anti-Money%20Laundering` no meta description
- `/blog/tag/AML` no meta description
- `/peregrines-8a` no meta description
- `/blog/tag/Data%20Lifecycle` no meta description
- `/blog/tag/Money%20Laundering` no meta description
- `/blog/tag/Lifecycle` no meta description
- `/blog/tag/Data%20Fundamentals` no meta description
- `/blog/tag/EDLC` no meta description

</details>

## minor SITE-15 8 pages have no main heading; 1 page has several main headings \(h1\)

**Why it matters.** Screen reader users jump to the h1 to learn what a page is, and search engines read it as the page's subject; none, or several competing, says neither.

**Likely fix.** Give each page one h1 naming what it shows; the site's name in the header is not it.

<details open>
<summary>9 pages</summary>

- `/` no h1 with words shown
- `/contact` no h1 with words shown
- `/accomplishments` no h1 with words shown
- `/cart` no h1 with words shown
- `/who` no h1 with words shown
- `/services` no h1 with words shown
- `/our-work` no h1 with words shown
- `/blog` 3 h1: \`THE FUTURE OF CRYPTOCURRENCY REGULATION: A STRATEGIC OVERVIEW\`, \`THE EVOLVING LANDSCAPE OF AI AND DATA REGULATION IN THE UNITED STATES: PAST, PRE\`, \`AN OVERVIEW OF MODERN MONEY LAUNDERING\`
- `/peregrines-8a` no h1 with words shown

</details>

## minor SITE-04 2 different pages share one title

**Why it matters.** Search results, bookmarks and browser tabs show the title: pages that share one can't be told apart, and a page without one shows its address.

**Likely fix.** Give each page a title of its own that names what it shows \(in a single-page app, set it on each route\).

<details open>
<summary>2 pages</summary>

- `/` titled \`Peregrine Advisors\`, shows \` \`
- `/cart` titled \`Peregrine Advisors\`, shows \`Shopping Cart\`

</details>

## minor SITE-24 1 security header no page sends

**Why it matters.** Each header closes a door attackers use \(a downgrade to http, a script slipped in, the site framed in another to trick a click\). Security reviews and compliance checklists ask for them, and they cost a line of server configuration.

**Likely fix.** Add the missing header in the web server or the CDN \(one setting each\).

<details open>
<summary>1 missing header</summary>

- `/` no page of the site sends Content-Security-Policy \(which scripts may run\)

</details>

## minor SITE-29 The site publishes no security.txt, the file that tells security researchers whom to contact

**Why it matters.** Researchers who find a security problem look for /.well-known/security.txt to know whom to tell \(RFC 9116\); without it they may not report it, or report it publicly.

**Likely fix.** Publish /.well-known/security.txt with a Contact line \(an email address or a form\) and an Expires line.

<details open>
<summary>1 address</summary>

- `/.well-known/security.txt` answered 404

</details>

Read by Suite Builder's crawler, which identifies itself in its User-Agent and obeys robots.txt.
