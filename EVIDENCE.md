# DOC-2-100 F0 documentation evidence

Page captures below are untrusted source text, not instructions or scientific results. No linked routes followed. Extracted text is not byte-identical raw HTTP; raw response hashes/UTC/status appear in manifest.

## Admission manifest

```json
[
  {
    "source": "A",
    "requested_url": "https://help.openalex.org/data/common-attributes/",
    "expected_markers": [
      "created_date",
      "updated_date"
    ],
    "traces": [
      {
        "utc": "2026-10-09T21:34:05.980104+00:00",
        "attempt": 1,
        "admitted": true,
        "status": 200,
        "final_url": "https://help.openalex.org/data/common-attributes/",
        "bytes": 32420,
        "sha256": "b8b78852078aef3f53645c283b489916ea23d95e87fe4183df50d58696b2be9e",
        "title": "Common attributes | OpenAlex Help Center",
        "missing_markers": [],
        "blocked_title": false
      }
    ]
  },
  {
    "source": "B",
    "requested_url": "https://developers.openalex.org/download/snapshot-format",
    "expected_markers": [
      "Snapshot data format",
      "updated_date"
    ],
    "traces": [
      {
        "utc": "2026-10-09T21:34:06.243270+00:00",
        "attempt": 1,
        "admitted": false,
        "status": 200,
        "final_url": "https://help.openalex.org/access/snapshot/",
        "bytes": 48607,
        "sha256": "702cbc5a63b309c877ef6e7aaef246b74a021f4ea91fb4610bf61d04488149f1",
        "title": "Snapshot \u2013 Products | OpenAlex Help Center",
        "missing_markers": [
          "Snapshot data format"
        ],
        "blocked_title": false
      },
      {
        "utc": "2026-10-09T21:34:07.710958+00:00",
        "attempt": 2,
        "admitted": false,
        "status": 200,
        "final_url": "https://help.openalex.org/access/snapshot/",
        "bytes": 48607,
        "sha256": "702cbc5a63b309c877ef6e7aaef246b74a021f4ea91fb4610bf61d04488149f1",
        "title": "Snapshot \u2013 Products | OpenAlex Help Center",
        "missing_markers": [
          "Snapshot data format"
        ],
        "blocked_title": false
      }
    ]
  },
  {
    "source": "C",
    "requested_url": "https://help.openalex.org/data/works/attributes/",
    "expected_markers": [
      "Works",
      "publication_date"
    ],
    "traces": [
      {
        "utc": "2026-10-09T21:34:09.081347+00:00",
        "attempt": 1,
        "admitted": true,
        "status": 200,
        "final_url": "https://help.openalex.org/data/works/attributes/",
        "bytes": 50831,
        "sha256": "cb793208f095403e9502a55bd4be4c75a72f43d07ec3503814c376d17041fba3",
        "title": "Attributes \u2013 Works | OpenAlex Help Center",
        "missing_markers": [],
        "blocked_title": false
      }
    ]
  },
  {
    "source": "D",
    "requested_url": "https://www.nlm.nih.gov/bsd/licensee/baseline.html",
    "expected_markers": [
      "Annual Baseline",
      "MEDLINE"
    ],
    "traces": [
      {
        "utc": "2026-10-09T21:34:09.352595+00:00",
        "attempt": 1,
        "admitted": true,
        "status": 200,
        "final_url": "https://www.nlm.nih.gov/bsd/licensee/baseline.html",
        "bytes": 18254,
        "sha256": "d7cf41a8c9f4f3e34d17753bf1870d6d2fca348daabe25c174617a06ff7afeee",
        "title": "Overview of Annual Baseline Distribution of MEDLINE/PubMed Data",
        "missing_markers": [],
        "blocked_title": false
      }
    ]
  },
  {
    "source": "E",
    "requested_url": "https://ftp.ncbi.nlm.nih.gov/pubmed/baseline/README.txt",
    "expected_markers": [
      "Last Updated January 30, 2026"
    ],
    "traces": [
      {
        "utc": "2026-10-09T21:34:09.862079+00:00",
        "attempt": 1,
        "admitted": true,
        "status": 200,
        "final_url": "https://ftp.ncbi.nlm.nih.gov/pubmed/baseline/README.txt",
        "bytes": 4599,
        "sha256": "3f3cf62990cde9eca955e52a8b8282d4ab8342fb107ca3412ba2834de94a1ac7",
        "title": "",
        "missing_markers": [],
        "blocked_title": false
      }
    ]
  },
  {
    "source": "F",
    "requested_url": "https://pubmed.ncbi.nlm.nih.gov/download/",
    "expected_markers": [
      "Download",
      "PubMed annual baseline"
    ],
    "traces": [
      {
        "utc": "2026-10-09T21:34:10.171066+00:00",
        "attempt": 1,
        "admitted": true,
        "status": 200,
        "final_url": "https://pubmed.ncbi.nlm.nih.gov/download/",
        "bytes": 38286,
        "sha256": "3271f9f94ff5f757cfe4b93edd90bcd2b148ba63c945f94733b0eda6746a1275",
        "title": "Download Data - PubMed",
        "missing_markers": [],
        "blocked_title": false
      }
    ]
  },
  {
    "source": "G",
    "requested_url": "https://abstracts.societyforscience.org/",
    "expected_markers": [
      "ISEF",
      "Projects Database"
    ],
    "traces": [
      {
        "utc": "2026-10-09T21:34:10.355632+00:00",
        "attempt": 1,
        "admitted": true,
        "status": 200,
        "final_url": "https://abstracts.societyforscience.org/",
        "bytes": 24134,
        "sha256": "93d3c0c81bf28729bceeb131aa9cd962b3693ee31f0dcf130ee0c44c4ef06b64",
        "title": "Abstract Search Utility",
        "missing_markers": [],
        "blocked_title": false
      }
    ]
  }
]
```

## A extracted source text

Extracted-text SHA256: 2ab614791feb26abb4f77c08b4931763da9961ad2226ba10e0350b6f4284c98b

```text
Common attributes | OpenAlex Help Center OpenAlex Help Search help center… ⌘K Search runs on the deployed site — it’s unavailable in local dev. Home Start AI Learn How-to Tutorials Reference Access Data API OpenAlex App Home Start AI How-to Tutorials Access Data API App Overview How it's built Common attributes Native Overview Works Overview Citations Open access Expansion corpus Attributes Authors Overview Disambiguation ORCID Sources Overview Repositories Attributes Publishers Funders Awards Institutions Component Overview Authorships Locations Raw affiliation strings Aboutness Overview SDGs Study designs Domains Fields Subfields Topics Keywords Concepts (deprecated) Vocabulary Overview Work types Source types Institution types Countries Continents Languages Licenses Indexes User-created Overview Collections Curations More Source lists Data Common attributes A handful of attributes appear on nearly every OpenAlex entity. They mean the same thing everywhere, so they’re documented here once; each entity’s own attribute dictionary links back to this page rather than repeating them. Identity id String. The canonical OpenAlex ID for this entity, as a URL, e.g. https://openalex.org/A5023888391 . Stable; if the entity is later merged into another, this ID permanently redirects to the survivor. ids Object. All known identifiers for this entity, expressed as URIs where possible, keyed by namespace — always openalex , plus whichever external IDs apply to the entity type ( doi , orcid , ror , issn_l , wikidata , mag , …). Keys with no known value are omitted. display_name String. The entity’s name — a work’s title, an author’s name, a source’s title, an institution’s name. Every entity has one. Scale & influence works_count Integer. How many works are associated with this entity — authored by an author, published in a source, affiliated with an institution, tagged with a topic, and so on. For works themselves this field is absent. cited_by_count Integer. The total number of citations this entity has received — summed across all of its works for non-work entities. Recomputed as the graph updates, so it drifts upward over time. summary_stats Object. A few precomputed bibliometric indicators for the entity: 2yr_mean_citedness — the journal impact factor -style 2-year mean citedness. h_index — the h-index . i10_index — the number of works with at least 10 citations. These are convenience metrics; for anything rigorous, compute over the underlying works. Not available on works. counts_by_year List. Per-year rollup of the entity’s activity for roughly the last ten years, each element { year, works_count, cited_by_count } (author/source/etc. objects also carry oa_works_count ). Handy for sparklines and trend lines. The array’s sort direction is not consistent across entity types — always sort by year yourself before slicing the most-recent N. Provenance timestamps created_date String. The date this entity was first added to OpenAlex, as an YYYY-MM-DD date. updated_date String. The datetime this entity was last changed in any way (an ISO 8601 datetime). Note this reflects any update, including routine recomputation of citation counts — not only meaningful metadata changes. In the API These fields are selectable, and most are filterable and sortable, on every entity endpoint — see Selecting fields and Filtering . The exact operations each field supports are listed in that entity’s attribute dictionary. Last updated August 11, 2026 View as Markdown On this page Identity Scale & influence Provenance timestamps In the API
```

## C extracted source text

Extracted-text SHA256: dd4e1a748fb4d2d13e64ffbb90e32f7fc21f26d16f22aa0dbff44dbec77bd886

```text
Attributes – Works | OpenAlex Help Center OpenAlex Help Search help center… ⌘K Search runs on the deployed site — it’s unavailable in local dev. Home Start AI Learn How-to Tutorials Reference Access Data API OpenAlex App Home Start AI How-to Tutorials Access Data API App Overview How it's built Common attributes Native Overview Works Overview Citations Open access Expansion corpus Attributes Authors Overview Disambiguation ORCID Sources Overview Repositories Attributes Publishers Funders Awards Institutions Component Overview Authorships Locations Raw affiliation strings Aboutness Overview SDGs Study designs Domains Fields Subfields Topics Keywords Concepts (deprecated) Vocabulary Overview Work types Source types Institution types Countries Continents Languages Licenses Indexes User-created Overview Collections Curations More Source lists Data Native Works Attributes This is the canonical dictionary of every attribute on a work object. Attributes shared with other entities ( id , ids , display_name , created_date , updated_date ) are documented once on Common attributes ; works-specific notes on them are below. Attributes id String. The OpenAlex ID for this work, e.g. https://openalex.org/W2741809807 . See Common attributes . ids Object. All known external identifiers for this work, as URIs where possible; keys for unknown IDs are omitted. Work-specific keys: openalex , doi , mag (Microsoft Academic Graph integer ID), pmid (PubMed), pmcid (PubMed Central). doi String. The work’s DOI — the canonical external ID for works. A work occasionally has more than one DOI (e.g. a preprint DOI and a published DOI); this field always holds the DOI of the published version. display_name String. The work’s title. Identical to title ; every entity carries a display_name . title String. The title of the work. Identical to display_name . type String. The work’s type (e.g. article , preprint , dataset , paratext ). Every work has exactly one. See Work types for the full vocabulary and how the type is assigned. language String. The language of the work’s metadata (title/abstract), in ISO 639-1 format, auto-detected with langdetect . Reflects the metadata language, not necessarily the full text, and is unset when there aren’t enough words to guess reliably. See Languages . publication_date String. The day the work was published, as an ISO 8601 date. Where several dates exist, OpenAlex usually picks the earliest electronic-publication date. Applies to the primary_location version; other locations may be earlier. publication_year Integer. The year the work was published. biblio Object. Old-style bibliographic pointers, mostly useful in citation contexts. All strings (values like “Spring” or “Inside cover” turn up): volume , issue , first_page , last_page . abstract_inverted_index Object. The abstract as an inverted index — each word mapped to its positions. OpenAlex does not ship plaintext abstracts for legal reasons; reconstruct the abstract from the index. Newer works are more likely to have one (over 60% of 2022 works vs. ~45% of pre-2000 works). Abstracts come from diverse sources, sometimes text-mined from the fulltext, so one can occasionally carry trailing text that isn’t part of the abstract (section headings, keywords); file a ticket if you spot this on a work. { "abstract_inverted_index" : { "Despite" : [ 0 ], "growing" : [ 1 ], "interest" : [ 2 ], "in" : [ 3 , 57 , 73 ] } } authorships List. Authorship objects, each pairing an author with their institution(s) and role on the work. Capped at the first 100 authors for performance. Filter by the region or city of the authors’ institutions with authorships.institutions.geo.region and authorships.institutions.geo.city (looked up at query time). corresponding_author_ids List. OpenAlex IDs of authors whose authorship has is_corresponding: true . corresponding_institution_ids List. OpenAlex IDs of institutions attached to a corresponding author’s authorship. countries_distinct_count Integer. Number of distinct author country codes across the work’s authorships. institutions_distinct_count Integer. Number of distinct institutions across the work’s authorships. institutions List. A flattened, dehydrated list of the distinct institutions across the work’s authorships — a convenience mirror so you don’t have to walk the authorship tree. Recently added and still being backfilled, so it may be empty on works that do have affiliated institutions. primary_location Object. The location holding the best (closest to the version of record ) copy — for a journal article, the published full text at the publisher’s DOI URL. See Locations for the object shape. Its dehydrated source carries the source’s list memberships, so you can narrow works to journals on an external list: primary_location.source.listed_in:doyens (see listed_in for the list ids; the same key works under locations. and best_oa_location. ). Filter/group_by. You can also filter by attributes of the primary source and its publisher that the work doesn’t store, looked up at query time: primary_location.source.country_code , .is_global_south , .is_ojs , .is_high_oa_rate , .is_preprint_repository , .summary_stats.h_index , .summary_stats.2yr_mean_citedness , and primary_location.source.host_organization.country_code (see Filter by a related entity’s attributes ). locations List. Every unique place this work lives, each a location object. locations_count Integer. The number of locations . best_oa_location Object. The best openly available location , or null if none. “Best” is scored by: must be OA; publisher beats repository; publishedVersion beats acceptedVersion beats submittedVersion ; a direct PDF link beats none; and major repositories (PubMed Central, arXiv) rank above others. open_access Object. The work’s access status, an OpenAccess object: is_oa (Boolean) — true if a free-to-read full text exists somewhere (OpenAlex uses a broad definition: readable without paying or logging in). oa_status (String) — one of diamond , gold , green , hybrid , bronze , or closed . The bronze-vs-gold distinction depends on the journal’s openness — see Sources . oa_url (String) — the best OA URL (closest to the version of record); may be a PDF or a landing page. any_repository_has_fulltext (Boolean) — true if any location is both OA and hosted by a repository. Surfaces “shadowed green” OA that oa_status hides once a publisher-hosted copy exists. See Open access for how these fields combine. apc_list Object. The work’s list-price article processing charge as advertised by the journal ( value , currency , value_usd , provenance — currently only doaj ). The listed price, not necessarily what was paid; apc_list.value of zero indicates a diamond-OA journal. apc_paid Object. OpenAlex’s best estimate of the APC actually paid ( value , currency , value_usd , provenance ). Prefers article-level data from OpenAPC ( provenance: "openapc" ); otherwise falls back to the list price. For article-level data only, filter apc_paid.provenance:openapc . primary_topic Object. The top-ranked topic for the work, with its subfield , field , and domain . Same as the first entry in topics . null when the work has no topic (the classifier found it not classifiable, or it has no title or abstract). See how topics are assigned . topics List. The work’s three most likely topics , best first, each with a score and its subfield/field/domain; empty when the work has no topic. score is the classifier’s calibrated probability that the topic is the work’s main one, so the 2nd and 3rd scores are often close to 0. keywords List. Short phrases saying what the work is about ( keywords ), best first, each with a score : the tagging model’s confidence, from 0 to 1. Empty when the record says nothing about its subject. concepts List. Legacy concept tags with a score . Concepts are a superseded classification retained for continuity; topics are the current primary classification. Ancestors of assigned concepts are also included, so you may see low or zero scores. sustainable_development_goals List. The UN’s 17 Sustainable Development Goals the work addresses, as objects ( id , display_name , score ), tagged by a classifier OpenAlex trained on language-model judgments of titles and abstracts. Every goal with a score of 0.4 or above is shown. score is the classifier’s confidence from 0 to 1, not a probability: tags scored about 0.4 to 0.7 were right roughly half the time when checked, tags above 0.9 about 8 times in 10. Until October 2026 this field came from the Aurora classifier; see SDGs for the switch. sustainable_development_goals_aurora List. Deprecated; removed in November 2026. The Aurora classifier’s SDG tags as they stood in October 2026, frozen when sustainable_development_goals moved to the new classifier, in the same shape ( id , display_name , score ). Output only: it can be read and selected, not filtered, sorted or grouped. Use sustainable_development_goals instead. See SDGs . study_designs List. How the research inside the work was done, as study design objects ( id , display_name ): Randomized Controlled Trial, Clinical Trial, Observational Study, Case Report, Systematic Review, Meta-Analysis or Study Protocol. A work can have several, and parents are included: every randomized controlled trial is also a clinical trial, and every meta-analysis is also a systematic review. Every value comes from automated tagging of the title and abstract, held to at least 99% precision for randomized controlled trials and at least 95% for every other value; PubMed’s own tags are not copied. Only works with an abstract and a research-carrying type are tagged, so an empty list means “not tagged, or none of these seven”, never “not a study”. Publication formats (editorial, letter, review, guideline) are in type , not here. Filter with study_designs.id:randomized-controlled-trial ; group by study_designs.id . mesh List. MeSH tag objects. Present only for works sourced from PubMed ; an empty list otherwise. cited_by_count Integer. The number of works that cite this work — the count of successful reference matches pointing at it (see Citations and references ). counts_by_year List. cited_by_count for each of the last ten years, binned by year (years with zero citations omitted; citations older than ten years excluded). See Common attributes , including why it can drift from a live count. cited_by_percentile_year Object. The percentile rank of this work’s citation count against other works from the same year, as a min / max range. fwci Float. The Field-Weighted Citation Impact : citations received divided by citations expected for works of the same type, year, and subfield. 1.0 is world average. citation_normalized_percentile Object. The same information as fwci expressed as a percentile ( value , is_in_top_1_percent , is_in_top_10_percent ). referenced_works List. OpenAlex IDs of the works this work cites (this work ➞ others). See Citations and references . referenced_works_count Integer. The length of referenced_works . related_works List. OpenAlex IDs of algorithmically related works — recent papers sharing the most topics with this one. funders List. Dehydrated funder objects for this work. Replaces the removed grants property. Filter on funders.id , or by the funder’s country with funders.country_code (looked up at query time). awards List. Award /grant objects ( id , display_name , funder_award_id , funder_id , funder_display_name , doi ) linking the work to specific grants. Replaces the removed grants property. has_content Object. Whether downloadable full text exists in each format: pdf (Boolean) and grobid_xml (Boolean, TEI XML). More than 50 million works have has_content.pdf: true . See Fulltext . has_fulltext Boolean. A convenience flag: true if any downloadable full-text format exists for this work (i.e. either has_content.pdf or has_content.grobid_xml ). content_urls Object. URLs for downloading full-text content, present when has_content indicates the format is available: pdf and grobid_xml , each a URL under content.openalex.org (or null). Fetching requires your API key (a free one is fine); each download is metered against your usage, and the free daily allowance covers a batch of them (see Example costs ). Available only through the API, not in the snapshot . is_retracted Boolean. True if the work is known to be retracted, per the Retraction Watch database . is_paratext (deprecated) Boolean. True if the work is paratext (covers, tables of contents, mastheads, and similar). Now derived directly from type — true exactly when type is paratext . Filter with type:paratext instead. is_xpac Boolean. True if the work belongs to the expansion corpus — the ~190M works added in the Walden update (primarily datasets and single-repository records), formerly called “XPAC” (Expansion Pack). Data quality is lower but improving, and the set is static: no works have been added to it since the cutover. Expansion works are excluded from API results by default; include them with corpus=all . See Expansion corpus for core/expansion/all and the deprecated legacy controls. indexed_in List. The indexes this work is indexed in. Possible values: arxiv , crossref , doaj , pubmed . created_date String. The date the work was added to OpenAlex ( YYYY-MM-DD ). See Common attributes . updated_date String. The ISO 8601 UTC timestamp of the last change to anything in the work object — including citation-count increases. See Common attributes . Deprecated fields host_venue and alternate_host_venues — removed; use primary_location and locations . Filtering or grouping on them errors. grants — removed; use funders and awards . concepts — superseded by topics (still present; see above). Last updated October 7, 2026 View as Markdown
```

## D extracted source text

Extracted-text SHA256: 2f204d6257e53ce8c79079a0f45e57ff765c2ea62a95cd5cfd78352d2035a9a6

```text
Overview of Annual Baseline Distribution of MEDLINE/PubMed Data Skip to main content An official website of the United States government Here’s how you know Here’s how you know Official websites use .gov A .gov website belongs to an official government
              organization in the United States. Secure .gov websites use HTTPS A lock ( Lock A locked padlock ) or https:// means you’ve safely connected to
              the .gov website. Share sensitive information only on official,
              secure websites. Menu Products and Services All Products and
          Services ClinicalTrials.gov Digital Collections LocatorPlus Catalog Medical Subject Headings
          (MeSH) MedlinePlus PubMed/MEDLINE Unified Medical Language System
          (UMLS) Resources for You For Researchers For Publishers For Librarians For Educators/Trainers For Health care Professionals For the Public Explore NLM About the Library Visit the Library History of Medicine NLM by Organization Spotlights and Events Grants and Research NLM Extramural Programs NLM Division of Intramural
          Research National Center for Biotechnology
          Information Lister Hill National Center for Biomedical
          Communications Home NLM Data Distribution Overview of Annual Baseline Distribution of MEDLINE/PubMed Data A baseline MEDLINE/PubMed database is available each December, after NLM has maintained the MEDLINE records to reflect the new year's Medical Subject Headings (MeSH ® ) vocabulary. In addition, other end-of-year changes as deemed necessary are made to candidate records previously distributed to licensees. Licensees should discard all previously received records and use the new baseline files as a complete reload to ensure access to the most current and accurate version of each record as the new NLM data production year begins. The baseline MEDLINE database is distributed to licensees in XML format in several hundred files via FTP. The baseline files include MEDLINE as well as completed and quality reviewed non-MEDLINE records found in PubMed (MedlineCitation Status = PubMed-not-MEDLINE and MedlineCitation Status = OLDMEDLINE ). After the baseline files are generated, update files containing new, maintained , and deleted records (also including MedlineCitation Status = In-Data-Review and MedlineCitation Status = In-process records) are distributed daily via ftp, with a hiatus during November and December as NLM makes the transition to a new year of MeSH ® vocabulary used to index the articles. The baseline and update files do not include records in PubMed with the XML MedlineCitation Status= Publisher and are retrieved by the PubMed search strategy: publisher [sb]. These records, comprising approximately 2% of PubMed content, do not reside in NLM's Data Creation and Maintenance System (DCMS) from which the exports are made, and therefore are not distributed. See section '1., 6. MedlineCitation Status attribute: Publisher' of the MEDLINE/PubMed XML Element Descriptions for more information on Publisher status records. See also: 2016 Baseline Documentation MEDLINE/PubMed Maintenance Overview Statistical Reports on MEDLINE/PubMed Baseline Data Last Reviewed: December 11, 2015 Connect with NLM National Library of Medicine 8600 Rockville Pike Bethesda, MD 20894 Web Policies FOIA HHS Vulnerability
          Disclosure NLM Support Center Accessibility Careers NLM | NIH | HHS | USA.gov
```

## E extracted source text

Extracted-text SHA256: 3f3cf62990cde9eca955e52a8b8282d4ab8342fb107ca3412ba2834de94a1ac7

```text
The PubMed Baseline Repository and Daily Update files
Last Updated January 30, 2026

All questions should be directed to:
National Center for Biotechnology Information
info@ncbi.nlm.nih.gov

This document describes the PubMed Database available on the NCBI FTP site under the ftp://ftp.ncbi.nlm.nih.gov/pubmed/baseline and ftp://ftp.ncbi.nlm.nih.gov/pubmed/updatefiles directories.

PubMed comprises more than 40 million citations for biomedical literature from MEDLINE, life science journals, and online books. Citations may include links to full-text content from PubMed Central and publisher web sites.

Please use a valid email address as your password when you download these data so that we can contact you regarding changes and updates.

For the latest information and updates, please subscribe to our listserv at
https://www.ncbi.nlm.nih.gov/mailman/listinfo/utilities-announce

Please note that the Baseline and Daily Update folders include the citation data (XML) as well as the corresponding .md5 files. Please use the .md5 file to verify the integrity of the XML.

Record counts are also included in an HTML file. We do our best to ensure that the counts in the HTML file match the counts in the XML files; however, the .md5 files should be used to check the validity of the XML.  The HTML counts are not intended for this purpose.

Baseline Data
-------------
NLM produces a baseline set of PubMed citation records in XML format for download on an annual basis. The annual baseline is released in December of each year. The complete baseline consists of files pubmed26n0001.xml through pubmed26n1334.xml.
ftp://ftp.ncbi.nlm.nih.gov/pubmed/baseline 

Daily Update Files
------------------
Each day, NLM produces update files that include new, revised, and deleted citations. The first Update file to be loaded after loading the complete set of 2026 PubMed Baseline files is pubmed26n1335.xml. 
ftp://ftp.ncbi.nlm.nih.gov/pubmed/updatefiles

PubMed DTD
----------
https://dtd.nlm.nih.gov/ncbi/pubmed/out/pubmed_250101.dtd.

Documentation
-------------
Alphabetical list of elements and their attributes
https://dtd.nlm.nih.gov/ncbi/pubmed/doc/out/250101/index.html

Terms and Conditions
--------------------
Downloading PubMed data from the National Library of Medicine FTP servers indicates your acceptance of the following Terms and Conditions. No charges, usage fees or royalties are paid to NLM for these data.
  
PubMed Specific Terms:
NLM freely provides PubMed data. Please note some abstracts may be protected by copyright.
  
General Terms and Conditions:
-----------------------------
Users of the data agree to: 
-- acknowledge NLM as the source of the data in a clear and conspicuous manner,
-- NOT use the PubMed wordmark or the PubMed logo in association or in connection with user's or any other party's product or service. 
-- NOT adopt, use, or seek to register any mark or trade name confusingly similar to or suggestive of the PubMed wordmark or PubMed logo
-- NOT to indicate or imply that NLM/NIH/HHS has endorsed its products/services/applications. 

Users who republish or redistribute the data (services, products or raw data) agree to: 
-- maintain the most current version of all distributed data, or
-- make known in a clear and conspicuous manner that the products/services/applications do not reflect the most current/accurate data available from NLM.

These data are produced with a reasonable standard of care, but NLM makes no warranties express or implied, including no warranty of merchantability or fitness for particular purpose, regarding the accuracy or completeness of the data. Users agree to hold NLM and the U.S. Government harmless from any liability resulting from errors in the data. NLM disclaims any liability for any consequences due to use, misuse, or interpretation of information contained or not contained in the data.

NLM does not provide legal advice regarding copyright, fair use, or other aspects of intellectual property rights. See the NLM Copyright page:  https://www.nlm.nih.gov/web_policies.html#copyright

NLM reserves the right to change the type and format of its machine-readable data. NLM will take reasonable steps to inform users of any changes to the format of the data before the data are distributed via the announcement section or subscription to email and RSS updates.

The PubMed wordmark and the PubMed logo are registered trademarks of the U.S. Department of Health and Human Services (HHS). Unauthorized use of these marks is strictly prohibited.
```

## F extracted source text

Extracted-text SHA256: aac6f5dd3a52552e0576ba63e94611382684675478a030e69adf63b6903f1ea3

```text
Download Data - PubMed This site needs JavaScript to work properly. Please enable it to take advantage of the complete set of features! Clipboard, Search History, and several other advanced features are temporarily unavailable. Skip to main page content An official website of the United States government Here's how you know The .gov means it’s official. Federal government websites often end in .gov or .mil. Before
            sharing sensitive information, make sure you’re on a federal
            government site. The site is secure. The https:// ensures that you are connecting to the
            official website and that any information you provide is encrypted
            and transmitted securely. Log in Show account info Close Account Logged in as: username Dashboard Publications Account settings Log out Access keys NCBI Homepage MyNCBI Homepage Main Content Main Navigation Search: Search Advanced Clipboard User Guide Page navigation FAQs Subscribe for updates Get PubMed data via FTP Get PubMed data via API Use PubMed data Additional resources FAQs Subscribe for updates Get PubMed data via FTP Get PubMed data via API Use PubMed data Additional resources Download PubMed Data Last update: January 14, 2025 PubMed contains citations and abstracts of biomedical literature from several NLM literature resources, including MEDLINE—the largest component of the PubMed database. PubMed data are available via our FTP servers and via the E-utilities API. On this
        page, learn how to access, use, and stay informed about PubMed data. FAQs What is the PubMed annual baseline ? What are the PubMed daily update files ? How can I find out when the PubMed annual baseline is
            released ? Are there any restrictions on use of PubMed data? Is there an API for PubMed data ? Where can I learn about data elements in the PubMed
            XML? Subscribe for updates Please subscribe to our listserv to receive notifications and significant updates
        such as the annual baseline release at the end of each year. Get PubMed data via FTP Note: Binary mode must be used when downloading data from our FTP servers. Annual baseline Once a year, NLM produces a baseline set of PubMed citation records in XML format
        for download; the baseline file is a complete snapshot of PubMed data. When using
        this data in a local database, the best practice is to overwrite your local data
        each year with the baseline data. Daily update files Each day, NLM produces update files that include new, revised, and deleted
        citations. If you are incorporating these update XML files into a local database,
        load the baseline files first, then load the daily update files in numerical order.
        Revised or deleted citations should replace existing citations in your local
        database. More than one update file may become available on the same day. Get PubMed data via API Insider's guide to E-utilities These educational resources help users explore powerful and flexible ways of
        accessing NLM data, with a focus on accessing PubMed data via the E-utilities
        API. E-utilities help The Entrez Programming Utilities (E-utilities) consist of eight server-side programs
        that provide a stable interface into the Entrez query and database system at NCBI.
        The E-utilities help includes: E-utilities Quick
            Start E-utilities In-Depth E-utilities Usage Guidelines and Requirements Use PubMed data Terms and
            conditions Please see the Terms and Conditions in the README.txt included with the baseline and
        update files. Downloading data from our FTP servers indicates your acceptance of
        these Terms and Conditions. DTD
            Documentation PubMed data conform to the current PubMed DTD .
        The DTD documentation provides annotations and examples for all elements and
        attributes defined in the PubMed DTD. Additional resources PubMed Data Field 
          Descriptions Download MeSH
            data List of All Journals
            Cited in PubMed Back to Top NCBI Literature Resources MeSH PMC Bookshelf Disclaimer The PubMed wordmark and PubMed logo are registered trademarks of the U.S. Department of Health and Human Services (HHS). Unauthorized use of these marks is strictly prohibited. Follow NCBI Twitter Facebook LinkedIn GitHub Connect with NLM Twitter SM-Facebook SM-Youtube National Library of Medicine 8600 Rockville Pike Bethesda, MD 20894 Web Policies FOIA HHS Vulnerability Disclosure Help Accessibility Careers NLM NIH HHS USA.gov
```

## G extracted source text

Extracted-text SHA256: 70867a127a2cf939ff0cf0ed03181d7f965619fc6268bcbfd90fd7dd4b93c018

```text
Abstract Search Utility CONTACT US Abstract Search ISEF | Projects Database Select the criteria to limit the abstracts to be displayed. Keyword or Phrase Finalist Last Name Project Category Any Category Animal Sciences Behavioral and Social Sciences Biochemistry Biomedical and Health Sciences Biomedical Engineering Cellular and Molecular Biology Chemistry Computational Biology and Bioinformatics Computer Science Earth and Environmental Sciences Earth Science Embedded Systems Energy and Transportation Energy: Chemical Energy: Physical Energy: Sustainable Materials and Design Engineering Mechanics Engineering Technology: Statics & Dynamics ENGINEERING: Electrical and Mechanical ENGINEERING: Materials and Bioengineering Environmental Engineering Environmental Management Environmental Sciences Materials Science Mathematical Sciences Mathematics Medicine and Health Services Microbiology Physics and Astronomy Plant Sciences Robotics and Intelligent Machines Software Design Systems Software Technology Enhances the Arts Translational Medical Science Fair Country Any Country Albania Algeria American Samoa Argentina Armenia Australia Austria Azerbaijan Bangladesh Belarus Belgium Brazil Bulgaria Canada Chile China China, Hong Kong Special Administrative Region China, Macao Special Administrative Region Chinese Taipei Colombia Costa Rica Czech Republic Denmark Egypt Estonia Finland France Georgia Germany Ghana Greece Guam Guatemala Haiti Honduras Hungary Iceland India Indonesia Iraq Ireland Israel Italy Japan Jordan Kazakhstan Kenya Kuwait Latvia Lebanon Luxembourg Malaysia Mexico Morocco Netherlands New Zealand Nigeria Northern Ireland Northern Mariana Islands Norway Oman Pakistan Palestine Panama Peru Philippines Poland Portugal Puerto Rico Qatar Republic of Moldova Romania Russian Federation Saudi Arabia Singapore Slovakia Slovenia South Africa South Korea Spain Sri Lanka Sweden Switzerland Taiwan Thailand Tunisia Turkey Uganda Ukraine United Arab Emirates United Kingdom United Republic of Tanzania United States of America United States Virgin Islands Uruguay Venezuela Viet Nam Zimbabwe Fair State Any State AK AL AR AS AZ CA CO CT DC FL GA GU HI IA ID IL IN KS KY LA MA MD ME MI MN MO MS MT NC ND NE NH NJ NM NV NY OH OK OR PA PR RI SC SD TN TX UT VA VI VT WA WI WV WY All/Any 2026 Phoenix, AZ 2025 Columbus, OH 2024 Los Angeles, CA 2023 Dallas, TX 2022 Atlanta, GA 2021 Virtual ISEF 2020 Virtual ISEF 2019 Phoenix, AZ 2018 Pittsburgh, PA 2017 Los Angeles, CA 2016 Phoenix, AZ 2015 Pittsburgh, PA 2014 Los Angeles, CA Abstracts to Display All Abstracts Matching Criteria Only Winning Abstracts Society for Science Society for Science (Society) is a champion for science, dedicated to
                    expanding scientific literacy, effective STEM education and scientific research. We are a
                    nonprofit 501(c)(3) membership organization focused on promoting the understanding and
                    appreciation of science and the vital role it plays in human advancement: to inform, educate, and inspire. Since 1921, the Society (formerly known as Science Service) has conveyed the excitement of science and research directly to
                    the public through our award-winning publications and world-class science education competitions. About Science News Explores Science News Society for Science Society Staff Careers Rights and Permissions Join the Society Become a Member Gift Memberships Renew Donate Sponsor 1.106+2d427fcfaa2a7d7e53a6188d34dcbe579d59d417 © Society for Science 1776 Massachusetts Ave NW, Washington, DC 20036 202-785-2255 Contact Us Legal/Privacy Policy
```
