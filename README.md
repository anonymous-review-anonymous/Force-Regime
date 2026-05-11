<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<title>Force-Regime Downward Compatibility</title>
<meta name="viewport" content="width=device-width, initial-scale=1">

<style>

/* ---------- global ---------- */
*,
*::before,
*::after{
  box-sizing:border-box;
}

body{
  font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Helvetica,Arial,sans-serif;
  margin:0;
  background:#fff;
  color:#222;
  line-height:1.65;
}

.container{
  max-width:900px;
  margin:auto;
  padding:50px 20px;
}

h1{
  font-size:3em;
  margin-bottom:15px;
  line-height:1.25;
  font-weight:600;
}

.main-title{
  display:flex;
  align-items:center;
  justify-content:center;
  gap:9px;
  text-align:center; 
}

.hero-title{
  display:flex;
  align-items:center;
  justify-content:center;
  gap:18px;
  margin-bottom:10px;
}

.hero-icon{
  height:60px;
  opacity:.9;
}

.hero-text{
  text-align:center;
}

.title-main{
  font-size:3.2rem;
  font-weight:700;
  margin:0;
  letter-spacing:.5px;
}

.title-sub{
  font-size:1.35rem;
  font-weight:400;
  margin:6px 0 0 0;
  color:#444;
  line-height:1.4;
  max-width:800px;
}
  
.main-title img{ height:2.5em; }

.authors{
  text-align:center;
  font-size:1.15em;
}

.affiliation{
  text-align:center;
  color:#666;
  margin-bottom:28px;
}

/* ---------- buttons ---------- */
.links{
  text-align:center;
  margin:30px 0 20px 0;
}

.links a{
  display:inline-block;
  margin:6px;
  padding:11px 20px;
  border-radius:9px;
  text-decoration:none;
  color:white;
  background:#2d6cdf;
  font-weight:600;
  font-size:15px;
  transition:.2s;
}

.links a:hover{
  background:#1b4fb3;
  transform:translateY(-1px);
}

.links a.disabled{
  pointer-events:none;
  cursor:default;
  opacity:.45;
}

/* ---------- sections ---------- */
.section{ margin-top:55px; }

h2{
  border-bottom:2px solid #eee;
  padding-bottom:6px;
  font-weight:600;
}

p{ font-size:17px; }

/* ---------- KPI cards ---------- */
.kpi{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
  gap:14px;
  margin-top:22px;
}

.kpi .card{
  border:1px solid #eee;
  border-radius:12px;
  padding:16px;
  background:#fff;
  box-shadow:0 4px 18px rgba(0,0,0,.05);
}

.kpi .big{
  font-size:20px;
  font-weight:700;
}

.kpi .small{
  font-size:13px;
  color:#666;
  margin-top:6px;
}

/* ---------- video ---------- */
.video{
  position:relative;
  padding-bottom:56.25%;
  height:0;
  overflow:hidden;
  border-radius:12px;
  box-shadow:0 4px 18px rgba(0,0,0,.08);
  background:#000;
}

.video iframe{
  position:absolute;
  inset:0;
  width:100%;
  height:100%;
  border:0;
}

/* ---------- images ---------- */
.teaser{
  width:100%;
  border-radius:12px;
  box-shadow:0 4px 18px rgba(0,0,0,.08);
}

/* ---------- video grid ---------- */
.yt-grid{
  display:grid;
  grid-template-columns:repeat(2,1fr);
  gap:28px;
}

.yt-card{text-align:center;}

.yt-wrap{
  position:relative;
  width:100%;
  padding-bottom:56.25%;
  border-radius:12px;
  overflow:hidden;
  box-shadow:0 4px 18px rgba(0,0,0,.08);
  background:#000;
}

.yt-wrap iframe{
  position:absolute;
  inset:0;
  width:100%;
  height:100%;
  border:0;
}

.yt-label{
  margin-top:6px;
  font-size:14px;
  font-weight:600;
  color:#333;
}

.section-caption{
  margin-top:14px;
  font-size:15px;
  color:#444;
  line-height:1.55;
}

/* ---------- footer ---------- */
.footer{
  text-align:center;
  margin-top:70px;
  font-size:.9em;
  color:#888;
}

.resource-note{
  text-align:center;
  font-size:14px;
  color:#777;
  margin-top:10px;
  font-style:italic;
}

/* ---------- responsive ---------- */
@media (max-width:700px){
  .yt-grid{ grid-template-columns:1fr; }
  h1{ font-size:2.2em; }
}

</style>
</head>

<body>
<div class="container">

<h1 class="main-title">
Force-Regime Downward Compatibility in Contact-Rich Bimanual Imitation Learning
</h1>

<div class="authors">Anonymous Authors</div>
<div class="affiliation">Affiliation withheld for double-blind review</div>

<div class="links">
<a href="https://youtu.be/kj5nVsSxAcY" target="_blank">Video</a>
<a class="disabled">Hardware</a>
<a class="disabled">Dataset</a>
<a class="disabled">Paper</a>
<a class="disabled">Code</a>
</div>

<div class="resource-note">
This is a quick preview for collaborators; the formal website and submission videos will be updated within two days.
</div>

<!-- OVERVIEW -->
<div class="section">
<h2>Overview</h2>
<p>
We study force-regime generalization in contact-rich bimanual stopper removal.
The visual task remains nearly identical across conditions, but the hidden pulling resistance changes.
The preview videos show representative policy behaviors under programmable force regimes and real-bottle pressure-induced resistance.
</p>

<div class="kpi">

<div class="card">
<div class="big">Hidden force regimes</div>
<div class="small">
A programmable bottle-like device changes pulling resistance while preserving the external task geometry and visual appearance.
</div>
</div>

<div class="card">
<div class="big">Downward compatibility</div>
<div class="small">
High-force-trained policies transfer to easier regimes, while lower-force policies fail when tested under harder resistance.
</div>
</div>

<div class="card">
<div class="big">Real-bottle validation</div>
<div class="small">
Atmospheric-pressure and negative-pressure wine-bottle conditions provide a realistic harder/easier comparison outside the programmable device.
</div>
</div>

</div>
</div>

<!-- MAIN VIDEO -->
<div id="video" class="section">
<h2>Main Preview Video</h2>
<div class="video">
<iframe src="https://www.youtube.com/embed/kj5nVsSxAcY" allowfullscreen></iframe>
</div>

<div class="section-caption">
  <strong>Main Preview.</strong>
  This video provides a quick collaborator-facing overview of the task setup, programmable force regimes, and representative policy behaviors.
  The formal submission video is still under preparation.
</div>
</div>

<!-- ===== Programmable Device Videos ===== -->
<div id="programmable-videos" class="section">
<h2>Programmable Device Cross-Regime Videos</h2>

<p>
These videos show representative ACT policy rollouts on the programmable stopper-removal device.
Rows correspond to the training force regime and columns correspond to the test force regime.
The highlighted cases illustrate both in-regime execution and asymmetric force-regime transfer.
</p>

<div class="yt-grid">

<div class="yt-card"><div class="yt-wrap">
<iframe src="https://www.youtube.com/embed/3nCS5D1Bua0?mute=1" allowfullscreen></iframe>
</div><div class="yt-label">3 N-Trained Policy Tested under 0 N Resistance</div></div>

<div class="yt-card"><div class="yt-wrap">
<iframe src="https://www.youtube.com/embed/tlnyckENcog?mute=1" allowfullscreen></iframe>
</div><div class="yt-label">In-Regime Execution: 3 N-Trained Policy Tested under 3 N Resistance</div></div>

<div class="yt-card"><div class="yt-wrap">
<iframe src="https://www.youtube.com/embed/Uqu3Ijqecrw?mute=1" allowfullscreen></iframe>
</div><div class="yt-label">Upward Transfer: 3 N-Trained Policy Tested under 6 N Resistance</div></div>

<div class="yt-card"><div class="yt-wrap">
<iframe src="https://www.youtube.com/embed/srl3XB_VHSI?mute=1" allowfullscreen></iframe>
</div><div class="yt-label">Upward Transfer Failure: 3 N-Trained Policy Tested under 9 N Resistance</div></div>

<div class="yt-card"><div class="yt-wrap">
<iframe src="https://www.youtube.com/embed/Lt2-2X9F7wk?mute=1" allowfullscreen></iframe>
</div><div class="yt-label">Downward Transfer: 9 N-Trained Policy Tested under 0 N Resistance</div></div>

<div class="yt-card"><div class="yt-wrap">
<iframe src="https://www.youtube.com/embed/Of9iHqqWSSw?mute=1" allowfullscreen></iframe>
</div><div class="yt-label">Downward Transfer: 9 N-Trained Policy Tested under 3 N Resistance</div></div>

<div class="yt-card"><div class="yt-wrap">
<iframe src="https://www.youtube.com/embed/3grfxw67uD8?mute=1" allowfullscreen></iframe>
</div><div class="yt-label">Downward Transfer: 9 N-Trained Policy Tested under 6 N Resistance</div></div>

<div class="yt-card"><div class="yt-wrap">
<iframe src="https://www.youtube.com/embed/_Dgg9G6eKDE?mute=1" allowfullscreen></iframe>
</div><div class="yt-label">In-Regime Execution: 9 N-Trained Policy Tested under 9 N Resistance</div></div>

<div class="section-caption">
  <strong>Programmable Device Videos.</strong>
  Representative rollouts corresponding to the highlighted train--test settings in the programmable force-regime matrix.
  The 9 N-trained policy transfers reliably to easier regimes, whereas the 3 N-trained policy fails when tested under sufficiently higher resistance.
</div>

</div>
</div>

<!-- ===== Real-Bottle AP/NP Videos ===== -->
<div id="real-bottle-videos" class="section">
<h2>Real-Bottle AP/NP Validation Videos</h2>

<p>
These videos show cross-condition testing on a real wine bottle with a pumpable vacuum stopper.
The atmospheric-pressure condition uses 0 pump cycles, while the negative-pressure condition uses 70 pump cycles before each trial.
</p>

<div class="yt-grid">

<div class="yt-card"><div class="yt-wrap">
<iframe src="https://www.youtube.com/embed/ginMLkt15Kc?mute=1" allowfullscreen></iframe>
</div><div class="yt-label">In-Regime Real-Bottle Execution: AP-Trained Policy Tested under 0-Pump AP</div></div>

<div class="yt-card"><div class="yt-wrap">
<iframe src="https://www.youtube.com/embed/MQDoPbmi6PE?mute=1" allowfullscreen></iframe>
</div><div class="yt-label">Real-Bottle Upward Transfer: 0-Pump AP-Trained Policy Tested under 70-Pump NP</div></div>

<div class="yt-card"><div class="yt-wrap">
<iframe src="https://www.youtube.com/embed/S44IkBpVMkw?mute=1" allowfullscreen></iframe>
</div><div class="yt-label">Real-Bottle Downward Transfer: 70-Pump NP-Trained Policy Tested under 0-Pump AP</div></div>

<div class="yt-card"><div class="yt-wrap">
<iframe src="https://www.youtube.com/embed/yIyjBJyEsAY?mute=1" allowfullscreen></iframe>
</div><div class="yt-label">In-Regime Real-Bottle Execution: NP-Trained Policy Tested under 70-Pump Negative Pressure</div></div>

<div class="section-caption">
  <strong>Real-Bottle AP/NP Videos.</strong>
  Representative real-bottle executions under atmospheric-pressure and negative-pressure conditions.
  The harder NP-trained policy transfers reliably to AP, whereas the easier AP-trained policy rarely succeeds under NP.
</div>

</div>
</div>

<div class="section">
  <h2>Citation</h2>
  <pre>
@article{ForceRegime2026,
title={Force-Regime Downward Compatibility in Contact-Rich Bimanual Imitation Learning},
author={Anonymous Authors},
journal={Under Review},
year={2026}
}
  </pre>
</div>

<div class="footer">
  Anonymous project page for collaborator preview.
</div>

</div>
</body>
</html>
