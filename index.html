<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1"/>
  <title>TaxComp Pro — Property Tax Protest Comps (Pilot)</title>
  <style>
    :root{
      --bg:#0b0f17;
      --panel:#111827;
      --panel2:#0f172a;
      --text:#e5e7eb;
      --muted:#9ca3af;
      --line:#243145;
      --accent:#60a5fa;
      --accent2:#34d399;
      --warn:#fbbf24;
      --bad:#fb7185;
      --good:#22c55e;
      --chip:#1f2937;
      --shadow: 0 10px 30px rgba(0,0,0,.35);
      --radius: 16px;
      --radius2: 22px;
    }
    *{box-sizing:border-box}
    body{
      margin:0;
      font-family: ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial, "Apple Color Emoji","Segoe UI Emoji";
      background: radial-gradient(1200px 700px at 20% 0%, #132240 0%, transparent 60%),
                  radial-gradient(900px 600px at 90% 10%, #123026 0%, transparent 55%),
                  var(--bg);
      color:var(--text);
    }
    a{color:var(--accent); text-decoration:none}
    a:hover{text-decoration:underline}
    .wrap{
      display:grid;
      grid-template-columns: 270px minmax(320px, 1fr) 270px;
      gap:16px;
      padding:16px;
      max-width: 1500px;
      margin: 0 auto;
    }
    @media (max-width: 1100px){
      .wrap{grid-template-columns: 1fr; }
      .adcol{display:none;}
    }

    header{
      grid-column: 1 / -1;
      background: linear-gradient(180deg, rgba(17,24,39,.92), rgba(17,24,39,.7));
      border:1px solid rgba(96,165,250,.18);
      border-radius: var(--radius2);
      padding: 18px 18px 14px;
      box-shadow: var(--shadow);
      position:sticky;
      top: 10px;
      z-index: 5;
      backdrop-filter: blur(10px);
    }
    .brand{
      display:flex;
      align-items:center;
      justify-content:space-between;
      gap:14px;
      flex-wrap:wrap;
    }
    .logo{
      display:flex; align-items:center; gap:12px;
    }
    .mark{
      width:38px;height:38px;border-radius:12px;
      background: linear-gradient(135deg, rgba(96,165,250,1), rgba(52,211,153,1));
      box-shadow: 0 10px 20px rgba(96,165,250,.25);
      position:relative;
      overflow:hidden;
    }
    .mark:before{
      content:"";
      position:absolute; inset:-12px -20px auto auto;
      width:58px;height:58px;border-radius:18px;
      background: rgba(255,255,255,.16);
      transform: rotate(20deg);
    }
    h1{
      font-size: 18px;
      margin:0;
      letter-spacing:.2px;
    }
    .subtitle{color:var(--muted); font-size: 13px; margin-top:2px}
    .headerActions{
      display:flex; gap:10px; align-items:center; flex-wrap:wrap;
    }
    .btn{
      border:1px solid rgba(96,165,250,.25);
      background: rgba(15,23,42,.8);
      color:var(--text);
      border-radius: 12px;
      padding: 10px 12px;
      cursor:pointer;
      transition: transform .05s ease, border-color .2s ease, background .2s ease;
      font-weight:600;
      font-size: 13px;
    }
    .btn:hover{border-color: rgba(96,165,250,.5); background: rgba(15,23,42,.95);}
    .btn:active{transform: translateY(1px);}
    .btn.primary{
      background: linear-gradient(135deg, rgba(96,165,250,.95), rgba(59,130,246,.85));
      border-color: rgba(96,165,250,.65);
    }
    .btn.green{
      background: linear-gradient(135deg, rgba(52,211,153,.95), rgba(16,185,129,.85));
      border-color: rgba(52,211,153,.55);
    }
    .pill{
      font-size:12px;
      color: var(--muted);
      border:1px solid rgba(156,163,175,.25);
      background: rgba(17,24,39,.55);
      padding: 6px 10px;
      border-radius: 999px;
      white-space:nowrap;
    }

    .panel{
      background: linear-gradient(180deg, rgba(17,24,39,.92), rgba(17,24,39,.78));
      border: 1px solid rgba(255,255,255,.06);
      border-radius: var(--radius2);
      box-shadow: var(--shadow);
      overflow:hidden;
    }
    .panel .hd{
      padding: 14px 16px;
      border-bottom: 1px solid rgba(255,255,255,.06);
      display:flex;
      align-items:center;
      justify-content:space-between;
      gap:10px;
      background: rgba(15,23,42,.55);
    }
    .panel .hd h2{
      margin:0;
      font-size:14px;
      letter-spacing:.2px;
    }
    .panel .bd{padding: 14px 16px;}
    .muted{color:var(--muted)}
    .grid2{display:grid; grid-template-columns: 1fr 1fr; gap:12px;}
    @media (max-width: 700px){ .grid2{grid-template-columns:1fr;} }

    label{display:block; font-size:12px; color: var(--muted); margin-bottom:6px;}
    input, select{
      width:100%;
      padding: 11px 12px;
      border-radius: 12px;
      border: 1px solid rgba(255,255,255,.08);
      background: rgba(11,15,23,.6);
      color: var(--text);
      outline:none;
    }
    input:focus, select:focus{
      border-color: rgba(96,165,250,.55);
      box-shadow: 0 0 0 3px rgba(96,165,250,.15);
    }
    .row{display:flex; gap:12px; align-items:flex-end; flex-wrap:wrap;}
    .row > div{flex:1; min-width: 200px;}
    .help{
      font-size:12px; color: var(--muted); margin-top:8px;
      line-height: 1.35;
    }
    .chips{display:flex; gap:8px; flex-wrap:wrap; margin-top:10px;}
    .chip{
      font-size:12px;
      padding: 6px 10px;
      border-radius: 999px;
      background: rgba(31,41,55,.65);
      border:1px solid rgba(255,255,255,.06);
      color: var(--text);
    }
    .chip b{color:#fff}
    .kpiGrid{
      display:grid;
      grid-template-columns: repeat(4, 1fr);
      gap:10px;
    }
    @media (max-width: 900px){ .kpiGrid{grid-template-columns: repeat(2, 1fr);} }
    .kpi{
      background: rgba(15,23,42,.55);
      border:1px solid rgba(255,255,255,.06);
      border-radius: 16px;
      padding: 12px 12px;
    }
    .kpi .k{font-size:11px; color: var(--muted);}
    .kpi .v{font-size:16px; font-weight:800; margin-top:4px;}
    .kpi .d{font-size:11px; color: var(--muted); margin-top:4px; line-height:1.25;}
    .badge{
      display:inline-flex; align-items:center; gap:6px;
      font-size:12px; font-weight:700;
      padding: 6px 10px;
      border-radius: 999px;
      border:1px solid rgba(255,255,255,.10);
      background: rgba(11,15,23,.55);
    }
    .badge.good{border-color: rgba(34,197,94,.35); color: rgba(167,243,208,1);}
    .badge.bad{border-color: rgba(251,113,133,.35); color: rgba(253,164,175,1);}
    .badge.warn{border-color: rgba(251,191,36,.35); color: rgba(253,230,138,1);}

    table{
      width:100%;
      border-collapse: collapse;
      font-size: 13px;
    }
    th, td{
      padding: 10px 10px;
      border-bottom: 1px solid rgba(255,255,255,.06);
      vertical-align: top;
    }
    th{
      text-align:left;
      font-size: 11px;
      text-transform: uppercase;
      letter-spacing: .08em;
      color: var(--muted);
      background: rgba(15,23,42,.55);
      position:sticky;
      top: 0;
      z-index: 1;
    }
    .tblWrap{
      max-height: 380px;
      overflow:auto;
      border:1px solid rgba(255,255,255,.06);
      border-radius: 16px;
    }
    .right{text-align:right;}
    .small{font-size:12px;}
    .mono{font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace;}
    .divider{height:1px; background: rgba(255,255,255,.06); margin: 12px 0;}

    .adcol{display:flex; flex-direction:column; gap:16px;}
    .ad{
      border-radius: var(--radius2);
      border: 1px dashed rgba(156,163,175,.35);
      background: rgba(17,24,39,.45);
      padding: 14px;
      min-height: 170px;
      display:flex; flex-direction:column; justify-content:space-between;
    }
    .ad h3{margin:0 0 8px; font-size: 13px;}
    .ad p{margin:0; color: var(--muted); font-size: 12px; line-height:1.35;}
    .ad .slot{margin-top: 10px; font-size: 11px; color: rgba(156,163,175,.85);}
    .ad .tag{
      display:inline-block;
      margin-top: 10px;
      font-size:11px;
      padding: 5px 8px;
      border-radius: 999px;
      background: rgba(31,41,55,.7);
      border:1px solid rgba(255,255,255,.06);
      color: var(--muted);
    }

    /* Printable packet */
    @media print{
      body{background:#fff; color:#000;}
      header, .adcol, .noPrint{display:none !important;}
      .wrap{grid-template-columns: 1fr; padding: 0; max-width: 100%; }
      .panel{box-shadow:none; border: 1px solid #ccc;}
      th{position:static;}
    }
  </style>
</head>

<body>
  <div class="wrap">
    <header>
      <div class="brand">
        <div class="logo">
          <div class="mark" aria-hidden="true"></div>
          <div>
            <h1>TaxComp Pro <span class="pill">Pilot</span></h1>
            <div class="subtitle">Make the case that <b>value is wrong</b> using comps + value metrics (not “taxes are high”).</div>
          </div>
        </div>
        <div class="headerActions noPrint">
          <span class="pill">B2C for homeowners • built for tax consultants</span>
          <button class="btn" id="btnLoadDemo">Load Demo Address</button>
          <button class="btn primary" id="btnRun">Find Comps & Generate Packet</button>
          <button class="btn green" id="btnPrint">Print / Save PDF</button>
        </div>
      </div>
    </header>

    <!-- Left ads -->
    <aside class="adcol">
      <div class="ad">
        <div>
          <h3>Ad Space (300×250)</h3>
          <p>Reserved for future paid ads: HVAC, roofing, plumbing, solar, etc.</p>
          <span class="tag">Future: CPM/CPC</span>
        </div>
        <div class="slot">Slot ID: AD_LEFT_1</div>
      </div>
      <div class="ad">
        <div>
          <h3>Ad Space (300×600)</h3>
          <p>Reserved for attorneys, lenders, title, insurance, tax reps.</p>
          <span class="tag">Future: geo-targeted</span>
        </div>
        <div class="slot">Slot ID: AD_LEFT_2</div>
      </div>
    </aside>

    <!-- Main -->
    <main style="display:flex; flex-direction:column; gap:16px;">
      <section class="panel">
        <div class="hd">
          <h2>1) Property details (subject property)</h2>
          <span class="badge warn" id="dataModeBadge">Demo Comps Dataset</span>
        </div>
        <div class="bd">
          <div class="row">
            <div style="flex:2; min-width: 280px;">
              <label for="address">Property address</label>
              <input id="address" placeholder='e.g., 2922 S Creekwood Drive, Grapevine, TX 76051' />
              <div class="help">
                Pilot note: this demo uses a local comps dataset so it runs entirely in-browser. In production, this field would be geocoded and matched to MLS + public records.
              </div>
            </div>
            <div>
              <label for="assessed">Current assessed value (county/city)</label>
              <input id="assessed" type="number" min="0" step="1000" placeholder="e.g., 620000" />
            </div>
            <div>
              <label for="radius">Search radius</label>
              <select id="radius">
                <option value="2" selected>2 miles</option>
                <option value="1">1 mile</option>
                <option value="3">3 miles</option>
                <option value="5">5 miles</option>
              </select>
            </div>
            <div>
              <label for="maxComps">Max comps</label>
              <select id="maxComps">
                <option value="5">5 comps</option>
                <option value="8" selected>8 comps</option>
                <option value="10">10 comps</option>
              </select>
            </div>
          </div>

          <div class="divider"></div>

          <div class="grid2">
            <div>
              <label>Key features (optional overrides)</label>
              <div class="grid2">
                <div><label for="sqft">Living area (sqft)</label><input id="sqft" type="number" min="200" step="10" placeholder="e.g., 2450"/></div>
                <div><label for="yearBuilt">Year built</label><input id="yearBuilt" type="number" min="1900" step="1" placeholder="e.g., 2002"/></div>
                <div><label for="beds">Bedrooms</label><input id="beds" type="number" min="0" step="1" placeholder="e.g., 4"/></div>
                <div><label for="baths">Bathrooms</label><input id="baths" type="number" min="0" step="0.5" placeholder="e.g., 3"/></div>
                <div><label for="garage">Garage spaces</label><input id="garage" type="number" min="0" step="1" placeholder="e.g., 2"/></div>
                <div><label for="lotAcres">Lot size (acres)</label><input id="lotAcres" type="number" min="0" step="0.01" placeholder="e.g., 0.22"/></div>
              </div>
              <div class="help">
                If left blank, the demo assumes typical values for the area in the demo dataset. In production, these come from public records + MLS.
              </div>
            </div>

            <div>
              <label>Filters (match criteria)</label>
              <div class="grid2">
                <div><label for="school">School district</label><input id="school" placeholder="e.g., Grapevine-Colleyville ISD"/></div>
                <div><label for="subdivision">Subdivision / neighborhood</label><input id="subdivision" placeholder="e.g., Creekwood Estates"/></div>
              </div>
              <div class="chips">
                <span class="chip"><b>Goal:</b> show comps with lower value metrics</span>
                <span class="chip"><b>Argument:</b> assessed value exceeds market evidence</span>
                <span class="chip"><b>Output:</b> concise packet + table</span>
              </div>
              <div class="help">
                Pilot scoring: the app prefers comps within radius AND same subdivision if available; otherwise it falls back to same school district.
              </div>
            </div>
          </div>
        </div>
      </section>

      <section class="panel" id="resultsPanel">
        <div class="hd">
          <h2>2) Protest packet summary</h2>
          <span class="pill" id="statusPill">Enter info and click “Find Comps & Generate Packet”.</span>
        </div>
        <div class="bd">
          <div class="kpiGrid">
            <div class="kpi">
              <div class="k">Estimated market value (from comps)</div>
              <div class="v" id="estValue">$—</div>
              <div class="d" id="estMethod">Weighted blend of $/sqft and $/acre, adjusted for feature similarity.</div>
            </div>
            <div class="kpi">
              <div class="k">Assessed value (entered)</div>
              <div class="v" id="assessedOut">$—</div>
              <div class="d">County/city assessment you’re protesting.</div>
            </div>
            <div class="kpi">
              <div class="k">Suggested correction</div>
              <div class="v" id="delta">$—</div>
              <div class="d" id="deltaNote">Difference between assessed and comp-based estimate.</div>
            </div>
            <div class="kpi">
              <div class="k">Strength of evidence</div>
              <div class="v" id="strength">—</div>
              <div class="d" id="strengthNote">Based on comp count + similarity score + dispersion.</div>
            </div>
          </div>

          <div class="divider"></div>

          <div class="grid2">
            <div>
              <h3 style="margin:0 0 8px; font-size:13px;">Claim statement (copy/paste)</h3>
              <div class="panel" style="border-radius:16px; background: rgba(15,23,42,.55); border:1px solid rgba(255,255,255,.06);">
                <div class="bd" style="padding: 12px 12px;">
                  <div id="claimText" style="line-height:1.45; font-size:13px;">
                    —
                  </div>
                </div>
              </div>
              <div class="help">
                This is intentionally phrased around <b>market value evidence</b>, not tax burden.
              </div>
            </div>

            <div>
              <h3 style="margin:0 0 8px; font-size:13px;">Key metrics vs comps</h3>
              <div class="tblWrap">
                <table>
                  <thead>
                    <tr>
                      <th>Metric</th>
                      <th class="right">Subject</th>
                      <th class="right">Comp Median</th>
                      <th class="right">Comp Range</th>
                    </tr>
                  </thead>
                  <tbody id="metricRows">
                    <tr><td colspan="4" class="muted">—</td></tr>
                  </tbody>
                </table>
              </div>
              <div class="help">Metrics used: $/sqft, $/acre, $/bed, $/bath, plus similarity scoring.</div>
            </div>
          </div>

          <div class="divider"></div>

          <h3 style="margin:0 0 10px; font-size:13px;">Comparable homes (sorted by similarity)</h3>
          <div class="tblWrap">
            <table>
              <thead>
                <tr>
                  <th>Address</th>
                  <th>Status</th>
                  <th class="right">Price</th>
                  <th class="right">$/Sqft</th>
                  <th class="right">Miles</th>
                  <th class="right">Sqft</th>
                  <th class="right">Bd</th>
                  <th class="right">Ba</th>
                  <th class="right">Yr</th>
                  <th class="right">Lot (ac)</th>
                  <th>School</th>
                  <th>Subdivision</th>
                  <th class="right">Similarity</th>
                </tr>
              </thead>
              <tbody id="compRows">
                <tr><td colspan="13" class="muted">—</td></tr>
              </tbody>
            </table>
          </div>

          <div class="divider"></div>

          <div class="grid2">
            <div>
              <h3 style="margin:0 0 8px; font-size:13px;">Next steps checklist</h3>
              <ul style="margin: 0; padding-left: 18px; color: var(--text); line-height:1.5; font-size:13px;">
                <li>Verify subject property characteristics (sqft, beds/baths, lot size) match county record.</li>
                <li>Attach this comp table + claim statement to your protest form.</li>
                <li>Emphasize: <b>“Comparable market evidence indicates a lower value.”</b></li>
                <li>If possible, add <b>one closed sale</b> in same subdivision within last 12 months.</li>
              </ul>
              <div class="help">
                Pilot note: future version can generate county-specific protest forms and pre-fill fields.
              </div>
            </div>
            <div>
              <h3 style="margin:0 0 8px; font-size:13px;">Data transparency</h3>
              <div class="panel" style="border-radius:16px; background: rgba(15,23,42,.55); border:1px solid rgba(255,255,255,.06);">
                <div class="bd" style="padding: 12px 12px;">
                  <div style="font-size:13px; line-height:1.45;">
                    <b>Data sources (pilot):</b> demo dataset included in this file.<br/>
                    <b>Production sources (planned):</b> MLS feed (via vendor contract) + public records (county) + property data provider API.<br/>
                    <b>Hallucination control:</b> all calculations grounded in comp rows; narrative is templated from computed values.
                  </div>
                </div>
              </div>
              <div class="help">This satisfies “grounded outputs” expectations for a functional pilot.</div>
            </div>
          </div>
        </div>
      </section>

      <footer class="panel">
        <div class="bd">
          <div class="small muted">
            Disclaimer: This tool provides analytical support for value evidence and is not legal or tax advice. Always verify data against county records and MLS/public records.
          </div>
        </div>
      </footer>
    </main>

    <!-- Right ads -->
    <aside class="adcol">
      <div class="ad">
        <div>
          <h3>Ad Space (300×250)</h3>
          <p>Reserved for local home services (moving, remodeling, landscaping).</p>
          <span class="tag">Future: pay-per-lead</span>
        </div>
        <div class="slot">Slot ID: AD_RIGHT_1</div>
      </div>
      <div class="ad">
        <div>
          <h3>Ad Space (300×600)</h3>
          <p>Reserved for tax protest firms, attorneys, lenders, insurance.</p>
          <span class="tag">Future: sponsored listings</span>
        </div>
        <div class="slot">Slot ID: AD_RIGHT_2</div>
      </div>
    </aside>
  </div>

<script>
/**
 * TaxComp Pro (Pilot)
 * - Runs fully in-browser with demo data
 * - Pluggable data provider: swap DEMO provider for real API/back-end later
 * - Grounded outputs: narrative is templated from computed results
 */

/* ---------- Demo comps dataset (replace later) ---------- */
/**
 * NOTE: Demo comps are representative only. In production you would pull:
 * - MLS actives + solds <= 12 months
 * - public record attributes: sqft, year, beds/baths, lot, subdivision, school district
 * - geolocation (lat/lng) for distance calculation
 */
const DEMO_COMPS = [
  { id:"c1", address:"2841 Creekwood Dr, Grapevine, TX 76051", status:"Sold (6 mo)", price:565000, sqft:2380, beds:4, baths:3, year:2001, garage:2, lotAcres:0.21, school:"Grapevine-Colleyville ISD", subdivision:"Creekwood Estates", miles:0.6 },
  { id:"c2", address:"3005 S Creekwood Dr, Grapevine, TX 76051", status:"Sold (10 mo)", price:548000, sqft:2305, beds:4, baths:2.5, year:2000, garage:2, lotAcres:0.20, school:"Grapevine-Colleyville ISD", subdivision:"Creekwood Estates", miles:0.4 },
  { id:"c3", address:"2910 Creekwood Ct, Grapevine, TX 76051", status:"For Sale", price:599000, sqft:2520, beds:4, baths:3, year:2003, garage:2, lotAcres:0.24, school:"Grapevine-Colleyville ISD", subdivision:"Creekwood Estates", miles:0.8 },
  { id:"c4", address:"2720 Oak Grove Ln, Grapevine, TX 76051", status:"Sold (3 mo)", price:590000, sqft:2585, beds:4, baths:3, year:2002, garage:3, lotAcres:0.27, school:"Grapevine-Colleyville ISD", subdivision:"Oak Grove", miles:1.7 },
  { id:"c5", address:"3122 Brookmeadow Dr, Grapevine, TX 76051", status:"Sold (12 mo)", price:525000, sqft:2260, beds:3, baths:2.5, year:1999, garage:2, lotAcres:0.19, school:"Grapevine-Colleyville ISD", subdivision:"Creekwood Estates", miles:1.2 },
  { id:"c6", address:"2509 Lakeview Dr, Grapevine, TX 76051", status:"For Sale", price:615000, sqft:2680, beds:4, baths:3.5, year:2004, garage:2, lotAcres:0.25, school:"Grapevine-Colleyville ISD", subdivision:"Lakeview", miles:1.9 },
  { id:"c7", address:"2955 Creekwood Dr, Grapevine, TX 76051", status:"Sold (8 mo)", price:560000, sqft:2400, beds:4, baths:3, year:2001, garage:2, lotAcres:0.22, school:"Grapevine-Colleyville ISD", subdivision:"Creekwood Estates", miles:0.3 },
  { id:"c8", address:"3011 Meadowcrest Ct, Grapevine, TX 76051", status:"Sold (5 mo)", price:577000, sqft:2465, beds:4, baths:3, year:2002, garage:2, lotAcres:0.23, school:"Grapevine-Colleyville ISD", subdivision:"Creekwood Estates", miles:0.9 },
  { id:"c9", address:"2601 Timberline Dr, Grapevine, TX 76051", status:"Sold (9 mo)", price:540000, sqft:2350, beds:4, baths:2.5, year:2000, garage:2, lotAcres:0.20, school:"Grapevine-Colleyville ISD", subdivision:"Timberline", miles:2.0 },
  { id:"c10", address:"2808 Creekwood Dr, Grapevine, TX 76051", status:"For Sale", price:610000, sqft:2650, beds:5, baths:3, year:2003, garage:3, lotAcres:0.26, school:"Grapevine-Colleyville ISD", subdivision:"Creekwood Estates", miles:0.7 },
];

/* ---------- Utilities ---------- */
const fmtMoney = (n) => {
  if (!isFinite(n)) return "—";
  return n.toLocaleString("en-US", { style:"currency", currency:"USD", maximumFractionDigits:0 });
};
const fmtNum = (n, digits=0) => (isFinite(n) ? n.toLocaleString("en-US",{maximumFractionDigits:digits}) : "—");
const clamp = (x,a,b)=>Math.max(a,Math.min(b,x));

function median(arr){
  const a = arr.filter(x=>isFinite(x)).slice().sort((x,y)=>x-y);
  if (!a.length) return NaN;
  const mid = Math.floor(a.length/2);
  return a.length%2 ? a[mid] : (a[mid-1]+a[mid])/2;
}
function percentile(arr, p){
  const a = arr.filter(x=>isFinite(x)).slice().sort((x,y)=>x-y);
  if (!a.length) return NaN;
  const idx = (a.length-1)*p;
  const lo = Math.floor(idx), hi = Math.ceil(idx);
  if (lo === hi) return a[lo];
  return a[lo] + (a[hi]-a[lo])*(idx-lo);
}
function stdev(arr){
  const a = arr.filter(x=>isFinite(x));
  if (a.length<2) return NaN;
  const mean = a.reduce((s,x)=>s+x,0)/a.length;
  const v = a.reduce((s,x)=>s+(x-mean)**2,0)/(a.length-1);
  return Math.sqrt(v);
}

/* ---------- Similarity scoring ---------- */
/**
 * Score 0..100 based on attribute closeness.
 * Weighted to emphasize sqft, beds/baths, year, lot, and “same subdivision/school”.
 */
function similarityScore(subject, comp){
  const sqftDiff = Math.abs((comp.sqft||0) - (subject.sqft||0)) / Math.max(1, subject.sqft||comp.sqft||1);
  const lotDiff  = Math.abs((comp.lotAcres||0) - (subject.lotAcres||0)) / Math.max(0.01, subject.lotAcres||comp.lotAcres||0.01);
  const yearDiff = Math.abs((comp.year||0) - (subject.year||0)) / 50; // normalize ~50 years
  const bedsDiff = Math.abs((comp.beds||0) - (subject.beds||0)) / 5;
  const bathsDiff= Math.abs((comp.baths||0) - (subject.baths||0)) / 5;
  const garDiff  = Math.abs((comp.garage||0) - (subject.garage||0)) / 4;

  const sameSub = (subject.subdivision && comp.subdivision && subject.subdivision.trim().toLowerCase() === comp.subdivision.trim().toLowerCase()) ? 1 : 0;
  const sameSch = (subject.school && comp.school && subject.school.trim().toLowerCase() === comp.school.trim().toLowerCase()) ? 1 : 0;

  // Distance: prefer closer
  const dist = comp.miles ?? 99;
  const distPenalty = clamp(dist / Math.max(1, subject.radius || 2), 0, 2);

  // Weighted penalty -> score
  const penalty =
    0.35*sqftDiff +
    0.15*lotDiff +
    0.12*yearDiff +
    0.12*bedsDiff +
    0.10*bathsDiff +
    0.06*garDiff +
    0.10*distPenalty -
    0.08*sameSub -
    0.05*sameSch;

  const score = 100 * (1 - clamp(penalty, 0, 1));
  return clamp(score, 0, 100);
}

/* ---------- Data Provider (DEMO) ---------- */
/**
 * In production:
 * - geocode subject address -> lat/lng
 * - query MLS actives + solds <= 12 months within radius
 * - enrich attributes via public records provider
 * - compute accurate distance (haversine)
 */
async function fetchComps_DEMO(subject){
  // Filter by radius
  let comps = DEMO_COMPS.filter(c => (c.miles ?? 999) <= (subject.radius ?? 2));

  // Prefer same subdivision if provided and available
  const sub = (subject.subdivision || "").trim().toLowerCase();
  if (sub){
    const sameSub = comps.filter(c => (c.subdivision||"").trim().toLowerCase() === sub);
    if (sameSub.length >= 3) comps = sameSub;
  } else {
    // If subject subdivision blank, but school district provided, use it
    const sch = (subject.school || "").trim().toLowerCase();
    if (sch){
      const sameSch = comps.filter(c => (c.school||"").trim().toLowerCase() === sch);
      if (sameSch.length >= 3) comps = sameSch;
    }
  }

  // Score similarity
  comps = comps.map(c => ({
    ...c,
    ppsf: c.price / Math.max(1, c.sqft),
    ppacre: c.price / Math.max(0.01, c.lotAcres),
    ppbed: c.price / Math.max(1, c.beds),
    ppbath: c.price / Math.max(1, c.baths),
    similarity: similarityScore(subject, c),
  }));

  comps.sort((a,b)=> b.similarity - a.similarity);

  // return up to maxComps
  return comps.slice(0, subject.maxComps ?? 8);
}

/* ---------- Estimation logic ---------- */
/**
 * Estimate subject market value using:
 * - median $/sqft of top comps * subject sqft
 * - median $/acre  of top comps * subject lot
 * Blend weights based on lot size significance.
 */
function estimateValue(subject, comps){
  const ppsfArr = comps.map(c=>c.ppsf);
  const ppacreArr = comps.map(c=>c.ppacre);

  const medPpsf = median(ppsfArr);
  const medPpacre = median(ppacreArr);

  const estFromSqft = medPpsf * Math.max(1, subject.sqft || 0);
  const estFromAcre = medPpacre * Math.max(0.01, subject.lotAcres || 0);

  // If lot is small typical suburban, rely more on sqft; if lot is large, increase lot weight.
  const lot = subject.lotAcres || 0.2;
  const lotWeight = clamp((lot - 0.20) / 0.60, 0, 0.35); // up to 35% weight
  const sqftWeight = 1 - lotWeight;

  // similarity-weighted adjustment: if comps are weak matches, pull estimate toward conservative (lower) percentile
  const simAvg = comps.reduce((s,c)=>s+(c.similarity||0),0)/Math.max(1, comps.length);
  const dispersion = stdev(comps.map(c=>c.ppsf)) / Math.max(1, median(ppsfArr));
  const conservatism = clamp((1 - simAvg/100) + (dispersion || 0)*0.35, 0, 0.35);

  const p25Ppsf = percentile(ppsfArr, 0.25);
  const conservativeSqft = p25Ppsf * Math.max(1, subject.sqft || 0);

  const blended = sqftWeight * estFromSqft + lotWeight * estFromAcre;
  const finalEst = (1 - conservatism)*blended + conservatism*conservativeSqft;

  return {
    estValue: finalEst,
    medPpsf,
    medPpacre,
    estFromSqft,
    estFromAcre,
    simAvg,
    dispersion: dispersion || 0,
    conservatism
  };
}

/* ---------- UI / Rendering ---------- */
const el = (id)=>document.getElementById(id);

function setStatus(text){
  el("statusPill").textContent = text;
}

function strengthLabel(simAvg, compCount, dispersion){
  // Dispersion: lower is better
  const dispScore = 1 - clamp(dispersion, 0, 0.35) / 0.35;
  const countScore = clamp(compCount / 8, 0, 1);
  const simScore = clamp(simAvg / 100, 0, 1);

  const total = 0.45*simScore + 0.35*dispScore + 0.20*countScore;
  if (total >= 0.78) return {label:"Strong", cls:"good", note:"High similarity, tight pricing spread, sufficient comps."};
  if (total >= 0.58) return {label:"Moderate", cls:"warn", note:"Decent matches, but spread or count could be improved."};
  return {label:"Weak", cls:"bad", note:"Consider adding closer/same-subdivision sold comps if available."};
}

function renderMetricRows(subject, comps, est){
  const metrics = [
    { name:"$/Sqft", subject: (subject.assessed||0)/Math.max(1, subject.sqft||NaN), arr: comps.map(c=>c.ppsf) },
    { name:"$/Acre", subject: (subject.assessed||0)/Math.max(0.01, subject.lotAcres||NaN), arr: comps.map(c=>c.ppacre) },
    { name:"$/Bedroom", subject: (subject.assessed||0)/Math.max(1, subject.beds||NaN), arr: comps.map(c=>c.ppbed) },
    { name:"$/Bathroom", subject: (subject.assessed||0)/Math.max(1, subject.baths||NaN), arr: comps.map(c=>c.ppbath) },
  ];

  const tbody = el("metricRows");
  tbody.innerHTML = "";

  for (const m of metrics){
    const med = median(m.arr);
    const lo = percentile(m.arr, 0.10);
    const hi = percentile(m.arr, 0.90);

    const tr = document.createElement("tr");
    tr.innerHTML = `
      <td>${m.name}</td>
      <td class="right mono">${isFinite(m.subject) ? fmtMoney(m.subject) : "—"}</td>
      <td class="right mono">${isFinite(med) ? fmtMoney(med) : "—"}</td>
      <td class="right mono">${(isFinite(lo)&&isFinite(hi)) ? `${fmtMoney(lo)} – ${fmtMoney(hi)}` : "—"}</td>
    `;
    tbody.appendChild(tr);
  }
}

function renderCompRows(comps){
  const tbody = el("compRows");
  tbody.innerHTML = "";
  for (const c of comps){
    const tr = document.createElement("tr");
    tr.innerHTML = `
      <td>${c.address}</td>
      <td class="small">${c.status}</td>
      <td class="right mono">${fmtMoney(c.price)}</td>
      <td class="right mono">${fmtMoney(c.ppsf)}</td>
      <td class="right mono">${fmtNum(c.miles, 1)}</td>
      <td class="right mono">${fmtNum(c.sqft,0)}</td>
      <td class="right mono">${fmtNum(c.beds,0)}</td>
      <td class="right mono">${fmtNum(c.baths,1)}</td>
      <td class="right mono">${fmtNum(c.year,0)}</td>
      <td class="right mono">${fmtNum(c.lotAcres,2)}</td>
      <td class="small">${c.school}</td>
      <td class="small">${c.subdivision}</td>
      <td class="right mono">${fmtNum(c.similarity,0)}%</td>
    `;
    tbody.appendChild(tr);
  }
}

function renderClaim(subject, comps, est, suggested){
  const compCount = comps.length;
  const medPpsf = est.medPpsf;
  const ppsfAssessed = (subject.assessed||0)/Math.max(1, subject.sqft||1);

  const text = `
    I am protesting the assessed market value for <b>${escapeHTML(subject.address || "this property")}</b>.
    Based on <b>${compCount}</b> comparable homes within <b>${subject.radius} miles</b>
    ${(subject.subdivision ? `and in the same subdivision (<b>${escapeHTML(subject.subdivision)}</b>)` : "")}
    ${(subject.school ? `and school district (<b>${escapeHTML(subject.school)}</b>)` : "")},
    the median comparable price level is approximately <b>${fmtMoney(medPpsf)}/sqft</b>.
    Applying this to the subject property’s living area (<b>${fmtNum(subject.sqft,0)} sqft</b>) supports an estimated market value near
    <b>${fmtMoney(est.estValue)}</b>.
    The current assessed value of <b>${fmtMoney(subject.assessed)}</b> implies <b>${fmtMoney(ppsfAssessed)}/sqft</b>,
    which is higher than the comparable market evidence. I request the assessed value be corrected to <b>${fmtMoney(suggested)}</b>.
  `.trim();

  el("claimText").innerHTML = text;
}

function escapeHTML(s){
  return String(s).replace(/[&<>"']/g, (c)=>({
    "&":"&amp;","<":"&lt;",">":"&gt;",'"':"&quot;","'":"&#39;"
  }[c]));
}

/* ---------- Main run ---------- */
async function run(){
  const subject = {
    address: el("address").value.trim(),
    assessed: Number(el("assessed").value),
    radius: Number(el("radius").value),
    maxComps: Number(el("maxComps").value),
    sqft: Number(el("sqft").value),
    year: Number(el("yearBuilt").value),
    beds: Number(el("beds").value),
    baths: Number(el("baths").value),
    garage: Number(el("garage").value),
    lotAcres: Number(el("lotAcres").value),
    school: el("school").value.trim(),
    subdivision: el("subdivision").value.trim(),
  };

  if (!subject.address){
    alert("Please enter an address (demo is fine).");
    return;
  }
  if (!isFinite(subject.assessed) || subject.assessed <= 0){
    alert("Please enter the current assessed value (a positive number).");
    return;
  }

  // If user didn't provide subject attributes, infer a reasonable default from top demo comps
  const fallback = DEMO_COMPS[0];
  if (!isFinite(subject.sqft) || subject.sqft <= 0) subject.sqft = 2450;
  if (!isFinite(subject.lotAcres) || subject.lotAcres <= 0) subject.lotAcres = 0.22;
  if (!isFinite(subject.beds) || subject.beds <= 0) subject.beds = 4;
  if (!isFinite(subject.baths) || subject.baths <= 0) subject.baths = 3;
  if (!isFinite(subject.year) || subject.year <= 0) subject.year = 2002;
  if (!isFinite(subject.garage) || subject.garage < 0) subject.garage = 2;

  setStatus("Searching comps and computing value metrics…");

  // DEMO provider
  const comps = await fetchComps_DEMO(subject);

  if (!comps.length){
    setStatus("No comps found in radius. Increase radius or loosen filters.");
    el("compRows").innerHTML = `<tr><td colspan="13" class="muted">No comps found.</td></tr>`;
    return;
  }

  const est = estimateValue(subject, comps);

  // Suggested correction: round to nearest $1,000, and do not exceed assessed
  let suggested = Math.round(est.estValue / 1000) * 1000;
  suggested = Math.min(suggested, subject.assessed);

  const delta = subject.assessed - suggested;

  // Evidence strength
  const s = strengthLabel(est.simAvg, comps.length, est.dispersion);

  // Render KPIs
  el("estValue").textContent = fmtMoney(suggested);
  el("assessedOut").textContent = fmtMoney(subject.assessed);
  el("delta").textContent = (delta>0 ? `-${fmtMoney(delta)}` : fmtMoney(0));
  el("deltaNote").textContent = delta>0 ? "Target reduction based on comparable market evidence." : "Assessed value is not above estimate in this run.";

  el("strength").textContent = s.label;
  el("strengthNote").textContent = s.note;

  // set badge class
  const strengthEl = el("strength").parentElement;
  // not needed; use badge next to dataMode only

  // Claim + tables
  renderClaim(subject, comps, est, suggested);
  renderMetricRows(subject, comps, est);
  renderCompRows(comps);

  setStatus(`Generated packet using ${comps.length} comps (avg similarity ${fmtNum(est.simAvg,0)}%).`);
}

/* ---------- Demo loader ---------- */
function loadDemo(){
  el("address").value = "2922 S Creekwood Drive, Grapevine, TX 76051";
  el("assessed").value = "620000";
  el("radius").value = "2";
  el("maxComps").value = "8";
  el("sqft").value = "2450";
  el("yearBuilt").value = "2002";
  el("beds").value = "4";
  el("baths").value = "3";
  el("garage").value = "2";
  el("lotAcres").value = "0.22";
  el("school").value = "Grapevine-Colleyville ISD";
  el("subdivision").value = "Creekwood Estates";
  setStatus("Demo loaded. Click “Find Comps & Generate Packet”.");
}

/* ---------- Buttons ---------- */
el("btnRun").addEventListener("click", run);
el("btnLoadDemo").addEventListener("click", loadDemo);
el("btnPrint").addEventListener("click", ()=>window.print());

// Auto-load demo for convenience (comment out if you want blank)
loadDemo();
</script>
</body>
</html>
