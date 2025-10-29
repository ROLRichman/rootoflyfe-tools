# rootoflyfe-tools
Root Of Lyfe Holdings — Financial Tools, Loan &amp; Capital Calculators

<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>ROâ€™Lyfe â€” Visual Online Loan & Deal Intake (MoneyBroker v4)</title>
<meta name="description" content="Root Of Lyfe Holdings â€” calculators, creative finance compare, quick snapshot, AI advisor, and underwriting submission." />
<style>
  :root{
    --bg:#0f1115; --bg2:#11161b;
    --panel:#141a20; --card:#0f141a;
    --ink:#eaf5ef; --muted:#a7b5b0;
    --mint:#38d39f; --mint2:#6ee7c9;
    --ring:#23323b; --ghost:#1a2230;
  }
  *{box-sizing:border-box}
  html,body{margin:0;background:linear-gradient(180deg,var(--bg),var(--bg2));color:var(--ink);font:500 16px/1.5 system-ui,-apple-system,Segoe UI,Roboto,Inter,Arial}
  a{color:var(--mint2);text-decoration:none} a:hover{text-decoration:underline}
  .wrap{max-width:1020px;margin:0 auto;padding:18px}
  .nav{position:sticky;top:0;z-index:20;background:linear-gradient(180deg,rgba(15,17,21,.96),rgba(15,17,21,.78));backdrop-filter:saturate(1.15) blur(6px);border-bottom:1px solid #1f2830}
  .row{display:flex;gap:12px;flex-wrap:wrap;align-items:center;justify-content:space-between}
  .brand{display:flex;align-items:center;gap:10px}
  .leaf{font-size:22px}
  .title{font-weight:800;letter-spacing:.2px}
  .tag{color:var(--muted);font-size:12px}
  .menu{display:flex;flex-wrap:wrap;gap:8px}
  .menu a{border:1px solid #23313a;border-radius:10px;padding:8px 10px;color:var(--ink)}
  .menu a:hover{background:#12171d}
  section{scroll-margin-top:78px}
  .hero{border-bottom:1px solid #1e2730;background:
    radial-gradient(900px 500px at 0% -10%,rgba(56,211,159,.10),transparent 60%),
    radial-gradient(800px 500px at 100% -10%,rgba(110,231,201,.07),transparent 55%)}
  .hero h1{font-size:clamp(24px,4.6vw,40px);line-height:1.15;margin:.35rem 0}
  .pill{display:inline-flex;gap:8px;align-items:center;padding:6px 10px;border:1px dashed #2a3440;border-radius:999px;color:var(--muted);font-size:12px}
  .btn{display:inline-flex;align-items:center;gap:8px;padding:10px 14px;border-radius:12px;border:1px solid #2a3440;background:#11161c;color:var(--ink);font-weight:700;cursor:pointer}
  .btn.primary{background:linear-gradient(90deg,var(--mint),var(--mint2));color:#0b1411;border-color:transparent}
  .grid-2{display:grid;gap:16px}
  @media(min-width:860px){.grid-2{grid-template-columns:1.05fr .95fr}}
  .card{background:linear-gradient(180deg,var(--card),var(--panel));border:1px solid var(--ring);border-radius:16px;padding:16px}
  .h2{font-size:clamp(20px,3.8vw,28px);margin:0 0 8px}
  .muted{color:var(--muted)}
  input,select,textarea{width:100%;padding:12px 14px;border-radius:12px;border:1px solid #2a3440;background:#0f141a;color:#e8f4f0}
  label{display:block;margin:12px 0 6px}
  .actions{display:flex;gap:10px;flex-wrap:wrap;margin-top:12px}
  .result{white-space:pre-wrap;background:#0e141a;border:1px dashed #334152;color:#d9e9e3;border-radius:14px;padding:14px;margin-top:12px}
  .note{font-size:12px;color:var(--muted)}
  .video{position:relative;aspect-ratio:16/9;border:1px solid var(--ring);border-radius:14px;overflow:hidden;background:#0b0f12}
  iframe{position:absolute;inset:0;width:100%;height:100%;border:0}
  .section-title{display:flex;align-items:center;gap:8px;margin:24px 0 8px}
  .split{display:grid;gap:14px}
  @media(min-width:720px){.split{grid-template-columns:1fr 1fr}}
  details.qa{background:#0d1319;border:1px solid #273443;border-radius:14px;padding:12px;margin:10px 0}
  details.qa summary{cursor:pointer;font-weight:700}
  .qa-follow{margin-top:10px;border-top:1px dashed #2a3544;padding-top:10px}
  #toast{position:fixed;left:50%;bottom:18px;transform:translateX(-50%);background:#0e151b;border:1px solid #26333f;padding:10px 14px;border-radius:10px;display:none}
  /* small helper so print-to-PDF is tidy */
  @media print{
    .menu,.actions .btn[href^="mailto:"],.actions .btn#cf_send,.actions .btn#qs_send,.actions .btn#of_send,.actions .btn#qa_send{display:none!important}
    body{background:#fff;color:#000}
    .card{border:1px solid #999}
  }
</style>
</head>
<body>

<!-- NAV -->
<header class="nav">
  <div class="wrap row">
    <div class="brand">
      <div class="leaf">ðŸŒ¿</div>
      <div>
        <div class="title">Root Of Lyfe</div>
        <div class="tag">Rooted in Access. Built for Growth.</div>
      </div>
    </div>
    <nav class="menu">
      <a href="#intro">Intro</a>
      <a href="#videos">Video Hub</a>
      <a href="#hub">Capital Hub</a>
      <a href="#compare">Creative Compare</a>
      <a href="#snapshot">Snapshot</a>
      <a href="#offer">Submit Deal</a>
      <a href="https://form.jotform.com/252443109820047" target="_blank" rel="noopener">Apply</a>
    </nav>
  </div>
</header>

<!-- HERO + AUDIO -->
<section class="hero" id="intro">
  <div class="wrap grid-2">
    <div>
      <span class="pill">ðŸŒ¿ Root Of Lyfe Holdings â€¢ Nationwide â€¢ Private & Alt Capital</span>
      <h1>Fund deals, compare creative finance, and submit to underwriting â€” fast.</h1>
      <p class="muted">Explore options, preview terms, download a clean PDF, or send your snapshot to underwriting via webhook.</p>
      <div class="actions">
        <a class="btn primary" href="#hub">Explore Capital Hub</a>
        <a class="btn" href="#snapshot">Get Quick Snapshot</a>
      </div>
      <p class="note" style="margin-top:8px">Compliance: Educational tools only. Final approvals, rates, terms and fees are set by underwriting and closing docs. No lender names listed on this page.</p>
    </div>
    <div class="card">
      <div class="section-title"><strong>ðŸŽ§ Intro Audio</strong><span class="muted">(click to play)</span></div>
      <audio id="rolAudio" controls preload="none" style="width:100%">
        <source src="https://www.dropbox.com/scl/fi/5rog3lgwhr9xj24mytrq4/Root-Of-Lyfe-Introduction.m4a_rlkey-kp9aegq7hdh85feszh6y0kwrj-st-rhuhohao-dl-0.mp3-online-audio-converter.com.mp3?dl=1" type="audio/mpeg">
      </audio>
      <div class="actions">
        <button class="btn" onclick="document.getElementById('rolAudio').play()">â–¶ Click to Play</button>
        <a class="btn" href="https://www.dropbox.com/scl/fi/5rog3lgwhr9xj24mytrq4/Root-Of-Lyfe-Introduction.m4a_rlkey-kp9aegq7hdh85feszh6y0kwrj-st-rhuhohao-dl-0.mp3-online-audio-converter.com.mp3?dl=1" target="_blank">â¬‡ Download</a>
      </div>
      <div class="note" style="margin-top:6px">Tip: Hosting audio on your own domain/CDN improves reliability across browsers.</div>
    </div>
  </div>
</section>

<!-- VIDEO HUB -->
<section id="videos">
  <div class="wrap">
    <div class="h2">ðŸŽ¥ Video Hub â€” Education & Testimonials</div>
    <p class="muted">Shorts and full videos to warm up prospects and explain creative options.</p>
    <div class="split">
      <div class="video"><iframe src="https://www.youtube.com/embed/IvhD3ewyzD4?mute=1&playsinline=1" title="Short 1" loading="lazy" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div>
      <div class="video"><iframe src="https://www.youtube.com/embed/qjYLxRoLYmY?mute=1&playsinline=1" title="Short 2" loading="lazy" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div>
    </div>
    <div class="split" style="margin-top:14px">
      <div class="video"><iframe src="https://www.youtube.com/embed/fAbbiJP3wMs?mute=1&playsinline=1" title="Video 1" loading="lazy" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div>
      <div class="video"><iframe src="https://www.youtube.com/embed/iAlUx755K2s?mute=1&playsinline=1" title="Video 2" loading="lazy" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div>
    </div>
    <div class="split" style="margin-top:14px">
      <div class="video"><iframe src="https://www.youtube.com/embed/daq64anGa9s?mute=1&playsinline=1" title="Credit Repair Testimonial" loading="lazy" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div>
      <div class="video"><iframe src="https://www.youtube.com/embed/6FXApQ1y2KE?mute=1&playsinline=1" title="Creative Financing Tutorial" loading="lazy" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div>
    </div>
  </div>
</section>

<!-- CAPITAL HUB -->
<section id="hub">
  <div class="wrap grid-2">
    <div class="card">
      <div class="h2">ðŸ’µ Proof of Funds â€” Same Day</div>
      <p class="muted">Up to <strong>$500,000</strong> for non-owner-occupied properties. Collateral verification included; same-day once docs are complete.</p>
      <div class="actions">
        <a class="btn primary" href="https://form.jotform.com/252443109820047" target="_blank" rel="noopener">ðŸ§¾ Request Proof of Funds</a>
      </div>
      <hr style="border:1px solid var(--ring);margin:14px 0">
      <div class="h2">ðŸ’¼ Business Loan & Funding</div>
      <ul class="muted" style="margin:0 0 8px 18px">
        <li>Soft-pull prequalification (no score impact)</li>
        <li>2â€“6 months business bank statements</li>
        <li>All entity types (LLC, Corp, DBA)</li>
      </ul>
      <div class="actions">
        <a class="btn" href="https://www.myscoreiq.com/get-fico-preferred.aspx?offercode=4321396B" target="_blank" rel="noopener">ðŸ’³ Check Credit</a>
        <a class="btn primary" href="https://form.jotform.com/252443109820047" target="_blank" rel="noopener">ðŸ“„ Apply Now</a>
      </div>
    </div>
    <div class="card">
      <div class="h2">ðŸ¤ Partners â€¢ Live Quotes</div>
      <p class="muted">Need speed? Get instant guidance or talk to a live agent for a 5-minute quote.</p>
      <div class="actions">
        <a class="btn" href="https://my.americasfundingexperts.com/?id=1820217000190862001" target="_blank" rel="noopener">âš¡ AFE â€” Quick Quotes</a>
        <a class="btn" href="https://go.mypartner.io/business-financing/?ref=001Qk00000MkqgTIAR" target="_blank" rel="noopener">ðŸ—£ï¸ Live Agent (5-Min)</a>
        <a class="btn" href="https://rolrichman.link/" target="_blank" rel="noopener">ðŸŒ¿ Resources & PDFs</a>
      </div>
    </div>
  </div>
</section>

<!-- CREATIVE COMPARE -->
<section id="compare">
  <div class="wrap card">
    <div class="h2">ðŸ“Š Creative Financing â€” Quick Compare</div>
    <p class="muted">Estimate <b>cash vs. seller-finance vs. refi</b>. Includes a fix-and-flip cost panel like your screenshot.</p>
    <div class="split">
      <div>
        <label>ARV ($)</label><input id="cf_arv" type="number" value="350000">
        <label>Rehab ($)</label><input id="cf_rehab" type="number" value="50000">
        <label>Cash % of ARV</label><input id="cf_cash" type="number" value="65">
        <label>Seller Finance % of ARV</label><input id="cf_seller" type="number" value="75">
        <label>Refi LTV %</label><input id="cf_ltv" type="number" value="65">
        <label>Address / Notes (optional)</label><input id="cf_addr" type="text" placeholder="123 Main St., City ST">
      </div>
      <div>
        <details open>
          <summary class="muted">Advanced Fix-&-Flip (points, interest, fees)</summary>
          <div class="split" style="margin-top:8px">
            <div><label>HML Cap (% ARV)</label><input id="cf_cap" type="number" value="65"></div>
            <div><label>Rate (%/yr)</label><input id="cf_rate" type="number" value="12"></div>
            <div><label>Hold (months)</label><input id="cf_months" type="number" value="6"></div>
            <div><label>Points (%)</label><input id="cf_points" type="number" value="3"></div>
            <div><label>Realtor (%)</label><input id="cf_realtor" type="number" value="5"></div>
            <div><label>Admin/Misc ($)</label><input id="cf_admin" type="number" value="1000"></div>
            <div><label>Closing ($)</label><input id="cf_closing" type="number" value="5250"></div>
            <div><label>Holding ($)</label><input id="cf_holding" type="number" value="2500"></div>
          </div>
        </details>
      </div>
    </div>
    <div class="actions">
      <button class="btn primary" id="cf_calc">Calculate</button>
      <button class="btn" id="cf_print">â¬‡ Download PDF</button>
      <button class="btn" id="cf_email">ðŸ“§ Email Offer</button>
      <button class="btn" id="cf_send">ðŸ“¤ Send to Underwriting</button>
    </div>
    <div id="cf_out" class="result">Results will appear here.</div>
    <div id="cf_ai" class="note"></div>
    <div class="note">âš  Educational only. Final terms depend on underwriting.</div>
  </div>
</section>

<!-- QUICK SNAPSHOT -->
<section id="snapshot">
  <div class="wrap card">
    <div class="h2">ðŸ’° Quick Snapshot Calculator</div>
    <p class="muted">Estimate Broker Fee, Monthly Payment, and a clean summary for underwriting.</p>
    <div class="split">
      <div>
        <label>Loan Amount ($)</label><input id="qs_amt" type="number" value="100000">
        <label>Broker Fee (%)</label><input id="qs_fee" type="number" value="3">
      </div>
      <div>
        <label>Term (months)</label><input id="qs_term" type="number" value="12">
        <label>Interest Rate (%/yr)</label><input id="qs_rate" type="number" value="12">
      </div>
    </div>
    <div class="actions">
      <button class="btn primary" id="qs_calc">Calculate</button>
      <button class="btn" id="qs_print">â¬‡ Download PDF</button>
      <button class="btn" id="qs_email">ðŸ“§ Email Snapshot</button>
      <button class="btn" id="qs_send">ðŸ“¤ Send to Underwriting</button>
    </div>
    <div id="qs_out" class="result">Results will appear here.</div>
    <div id="qs_ai" class="note"></div>
    <div class="note">âš  For estimation only. Actual payments depend on underwriting and final terms.</div>
  </div>
</section>

<!-- OFFER SUBMIT + SMART Q&A -->
<section id="offer">
  <div class="wrap card">
    <div class="h2">ðŸ§¾ Submit Your Offer / Deal Details</div>
    <div class="split">
      <div>
        <label>Your Name</label><input id="of_name" type="text" placeholder="Your full name">
        <label>Email</label><input id="of_email" type="email" placeholder="you@domain.com">
        <label>Phone</label><input id="of_phone" type="tel" placeholder="(optional)">
      </div>
      <div>
        <label>Offer Type</label>
        <select id="of_type">
          <option>Real Estate â€” Cash Offer</option>
          <option>Real Estate â€” Seller Finance</option>
          <option>Real Estate â€” Refi</option>
          <option>Business â€” Working Capital</option>
          <option>Business â€” SBA / Term</option>
          <option>Business â€” Revenue-Based / MCA</option>
        </select>
        <label>Headline Offer Amount ($)</label><input id="of_head" type="number" placeholder="e.g., 215000">
        <label>Backup Offer / Finance ($)</label><input id="of_back" type="number" placeholder="e.g., 156000">
      </div>
    </div>
    <label>Notes (address, terms, down payment, revenue, etc.)</label>
    <textarea id="of_notes" rows="4" placeholder="Key details the underwriter must see..."></textarea>
    <div class="actions">
      <button class="btn primary" id="of_sum">Summarize</button>
      <button class="btn" id="of_print">â¬‡ Download PDF</button>
      <button class="btn" id="of_emailbtn">ðŸ“§ Email Us</button>
      <button class="btn" id="of_send">ðŸ“¤ Send to Underwriting</button>
    </div>
    <div id="of_out" class="result">Fill the fields above and click â€œSummarizeâ€.</div>

    <div class="section-title" style="margin-top:16px"><strong>ðŸ§  Deal Intake â€” Smart Q&A</strong><span class="muted">(autosaves as you type)</span></div>
    <details class="qa" id="q1"><summary>1) Whatâ€™s the property address (or business name & city)?</summary>
      <textarea id="a1" rows="2" placeholder="123 Main St, City ST / OR Business LLC, City"></textarea>
    </details>
    <details class="qa" id="q2"><summary>2) Whatâ€™s the goal? (Cash sale, seller finance, refi, working capital, equipment, etc.)</summary>
      <textarea id="a2" rows="2" placeholder="Brief objective"></textarea>
      <div class="qa-follow">
        <label>If seller finance: desired down payment & term?</label>
        <input id="a2b" type="text" placeholder="e.g., 10% down, 4â€“5 yrs, balloon at refi">
      </div>
    </details>
    <details class="qa" id="q3"><summary>3) Numbers: ARV/value, rehab/use of funds, monthly revenue (if business)</summary>
      <textarea id="a3" rows="3" placeholder="ARV/Value: $... | Rehab/Use: $... | Revenue: $..."></textarea>
    </details>
    <details class="qa" id="q4"><summary>4) Timing & constraints (deadline, credit, reserves, experience)</summary>
      <textarea id="a4" rows="3" placeholder="Close by __ | FICO ~__ | Cash reserves ~__ | RE experience (deals) __"></textarea>
    </details>

    <div class="actions">
      <button class="btn" id="qa_print">â¬‡ Download Q&A PDF</button>
      <button class="btn" id="qa_email">ðŸ“§ Email Q&A</button>
      <button class="btn" id="qa_send">ðŸ“¤ Send Q&A to Underwriting</button>
    </div>

    <div class="note" style="margin-top:8px">
      Coordinated by <b>Richman & Chris</b> â€” Root Of Lyfe Holdings LLC â€¢ For funding: <b>richman@rootoflyfe.com</b><br>
      Attach files via email or use your JotForm uploader.
    </div>
  </div>
</section>

<!-- FOOTER -->
<section>
  <div class="wrap" style="text-align:center;color:var(--muted);padding-bottom:40px">
    Â© Root Of Lyfe Holdings LLC â€” Educational estimates only. Final approvals, rates, terms and fees are set by underwriting and closing documents.
  </div>
</section>

<div id="toast">Saved.</div>

<script>
  // ---------- helpers ----------
  const $ = id => document.getElementById(id);
  const fmt0 = n => Number(n||0).toLocaleString(undefined,{maximumFractionDigits:0});
  const money = n => "$"+fmt0(Math.round(Number(n||0)));
  const toast = (msg="Saved.", ms=1100)=>{const t=$('toast'); if(!t) return; t.textContent=msg; t.style.display='block'; setTimeout(()=>t.style.display='none',ms);};
  const postWebhook = async (payload) => {
    try{
      const res = await fetch("https://rootoflyfe.com/api/webhook/rolfunding",{
        method:"POST", headers:{"Content-Type":"application/json"},
        body: JSON.stringify(payload)
      });
      alert(res.ok ? "Submitted to underwriting." : "Submit failed.");
    }catch(e){ alert("Network error."); }
  };

  // ---------- Creative Compare ----------
  function calcCF(){
    const arv=+($('cf_arv').value||0), rehab=+($('cf_rehab').value||0);
    const cashPct=+($('cf_cash').value||0), sellerPct=+($('cf_seller').value||0), ltv=+($('cf_ltv').value||0);
    const cap=+($('cf_cap').value||0), rate=(+($('cf_rate').value||0))/100, months=+($('cf_months').value||0);
    const pts=(+($('cf_points').value||0))/100, realtorPct=(+($('cf_realtor').value||0))/100;
    const admin=+($('cf_admin').value||0), closing=+($('cf_closing').value||0), holding=+($('cf_holding').value||0);
    const addr= ($('cf_addr').value||"").trim()||"â€”";

    const cashOffer = Math.max(0, (arv*cashPct/100) - rehab);
    const sellerHeadline = Math.max(0, arv*sellerPct/100);
    const refiVal = Math.max(0, arv*ltv/100);

    const hmlLoan = Math.min(arv*cap/100, refiVal||arv*cap/100);
    const points = hmlLoan*pts;
    const interest = hmlLoan*rate*(months/12);
    const realtor = arv*realtorPct;
    const tpc = rehab + points + interest + admin + realtor + closing + holding;

    const resale = [arv-20000, arv-10000, arv, arv+10000, arv+20000].map(v => ({resale:v, net:v - tpc}));
    const lines=[];
    lines.push(`ARV: ${money(arv)} | HML Loan (â‰¤${cap}% ARV): ${money(hmlLoan)}`);
    lines.push(`Points: ${money(points)} | Interest: ${money(interest)} | Admin: ${money(admin)}`);
    lines.push(`Realtor: ${money(realtor)} | Closing: ${money(closing)} | Holding: ${money(holding)}`);
    lines.push(`TPC (Total Project Cost): ${money(tpc)}\n`);
    resale.forEach(s => lines.push(`Resale ${money(s.resale)} â†’ Net ${money(s.net)}`));
    lines.push(`\nCash Offer Target (${cashPct}% ARV â€“ rehab): ${money(cashOffer)}`);
    lines.push(`Seller Finance (â‰ˆ ${sellerPct}% ARV headline): ${money(sellerHeadline)}`);
    lines.push(`Refi Option (â‰¤ ${ltv}% LTV on ARV): ${money(refiVal)} (illustrative)\n`);
    lines.push(`Address/Notes: ${addr}`);

    const text = lines.join("\n");
    $('cf_out').textContent = text;

    const marginMid = resale[2].net;
    $('cf_ai').textContent =
      (marginMid>25000)
        ? "ðŸ§  Advisor: Solid spread at mid-resale. Consider locking a cash offer near target and keep seller-finance as backup."
        : "ðŸ§  Advisor: Tight margin. Negotiate purchase/rehab; consider seller-finance to protect cash and improve DSCR.";

    return {arv,rehab,cashPct,sellerPct,ltv,cap,rate:rate*100,months,pts:pts*100,realtorPct:realtorPct*100,admin,closing,holding,
            cashOffer,sellerHeadline,refiVal,tpc,addr,text};
  }
  $('cf_calc')?.addEventListener('click', calcCF);
  $('cf_print')?.addEventListener('click', ()=>{ if(!$('cf_out').textContent.trim()) calcCF(); window.print(); });
  $('cf_email')?.addEventListener('click', ()=>{
    const r=calcCF();
    const subject=encodeURIComponent(`ROL Creative Offer â€” ${r.addr||'Estimate'}`);
    const body=encodeURIComponent(r.text+`\n\nâ€” Generated by Root Of Lyfe Quick Compare`);
    window.location.href=`mailto:richman@rootoflyfe.com?subject=${subject}&body=${body}`;
  });
  $('cf_send')?.addEventListener('click', ()=>postWebhook({channel:"Creative Compare", payload:calcCF()}));

  // ---------- Quick Snapshot ----------
  function pmt(rate, nper, pv){ const r=(rate)/12; return (r===0)? pv/nper : (pv*r)/(1-Math.pow(1+r,-nper)); }
  function calcQS(){
    const amt=+($('qs_amt').value||0), feePct=(+($('qs_fee').value||0))/100;
    const term=+($('qs_term').value||0), apr=(+($('qs_rate').value||0))/100;
    const fee = amt*feePct;
    const pay = pmt(apr, term, amt);
    const total = pay*term;
    const interest = total-amt;
    const text = `Loan Amount: ${money(amt)}
Broker Fee (${(feePct*100).toFixed(1)}%): ${money(fee)}
Total Return (Loan + Fee): ${money(amt+fee)}
--- Payment Estimate ---
Rate: ${(apr*100).toFixed(2)}% | Term: ${term} mo
Monthly Payment: ${money(pay)}
Total Paid: ${money(total)} | Total Interest: ${money(interest)}`;
    $('qs_out').textContent = text;
    $('qs_ai').textContent = (apr*100<=12)
      ? "ðŸ§  Advisor: Pricing looks workable; ensure ROI > cost of capital. If cashflow is tight, consider longer term or partial seller-carry."
      : "ðŸ§  Advisor: Higher APR â€” match term to ROI timeline and avoid over-leveraging.";
    return {amount:amt, fee, term, apr:apr*100, monthly:pay, total, interest, text};
  }
  $('qs_calc')?.addEventListener('click', calcQS);
  $('qs_print')?.addEventListener('click', ()=>{ if(!$('qs_out').textContent.trim()) calcQS(); window.print(); });
  $('qs_email')?.addEventListener('click', ()=>{
    const r=calcQS();
    const subject=encodeURIComponent(`ROL Funding Snapshot â€” ${money(r.amount)}`);
    const body=encodeURIComponent(r.text+`\n\nâ€” Generated by Root Of Lyfe Snapshot`);
    window.location.href=`mailto:richman@rootoflyfe.com?subject=${subject}&body=${body}`;
  });
  $('qs_send')?.addEventListener('click', ()=>postWebhook({channel:"Quick Snapshot", payload:calcQS()}));

  // ---------- Offer Submit ----------
  function summarizeOffer(){
    const name=($('of_name').value||"").trim(), email=($('of_email').value||"").trim(), phone=($('of_phone').value||"").trim();
    const type=$('of_type').value, head=+($('of_head').value||0), back=+($('of_back').value||0);
    const notes=($('of_notes').value||"").trim();
    const text = `Offer Summary
â€” â€” â€”
Type: ${type}
Headline: ${money(head)}
Backup: ${money(back)}
Name: ${name}
Email: ${email}
Phone: ${phone}
Notes: ${notes}`;
    $('of_out').textContent = text;
    return {type, head, back, name, email, phone, notes, text};
  }
  $('of_sum')?.addEventListener('click', summarizeOffer);
  $('of_print')?.addEventListener('click', ()=>{ if(!$('of_out').textContent.trim()) summarizeOffer(); window.print(); });
  $('of_emailbtn')?.addEventListener('click', ()=>{
    const r=summarizeOffer();
    const subject=encodeURIComponent(`ROL Offer â€” ${r.type} â€” ${money(r.head)}`);
    const body=encodeURIComponent(r.text+`\n\nâ€” Generated by Root Of Lyfe Offer Submit`);
    window.location.href=`mailto:richman@rootoflyfe.com?subject=${subject}&body=${body}`;
  });
  $('of_send')?.addEventListener('click', ()=>postWebhook({channel:"Offer Submit", payload:summarizeOffer()}));

  // ---------- Q&A Autosave (localStorage) ----------
  const fields = ["a1","a2","a2b","a3","a4"];
  fields.forEach(id=>{
    const node=$(id);
    if(!node) return;
    const key="rol_qa_"+id;
    try{ const v=localStorage.getItem(key); if(v) node.value=v; }catch(e){}
    node.addEventListener('input', ()=>{
      try{ localStorage.setItem(key,node.value||""); toast(); }catch(e){}
    });
  });
  function qaSummary(){
    const out = [
      "Q1 Address/Business: "+(($('a1')?.value)||""),
      "Q2 Goal: "+(($('a2')?.value)||""),
      "   Seller-finance terms: "+(($('a2b')?.value)||""),
      "Q3 Numbers: "+(($('a3')?.value)||""),
      "Q4 Timing/Constraints: "+(($('a4')?.value)||"")
    ].join("\n");
    return out.trim();
  }
  $('qa_print')?.addEventListener('click', ()=>{ window.print(); });
  $('qa_email')?.addEventListener('click', ()=>{
    const body=encodeURIComponent(qaSummary()+"\n\nâ€” ROL Q&A");
    const subject=encodeURIComponent("ROL Deal Intake â€” Q&A");
    window.location.href=`mailto:richman@rootoflyfe.com?subject=${subject}&body=${body}`;
  });
  $('qa_send')?.addEventListener('click', ()=>postWebhook({channel:"Deal Intake Q&A", payload:{qa:qaSummary()}}));
</script>

</body>
</html>
