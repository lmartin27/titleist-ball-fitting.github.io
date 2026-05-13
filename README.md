# lmartin27.github.io

<h2 class="sr-only">Titleist golf ball fitting reference guide — internship prep</h2>

<style>
.tabs{display:flex;border-bottom:0.5px solid var(--color-border-tertiary);margin-bottom:1.5rem;}
.tab-btn{background:none;border:none;border-bottom:2px solid transparent;padding:8px 14px;font-size:13px;font-weight:500;color:var(--color-text-secondary);cursor:pointer;margin-bottom:-1px;}
.tab-btn.active{color:var(--color-text-primary);border-bottom-color:var(--color-text-primary);}
.panel{display:none;}.panel.active{display:block;}
.ball-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(270px,1fr));gap:12px;}
.ball-card{background:var(--color-background-primary);border:0.5px solid var(--color-border-tertiary);border-radius:var(--border-radius-lg);overflow:hidden;}
.card-top{padding:12px 16px 10px;border-bottom:0.5px solid var(--color-border-tertiary);}
.card-name{font-size:15px;font-weight:500;color:var(--color-text-primary);margin:0 0 3px;}
.card-sub{font-size:12px;color:var(--color-text-secondary);margin:0;}
.card-body{padding:12px 16px;}
.spec{display:flex;justify-content:space-between;align-items:center;font-size:13px;padding:5px 0;border-bottom:0.5px solid var(--color-border-tertiary);}
.spec-lbl{color:var(--color-text-secondary);}
.spec-val{font-weight:500;color:var(--color-text-primary);text-align:right;max-width:55%;}
.section-lbl{font-size:11px;font-weight:500;color:var(--color-text-secondary);letter-spacing:0.06em;text-transform:uppercase;margin:11px 0 5px;}
.for-item{font-size:13px;color:var(--color-text-primary);padding:2px 0;}
.for-item::before{content:"— ";color:var(--color-text-secondary);}
.avoid-txt{font-size:12px;color:var(--color-text-secondary);padding-top:8px;border-top:0.5px solid var(--color-border-tertiary);margin-top:8px;}
.tour-txt{font-size:12px;color:var(--color-text-secondary);margin-top:5px;}
.pillar-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:10px;margin-bottom:1.5rem;}
.pillar{background:var(--color-background-secondary);border-radius:var(--border-radius-md);padding:12px;}
.pillar-name{font-size:13px;font-weight:500;color:var(--color-text-primary);margin-bottom:4px;}
.pillar-desc{font-size:12px;color:var(--color-text-secondary);}
.sec-heading{font-size:11px;font-weight:500;color:var(--color-text-secondary);letter-spacing:0.06em;text-transform:uppercase;margin:1.25rem 0 10px;}
.q-row{display:flex;gap:12px;align-items:flex-start;padding:9px 0;border-bottom:0.5px solid var(--color-border-tertiary);}
.q-num{font-size:13px;font-weight:500;color:var(--color-text-secondary);min-width:18px;}
.q-main{font-size:13px;color:var(--color-text-primary);}
.q-note{font-size:12px;color:var(--color-text-secondary);margin-top:3px;}
.cue-row{display:flex;gap:12px;padding:8px 0;border-bottom:0.5px solid var(--color-border-tertiary);font-size:13px;}
.cue-lbl{font-weight:500;color:var(--color-text-primary);min-width:140px;}
.cue-desc{color:var(--color-text-secondary);flex:1;}
.default-box{border:0.5px solid var(--color-border-tertiary);background:var(--color-background-secondary);border-radius:var(--border-radius-md);padding:10px 16px;margin-bottom:14px;}
.default-label{font-size:11px;color:var(--color-text-secondary);margin-bottom:2px;}
.default-val{font-size:14px;font-weight:500;color:var(--color-text-primary);}
.d-block{background:var(--color-background-secondary);border-radius:var(--border-radius-md);padding:12px 16px;margin-bottom:10px;}
.d-q{font-size:13px;font-weight:500;color:var(--color-text-primary);margin-bottom:8px;}
.d-opt{display:flex;gap:8px;font-size:13px;padding:3px 0;}
.d-cond{color:var(--color-text-secondary);min-width:200px;}
.d-rec{font-weight:500;color:var(--color-text-primary);}
.key-note{font-size:12px;color:var(--color-text-secondary);margin-top:4px;padding-top:12px;border-top:0.5px solid var(--color-border-tertiary);}
.approach-note{font-size:13px;color:var(--color-text-secondary);margin:0 0 1.25rem;line-height:1.6;}
</style>

<div class="tabs">
  <button class="tab-btn active" onclick="switchTab('lineup',this)">The lineup</button>
  <button class="tab-btn" onclick="switchTab('framework',this)">Fitting framework</button>
  <button class="tab-btn" onclick="switchTab('decision',this)">Decision guide</button>
</div>

<div id="panel-lineup" class="panel active">
  <div class="ball-grid">
    <div class="ball-card" style="border-left:3px solid #378ADD;">
      <div class="card-top">
        <p class="card-name">Pro V1</p>
        <p class="card-sub">3-piece · urethane cover · black numbers</p>
      </div>
      <div class="card-body">
        <div class="spec"><span class="spec-lbl">Flight</span><span class="spec-val">Mid / penetrating</span></div>
        <div class="spec"><span class="spec-lbl">Long game spin</span><span class="spec-val">Mid</span></div>
        <div class="spec"><span class="spec-lbl">Short game spin</span><span class="spec-val">Very high</span></div>
        <div class="spec" style="border-bottom:none;"><span class="spec-lbl">Feel</span><span class="spec-val">Soft</span></div>
        <div class="section-lbl">Best for</div>
        <div class="for-item">Most players; balanced all-around default</div>
        <div class="for-item">Natural mid-high flight, wants control</div>
        <div class="for-item">High-spin players needing driver efficiency</div>
        <div class="avoid-txt">Avoid if: needs to add significant height; prefers firm/crisp feel</div>
        <div class="tour-txt">Scheffler, Hovland, Finau, Adam Scott</div>
      </div>
    </div>
    <div class="ball-card" style="border-left:3px solid #BA7517;">
      <div class="card-top">
        <p class="card-name">Pro V1x</p>
        <p class="card-sub">4-piece · urethane cover · red numbers</p>
      </div>
      <div class="card-body">
        <div class="spec"><span class="spec-lbl">Flight</span><span class="spec-val">High</span></div>
        <div class="spec"><span class="spec-lbl">Long game spin</span><span class="spec-val">Higher than Pro V1</span></div>
        <div class="spec"><span class="spec-lbl">Short game spin</span><span class="spec-val">Very high (highest in wedge testing)</span></div>
        <div class="spec" style="border-bottom:none;"><span class="spec-lbl">Feel</span><span class="spec-val">Firm / "clicky"</span></div>
        <div class="section-lbl">Best for</div>
        <div class="for-item">Needs more height and stopping power</div>
        <div class="for-item">Struggles to hold greens on approach shots</div>
        <div class="for-item">Low-spin player who needs more wedge bite</div>
        <div class="avoid-txt">Avoid if: already balloons it naturally; wants softest feel</div>
        <div class="tour-txt">Justin Thomas, Jordan Spieth, Matt Fitzpatrick</div>
      </div>
    </div>
    <div class="ball-card" style="border-left:3px solid #993C1D;">
      <div class="card-top">
        <p class="card-name">Pro V1x Left Dash</p>
        <p class="card-sub">4-piece · urethane cover · "Left Dash" sidestamp</p>
      </div>
      <div class="card-body">
        <div class="spec"><span class="spec-lbl">Flight</span><span class="spec-val">High (same as Pro V1x)</span></div>
        <div class="spec"><span class="spec-lbl">Long game spin</span><span class="spec-val">Significantly lower than V1x</span></div>
        <div class="spec"><span class="spec-lbl">Short game spin</span><span class="spec-val">Lower than Pro V1 and V1x</span></div>
        <div class="spec" style="border-bottom:none;"><span class="spec-lbl">Feel</span><span class="spec-val">Firmest of the four</span></div>
        <div class="section-lbl">Best for</div>
        <div class="for-item">Wants high flight without excess spin</div>
        <div class="for-item">Wants to reduce driver spin, keep height</div>
        <div class="for-item">Distance-focused; firm feel is a must</div>
        <div class="avoid-txt">Avoid if: stopping power and short game spin are the priority</div>
        <div class="tour-txt">Distance-focused tour players; niche fit in most fittings</div>
      </div>
    </div>
    <div class="ball-card" style="border-left:3px solid #0F6E56;">
      <div class="card-top">
        <p class="card-name">AVX</p>
        <p class="card-sub">3-piece · urethane cover · "AVX" sidestamp</p>
      </div>
      <div class="card-body">
        <div class="spec"><span class="spec-lbl">Flight</span><span class="spec-val">Low / penetrating</span></div>
        <div class="spec"><span class="spec-lbl">Long game spin</span><span class="spec-val">Lower than Pro V1</span></div>
        <div class="spec"><span class="spec-lbl">Short game spin</span><span class="spec-val">Mid-high</span></div>
        <div class="spec" style="border-bottom:none;"><span class="spec-lbl">Feel</span><span class="spec-val">Softest of the four</span></div>
        <div class="section-lbl">Best for</div>
        <div class="for-item">Naturally hits it high; wants to flight it down</div>
        <div class="for-item">Plays in wind; wants a penetrating, stable ball</div>
        <div class="for-item">Softest possible feel is the top priority</div>
        <div class="avoid-txt">Avoid if: needs more height or stopping power; prefers firm feel</div>
        <div class="tour-txt">Wind-affected markets; high-launch players seeking control</div>
      </div>
    </div>
  </div>
</div>

<div id="panel-framework" class="panel">
  <div class="pillar-grid">
    <div class="pillar"><div class="pillar-name">Flight</div><div class="pillar-desc">Apex height and trajectory window — the first filter in any fitting conversation.</div></div>
    <div class="pillar"><div class="pillar-name">Spin</div><div class="pillar-desc">Short game spin determines stopping power. Long game spin shapes distance and control.</div></div>
    <div class="pillar"><div class="pillar-name">Feel</div><div class="pillar-desc">Soft vs firm is preference-driven — but it affects confidence and plays into every shot.</div></div>
  </div>

  <div class="sec-heading">Titleist's approach: green to tee</div>
  <p class="approach-note">Start with scoring shots — half wedge, full wedge, 7-iron, then driver. Every Titleist ball achieves max distance off the tee; the real differentiation is how it behaves inside 120 yards. Fit the short game first, verify with the long game after.</p>

  <div class="sec-heading">Conversation questions</div>
  <div class="q-row"><span class="q-num">1</span><div><div class="q-main">What ball are you currently playing?</div><div class="q-note">Reveals their baseline and what feel/flight they're already used to</div></div></div>
  <div class="q-row"><span class="q-num">2</span><div><div class="q-main">What's your handicap, and how often do you get out?</div><div class="q-note">Signals consistency level — affects how much they'll notice performance differences</div></div></div>
  <div class="q-row"><span class="q-num">3</span><div><div class="q-main">How would you describe the greens you typically play — firm or soft?</div><div class="q-note">Firm greens demand more spin and height to hold; soft greens are forgiving of a lower-spinning ball</div></div></div>
  <div class="q-row"><span class="q-num">4</span><div><div class="q-main">What feel do you prefer — soft, medium, or firm?</div><div class="q-note">Quickly narrows between Pro V1 / AVX (soft) and Pro V1x / Left Dash (firm)</div></div></div>
  <div class="q-row"><span class="q-num">5</span><div><div class="q-main">How would you describe your ball flight — low, mid, or high?</div><div class="q-note">Sets up the flight pillar. High hitters lean AVX or Pro V1; low hitters lean Pro V1x</div></div></div>
  <div class="q-row" style="border-bottom:none;"><span class="q-num">6</span><div><div class="q-main">Where's your biggest gap right now — distance, control, stopping power, or feel?</div><div class="q-note">Makes the recommendation feel tailored to their actual goal, not just specs</div></div></div>

  <div class="sec-heading" style="margin-top:1.5rem;">Visual cues while watching them hit</div>
  <div class="cue-row"><span class="cue-lbl">Peak height</span><span class="cue-desc">High apex → consider AVX or Pro V1. Low, flat flight → Pro V1x to add height.</span></div>
  <div class="cue-row"><span class="cue-lbl">Landing angle</span><span class="cue-desc">Ball lands steep and checks = good spin. Lands shallow and releases = needs more spin.</span></div>
  <div class="cue-row"><span class="cue-lbl">Green behavior</span><span class="cue-desc">Does the ball hold the green or release? Best real-world spin indicator without data.</span></div>
  <div class="cue-row"><span class="cue-lbl">Ball flight shape</span><span class="cue-desc">High draw = naturally lower spin. Low fade = naturally higher spin. Adjust fit accordingly.</span></div>
  <div class="cue-row" style="border-bottom:none;"><span class="cue-lbl">Strike consistency</span><span class="cue-desc">Inconsistent contact = they'll feel differences less. When in doubt, default to Pro V1.</span></div>
</div>

<div id="panel-decision" class="panel">
  <div class="default-box">
    <div class="default-label">Default starting point</div>
    <div class="default-val">Pro V1 — works for most players, most games, most conditions</div>
  </div>
  <div class="d-block">
    <div class="d-q">What feel do they prefer?</div>
    <div class="d-opt"><span class="d-cond">Soft or very soft</span><span class="d-rec">→ Pro V1 or AVX (check flight next)</span></div>
    <div class="d-opt"><span class="d-cond">Firm or crisp</span><span class="d-rec">→ Pro V1x or Left Dash (check priority next)</span></div>
    <div class="d-opt"><span class="d-cond">No strong preference</span><span class="d-rec">→ Stay with Pro V1 baseline</span></div>
  </div>
  <div class="d-block">
    <div class="d-q">What's their typical ball flight?</div>
    <div class="d-opt"><span class="d-cond">Already hits it high</span><span class="d-rec">→ AVX (flights it down, softest feel)</span></div>
    <div class="d-opt"><span class="d-cond">Mid / neutral</span><span class="d-rec">→ Pro V1 is likely the fit</span></div>
    <div class="d-opt"><span class="d-cond">Low, needs more height</span><span class="d-rec">→ Pro V1x (adds height + stopping power)</span></div>
  </div>
  <div class="d-block">
    <div class="d-q">What's their biggest scoring priority?</div>
    <div class="d-opt"><span class="d-cond">Stopping power / holding greens</span><span class="d-rec">→ Pro V1x (highest wedge spin)</span></div>
    <div class="d-opt"><span class="d-cond">Balanced control + distance</span><span class="d-rec">→ Pro V1</span></div>
    <div class="d-opt"><span class="d-cond">Max distance, high ball, less spin</span><span class="d-rec">→ Left Dash</span></div>
    <div class="d-opt"><span class="d-cond">Softest feel + lower flight</span><span class="d-rec">→ AVX</span></div>
  </div>
  <div class="d-block">
    <div class="d-q">Any course or condition factors?</div>
    <div class="d-opt"><span class="d-cond">Windy + naturally hits it high</span><span class="d-rec">→ AVX (penetrating flight resists wind)</span></div>
    <div class="d-opt"><span class="d-cond">Firm greens, struggles to hold</span><span class="d-rec">→ Pro V1x (most stopping power)</span></div>
    <div class="d-opt"><span class="d-cond">Soft greens, no wind concern</span><span class="d-rec">→ Pro V1 or follow feel preference</span></div>
  </div>
  <div class="key-note">Key insight: Titleist does not fit based on swing speed alone. Two players with identical swing speeds can need entirely different balls based on their natural spin, trajectory, and short game needs.</div>
</div>

<script>
function switchTab(id,btn){
  document.querySelectorAll('.tab-btn').forEach(b=>b.classList.remove('active'));
  document.querySelectorAll('.panel').forEach(p=>p.classList.remove('active'));
  document.getElementById('panel-'+id).classList.add('active');
  btn.classList.add('active');
}
</script>
