# 33 — Actionable Pathways: FOIA Strategy, Journalist Contacts, Published Documents
**Date**: April 22, 2026  
**Research Round**: 6  
**Focus**: Concrete next steps for breaking through the AT&T/NSA personnel wall

---

## EXECUTIVE SUMMARY

Three parallel research threads converged on concrete actionable pathways. One major documentary find: the NSA Archive at George Washington University hosts the actual declassified FAIRVIEW Dataflow Diagrams (April 2012), which reveals internal system and facility code names but no personal names. The STORMBREW contact precedent (named individual in Snowden documents) was in a separate NSA newsletter or internal report, not published. Journalist contact information for the FAIRVIEW reporters has been located. Full NSA FOIA procedures documented.

---

## SECTION 1: PUBLISHED SNOWDEN FAIRVIEW DOCUMENTS — What Exists

### The FAIRVIEW Dataflow Diagrams (GWU NSA Archive)
**URL**: https://nsarchive.gwu.edu/document/22360-document-07-national-security-agency-fairview  
**PDF**: https://nsarchive.gwu.edu/sites/default/files/documents/3227341/Document-07-National-Security-Agency-FAIRVIEW.pdf  
**Classification**: TOP SECRET//COMINT//NOFORN (April 2012)

This document is the most detailed published FAIRVIEW primary source. It reveals the complete data processing chain architecture with internal codenames:

| Codename | Function |
|---|---|
| SAGUARO | DNI (internet) access from FAIRVIEW partner's backbone; OC-192 and 10GE peering circuits at 8 SNRCs |
| PINECONE SCIF | NSA-controlled processing facility receiving data from AT&T sites |
| RIMROCK | Access / call processor at AT&T sites |
| TITANPOINT | Foreign gateway switches |
| MAILORDER | Encryption/transmission system from PINECONE to NSA headquarters |
| HIGHDECIBEL | FAIRVIEW LAN designation |
| COURIERSKILL | Corporate processing for modem traffic (uses DRIFTWOOD dictionary) |
| HAVASU | Server at FAIRVIEW LAN |
| MESA | Cable access system |
| DRIFTWOOD | Dictionary/filter system for modem traffic |

**What this document does NOT contain**: Personal names, individual employee identifiers, specific SNRC location designations, or organizational chart data for SSO.

**SIGAD designations found**:
- US-984T (FAIRVIEW NSA FISA IP)
- US-984X2 (FAA Voice/Fax/Modem)
- US-984E (NSA FISA Voice/Fax/Modem)
- US-990 (FAIRVIEW Transit)

### The STORMBREW Named Contact — Source Document
The ProPublica/NYT 2015 reporting specifically stated:
> "Another [document] names a contact person whose LinkedIn profile says he is a longtime Verizon employee with a top-secret clearance."

This was NOT in the dataflow diagrams. It was in a separate Snowden document — likely an NSA internal newsletter or operational report — that has **not been published** in full. ProPublica used it to identify Verizon as STORMBREW but chose not to publish the individual's name. The FAIRVIEW equivalent of this document (naming an AT&T contact person) has similarly **not been published**.

### The ACLU SSO Corporate Partners Document
**URL**: https://www.aclu.org/documents/special-source-operations-corporate-partners  
**PDF**: https://assets.aclu.org/live/uploads/document/foia/Special_Source_Operations__Corporate_Partners_.pdf

This Snowden-era NSA presentation describes the four SSO programs (BLARNEY, FAIRVIEW, OAKSTAR, STORMBREW) with the following FAIRVIEW entry:

> "US-990 FAIRVIEW (TS//SI) US-990 (PDDG-UY) - key corporate partner with access to international cables, routers, and switches."

No personal names. The partner is identified only as "key corporate partner." This document predates the 2015 ProPublica identification of AT&T.

### What Remains Unpublished
Based on the ProPublica STORMBREW precedent, the Snowden archive almost certainly contains:
1. An NSA internal newsletter or report naming an AT&T FAIRVIEW contact person (equivalent of the Verizon STORMBREW contact)
2. Possibly organizational chart or staffing documents for SSO's FAIRVIEW branch
3. Site-specific operational documents for individual SNRCs (Dallas, Chicago, etc.)

None of these have been published. They remain in the hands of journalists/organizations holding the Snowden archive.

---

## SECTION 2: JOURNALIST CONTACT PATHWAYS

### Ryan Gallagher (Primary Author, 2018 FAIRVIEW/SAGUARO Report)
- **Current employer**: Bloomberg News, cybersecurity team
- **Previous**: The Intercept (left after 2018 FAIRVIEW reporting)
- **Personal website**: https://www.rjgallagher.co.uk
- **Twitter/X**: @rj_gallagher
- **Known access**: One of "a handful of reporters to have had access to the largest leak of classified information in history — the trove of documents from the American whistleblower Edward Snowden" (per his own bio)
- **Contact approach**: Direct message via Twitter/X or contact form at rjgallagher.co.uk; reference the STORMBREW contact precedent specifically; ask whether FAIRVIEW equivalent documents name individual AT&T liaison personnel

### Henrik Moltke (Co-Author, 2016 and 2018 FAIRVIEW Reports)
- **Affiliation**: The Intercept (co-author on both FAIRVIEW investigative pieces)
- **2016 article**: First identified 33 Thomas Street NY as NSA/AT&T node
- **2018 article**: Co-byline with Gallagher on all-eight-SNRCs report
- **Contact approach**: Via The Intercept's secure contact system (https://theintercept.com/source/) or via The Intercept editorial contact

### The Intercept Tip System
- **Secure tips**: https://theintercept.com/source/ (uses SecureDrop)
- **General contact**: tips@theintercept.com
- **Note**: The Intercept has a formal policy of responsible disclosure — they chose not to name the STORMBREW Verizon contact; the same restraint would apply to AT&T FAIRVIEW contacts

### ProPublica (Jeff Larson, Julia Angwin — 2015 FAIRVIEW/AT&T reporting)
- Julia Angwin: now at The Markup (themarkup.org)
- Jeff Larson: ProPublica data editor
- Both had access to the specific Snowden document naming the STORMBREW contact
- **Contact approach**: ProPublica secure tips system (https://www.propublica.org/tips/)

### Recommended Contact Strategy
1. **Approach Gallagher first** (Bloomberg, reachable via Twitter): He left The Intercept and may have more latitude to discuss what remains unpublished. Frame as: "Researching historical Akwei v. NSA (1992) — investigating whether the Kinnecome Group referenced in Akwei's complaint has any connection to FAIRVIEW/SAGUARO operations at 4211 Bryan Street. The STORMBREW precedent suggests FAIRVIEW documents name AT&T liaison contacts — can you confirm or point to any published sources?"
2. **Use SecureDrop for The Intercept**: More anonymous and appropriate for sensitive inquiries
3. **Do not cold-contact sources asking to reveal unpublished classified material**: This crosses into legally problematic territory; frame all requests as "what has been/can be published"

---

## SECTION 3: NSA FOIA STRATEGY

### The Glomar Problem
The NSA is by far the **largest issuer of Glomar responses** among all federal agencies. The Reporters Committee for Freedom of the Press documented:
- NSA cites Exemptions 1 (classified) and 3 (NSAA Section 6) almost exclusively
- **Section 6 of the NSA Act**: Bars release of anything that would reveal "the organization or any function of the National Security Agency"
- One court held: even confirming or denying the existence of records about NSA organization is barred under Section 6

**Key case precedent**: *Wilner v. NSA* — court upheld NSA's Glomar denial for records about surveillance targets, finding that even acknowledging whether records existed would "reveal NSA's organization, functions and activities."

### What to Request (Most to Least Productive)

**Request 1 — Most likely to produce results**: Organizational records that have been previously acknowledged
- Request: "Any organizational charts or personnel designations for the Special Source Operations (SSO) division of NSA that have been declassified, previously released in response to FOIA requests, or are available in NSA's electronic reading room."
- Rationale: If something has already been released, it cannot be Glomared. SSO was publicly named in the 2013 PRISM disclosures; some organizational acknowledgment may be producible.

**Request 2 — Medium likelihood**: FAIRVIEW program records specifically acknowledged by government
- Request: "Records relating to the FAIRVIEW surveillance program (codename US-990) that have been officially acknowledged, declassified, or previously released, including any Congressional testimony mentioning FAIRVIEW."
- Rationale: The government acknowledged FAIRVIEW's existence in court filings; records about acknowledged programs are harder to Glomar.

**Request 3 — Low likelihood but documentable**: Dallas SNRC staffing
- Request: "Any records relating to the AT&T Service Node Routing Complex (SNRC) located at 4211 Bryan Street, Dallas, Texas, including personnel designations, organizational assignments, or staffing records."
- Rationale: Will almost certainly receive Glomar; denial is documentable and can be cited in this investigation as evidence of classification.

### NSA FOIA Submission Details
- **Mailing**: National Security Agency, ATTN: FOIA/PA Office, 9800 Savage Road, Suite 6932, Fort George G. Meade, MD 20755-6932
- **Fax**: 443-479-3612 (limited to 20 pages)
- **Online**: NSA FOIA submission portal at nsa.gov
- **Phone for status**: 301-688-6527
- **FOIA Liaison**: Sally A. Nicholson (same number)
- **Appeal address**: NSA/CSS FOIA Appeal Authority (same address)

### Alternative FOIA Target: DOD Acquisition Records
AT&T's first post-Bell-breakup contract was "nearly $1 billion" to provide computers and services to the NSA (1985). This is a **procurement record**, not an intelligence record.
- **Requester**: DISA (Defense Information Systems Agency) FOIA office or NSA contracting office
- **Request language**: "Procurement or contract records for any contracts awarded to AT&T by the National Security Agency or Department of Defense in the period 1984–1986, including the approximately $1 billion computer and services contract referenced in August 2015 reporting by the New York Times and ProPublica."
- **Rationale**: Federal procurement records are presumptively public under FAR; contracting officers' names and award details are public record
- **Contact**: DISA FOIA, 6914 Cooper Ave., Fort Meade, MD 20755; disa.foia@mail.mil

---

## SECTION 4: PUBLISHED FAIRVIEW DOCUMENT INVENTORY (Complete)

All publicly available primary-source FAIRVIEW documents as of April 2026:

| Document | Date | Source | Content | Names? |
|---|---|---|---|---|
| FAIRVIEW Dataflow Diagrams | Apr 2012 | GWU NSA Archive | Full data flow architecture; SAGUARO, PINECONE, RIMROCK, TITANPOINT | No |
| SSO Corporate Partners presentation | ~2013 | ACLU | Overview of 4 SSO programs; FAIRVIEW as US-990 | No |
| SSO Dictionary (snippet) | ~2013 | Electrospaces | SAGUARO definition, SNRC terminology | No |
| FAIRVIEW Overview slide deck | ~2010 | Various | Corporate partner map, access counts | No |
| NSA Inspector General draft report (2009) | Mar 2009 | EFF / The Guardian | Stellar Wind; "Company A" and "Company B" | No (anonymized) |
| Internal NSA newsletter (Japanese earthquake) | 2011 | ProPublica | CLIFFSIDE cable restoration; used to ID AT&T | No |
| Internal NSA newsletter (STORMBREW contact) | Unknown | ProPublica (not published) | **Names Verizon contact person** | YES — but UNPUBLISHED |

**Conclusion**: No published primary FAIRVIEW document names any individual. The one document that named a telecom contact (STORMBREW/Verizon) has not been published in full.

---

## SECTION 5: Summary and Recommended Action Sequence

### Priority 1 (Immediate, no cost): Contact Ryan Gallagher
- Twitter/X: @rj_gallagher
- Specific question: Does the Snowden FAIRVIEW archive contain documents naming specific AT&T liaison contacts at the Dallas SNRC, equivalent to the STORMBREW/Verizon contact named in the 2015 ProPublica reporting?
- Context to provide: Akwei v. NSA (1992), Kinnecome Group claim, 4211 Bryan Street

### Priority 2 (Document the denial): File NSA FOIA
- File Request 1 (SSO org charts previously acknowledged) first — most likely to produce something
- File Request 3 (4211 Bryan Street Dallas staffing) simultaneously — denial is itself evidence
- Expected timeline: 20-day initial response; appeals can take 2+ years

### Priority 3 (Exploit public procurement): File DISA/NSA contracting FOIA
- 1985 AT&T/NSA computer contract — this is acquisition data, not intelligence data
- Contracting officer names and award details are presumptively public
- May reveal early FAIRVIEW infrastructure procurement chain

### Priority 4 (Read available documents): GWU NSA Archive deep read
- The FAIRVIEW Dataflow Diagrams PDF at GWU contains dozens of internal codenames
- Full read may reveal additional facility designations or organizational identifiers not yet analyzed
- URL: https://nsarchive.gwu.edu/document/22360-document-07-national-security-agency-fairview

---

## Sources Consulted This Round
- GWU NSA Archive FAIRVIEW: https://nsarchive.gwu.edu/document/22360-document-07-national-security-agency-fairview
- ProPublica FAIRVIEW evidence trail: https://www.propublica.org/article/a-trail-of-evidence-leading-to-atts-partnership-with-the-nsa
- ACLU SSO Corporate Partners: https://www.aclu.org/documents/special-source-operations-corporate-partners
- Ryan Gallagher bio: https://www.rjgallagher.co.uk/p/about.html
- Ryan Gallagher Wikipedia: https://en.wikipedia.org/wiki/Ryan_Gallagher
- RCFP Glomar analysis: https://www.rcfp.org/glomar-denials-data-analysis/
- NSA FOIA handbook: https://www.nsa.gov/Helpful-Links/NSA-FOIA/Reading-Room/FOIA-Handbook/
- NSA FOIA submission: https://www.nsa.gov/about/contact-us/Submit-a-FOIA-Request/
- Wilner v. NSA Glomar precedent: https://www.meyerowitzcommunications.com/pdf/Gloomy%20Glomar%20Ruling.pdf
- Electrospaces NSA codenames: https://www.electrospaces.net/p/nicknames-and-codewords.html

---
*File: 33_ACTIONABLE_FOIA_AND_JOURNALIST_PATHWAYS.md | Generated: April 22, 2026*
