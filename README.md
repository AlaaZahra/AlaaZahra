
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Alaa Zahra — GitHub Profile</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Share+Tech+Mono&display=swap');
  *{box-sizing:border-box;margin:0;padding:0}
  :root{
    --green:#00ff88;--green2:#00cc66;--green3:#008844;
    --purple:#b44fff;--blue:#00aaff;--red:#ff4466;
    --bg:#0a0f0a;--bg2:#0f1a0f;--dim:#1e2e1e;--border:#1e3a1e;
    --amber:#ffaa00;--mono:'Share Tech Mono',monospace;
  }
  body{background:var(--bg);color:var(--green);font-family:var(--mono);font-size:13px;line-height:1.6;padding:0}
  .scanlines{pointer-events:none;position:fixed;top:0;left:0;width:100%;height:100%;background:repeating-linear-gradient(0deg,transparent,transparent 2px,rgba(0,255,0,0.02) 2px,rgba(0,255,0,0.02) 4px);z-index:999}
  .wrap{max-width:860px;margin:0 auto;padding:20px 16px;position:relative;z-index:1}
  .terminal-bar{background:var(--dim);border:1px solid var(--border);border-bottom:none;border-radius:8px 8px 0 0;padding:8px 14px;display:flex;align-items:center;gap:8px}
  .dot{width:12px;height:12px;border-radius:50%}
  .dot.r{background:#ff5f56}.dot.y{background:#ffbd2e}.dot.g{background:#27c93f}
  .term-title{color:#4a6a4a;font-size:11px;margin-left:4px}
  .terminal{background:var(--bg2);border:1px solid var(--border);border-radius:0 0 8px 8px;padding:20px;margin-bottom:20px}
  .prompt{color:var(--green3)}
  .cmd{color:var(--green)}
  .output{color:#5a8a5a;margin:4px 0 4px 16px}
  .hi{color:var(--green);font-weight:bold}
  .purple{color:var(--purple)}
  .blue{color:var(--blue)}
  .red{color:var(--red)}
  .amber{color:var(--amber)}
  .cursor{display:inline-block;width:9px;height:14px;background:var(--green);animation:blink 1s step-end infinite;vertical-align:middle}
  @keyframes blink{0%,100%{opacity:1}50%{opacity:0}}
  .ascii-name{font-size:10px;line-height:1.15;color:var(--green);white-space:pre;overflow-x:auto}
  .grid{display:grid;grid-template-columns:1fr 1fr;gap:14px;margin-bottom:20px}
  .card{background:var(--bg2);border:1px solid var(--border);border-radius:8px;padding:16px;position:relative;overflow:hidden}
  .card::before{content:'';position:absolute;top:0;left:0;right:0;height:2px;background:linear-gradient(90deg,transparent,var(--green),transparent)}
  .card-title{color:var(--green3);font-size:11px;letter-spacing:2px;text-transform:uppercase;margin-bottom:12px}
  .badge{display:inline-block;padding:2px 8px;border-radius:3px;font-size:11px;margin:3px 2px;border:1px solid}
  .badge.sec{color:var(--green);border-color:var(--green3);background:rgba(0,255,136,0.05)}
  .badge.ai{color:var(--blue);border-color:#004488;background:rgba(0,170,255,0.05)}
  .badge.cloud{color:var(--purple);border-color:#440088;background:rgba(180,79,255,0.05)}
  .badge.tool{color:var(--amber);border-color:#664400;background:rgba(255,170,0,0.05)}
  .stat-row{display:flex;justify-content:space-around;margin-top:16px;padding-top:14px;border-top:1px solid var(--border)}
  .stat{text-align:center}
  .stat-num{font-size:22px;color:var(--green)}
  .stat-label{font-size:10px;color:#4a6a4a;letter-spacing:1px}
  .proj{background:var(--bg2);border:1px solid var(--border);border-radius:8px;padding:14px 16px;margin-bottom:12px}
  .proj-head{display:flex;justify-content:space-between;align-items:flex-start;margin-bottom:6px}
  .proj-name{color:var(--green);font-size:13px}
  .proj-date{color:#4a6a4a;font-size:11px}
  .proj-desc{color:#5a8a5a;font-size:12px;margin-bottom:8px}
  .proj-link{color:var(--blue);font-size:11px;text-decoration:none}
  .proj-link:hover{color:var(--green)}
  .section-head{color:var(--green3);font-size:11px;letter-spacing:3px;text-transform:uppercase;margin:20px 0 10px;padding-bottom:6px;border-bottom:1px solid var(--border)}
  .online-dot{display:inline-block;width:8px;height:8px;border-radius:50%;background:var(--green);animation:pulse 2s ease-in-out infinite;margin-right:6px;vertical-align:middle}
  @keyframes pulse{0%,100%{box-shadow:0 0 0 0 rgba(0,255,136,0.4)}50%{box-shadow:0 0 0 6px rgba(0,255,136,0)}}
  .glitch{position:relative;display:inline-block}
  .glitch::before,.glitch::after{content:attr(data-text);position:absolute;top:0;left:0;width:100%}
  .glitch::before{color:var(--red);animation:g1 3s infinite;clip-path:polygon(0 0,100% 0,100% 40%,0 40%)}
  .glitch::after{color:var(--blue);animation:g2 3s infinite;clip-path:polygon(0 60%,100% 60%,100% 100%,0 100%)}
  @keyframes g1{0%,94%,100%{transform:none;opacity:0}95%{transform:translate(-2px,1px);opacity:0.8}97%{transform:translate(2px,-1px);opacity:0.8}}
  @keyframes g2{0%,94%,100%{transform:none;opacity:0}96%{transform:translate(2px,1px);opacity:0.8}98%{transform:translate(-2px,-1px);opacity:0.8}}
  @media(max-width:600px){.grid{grid-template-columns:1fr}.ascii-name{font-size:7px}}
</style>
</head>
<body>

<div class="scanlines"></div>
<div class="wrap">

  <div class="terminal-bar">
    <div class="dot r"></div><div class="dot y"></div><div class="dot g"></div>
    <span class="term-title">alaa@cyberlab:~$</span>
  </div>
  <div class="terminal">
    <pre class="ascii-name">
 ░█████╗░██╗░░░░░░█████╗░░█████╗░
 ██╔══██╗██║░░░░░██╔══██╗██╔══██╗
 ███████║██║░░░░░███████║███████║
 ██╔══██║██║░░░░░██╔══██║██╔══██║
 ██║░░██║███████╗██║░░██║██║░░██║
 ╚═╝░░╚═╝╚══════╝╚═╝░░╚═╝╚═╝░░╚═╝</pre>

    <div style="margin-top:14px">
      <span class="prompt">root@cyberlab:~$ </span><span class="cmd">whoami</span><br>
      <div class="output">
        <span class="online-dot"></span>
        <span class="glitch" data-text="Alaa Zahra">Alaa Zahra</span>
        — <span class="purple">Cybersecurity Researcher</span> · <span class="blue">AI/ML Engineer</span> · <span class="amber">SOC Analyst (incoming)</span>
      </div>

      <div style="margin-top:10px">
        <span class="prompt">root@cyberlab:~$ </span><span class="cmd">cat status.txt</span><br>
        <div class="output">
          <span class="hi">[+]</span> M.Sc. Cybersecurity — Queen's University, Canada <span class="amber">[IN PROGRESS]</span><br>
          <span class="hi">[+]</span> Digilians Initiative — Ministry of Communications × Armed Forces Academy <span style="color:var(--green2)">[ACTIVE]</span><br>
          <span class="hi">[+]</span> B.Sc. Computer Science — Benha University <span style="color:var(--green2)">[COMPLETE — Very Good]</span><br>
          <span class="hi">[+]</span> Location: Cairo, EG → Kingston, CA
        </div>
      </div>

      <div style="margin-top:10px">
        <span class="prompt">root@cyberlab:~$ </span><span class="cmd">ping cyshield.com --project "js-deobfuscation"</span><br>
        <div class="output">
          <span class="hi">[+]</span> Proposing: <span class="purple">AI-Based JavaScript De-obfuscation Engine</span><br>
          <span class="hi">[+]</span> Stack: LLM fine-tuning · AST static analysis · Chain-of-Thought prompting<br>
          <span class="red">[!]</span> Research gap confirmed — no fine-tuned model exists for malicious JS yet
        </div>
      </div>

      <div style="margin-top:10px">
        <span class="prompt">root@cyberlab:~$ </span><span class="cursor"></span>
      </div>
    </div>
  </div>

  <div class="grid">
    <div class="card">
      <div class="card-title">// tools_loaded[]</div>
      <span class="badge sec">Kali Linux</span>
      <span class="badge sec">Wireshark</span>
      <span class="badge sec">Fortinet</span>
      <span class="badge sec">HCIA</span>
      <span class="badge tool">GNS3</span>
      <span class="badge tool">Packet Tracer</span>
      <span class="badge tool">VMware</span>
      <span class="badge cloud">AWS</span>
      <span class="badge cloud">Terraform</span>
      <span class="badge cloud">Docker</span>
      <span class="badge ai">TensorFlow</span>
      <span class="badge ai">XGBoost</span>
      <span class="badge ai">Llama 3.2</span>
      <span class="badge ai">HuggingFace</span>
      <span class="badge ai">Streamlit</span>
      <span class="badge tool">Jupyter</span>
    </div>

    <div class="card">
      <div class="card-title">// focus_areas[]</div>
      <div class="output" style="margin:0">
        <span class="hi">[01]</span> <span class="purple">Malware Analysis</span> &amp; Reverse Engineering<br>
        <span class="hi">[02]</span> <span class="blue">AI-Driven</span> Threat Detection<br>
        <span class="hi">[03]</span> <span class="amber">Network Security</span> &amp; SOC Operations<br>
        <span class="hi">[04]</span> <span style="color:var(--green2)">Cloud-Native</span> Security Pipelines<br>
        <span class="hi">[05]</span> <span class="red">Code De-obfuscation</span> Research<br>
        <span class="hi">[06]</span> <span class="purple">LLM Fine-tuning</span> &amp; Deployment
      </div>
      <div class="stat-row">
        <div class="stat"><div class="stat-num">6</div><div class="stat-label">repos</div></div>
        <div class="stat"><div class="stat-num">7+</div><div class="stat-label">HF spaces</div></div>
        <div class="stat"><div class="stat-num">2</div><div class="stat-label">countries</div></div>
      </div>
    </div>
  </div>

  <div class="section-head">// recent_commits</div>

  <div class="proj">
    <div class="proj-head">
      <span class="proj-name"><span style="color:var(--green2)">&#9654;</span> cloud-project-main</span>
      <span class="proj-date">May 2026</span>
    </div>
    <div class="proj-desc">End-to-end AWS ML pipeline · 31.7 GB data · Llama 3.2 fine-tune via QLoRA · $0.88 total cost</div>
    <div>
      <span class="badge cloud">AWS</span><span class="badge cloud">Terraform</span><span class="badge cloud">EMR</span><span class="badge ai">QLoRA</span><span class="badge ai">Ollama</span>
      <a class="proj-link" href="https://github.com/AlaaZahra/cloud-project-main" style="float:right">→ github</a>
    </div>
  </div>

  <div class="proj">
    <div class="proj-head">
      <span class="proj-name"><span style="color:var(--green2)">&#9654;</span> ioc-sentinel</span>
      <span class="proj-date">Apr 2026</span>
    </div>
    <div class="proj-desc">Automated IOC extraction &amp; correlation engine for threat hunting · deployed live on HuggingFace</div>
    <div>
      <span class="badge sec">Threat Intel</span><span class="badge ai">Streamlit</span><span class="badge tool">Python</span>
      <a class="proj-link" href="https://github.com/AlaaZahra/ioc-sentinel" style="float:right">→ github</a>
    </div>
  </div>

  <div class="proj">
    <div class="proj-head">
      <span class="proj-name"><span style="color:var(--green2)">&#9654;</span> HousePricePrediction</span>
      <span class="proj-date">Feb 2026</span>
    </div>
    <div class="proj-desc">7-model regression study · Stacking Ensemble R²=0.9085 · Optuna + SHAP explainability</div>
    <div>
      <span class="badge ai">XGBoost</span><span class="badge ai">LightGBM</span><span class="badge ai">SHAP</span><span class="badge tool">Optuna</span>
      <a class="proj-link" href="https://github.com/AlaaZahra/HousePricePrediction" style="float:right">→ github</a>
    </div>
  </div>

  <div class="section-head">// connect</div>

  <div class="terminal" style="padding:14px">
    <span class="prompt">root@cyberlab:~$ </span><span class="cmd">cat links.sh</span><br>
    <div class="output" style="margin-top:8px">
      <a href="https://www.linkedin.com/in/alaa-zahra-59845b228/" style="color:var(--blue);text-decoration:none">
        <span class="hi">[linkedin]</span> /in/alaa-zahra-59845b228
      </a><br>
      <a href="https://huggingface.co/alaaabdelmaksod" style="color:var(--purple);text-decoration:none">
        <span class="hi">[huggingface]</span> alaaabdelmaksod — 7 deployed spaces
      </a><br>
      <a href="mailto:alaaabdelmaksodzahra@gmail.com" style="color:var(--green2);text-decoration:none">
        <span class="hi">[email]</span> alaaabdelmaksodzahra@gmail.com
      </a>
    </div>
  </div>

  <div style="text-align:center;margin-top:16px;color:#2a4a2a;font-size:11px">
    <span style="animation:blink 2s step-end infinite;display:inline-block">[ unauthorized access will be traced and prosecuted ]</span>
  </div>

</div>
</body>
</html>
