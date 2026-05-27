---
layout: default
title: End-to-End Claim Management Optimization
---

<style>
  html, body {
    background: #0f172a !important;
    background-color: #0f172a !important;
    color: #f8fafc !important;
    font-family: ui-sans-serif, system-ui, sans-serif !important;
    margin: 0;
    padding: 0;
    width: 100% !important;
    max-width: 100% !important;
  }

  /* FORCE TOUS LES CONTENEURS PARENTS DU THÈME GITHUB PAGES À S'ÉLARGIR À 95% */
  .wrapper, .container, .page-content, main, #content, .site-content {
    max-width: 80% !important;
    width: 80% !important;
    margin-left: auto !important;
    margin-right: auto !important;
    padding: 0 !important;
  }
  
  /* Justification stricte de tous les textes */
  p, li, td, th {
    text-align: justify !important;
    text-justify: inter-word;
  }

  .glass-card {
    background: rgba(15, 23, 42, 0.65) !important;
    backdrop-filter: blur(12px);
    border: 1px solid rgba(255, 255, 255, 0.08);
    box-shadow: 0 20px 40px 0 rgba(0, 0, 0, 0.4);
  }

  /* PERSONNALISATION DE LA BARRE DE DÉFILEMENT HORIZONTALE DU MENU */
  .custom-nav-scrollbar::-webkit-scrollbar {
    height: 5px !important;
  }
  .custom-nav-scrollbar::-webkit-scrollbar-track {
    background: #0f172a !important;
    border-radius: 10px !important;
  }
  .custom-nav-scrollbar::-webkit-scrollbar-thumb {
    background: #06b6d4 !important; /* Barre Cyan */
    border-radius: 10px !important;
  }
  .custom-nav-scrollbar::-webkit-scrollbar-thumb:hover {
    background: #10b981 !important; /* Devient Émeraude au survol */
  }
  /* Support Firefox */
  .custom-nav-scrollbar {
    scrollbar-width: thin !important;
    scrollbar-color: #06b6d4 #0f172a !important;
  }

  /* Suppression des éléments résiduels injectés par les thèmes par défaut de GitHub Pages */
  body > footer, 
  body > hr,
  .site-footer,
  .footer-meta {
    display: none !important;
    visibility: hidden !important;
    opacity: 0 !important;
    height: 0 !important;
    padding: 0 !important;
    margin: 0 !important;
  }
</style>

<script src="https://cdn.tailwindcss.com"></script>
<link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

<div class="max-w-[95%] mx-auto px-2 md:px-4 py-12 space-y-16">

  <div data-aos="fade-down">
    <a href="./optimization.html" class="inline-flex items-center gap-2 text-xs font-semibold text-emerald-400 hover:underline transition">
      <i class="fa-solid fa-arrow-left"></i> Back to Process Optimization
    </a>
  </div>

  <header class="relative rounded-2xl border border-white/10 p-8 md:p-12 bg-cover bg-center overflow-hidden" 
          style="background-image: linear-gradient(135deg, rgba(15, 23, 42, 0.95) 30%, rgba(30, 27, 75, 0.8) 100%), url('https://images.unsplash.com/photo-1618005182384-a83a8bd57fbe?auto=format&fit=crop&w=1600&q=80');" 
          data-aos="fade-down" data-aos-delay="100">
    <div class="relative z-10 space-y-4">
      <span class="inline-block px-3 py-1 rounded-full text-xs font-semibold bg-emerald-500/10 text-emerald-400 border border-emerald-500/20">
        Case Study Analysis
      </span>
      <h1 class="text-3xl md:text-5xl font-extrabold tracking-tight leading-tight text-white">
        End-to-End Claim Management Optimization
      </h1>
      <p class="text-slate-300 text-sm md:text-lg font-medium max-w-4xl">
        Process Design, Structural Bottlenecks, and Automated Multi-Tiered Financial Reporting Engine
      </p>
    </div>
  </header>
  
  <nav class="sticky top-4 z-50 w-full backdrop-blur-md bg-slate-900/80 border border-white/10 rounded-xl p-4 shadow-xl">
    <div class="flex flex-col lg:flex-row items-center justify-between gap-4">
        <a href="#home" class="text-sm font-bold tracking-wider text-white hover:text-cyan-400 transition-colors uppercase flex items-center gap-2 shrink-0">
            <span class="text-cyan-400">⚡</span> End-To-End Claims
        </a>       
        <div class="custom-nav-scrollbar flex items-center gap-4 md:gap-6 text-[11px] md:text-xs font-semibold uppercase tracking-wider overflow-x-auto max-w-full whitespace-nowrap pb-2 lg:pb-0">
            <a href="#problem-statement" class="text-slate-300 hover:text-cyan-400 transition-colors px-1">Problem Statement</a>
            <a href="#bpmn-section" class="text-slate-300 hover:text-cyan-400 transition-colors px-1">BPMN Initial Process</a>
            <a href="#sql-section" class="text-slate-300 hover:text-cyan-400 transition-colors px-1">SQL Database</a>
            <a href="#excel-section" class="text-slate-300 hover:text-cyan-400 transition-colors px-1">Excel Results</a>
            <a href="#second-bpmn" class="text-slate-300 hover:text-cyan-400 transition-colors px-1">Bpmn Optimized Process</a>
            <a href="#comparative-matrix-section" class="text-slate-300 hover:text-cyan-400 transition-colors px-1">Comparative Matrix</a>
            <a href="#deliverables" class="text-slate-300 hover:text-cyan-400 transition-colors px-1">Deliverables</a>
        </div>
    </div>
  </nav>
  <div id="home"></div>

  <section class="glass-card p-6 md:p-8 rounded-xl space-y-4" data-aos="fade-up">
    <h2 class="text-xl font-bold flex items-center gap-2">
      <i class="fa-solid fa-circle-info text-cyan-400"></i>
      <span class="bg-gradient-to-r text-transparent bg-clip-text from-cyan-400 to-blue-500">Introduction & Process Description</span>
    </h2>
    <p class="text-slate-200 text-sm md:text-base leading-relaxed">
      Throughout what follows, the process described is that of a customer return followed by a claim. Failures will be identified, modeled, and a proposed solution will be resolved.
    </p>
    <div class="p-5 bg-slate-950/40 rounded-lg border border-white/5 space-y-4 text-xs md:text-sm text-slate-300">
      <p>
        The customer submits a complaint to the company after receiving the package. Customer Service receives and reviews the claim, deciding either to initiate the return process or to escalate the matter to the Legal Department. In the event of legal action, the return procedure is immediately suspended. If the return is deemed legitimate, the customer receives an email requesting they ship the product back within 30 days; otherwise, the process is terminated and marked as aborted.
      </p>
      <p>
        Once the product is received, technicians perform a quality inspection to assess its condition. If the item is in good condition and the defect originated during production, the Accounting Department is notified to issue a full 100% refund. If the product was damaged by the customer, a notification is sent to Accounting to process a partial refund of 85%, or 70% if the product is severely damaged.
      </p>
      <p>
        Simultaneously, the technicians log the product details into the Excel database and store the item in the warehouse. Meanwhile, the accountant calculates the final refund amount and executes the payment, thus concluding the process.
      </p>
    </div>
  </section>

  <section class="glass-card p-6 md:p-8 rounded-xl space-y-4" data-aos="fade-up" data-aos-delay="100">
    <h2 class="text-xl font-bold flex items-center gap-2">
      <i class="fa-solid fa-magnifying-glass-chart text-emerald-400"></i>
      <span class="bg-gradient-to-r text-transparent bg-clip-text from-cyan-400 to-emerald-400">Interpretation of the Situation</span>
    </h2>
    <p class="text-slate-300 text-sm md:text-base leading-relaxed">
      The process is structured around strict decision-making flows where technical and accounting actions are interdependent:
    </p>   
    <div class="grid grid-cols-1 md:grid-cols-2 gap-6 text-xs md:text-sm">
      <div class="p-5 rounded-lg bg-slate-950/50 border border-white/5 space-y-3">
        <span class="font-bold text-cyan-400 block text-sm"><i class="fa-solid fa-gavel"></i> Receipt & Validation</span>
        <p class="text-slate-300"><strong>Case A (Legitimate):</strong> Initiation of the return procedure. The customer is notified and has a 30-day window to return the product.</p>
        <p class="text-slate-300"><strong>Case B (Abusive/Slanderous):</strong> Immediate termination of the return flow and escalation to legal counsel for defamation proceedings.</p>
      </div>
      <div class="p-5 rounded-lg bg-slate-950/50 border border-white/5 space-y-3">
        <span class="font-bold text-emerald-400 block text-sm"><i class="fa-solid fa-calculator"></i> Business Rules for Refunds</span>
        <ul class="space-y-2 text-slate-300">
          <li>• <strong class="text-white">100% Refund:</strong> If the issue is a production defect OR if it's a customer defect AND the product is in good condition.</li>
          <li>• <strong class="text-white">85% Refund:</strong> If the issue is customer-related BUT the product is damaged.</li>
          <li>• <strong class="text-white">70% Refund:</strong> If the issue is customer-related AND the product is very damaged.</li>
        </ul>
      </div>
    </div>
    <p class="text-slate-400 text-xs italic flex items-center gap-2"><i class="fa-solid fa-circle-exclamation text-amber-500"></i> Return Period Management: If the product is not received within the 30-day deadline, the procedure is permanently aborted.</p>
  </section>

  <section class="glass-card p-6 md:p-8 rounded-xl space-y-4" data-aos="fade-up">
    <h2 id="problem-statement" class="text-xl font-bold flex items-center gap-2">
      <i class="fa-solid fa-triangle-exclamation text-yellow-500"></i>
      <span class="bg-gradient-to-r text-transparent bg-clip-text from-yellow-400 to-orange-500">Problem Statement</span>
    </h2>
    <p class="text-slate-300 text-sm md:text-base leading-relaxed">
      An audit of the current Excel-based system reveals several critical flaws regarding task synchronization and data integrity:
    </p>
    <div class="grid grid-cols-1 md:grid-cols-2 gap-6 text-xs md:text-sm  text-align:justify !important">
      <div class="p-4 rounded-lg bg-red-500/5 border border-red-500/10">
        <strong class="text-red-400 block mb-1"><i class="fa-solid fa-ban"></i> Lack of Parallelism:</strong> Currently, the process relies on a linear ‘handover’—technicians fill out their reports, and accounting must then manually consult the file to perform calculations. This sequential workflow causes data reading errors and significant payment delays.
      </div>
      <div class="p-4 rounded-lg bg-red-500/5 border border-red-500/10">
        <strong class="text-red-400 block mb-1"><i class="fa-solid fa-gears"></i> Business Rule Complexity:</strong> The multi-tiered refund structure (100%, 85%, 70%) based on the intersection of two variables (Issue Source vs. Product Condition) makes manual data entry in Excel extremely high-risk for financial inaccuracies.
      </div>
      <div class="p-4 rounded-lg bg-red-500/5 border border-red-500/10">
        <strong class="text-red-400 block mb-1"><i class="fa-solid fa-eye-slash"></i> Invisibility of Legal Exceptions:</strong> Claims escalated to the Legal Department (e.g., defamation cases) often fall off the standard tracking radar, creating a disconnect between Customer Service and the Legal team.
      </div>
      <div class="p-4 rounded-lg bg-red-500/5 border border-red-500/10">
        <strong class="text-red-400 block mb-1"><i class="fa-solid fa-clock"></i> Inefficient Deadline Management (Time-Outs):</strong> No automated alerts are generated at the 30-day mark (J+30). This forces a manual, line-by-line review to identify expired claims that should be aborted, leading to wasted operational hours.
      </div>
    </div>
  </section>

  <section id="bpmn-section" class="glass-card rounded-xl border border-white/10 p-6 md:p-8 space-y-6" data-aos="fade-up">
    <div class="border-b border-white/10 pb-4 space-y-1">
        <h2 class="text-xs font-bold text-amber-500 uppercase tracking-widest flex items-center gap-2">
            <i class="fas fa-history"></i> Legacy Architecture
        </h2>
        <p class="text-xl md:text-2xl font-bold text-white">Initial Process Modelling</p>
    </div>    
    <div class="flex flex-col xl:flex-row gap-8 items-start">          
        <div class="w-full xl:w-1/5 space-y-4">
            <div class="inline-flex items-center gap-1.5 px-2 py-1 bg-amber-500/10 text-amber-400 text-[10px] font-bold rounded border border-amber-500/20 uppercase tracking-wider">
                <span class="w-1.5 h-1.5 rounded-full bg-amber-500 animate-pulse"></span> Legacy Workflow
            </div>
            <h3 class="text-base font-bold text-white tracking-wide">Historical Workflow Overview</h3>
            <p class="text-xs text-slate-300 leading-relaxed">
                This diagram models the historical claims management workflow originally executed within the organization. It highlights a highly siloed structure split across 4 distinct lanes plagued by heavy manual dependencies.
            </p>
        </div>
        <div class="w-full xl:w-4/5 bg-slate-950/60 p-4 rounded-xl border border-white/5 shadow-2xl flex justify-center items-center">
            <img src="./images/Initial Process Modelling.drawio.png" alt="Initial Process Modelling" class="w-full h-auto max-w-full rounded-lg opacity-90 hover:opacity-100 transition-opacity duration-300 object-contain">
        </div>
    </div>
    <div class="grid grid-cols-1 md:grid-cols-2 xl:grid-cols-4 gap-4 pt-6 border-t border-white/5 text-xs">
        <div class="p-5 bg-slate-900/90 hover:bg-slate-800/80 rounded-xl border border-white/20 shadow-xl space-y-3 transition-all duration-300 backdrop-blur-sm">
            <div class="flex items-center gap-3 text-amber-400 border-b border-white/10 pb-2">
                <i class="fas fa-user-clock text-base text-amber-400 shrink-0"></i>
                <h4 class="text-xs tracking-wider uppercase text-white font-black">Customer Uncertainty</h4>
            </div>
            <p class="text-xs text-slate-300 leading-relaxed">No tracking system for the strict 30-day deadline, creating structural confusion regarding absolute expiration thresholds.</p>
        </div>
        <div class="p-5 bg-slate-900/90 hover:bg-slate-800/80 rounded-xl border border-white/20 shadow-xl space-y-3 transition-all duration-300 backdrop-blur-sm">
            <div class="flex items-center gap-3 text-amber-400 border-b border-white/10 pb-2">
                <i class="fas fa-shield-alt text-base text-amber-400 shrink-0"></i>
                <h4 class="text-xs tracking-wider uppercase text-white font-black">Manual Filtering</h4>
            </div>
            <p class="text-xs text-slate-300 leading-relaxed">Customer Service evaluates case legitimacy on a case-by-case model without structural anti-fraud validation layers.</p>
        </div>
        <div class="p-5 bg-slate-900/90 hover:bg-slate-800/80 rounded-xl border border-white/20 shadow-xl space-y-3 transition-all duration-300 backdrop-blur-sm">
            <div class="flex items-center gap-3 text-amber-400 border-b border-white/10 pb-2">
                <i class="fas fa-file-invoice text-base text-amber-400 shrink-0"></i>
                <h4 class="text-xs tracking-wider uppercase text-white font-black">Administrative Burden</h4>
            </div>
            <p class="text-xs text-slate-300 leading-relaxed">Technicians are forced to log data manually into independent local Excel sheets instead of shared relational nodes.</p>
        </div>
        <div class="p-5 bg-slate-900/90 hover:bg-slate-800/80 rounded-xl border border-white/20 shadow-xl space-y-3 transition-all duration-300 backdrop-blur-sm">
            <div class="flex items-center gap-3 text-amber-400 border-b border-white/10 pb-2">
                <i class="fas fa-exclamation-triangle text-base text-amber-400 shrink-0"></i>
                <h4 class="text-xs tracking-wider uppercase text-white font-black">Sequential Accounting</h4>
            </div>
            <p class="text-xs text-slate-300 leading-relaxed">Calculations executed strictly downstream by the accounting team, generating manual validation loops and calculation risks.</p>
        </div>
    </div>
  </section>

 <section class="glass-card p-6 rounded-xl space-y-4" data-aos="fade-up" data-aos-delay="100">
    <h2 class="text-xl font-bold flex items-center gap-2">
      <i class="fa-solid fa-square-poll-horizontal text-emerald-400"></i>
      <span class="bg-gradient-to-r text-transparent bg-clip-text from-cyan-400 to-emerald-400">The Optimized Process</span>
    </h2>
    <p class="text-slate-300 text-sm leading-relaxed text-justify">
      In this phase, I optimized the manual claim process by implementing a structured data model and automated calculation rules.
    </p>
    <div class="grid grid-cols-1 md:grid-cols-2 gap-6 pt-2">
      <div class="space-y-3">
        <h3 class="text-sm font-bold text-white uppercase tracking-wider"><span class="text-emerald-400 font-bold">Key Improvements</span></h3>
        <ul class="space-y-2 text-xs text-slate-300 text-justify">
          <li class="flex items-start gap-1.5">
            <i class="fa-solid fa-bolt text-emerald-400 mt-0.5"></i>
            <span><strong>Logic Automation:</strong> Replaced manual refund estimations with precise SQL-based logic (<span class="text-emerald-400 font-bold">CASE WHEN</span>) and Excel formulas.</span>
          </li>
          <li class="flex items-start gap-1.5">
            <i class="fa-solid fa-shield-halved text-emerald-400 mt-0.5"></i>
            <span><strong>Financial Accuracy:</strong> Developed a calculation engine that automatically applies 70%, 85%, or 100% refund rates based on product condition and issue source.</span>
          </li>
          <li class="flex items-start gap-1.5">
            <i class="fa-solid fa-hourglass-end text-emerald-400 mt-0.5"></i>
            <span><strong>Time-Fencing:</strong> Integrated a “30-day rule” to automatically flag or abort expired claims, protecting company cash flow.</span>
          </li>
        </ul>
      </div>
      <div class="space-y-3">
        <h3 class="text-sm font-bold text-white uppercase tracking-wider"><span class="text-emerald-400 font-bold">Tools & Implementation</span></h3>
        <ul class="space-y-2 text-xs text-slate-300 text-justify">
          <li class="flex items-start gap-1.5">
            <i class="fa-solid fa-code text-cyan-400 mt-0.5"></i>
            <span><strong>SQL Implementation:</strong> Enforced strict business constraints using <span class="text-emerald-400 font-bold">ENUM</span> types and automated updates.</span>
          </li>
          <li class="flex items-start gap-1.5">
            <i class="fa-solid fa-table text-cyan-400 mt-0.5"></i>
            <span><strong>Excel:</strong> Consolidated multiple fragmented data sources to create a unified reporting view.</span>
          </li>
          <li class="flex items-start gap-1.5">
            <i class="fa-solid fa-calculator text-cyan-400 mt-0.5"></i>
            <span><strong>Formulas:</strong> Used nested <span class="text-emerald-400 font-bold">IF</span> and <span class="text-emerald-400 font-bold">AND</span> (<span class="text-emerald-400 font-bold">WENN/UND</span>) logic to ensure zero errors on edge cases (e.g., “Unknown” sources).</span>
          </li>
        </ul>
      </div>
    </div>
    <div class="mt-4 p-4 rounded-lg bg-emerald-500/10 border border-emerald-500/20 text-center flex items-center justify-center gap-3">
      <i class="fa-solid fa-circle-check text-2xl text-emerald-400"></i>
      <span class="text-sm font-semibold text-white">
        Result: Reduced manual processing time and human calculation errors.
      </span>
    </div>
  </section>
  
  <section id="sql-section" class="glass-card p-6 md:p-8 rounded-xl space-y-4" data-aos="fade-up">
    <h2 class="text-xl font-bold flex items-center gap-2">
      <i class="fa-solid fa-database text-cyan-400"></i>
      <span class="bg-gradient-to-r text-transparent bg-clip-text from-cyan-400 to-blue-500">SQL Database Architecture</span>
    </h2>
    <p class="text-slate-300 text-sm leading-relaxed text-justify">
      Below is the comprehensive relational schema script, business validation logic constraints, and data reporting generation pipeline implemented to resolve the operational gaps:
    </p>
    <div class="p-5 bg-slate-950 rounded-xl border border-white/10 text-xs font-mono overflow-x-auto shadow-2xl space-y-1">
      <p class="text-emerald-500 font-semibold mb-2">-- 1. Table Creation with Strict Business Constraints</p>
      <p><span class="text-pink-400">CREATE TABLE</span> Claim_Management (</p>
      <p class="pl-4">claim_id <span class="text-cyan-400">INT PRIMARY KEY AUTO_INCREMENT</span>,</p>
      <p class="pl-4">customer_name <span class="text-cyan-400">VARCHAR(100) NOT NULL</span>,</p>
      <p class="pl-4">product_name <span class="text-cyan-400">VARCHAR(100) NOT NULL</span>,</p>
      <p class="pl-4">product_price <span class="text-cyan-400">DECIMAL(10,2) NOT NULL</span>,</p>
      <p class="pl-4">claim_date <span class="text-cyan-400">DATE NOT NULL</span>,</p>
      <p class="pl-4">process_status <span class="text-purple-400">ENUM</span>(<span class="text-orange-300">'Pending_Return'</span>, <span class="text-orange-300">'Received'</span>, <span class="text-orange-300">'Aborted'</span>, <span class="text-orange-300">'Legal_Dispute'</span>) <span class="text-cyan-400">DEFAULT</span> <span class="text-orange-300">'Pending_Return'</span>,</p>
      <p class="pl-4">product_condition <span class="text-purple-400">ENUM</span>(<span class="text-orange-300">'Good'</span>, <span class="text-orange-300">'Damaged'</span>, <span class="text-orange-300">'Very_Damaged'</span>, <span class="text-orange-300">'Not_Received'</span>) <span class="text-cyan-400">DEFAULT</span> <span class="text-orange-300">'Not_Received'</span>,</p>
      <p class="pl-4">issue_source <span class="text-purple-400">ENUM</span>(<span class="text-orange-300">'Production'</span>, <span class="text-orange-300">'Customer'</span>, <span class="text-orange-300">'Unknown'</span>) <span class="text-cyan-400">DEFAULT</span> <span class="text-orange-300">'Unknown'</span>,</p>
      <p class="pl-4">refund_percentage <span class="text-cyan-400">INT DEFAULT 0</span>,</p>
      <p class="pl-4">refund_amount <span class="text-cyan-400">DECIMAL(10,2) DEFAULT 0.00</span></p>
      <p class="mb-4">);</p>
      <p class="text-emerald-500 font-semibold mb-2">-- 2. Mock Data Insertion (2026 Audit Dataset)</p>
      <p><span class="text-pink-400">INSERT INTO</span> Claim_Management (customer_name, product_name, product_price, claim_date, process_status, product_condition, issue_source)</p>
      <p><span class="text-pink-400">VALUES</span></p>
      <p class="pl-4">(<span class="text-orange-300">'Alice Johnson'</span>, <span class="text-orange-300">'HP PC AMD RYZEN 2025'</span>, 1200.00, <span class="text-orange-300">'2026-05-01'</span>, <span class="text-orange-300">'Received'</span>, <span class="text-orange-300">'Very_Damaged'</span>, <span class="text-orange-300">'Customer'</span>),</p>
      <p class="pl-4">(<span class="text-orange-300">'Bob Smith'</span>, <span class="text-orange-300">'Google 10 Pixel Phone'</span>, 800.00, <span class="text-orange-300">'2026-05-05'</span>, <span class="text-orange-300">'Received'</span>, <span class="text-orange-300">'Good'</span>, <span class="text-orange-300">'Customer'</span>),</p>
      <p class="pl-4">(<span class="text-orange-300">'Charlie Davis'</span>, <span class="text-orange-300">'Lenovo Tab M12'</span>, 500.00, <span class="text-orange-300">'2026-05-08'</span>, <span class="text-orange-300">'Received'</span>, <span class="text-orange-300">'Damaged'</span>, <span class="text-orange-300">'Customer'</span>),</p>
      <p class="pl-4">(<span class="text-orange-300">'Hans Mustermann'</span>, <span class="text-orange-300">'Iphone 13'</span>, 1200.00, <span class="text-orange-300">'2026-05-04'</span>, <span class="text-orange-300">'Received'</span>, <span class="text-orange-300">'Damaged'</span>, <span class="text-orange-300">'Production'</span>),</p>
      <p class="pl-4">(<span class="text-orange-300">'David Wilson'</span>, <span class="text-orange-300">'Google Pixel 8 Phone'</span>, 300.00, <span class="text-orange-300">'2026-04-01'</span>, <span class="text-orange-300">'Pending_Return'</span>, <span class="text-orange-300">'Not_Received'</span>, <span class="text-orange-300">'Unknown'</span>);</p>
      <p class="text-emerald-500 font-semibold mt-4 mb-2">-- 3. Corrected Multi-Tiered Matrix Logic Execution</p>
      <p><span class="text-pink-400">UPDATE</span> Claim_Management</p>
      <p><span class="text-pink-400">SET</span> refund_percentage = <span class="text-purple-400">CASE</span></p>
      <p class="pl-8"><span class="text-cyan-400">WHEN</span> issue_source = <span class="text-orange-300">'Customer'</span> <span class="text-cyan-400">AND</span> product_condition = <span class="text-orange-300">'Good'</span> <span class="text-cyan-400">THEN</span> 100</p>
      <p class="pl-8"><span class="text-cyan-400">WHEN</span> issue_source = <span class="text-orange-300">'Production'</span> <span class="text-cyan-400">AND</span> product_condition = <span class="text-orange-300">'Damaged'</span> <span class="text-cyan-400">THEN</span> 100</p>
      <p class="pl-8"><span class="text-cyan-400">WHEN</span> issue_source = <span class="text-orange-300">'Customer'</span> <span class="text-cyan-400">AND</span> product_condition = <span class="text-orange-300">'Damaged'</span> <span class="text-cyan-400">THEN</span> 85</p>
      <p class="pl-8"><span class="text-cyan-400">WHEN</span> issue_source = <span class="text-orange-300">'Customer'</span> <span class="text-cyan-400">AND</span> product_condition = <span class="text-orange-300">'Very_Damaged'</span> <span class="text-cyan-400">THEN</span> 70</p>
      <p class="pl-8"><span class="text-cyan-400">ELSE</span> 0</p>
      <p class="pl-4"><span class="text-purple-400">END</span></p>
      <p><span class="text-pink-400">WHERE</span> process_status = <span class="text-orange-300">'Received'</span>;</p>
      <p class="text-emerald-500 font-semibold mt-4 mb-2">-- 4. Financial Calculations Layer</p>
      <p><span class="text-pink-400">UPDATE</span> Claim_Management</p>
      <p><span class="text-pink-400">SET</span> refund_amount = (product_price * refund_percentage / 100)</p>
      <p><span class="text-pink-400">WHERE</span> process_status = <span class="text-orange-300">'Received'</span>;</p>
      <p class="text-emerald-500 font-semibold mt-4 mb-2">-- 5. Final Granular Audit View Output</p>
      <p><span class="text-pink-400">SELECT</span> claim_id, customer_name, product_name,</p>
      <p class="pl-4"><span class="text-purple-400">CONCAT</span>(product_price, <span class="text-orange-300">' €'</span>) <span class="text-pink-400">AS</span> unit_price, issue_source, product_condition,</p>
      <p class="pl-4"><span class="text-purple-400">CONCAT</span>(refund_percentage, <span class="text-orange-300">'%'</span>) <span class="text-pink-400">AS</span> rate,</p>
      <p class="pl-4"><span class="text-purple-400">CONCAT</span>(refund_amount, <span class="text-orange-300">' €'</span>) <span class="text-pink-400">AS</span> total_refunded, process_status</p>
      <p><span class="text-pink-400">FROM</span> Claim_Management;</p>
    </div>
    <div class="p-4 glass-card rounded-xl border border-white/10 mt-4" data-aos="zoom-in">
      <h3 class="text-xs font-bold text-cyan-400 mb-4 uppercase tracking-widest"><span class="text-emerald-400 font-bold">Table with the previous mySQL code</span></h3>
      <img src="./images/sql-table-result.png" alt="Datas Table" class="w-full rounded-lg border border-white/5 shadow-2xl">
      <p class="text-[10px] text-slate-400 mt-2 italic text-center">Visual Table of the data compiled from the database terminal.</p>
    </div>
    <div class="mt-4 p-4 rounded-lg bg-emerald-500/10 border border-emerald-500/20 text-center flex items-center justify-center gap-3">
      <i class="fa-solid fa-circle-check text-2xl text-emerald-400"></i>
      <span class="text-sm font-semibold text-white">
        Result: Visualisation of the <span class="text-emerald-400 font-bold">optimized</span> Datas and significant reduction of human errors.
      </span>
    </div>
  </section>
    
  <section id="second-bpmn" class="glass-card rounded-xl border border-white/10 p-6 md:p-8 space-y-8" data-aos="fade-up">
    <div class="border-b border-white/10 pb-4 space-y-1">
        <h2 class="text-xs font-bold text-cyan-400 uppercase tracking-widest flex items-center gap-2">
            <i class="fas fa-magic"></i> Process Optimization
        </h2>
        <p class="text-xl md:text-2xl font-bold text-white">Target Automation Architecture</p>
    </div>
    <div class="flex flex-col xl:flex-row-reverse gap-8 items-start">         
        <div class="w-full xl:w-1/5 space-y-4">
            <div class="inline-flex items-center gap-1.5 px-2 py-1 bg-emerald-500/10 text-emerald-400 text-[10px] font-bold rounded border border-emerald-500/20 uppercase tracking-wider">
                <span class="w-1.5 h-1.5 rounded-full bg-emerald-500 animate-pulse"></span> Automated Target
            </div>
            <p class="text-xs text-slate-300 leading-relaxed">
                To optimize the claims management process within the enterprise, and building upon the backend logic introduced by the database refactoring, this target BPMN 2.0 diagram introduces structural improvements.
            </p>
        </div>
        <div class="w-full xl:w-4/5 bg-slate-950/60 p-4 rounded-xl border border-white/5 shadow-2xl flex justify-center items-center">
            <img src="./images/optimized process visualisation.drawio.png" alt="Optimized Process Target" class="w-full h-auto max-w-full rounded-lg opacity-90 hover:opacity-100 transition-opacity duration-300 object-contain">
        </div>
    </div>
    <div class="grid grid-cols-1 md:grid-cols-2 xl:grid-cols-4 gap-4 pt-6 border-t border-white/5 text-xs">           
        <div class="p-5 bg-slate-900/90 hover:bg-slate-800/80 rounded-xl border border-white/20 shadow-xl space-y-3 transition-all duration-300 backdrop-blur-sm">
            <div class="flex items-center gap-3 text-cyan-400 border-b border-white/10 pb-2">
                <i class="fas fa-calculator text-base text-emerald-400 shrink-0"></i>
                <h4 class="text-xs tracking-wider uppercase text-white font-black">Accounting Disintermediation</h4>
            </div>
            <p class="text-xs text-slate-300 leading-relaxed">Financial refund processing has been 100% automated via dynamic ERP system modules.</p>
        </div>
        <div class="p-5 bg-slate-900/90 hover:bg-slate-800/80 rounded-xl border border-white/20 shadow-xl space-y-3 transition-all duration-300 backdrop-blur-sm">
            <div class="flex items-center gap-3 text-cyan-400 border-b border-white/10 pb-2">
                <i class="fas fa-shield-alt text-base text-rose-400 shrink-0"></i>
                <h4 class="text-xs tracking-wider uppercase text-white font-black">Anti-Fraud Security</h4>
            </div>
            <p class="text-xs text-slate-300 leading-relaxed">Integration of an automated upstream validation layer (<span class="font-mono text-purple-300 bg-slate-950 px-1 py-0.5 rounded">Run defamation filter</span>).</p>
        </div>
        <div class="p-5 bg-slate-900/90 hover:bg-slate-800/80 rounded-xl border border-white/20 shadow-xl space-y-3 transition-all duration-300 backdrop-blur-sm">
            <div class="flex items-center gap-3 text-cyan-400 border-b border-white/10 pb-2">
                <i class="fas fa-tools text-base text-blue-400 shrink-0"></i>
                <h4 class="text-xs tracking-wider uppercase text-white font-black">Streamlined Workload</h4>
            </div>
            <p class="text-xs text-slate-300 leading-relaxed">Technical staff are completely unburdened from administrative overhead to focus on diagnostics.</p>
        </div>
        <div class="p-5 bg-slate-900/90 hover:bg-slate-800/80 rounded-xl border border-white/20 shadow-xl space-y-3 transition-all duration-300 backdrop-blur-sm">
            <div class="flex items-center gap-3 text-cyan-400 border-b border-white/10 pb-2">
                <i class="fas fa-database text-base text-amber-400 shrink-0"></i>
                <h4 class="text-xs tracking-wider uppercase text-white font-black">Centralized Integration</h4>
            </div>
            <p class="text-xs text-slate-300 leading-relaxed">Elimination of local Excel files in favor of unified database relational models.</p>
        </div>
    </div>
  </section>
  
<section id="comparative-matrix-section" class="glass-card rounded-xl border border-white/10 p-6 md:p-8 space-y-6" data-aos="fade-up">
    <div class="border-b border-white/10 pb-4 space-y-1">
        <h2 class="text-xs font-bold text-cyan-400 uppercase tracking-widest flex items-center gap-2">
            <i class="fas fa-exchange-alt"></i> Benchmark Metrics
        </h2>
        <p class="text-xl md:text-2xl font-bold text-white">Comparative Process Matrix (Before vs. After)</p>
    </div>
    <div class="overflow-x-auto rounded-xl border border-white/5 shadow-2xl bg-slate-950/40">
        <table class="w-full text-left border-collapse text-xs md:text-sm table-fixed">
            <thead>
                <tr class="bg-slate-900/90 border-b border-white/10 text-slate-200 font-semibold tracking-wider">
                    <th class="p-4 w-[22%] text-cyan-400 font-extrabold uppercase tracking-wider">Optimization Pillar</th>
                    <th class="p-4 w-[26%] text-amber-400 font-extrabold uppercase tracking-wider">Initial Process (Manual & Siloed)</th>
                    <th class="p-4 w-[26%] text-emerald-400 font-extrabold uppercase tracking-wider">Target Process (Automated via SQL / ERP)</th>
                    <th class="p-4 w-[26%] text-purple-400 font-extrabold uppercase tracking-wider">Operational & Business Impact</th>
                </tr>
            </thead>
            <tbody class="divide-y divide-white/5 text-slate-300">                    
                <tr class="hover:bg-white/[0.02] transition-colors">
                    <td class="p-4 w-[22%] font-bold text-white bg-white/[0.01] align-top">Financial Management</td>
                    <td class="p-4 w-[26%] align-top leading-relaxed">Manual processing, case calculation, and verification handled directly by the Accounting team.</td>
                    <td class="p-4 w-[26%] align-top leading-relaxed">End-to-end execution managed instantly by the CRM / ERP system layer integrated with Payment Gateway APIs.</td>
                    <td class="p-4 w-[26%] text-emerald-400 font-medium bg-emerald-500/[0.02] align-top leading-relaxed">Total elimination of customer waiting queues and zero administrative backlog for back-office teams.</td>
                </tr>
                <tr class="hover:bg-white/[0.02] transition-colors">
                    <td class="p-4 w-[22%] font-bold text-white bg-white/[0.01] align-top">Security & Filtering</td>
                    <td class="p-4 w-[26%] align-top leading-relaxed">Delayed, human validation of claim legitimacy post-ingestion.</td>
                    <td class="p-4 w-[26%] align-top leading-relaxed">Automated abuse filtering (<span class="font-mono text-purple-300">Run defamation filter</span>) triggered immediately upon form submission.</td>
                    <td class="p-4 w-[26%] text-emerald-400 font-medium bg-emerald-500/[0.02] align-top leading-relaxed">Immediate protection for operational teams against fraudulent, duplicate, or malicious inquiries.</td>
                </tr>
                <tr class="hover:bg-white/[0.02] transition-colors">
                    <td class="p-4 w-[22%] font-bold text-white bg-white/[0.01] align-top">Data Infrastructure</td>
                    <td class="p-4 w-[26%] align-top leading-relaxed">Siloed, local, and fragmented data logging stored within shared Excel files.</td>
                    <td class="p-4 w-[26%] align-top leading-relaxed">Interconnected relational databases mapping state models (<span class="italic text-slate-400">Refund rules, Inventory System, Payment Gateway</span>).</td>
                    <td class="p-4 w-[26%] text-emerald-400 font-medium bg-emerald-500/[0.02] align-top leading-relaxed">100% data integrity, unified audit trail tracking, and absolute prevention of manual human input errors.</td>
                </tr>
            </tbody>
        </table>
    </div>
  </section>

  <div class="p-6 glass-card rounded-xl border border-white/10" data-aos="zoom-in">
    <h3 id="excel-section" class="text-xs font-bold text-cyan-400 mb-4 uppercase tracking-widest">Representation in Excel Dashboard</h3>
    <img src="./images/excel-powerquery-dash.png" alt="Excel View" class="w-full rounded-lg border border-white/5 shadow-2xl">
  </div>
  
 <section id="deliverables" class="mt-12 grid grid-cols-1 md:grid-cols-2 gap-6" data-aos="fade-up">  
    <div class="p-6 glass-card rounded-xl border border-white/10 flex flex-col justify-between">
        <div>
            <h3 class="text-xs font-bold text-cyan-400 mb-4 uppercase tracking-widest flex items-center gap-2">
                <i class="fas fa-history text-amber-500"></i> Initial Case Documents
            </h3>
            <p class="text-slate-300 text-sm mb-6">
                Download the original files and the legacy workflow mapping before the automation process.
            </p>
        </div>        
        <div class="space-y-3">
            <a href="./documents/process-overview.pdf" download class="flex items-center justify-between p-3 bg-white/5 hover:bg-white/10 rounded-lg border border-white/5 transition-all group">
                <div class="flex items-center gap-3">
                    <i class="fas fa-file-pdf text-rose-500 group-hover:scale-110 transition-transform"></i>
                    <span class="text-xs text-slate-200 font-medium">Process Overview (PDF)</span>
                </div>
                <i class="fas fa-arrow-alt-circle-down text-slate-400 group-hover:text-emerald-400 transition-colors"></i>
            </a>
            <a href="./documents/Initial Process Modelling.drawio" download class="flex items-center justify-between p-3 bg-white/5 hover:bg-white/10 rounded-lg border border-white/5 transition-all group">
                <div class="flex items-center gap-3">
                    <i class="fas fa-project-diagram text-orange-400 group-hover:scale-110 transition-transform"></i>
                    <span class="text-xs text-slate-200 font-medium">Initial BPMN Process (DRAW.IO)</span>
                </div>
                <i class="fas fa-arrow-alt-circle-down text-slate-400 group-hover:text-emerald-400 transition-colors"></i>
            </a>
        </div>
    </div>
    <div class="p-6 glass-card rounded-xl border border-white/10 flex flex-col justify-between">
        <div>
            <h3 class="text-xs font-bold text-cyan-400 mb-4 uppercase tracking-widest flex items-center gap-2">
                <i class="fas fa-magic text-emerald-400"></i> Optimized Solutions
            </h3>
            <p class="text-slate-300 text-sm mb-6">
                Access the automated architecture, engineered scripts, and dynamic data visualizations.
            </p>
        </div>        
        <div class="space-y-3">
            <a href="./documents/optimized process visualisation.drawio" download class="flex items-center justify-between p-3 bg-white/5 hover:bg-white/10 rounded-lg border border-white/5 transition-all group">
                <div class="flex items-center gap-3">
                    <i class="fas fa-project-diagram text-emerald-400 group-hover:scale-110 transition-transform"></i>
                    <span class="text-xs text-slate-200 font-medium">Optimized BPMN Process (DRAW.IO)</span>
                </div>
                <i class="fas fa-arrow-alt-circle-down text-slate-400 group-hover:text-emerald-400 transition-colors"></i>
            </a>
            <a href="./database/script.sql" download class="flex items-center justify-between p-3 bg-white/5 hover:bg-white/10 rounded-lg border border-white/5 transition-all group">
                <div class="flex items-center gap-3">
                    <i class="fas fa-code text-blue-400 group-hover:scale-110 transition-transform"></i>
                    <span class="text-xs text-slate-200 font-medium">MySQL Database Script (Open with VS Code)</span>
                </div>
                <i class="fas fa-arrow-alt-circle-down text-slate-400 group-hover:text-emerald-400 transition-colors"></i>
            </a>
            <a href="./documents/excel-visualisation.xlsx" download class="flex items-center justify-between p-3 bg-white/5 hover:bg-white/10 rounded-lg border border-white/5 transition-all group">
                <div class="flex items-center gap-3">
                    <i class="fas fa-file-excel text-green-500 group-hover:scale-110 transition-transform"></i>
                    <span class="text-xs text-slate-200 font-medium">Excel Visualisation Dashboard (XLSX)</span>
                </div>
                <i class="fas fa-arrow-alt-circle-down text-slate-400 group-hover:text-emerald-400 transition-colors"></i>
            </a>
        </div>
    </div>
    <div class="col-span-full p-6 glass-card rounded-xl border border-white/10 flex flex-col sm:flex-row items-center justify-between gap-6 text-center sm:text-left">
        <div>
            <h3 class="text-xs font-bold text-cyan-400 mb-1 uppercase tracking-widest flex items-center justify-center sm:justify-start gap-2">
                <i class="fas fa-share-alt text-purple-400"></i> Connect with me
            </h3>
            <p class="text-slate-400 text-xs">
                Interested in process optimization and data engineering? Let's discuss this project on my networks.
            </p>
        </div>
        <div class="flex items-center gap-4">
            <a href="https://www.linkedin.com/in/winston-engamba-7b3489325/" target="_blank" rel="noopener noreferrer" 
               class="w-10 h-10 flex items-center justify-center rounded-lg bg-white/5 hover:bg-[#0077b5]/20 border border-white/5 hover:border-[#0077b5]/50 text-slate-300 hover:text-[#0077b5] transition-all duration-300 text-sm group" title="LinkedIn">
                <i class="fab fa-linkedin-in group-hover:scale-110 transition-transform"></i>
            </a>
            <a href="https://github.com/wero-git/" target="_blank" rel="noopener noreferrer" 
               class="w-10 h-10 flex items-center justify-center rounded-lg bg-white/5 hover:bg-white/20 border border-white/5 hover:border-white/50 text-slate-300 hover:text-white transition-all duration-300 text-sm group" title="GitHub">
                <i class="fab fa-github group-hover:scale-110 transition-transform"></i>
            </a>
            <a href="mailto:rodokomon24@gmail.com" 
               class="w-10 h-10 flex items-center justify-center rounded-lg bg-white/5 hover:bg-emerald-500/20 border border-white/5 hover:border-emerald-500/50 text-slate-300 hover:text-emerald-400 transition-all duration-300 text-sm group" title="Email">
                <i class="fas fa-envelope group-hover:scale-110 transition-transform"></i>
            </a>
        </div>
    </div>
  </section>

  <div class="mt-16 pt-6 border-t border-white/5 flex flex-col sm:flex-row items-center justify-between gap-4 text-xs text-slate-500">
    <div>© 2026 - End-to-End Claims Optimization Project BY Winston R. Engamba O.</div>
    <a href="#home" class="flex items-center gap-2 text-slate-400 hover:text-cyan-400 transition-all font-medium uppercase tracking-wider">
        Back to top <i class="fas fa-arrow-up text-emerald-400"></i>
    </a>
  </div>
</div>
<div class="pt-6 text-center" data-aos="fade-up">
    <a href="./index.html" class="inline-flex items-center gap-2 text-sm font-semibold text-cyan-400 hover:underline transition">
      <i class="fa-solid fa-house"></i> Back Home
    </a>
  </div>

<script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
<script>AOS.init({ duration: 800, once: true });</script>
