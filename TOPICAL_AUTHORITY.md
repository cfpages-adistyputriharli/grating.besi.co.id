# Topical Authority — grating.besi.co.id

## Role and boundary

`grating.besi.co.id` is a Syamsul-owned product subdomain for steel grating used in industrial, building, infrastructure, and architectural projects in Indonesia. Its useful role is to help owners, engineers, contractors, procurement teams, fabricators, installers, and maintenance teams understand, specify, compare, buy, install, inspect, and maintain grating systems.

The site may independently cover subjects that also appear on `besi.co.id` or another owned domain; cross-domain overlap is not cannibalization. Within this domain, one page must own each primary intent. Existing product routes remain commercial landing pages. The authority catalog is non-geographic: it does not reproduce city, regency, province, or area-swapped sales pages.

This plan is editorial architecture, not an engineering approval. Load capacity, span, connection details, slip resistance, corrosion protection, fire behavior, accessibility, fabrication acceptance, and worker safety require current project criteria, primary standards, verified manufacturer data, calculations, and competent professional review before publication or use.

## Evidence audited

- Canonical repository: `cfpages-adistyputriharli/grating.besi.co.id`, branch `main`.
- Repository state before editing: clean and aligned with `origin/main`.
- Static WordPress export containing 2,715 tracked files: 1,934 HTML, 23 XML, and one pre-existing Markdown file.
- Sitemap evidence: `sitemap_index.xml` references eight post sitemaps and one page sitemap; the post sitemaps contain 1,471 URL entries, the page sitemap contains seven, and `sitemap-complete.xml` records 1,770 URLs. Archive routes account for the difference between editorial-looking URLs and the larger complete sitemap.
- Root HTML: 1,481 files. Of these, 1,480 are geography-oriented sales templates: 498 `jual-i-shape-*` routes, 491 `jual-plain-grating-*` routes, and 491 `jual-serrated-grating-*` routes. Seven I-shape slugs are duplicate-location variants with a `-2` suffix.
- Product/commercial pages inspected: `/`, `/i-shape/`, `/plain-grating/`, `/serrated-grating/`, `/tentang/`, `/jangkauan/`, and `/kontak/`.
- Archive/utility evidence: 296 category HTML files, 147 HTML files under the legacy `/sample-page/` tree, and the remaining author, feed, comment, 404, `hello-world`, and WordPress support routes.
- Existing messages include galvanized and stainless availability, custom sizes, delivery across Indonesia, “factory price” language, and a distributor-since-2012 claim. These are repository claims, not independently verified facts.
- Existing product coverage introduces I-shape, plain, and serrated grating, basic applications, size/price tables, and a plain-versus-serrated comparison. It does not yet provide a systematic specification, design, quality, installation, or lifecycle knowledge base.

## Existing coverage and risks

| Existing URL/pattern | Observed role/problem | Decision | Destination/owner | Verification needed |
|---|---|---|---|---|
| `/` | Commercial overview and product navigation; broad quality, price, material, and delivery claims | expand | Commercial overview linked to GRT-01, GRT-02, GRT-10, and GRT-11 hubs | Verify stock, material, custom-size, delivery, price, and project claims |
| `/i-shape/` | I-shape product landing page with definition, coating, size/price, and application sections | keep | Commercial I-shape route; neutral selection intent belongs to GRT-02-04 | Verify profile geometry, material, dimensions, coating, load data, and current offer |
| `/plain-grating/` | Plain grating landing page mixing product, comparison, size/price, and application intent | keep | Commercial plain route; neutral comparison belongs to GRT-02-02 and GRT-06-01 | Verify dimensions, material, finish, availability, and prices |
| `/serrated-grating/` | Serrated grating landing page emphasizing anti-slip use | keep | Commercial serrated route; neutral surface selection belongs to GRT-02-03 and GRT-06-01 | Verify tested slip-performance evidence and avoid universal “anti-slip” claims |
| `/tentang/` | Company history and supplier claims | expand | Company evidence page | Verify identity, operating history, facilities, team, certifications, and project evidence |
| `/jangkauan/` | National service-area directory | manual review | One factual service-area page, not thousands of thin location pages | Verify actual dispatch origins, service constraints, lead times, and covered areas |
| `/jual-i-shape-*.html` | 498 geography templates, including seven duplicate `-2` variants | manual review | Consolidate useful equity toward `/i-shape/` or a genuinely evidenced service-area route | GSC impressions, backlinks, indexation, uniqueness, conversions, and redirect mapping |
| `/jual-plain-grating-*.html` | 491 geography templates with substantially repeated intent | manual review | Consolidate useful equity toward `/plain-grating/` or evidenced service-area content | GSC, backlinks, local evidence, conversions, and redirect mapping |
| `/jual-serrated-grating-*.html` | 491 geography templates with substantially repeated intent | manual review | Consolidate useful equity toward `/serrated-grating/` or evidenced service-area content | GSC, backlinks, local evidence, conversions, and redirect mapping |
| `/category/**` | 296 archive and pagination HTML pages; not independent editorial coverage | noindex | Keep navigation archives only when useful to users | Canonical, indexation, pagination, crawl demand, and internal-link value |
| `/sample-page/**` | 147 legacy-export HTML files under a generic WordPress route | manual review | Redirect useful history to the real owner or remove/noindex dead output | Route contents, backlinks, indexation, and whether any page is intentionally linked |
| `/hello-world/`, `/author/`, `/feed/`, `/comments/`, `/404/` | Default, utility, or archive output | noindex | Utility behavior only | HTTP status, canonical, feed need, links, and indexation |
| Sitemap family | `sitemap-complete.xml` lists 1,770 URLs while child content sitemaps total 1,478 entries | manual review | One canonical sitemap index containing only intended canonical URLs | Live sitemap binding, duplicate sitemap submissions, status codes, canonicals, and noindex consistency |

No bulk deletion, redirect, or noindex action should be performed solely from this audit. Preserve useful history and use live GSC, backlink, conversion, canonical, and response-status evidence to decide URL by URL or pattern by pattern.

## Coverage matrix

| Completeness lens | Topic owners | Coverage decision |
|---|---|---|
| Definition, vocabulary, history, and measurement | GRT-01, GRT-04 | Explain the system and specification language before selection |
| Taxonomy, profiles, and variants | GRT-02 | Plain, serrated, I-shape, press-locked/welded terminology, and non-steel alternatives are separated by decision |
| Anatomy, components, and interfaces | GRT-01, GRT-09 | Bearing bars, cross bars, banding, supports, clips, cut-outs, and adjacent structure |
| Materials, properties, mechanisms, and protection | GRT-03, GRT-06, GRT-08 | Material, drainage, traction, corrosion, heat, and chemical exposure |
| Need recognition, survey, requirements, and design | GRT-05, GRT-07, GRT-08 | Translate use, span, traffic, environment, and hazards into a design brief |
| Comparison and selection | GRT-02, GRT-03, GRT-06, GRT-07 | Distinct choices by profile, material, surface, and application |
| Budget, quantity, and procurement | GRT-10, GRT-11 | Take-off, cost drivers, RFQ, bid comparison, supplier evidence, and substitutions |
| Preparation, fabrication, and quality | GRT-09, GRT-12 | Detailing, shop drawings, cutting, welding, coating, tolerances, and release |
| Logistics, installation, and handover | GRT-13 | Packing, lifting, storage, installation sequence, inspection, and records |
| Use, inspection, and maintenance | GRT-14 | Safe observation, cleaning, fastener checks, coating care, and maintenance records |
| Troubleshooting, repair, replacement, and end of life | GRT-15 | Symptom-led diagnosis, repair boundaries, replacement, reuse, and recycling |
| Stakeholders and site types | GRT-05, GRT-07, GRT-11, GRT-13 | Owner, designer, buyer, fabricator, installer, operator, and inspector paths |
| Climate, scale, retrofit, and quality level | GRT-05, GRT-08, GRT-09, GRT-10 | Humid/coastal/industrial exposure, spans, occupied sites, and service-life choices |
| Safety, health, failure modes, and governance | GRT-05, GRT-06, GRT-12, GRT-13, GRT-14 | Fall, trip, slip, overload, sharp-edge, lifting, hot-work, and degradation controls |
| Standards and evidence quality | GRT-04, GRT-05, GRT-11, GRT-12, GRT-16 | Verify applicable current requirements; never invent ratings or approvals |
| Environmental impact and circularity | GRT-03, GRT-08, GRT-15 | Durability, coating choices, repair, reuse, and end-of-life documentation |
| Myths and unsafe advice | GRT-06, GRT-08, GRT-14, GRT-16 | Correct universal anti-slip, zero-maintenance, coating, and visual-only acceptance claims |
| Editorial formats and search intents | GRT-01–GRT-16 | References, comparisons, calculations, checklists, diagnostics, diagrams, and commercial-support assets |
| Geography | GRT-08 only as climate/exposure science | No place-name swaps; location is material only when exposure or evidence changes substance |
| News and trends | N/A | Not a stable parent topic; material standards or product changes should update evergreen owner pages |
| Fabricated case studies | N/A | Publish only when real project records, permissions, measurements, and outcomes exist |

## Topical map

| Topic ID | Parent topic | Reader outcome | Required subtopics/questions | Evidence/formats | Boundary | Article target |
|---|---|---|---|---|---|---:|
| GRT-01 | Grating fundamentals and vocabulary | Recognize grating anatomy, functions, language, and system boundaries | What grating is and is not; bearing bar; cross bar; banding; panel; open area; span direction; support; clip; toe plate; stair tread; trench cover; common Indonesian and English terms | Labeled diagrams, glossary, annotated photos, sourced explanation | Fundamentals only; product choice belongs to GRT-02, dimensions to GRT-04, and structural adequacy to GRT-05 | 6 |
| GRT-02 | Types, profiles, and configurations | Choose the appropriate grating family without treating names as interchangeable | Plain versus serrated; I-shape; welded versus press-locked terminology; close mesh; heavy-duty configuration; steel versus alternative systems; profile identification | Decision tables, cross-section diagrams, manufacturer comparison, samples | Type classification only; material/finish belongs to GRT-03, traction to GRT-06, and application systems to GRT-07 | 6 |
| GRT-03 | Materials and protective finishes | Match substrate and finish to service conditions and evidence requirements | Carbon steel; hot-dip galvanizing; stainless grades; painted systems; raw steel; aluminum/FRP comparison; coating repair; finish documentation | Material data, coating records, decision matrix, expert review | Material and finish choice only; corrosion exposure diagnosis belongs to GRT-08 and fabrication QC to GRT-12 | 6 |
| GRT-04 | Dimensions, tolerances, and specification reading | Decode schedules and create unambiguous product descriptions | Bearing-bar size; pitch; cross-bar spacing; panel dimensions; banding; orientation; open area; mass; tolerances; drawings; unit conventions; sample specification | Annotated schedule, measurement diagrams, worked examples, checklist | Describes and measures geometry; load capacity belongs to GRT-05 and quantity take-off to GRT-10 | 6 |
| GRT-05 | Loads, spans, deflection, and structural design | Know what information a competent designer needs and where simplified rules stop | Load types; pedestrian and wheeled traffic; concentrated loads; clear span; bearing direction; deflection/serviceability; supports; openings; dynamic effects; design responsibility; retrofit survey | Calculation framework, load-path diagrams, engineer review, data-sheet checklist | Educational design framework only; no universal capacity table or engineering approval; application layout belongs to GRT-07 | 6 |
| GRT-06 | Walking surface, drainage, and human factors | Select surface geometry around slip, trip, drainage, comfort, and accessibility risks | Plain/serrated traction; wet/oily contamination; footwear; heel-safe mesh; small-object passage; drainage; debris; glare; noise; vibration; bicycle/wheel/animal considerations; testing limits | Hazard matrix, test-method review, site checklist, diagrams | Human-factor performance only; structural loads belong to GRT-05 and environmental corrosion to GRT-08 | 6 |
| GRT-07 | Application and system selection | Translate a use case into the right grating system and surrounding details | Walkways/platforms; stairs/landings; trenches/drains; machine access; mezzanines; façades/screens; industrial plants; public/commercial access; roof and service access | Application decision trees, detail diagrams, photo checklist, expert review | Application-level configuration only; calculations belong to GRT-05, interfaces to GRT-09, and installation to GRT-13 | 6 |
| GRT-08 | Exposure, corrosion, and service environment | Identify environmental threats and define a protection/inspection strategy | Indoor/outdoor; humid/rainy; coastal salt; chemical splash; immersion; heat; fire assumptions; galvanic contact; crevices; drainage traps; pollution; service-life planning | Exposure survey, corrosion map, material/coating evidence, specialist review | Exposure assessment only; initial material choice belongs to GRT-03 and maintenance response to GRT-14 | 6 |
| GRT-09 | Detailing, supports, fixings, and interfaces | Produce coordinated details that fit, drain, restrain, and remain serviceable | Bearing seat; edge clearances; clips; welded fixing; removable panels; banding; toe plates; kick plates; handrail interfaces; cut-outs; penetrations; adjacent concrete/steel; expansion and tolerances | Detail library, shop-drawing checklist, mock-up photos, designer review | Connection/detail intent only; structural verification belongs to GRT-05 and field installation procedure to GRT-13 | 6 |
| GRT-10 | Quantity take-off, cost drivers, and planning | Estimate scope transparently without pretending to provide a universal price | Net/gross area; panelization; waste; cut-outs; clips; banding; finish; fabrication; drawings; testing; packing; freight; installation; maintenance and lifecycle cost | Take-off worksheet, cost-breakdown table, worked example, assumptions log | Quantity and cost structure only; current quotation belongs to `/kontak/` and supplier evaluation to GRT-11 | 6 |
| GRT-11 | Procurement, supplier evidence, and substitutions | Issue a clear RFQ and compare offers on equivalent scope and proof | RFQ inputs; bid normalization; datasheets; material certificates; coating records; load tables; sample/mock-up; deviations; warranty; lead time; substitutions; traceability; counterfeit/mislabel risks | RFQ template, bid matrix, document register, audit checklist | Buyer governance only; technical design remains GRT-05 and manufacturing inspection remains GRT-12 | 6 |
| GRT-12 | Fabrication, coating, and quality control | Understand production stages, acceptance evidence, and defect escalation | Cutting; punching; welding/locking; distortion; banding; drainage/venting for coating; galvanizing sequence; coating damage; dimensional checks; weld/finish inspection; nonconformance; traceability | Process map, inspection-and-test plan, defect photos, qualified expert review | Shop production and release only; design details belong to GRT-09 and site installation to GRT-13 | 6 |
| GRT-13 | Logistics, installation, and handover | Plan safe delivery, storage, lifting, placement, fixing, and acceptance | Packing; transport; unloading; storage; lifting points; temporary restraint; work at height; cut edges; hot work; sequence; fit-up; fasteners; punch list; as-built and maintenance records | Method-statement outline, lifting/site checklist, handover register, safety review | Site execution only; product manufacture belongs to GRT-12 and routine maintenance to GRT-14 | 6 |
| GRT-14 | Inspection, cleaning, and preventive maintenance | Establish risk-based checks and respond before degradation becomes unsafe | Baseline; inspection frequency; loose clips; corrosion; coating damage; deformation; blocked openings; contamination; cleaning methods; records; restricted access; escalation thresholds | Inspection form, defect atlas, maintenance matrix, competent-person review | Routine observation and care only; diagnosis/repair decisions belong to GRT-15 and hazardous work to qualified specialists | 6 |
| GRT-15 | Failure diagnosis, repair, replacement, and end of life | Diagnose visible symptoms, choose escalation paths, and document repair or replacement | Rattle; movement; deflection; cracks; broken welds; bent bars; sharp edges; rust; coating loss; poor fit; recurring slip; temporary controls; repair versus replace; reuse/recycling | Symptom tree, stop-use matrix, repair decision table, expert review | Decision support, not DIY structural repair; prevention belongs to GRT-14 and original design to GRT-05 | 6 |
| GRT-16 | Claims, documentation, and project proof | Publish defensible technical and commercial information without invented certainty | Reading certificates; data-sheet limits; “anti-slip”; “SNI”; “stainless”; “galvanized”; load claims; factory-price claims; warranty language; project case requirements; photo provenance; update dates | Claim-evidence matrix, editorial checklist, document examples, expert/legal review | Evidence governance only; product sales remain existing commercial routes and procurement workflow belongs to GRT-11 | 6 |

## Related-domain opportunities

- `besi.co.id` can remain a broad steel-product reference and link contextually to this specialist domain; both domains may independently explain steel properties when useful.
- `konstruksi.besi.co.id` can approach supporting steelwork and construction coordination from a broader structural/fabrication perspective.
- `kawat.besi.co.id` can cover mesh and wire products that buyers may confuse with grating; cross-domain comparison should clarify entities rather than suppress either site.
- `plat.besi.co.id` can explain plate and chequered-plate alternatives for closed walking surfaces.
- `galvalume.id`, `steel.id`, and fabrication-oriented owned projects can later contribute material or process perspectives when canonical repositories exist.
- Cross-domain links must be editorially useful and transparent. They must not become a disguised sitewide link network or substitute for strong content and real evidence.

## Consolidation plan

1. Preserve `/i-shape/`, `/plain-grating/`, and `/serrated-grating/` as commercial/product owners. Remove neutral comparison and educational ambiguity by linking to the GRT-02 and GRT-06 knowledge assets.
2. Inventory every `jual-*-<location>` URL with GSC clicks/impressions, backlinks, conversions, canonical, indexation, content similarity, and any genuine local evidence.
3. Keep a local URL only when its substance is demonstrably local. For repeated templates, select the most relevant product or verified service-area owner, map redirects carefully, and monitor query loss and soft-404 behavior.
4. Resolve seven duplicate I-shape `-2` routes after checking which version has signals. Do not leave both indexable.
5. Noindex thin category, author, pagination, feed, comment, and default WordPress output when it has no standalone search value; retain crawlable navigation where useful.
6. Audit `/sample-page/**` before removal because its 147 exported HTML files may include hidden legacy paths or assets.
7. Publish one canonical sitemap index containing only canonical, indexable URLs. Do not submit both duplicate sitemap indexes or include redirected/noindexed/error URLs.
8. Add planned knowledge pages only after route ownership and URL policy are defined, so new articles do not inherit existing archive and template duplication.

## Internal-link architecture

- Create a central “Panduan Grating Besi” hub for GRT-01-01 and link all 16 parent hubs from it.
- Every child article links to its parent hub; every hub links to all six children and to the adjacent lifecycle hub.
- Selection path: GRT-01 fundamentals → GRT-02 type → GRT-03 material → GRT-04 specification → GRT-05 design → GRT-07 application.
- Delivery path: GRT-09 detailing → GRT-10 take-off → GRT-11 procurement → GRT-12 fabrication → GRT-13 installation.
- Ownership path: GRT-14 inspection → GRT-15 diagnosis/repair → GRT-16 evidence and records.
- Hazard pages link to prevention, stop-use criteria, professional review, and the specific owner page; they must not funnel readers directly to a quote without safety context.
- Commercial pages receive contextual links from selection, quantity, RFQ, and evidence pages only. They do not replace neutral references.
- Related links in `ARTICLE_CATALOG.md` are starting relationships, not a fixed widget copied onto every page.

## Evidence and editorial standards

- Use current primary standards, project specifications, manufacturer data, test reports, certificates, engineering calculations, and qualified expert review where the claim requires them.
- Identify the exact product, material, finish, dimensions, span, support, load case, environment, and test method behind any performance number. Never transfer a value from a different configuration.
- Do not claim universal slip resistance, corrosion immunity, maintenance-free life, fire performance, accessibility, SNI compliance, load capacity, or warranty.
- Treat repository claims such as galvanized/stainless availability, custom sizes, delivery reach, “factory price,” quality superlatives, and operating since 2012 as unverified until documentary evidence is attached.
- Separate sourced explanation, project-specific professional advice, editorial hypothesis, and commercial offer.
- Commission original diagrams and photography when possible. Record image provenance, product identity, scale, date, and permission; never present stock imagery as a completed project.
- Case studies require real constraints, approved records, methods, changes, measured outcomes, permissions, and limitations. Otherwise publish a labeled hypothetical worked example.
- Give all safety content stop conditions: damaged/unstable panels, suspected overload, unsafe access, work at height, lifting, welding, grinding, coating chemicals, and structural repair require competent controls.
- Review standards, products, contacts, availability, claims, and commercial details at a recorded interval and when a material change occurs.

## First bounded publication cluster

Publish 12 connected assets before scaling:

1. GRT-01-01 — central grating system guide.
2. GRT-01-02 — anatomy diagram.
3. GRT-02-02 — plain versus serrated decision guide.
4. GRT-02-04 — I-shape identification and selection.
5. GRT-03-02 — galvanized grating evidence guide.
6. GRT-04-01 — how to read dimensions.
7. GRT-04-06 — specification checklist.
8. GRT-05-01 — loads, span, and support inputs.
9. GRT-06-01 — surface selection around slip risk.
10. GRT-09-02 — supports and bearing details.
11. GRT-10-01 — take-off worksheet.
12. GRT-11-01 — RFQ checklist.

This cluster is coherent because it moves a buyer or designer from identifying the system through selection, specification, support coordination, quantity, and an evidence-ready inquiry. It can improve the existing product pages without publishing every cluster at once.

Monitor indexability and canonical selection, impressions grouped by distinct intent, engagement with diagrams/checklists, completed worksheet or RFQ actions, qualified inquiries with usable specifications, and GSC query/page overlap. Pause expansion when two pages begin earning the same query set or when evidence and editorial review cannot keep pace.

## Definition of done

- All 16 parent topics have six distinct briefs and the coverage ledger totals 96.
- IDs, titles, slugs, intents, coverage promises, and boundaries are unique and validated.
- Every related ID resolves; every article links to its hub and at least one contextually useful neighbor.
- Proposed slugs have no collision with the current normalized route inventory.
- No article is a city, regency, province, or geography-swapped variant.
- Existing product, archive, legacy, and location-template ownership is resolved with live evidence before redirects or indexation changes.
- Safety, structural, coating, standards, and performance claims pass competent review and carry product/project limitations.
- The first cluster is published as a connected, evidence-rich set and measured for indexation, distinct intent, task completion, qualified leads, and cannibalization before later waves.
