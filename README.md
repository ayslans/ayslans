<!doctype html>
<html lang="pt-BR"><head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Francisco Silva | README</title>
  <script src="https://cdn.tailwindcss.com/3.4.17"></script>
  <link href="https://fonts.googleapis.com/css2?family=Space+Mono:wght@400;700&amp;family=Alegreya:wght@400;500;700&amp;display=swap" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/lucide@0.263.0/dist/umd/lucide.min.js"></script>
  <style>
        :root { --vh: 1vh; }
        body { font-family: 'Alegreya', serif; }
        .mono { font-family: 'Space Mono', monospace; }
        .code-block { background: #ffffff; border: 1px solid #e5e7eb; }
        .glow { box-shadow: 0 0 20px rgba(99, 102, 241, 0.15); }
        .typing::after { content: '|'; animation: blink 1s step-end infinite; color: #7c3aed; }
        @keyframes blink { 50% { opacity: 0; } }
        @keyframes fadeUp { from { opacity: 0; transform: translateY(20px); } to { opacity: 1; transform: translateY(0); } }
        .fade-up { animation: fadeUp 0.6s ease forwards; }
        .fade-up-1 { animation-delay: 0.1s; opacity: 0; }
        .fade-up-2 { animation-delay: 0.2s; opacity: 0; }
        .fade-up-3 { animation-delay: 0.3s; opacity: 0; }
        .fade-up-4 { animation-delay: 0.4s; opacity: 0; }
        .badge { background: #f3f4f6; border: 1px solid #d1d5db; transition: all 0.2s; }
        .badge:hover { border-color: #7c3aed; transform: translateY(-2px); }
        .project-card { transition: all 0.3s; }
        .project-card:hover { transform: translateY(-4px); box-shadow: 0 8px 30px rgba(99, 102, 241, 0.2); }
    </style>
  <script src="/_sdk/data_sdk.js" type="text/javascript"></script>
  <script src="/_sdk/resizing_sdk.js" type="text/javascript"></script>
 </head>
 <body data-template-id="__page-root" class="min-h-screen text-gray-900" style="background: rgb(255, 255, 255);">
  <div class="w-full max-w-4xl mx-auto px-4 py-12 sm:px-8">
   <!-- Header -->
   <header class="mb-12 fade-up">
    <div class="code-block rounded-lg p-6 glow">
     <div class="flex items-center gap-2 mb-4">
      <span class="w-3 h-3 rounded-full bg-red-500"></span> <span class="w-3 h-3 rounded-full bg-yellow-500"></span> <span class="w-3 h-3 rounded-full bg-green-500"></span> <span class="mono text-xs text-gray-500 ml-2">readme.md</span>
     </div>
     <p class="mono text-gray-500 text-sm mb-1">// profile</p>
     <h1 data-template-id="hero-name" class="canva-text mono font-bold text-2xl sm:text-3xl mb-2" style="color: rgb(17, 24, 39); font-weight: 700; font-style: normal; font-size: 40px;">Francisco Silva</h1>
     <p data-template-id="hero-subtitle" class="canva-text mono text-sm sm:text-base typing" style="color: rgb(124, 58, 237); font-weight: 400; font-style: normal; font-size: 20px;">IA, Dados e Estratégia de Inovação</p>
    </div>
   </header><!-- About -->
   <section class="mb-12 fade-up fade-up-1">
    <h2 data-template-id="about-title" class="canva-text mono font-bold text-lg mb-4" style="color: rgb(124, 58, 237); font-weight: 700; font-style: normal; font-size: 28px;">## 📖 Sobre Mim</h2>
    <div data-template-id="about-section" class="canva-section code-block rounded-lg p-5" style="background: rgb(255, 255, 255);">
     <p data-template-id="about-text" class="canva-text text-sm leading-relaxed" style="color: rgb(75, 85, 99); font-weight: 400; font-style: normal; font-size: 18px;">Graduando em Engenharia de Software e desenvolvedor fullstack desde os 14 anos. Bacharelado em Administração (UVA), Mestrando em Administração (UECE), aprovado para Executive Management na Bayswater College London (UK) pela IBS Americas/USP.</p>
    </div>
   </section><!-- Projects -->
   <section class="mb-12 fade-up fade-up-3">
    <h2 data-template-id="projects-title" class="canva-text mono font-bold text-lg mb-4" style="color: rgb(124, 58, 237); font-weight: 700; font-style: normal; font-size: 28px;">## 🚀 Projetos em Destaque</h2>
    <div class="grid gap-4 sm:grid-cols-2">
     <div data-template-id="project-1" class="canva-card code-block rounded-lg p-5 project-card" style="background: rgb(255, 255, 255);">
      <h3 data-template-id="project-1-name" class="canva-text mono font-bold mb-2" style="color: rgb(17, 24, 39); font-weight: 700; font-style: normal; font-size: 22px;">Vórtex AI</h3>
      <p data-template-id="project-1-desc" class="canva-text text-xs mb-3" style="color: rgb(75, 85, 99); font-weight: 400; font-style: normal; font-size: 16px;">Startup de Consultoria e Automação (TRL 3) — Agentes de IA para organizações e profissionais liberais.</p>
      <p data-template-id="project-1-stack" class="canva-text mono text-xs" style="color: rgb(16, 185, 129); font-weight: 400; font-style: normal; font-size: 15px;">stack: [Python, GCP, LLMs]</p>
     </div>
     <div data-template-id="project-2" class="canva-card code-block rounded-lg p-5 project-card" style="background: rgb(255, 255, 255);">
      <h3 data-template-id="project-2-name" class="canva-text mono font-bold mb-2" style="color: rgb(17, 24, 39); font-weight: 700; font-style: normal; font-size: 22px;">RFP-Analyzer Enterprise</h3>
      <p data-template-id="project-2-desc" class="canva-text text-xs mb-3" style="color: rgb(75, 85, 99); font-weight: 400; font-style: normal; font-size: 16px;">Arquitetura de Inteligência de Mercado — Análise automatizada de editais e licitações públicas.</p>
      <p data-template-id="project-2-stack" class="canva-text mono text-xs" style="color: rgb(16, 185, 129); font-weight: 400; font-style: normal; font-size: 15px;">stack: [Python, GCP, Vertex AI, Gemini]</p>
     </div>
     <div data-template-id="project-3" class="canva-card code-block rounded-lg p-5 project-card" style="background: rgb(255, 255, 255);">
      <h3 data-template-id="project-3-name" class="canva-text mono font-bold mb-2" style="color: rgb(17, 24, 39); font-weight: 700; font-style: normal; font-size: 22px;">Nexus AI (POC)</h3>
      <p data-template-id="project-3-desc" class="canva-text text-xs mb-3" style="color: rgb(75, 85, 99); font-weight: 400; font-style: normal; font-size: 16px;">Agente Inteligente para Gestão da Inovação — Automação de processos em hubs de inovação e P&amp;D.</p>
      <p data-template-id="project-3-stack" class="canva-text mono text-xs" style="color: rgb(16, 185, 129); font-weight: 400; font-style: normal; font-size: 15px;">stack: [Python, Agentic Workflows, LLM APIs]</p>
     </div>
     <div data-template-id="project-4" class="canva-card code-block rounded-lg p-5 project-card" style="background: rgb(255, 255, 255);">
      <h3 data-template-id="project-4-name" class="canva-text mono font-bold mb-2" style="color: rgb(17, 24, 39); font-weight: 700; font-style: normal; font-size: 22px;">Análise Setorial</h3>
      <p data-template-id="project-4-desc" class="canva-text text-xs mb-3" style="color: rgb(75, 85, 99); font-weight: 400; font-style: normal; font-size: 16px;">Modelagem estatística para compreender o impacto da IA no setor industrial.</p>
      <p data-template-id="project-4-stack" class="canva-text mono text-xs" style="color: rgb(16, 185, 129); font-weight: 400; font-style: normal; font-size: 15px;">stack: [TypeScript, R, Python, Bibliometrix]</p>
     </div>
    </div>
   </section><!-- Tech Stack -->
   <section class="mb-12 fade-up fade-up-4">
    <h2 data-template-id="stack-title" class="canva-text mono font-bold text-lg mb-4" style="color: rgb(124, 58, 237); font-weight: 700; font-style: normal; font-size: 28px;">## 🛠️ Tech Stack</h2>
    <div class="flex flex-wrap gap-2">
     <span data-template-id="tech-1" class="canva-tag badge rounded-md px-3 py-1 mono text-xs" style="color: rgb(124, 58, 237); font-weight: 400; font-style: normal; font-size: 16px;">Python</span> <span data-template-id="tech-2" class="canva-tag badge rounded-md px-3 py-1 mono text-xs" style="color: rgb(124, 58, 237); font-weight: 400; font-style: normal; font-size: 16px;">R</span> <span data-template-id="tech-3" class="canva-tag badge rounded-md px-3 py-1 mono text-xs" style="color: rgb(124, 58, 237); font-weight: 400; font-style: normal; font-size: 16px;">TypeScript</span> <span data-template-id="tech-4" class="canva-tag badge rounded-md px-3 py-1 mono text-xs" style="color: rgb(124, 58, 237); font-weight: 400; font-style: normal; font-size: 16px;">GCP</span> <span data-template-id="tech-5" class="canva-tag badge rounded-md px-3 py-1 mono text-xs" style="color: rgb(124, 58, 237); font-weight: 400; font-style: normal; font-size: 16px;">Vertex AI</span> <span data-template-id="tech-6" class="canva-tag badge rounded-md px-3 py-1 mono text-xs" style="color: rgb(124, 58, 237); font-weight: 400; font-style: normal; font-size: 16px;">BigQuery</span> <span data-template-id="tech-7" class="canva-tag badge rounded-md px-3 py-1 mono text-xs" style="color: rgb(124, 58, 237); font-weight: 400; font-style: normal; font-size: 16px;">Power BI</span> <span data-template-id="tech-8" class="canva-tag badge rounded-md px-3 py-1 mono text-xs" style="color: rgb(124, 58, 237); font-weight: 400; font-style: normal; font-size: 16px;">NLP</span> <span data-template-id="tech-9" class="canva-tag badge rounded-md px-3 py-1 mono text-xs" style="color: rgb(124, 58, 237); font-weight: 400; font-style: normal; font-size: 16px;">Deep Learning</span> <span data-template-id="tech-10" class="canva-tag badge rounded-md px-3 py-1 mono text-xs" style="color: rgb(124, 58, 237); font-weight: 400; font-style: normal; font-size: 16px;">Web Scraping</span>
    </div>
   </section><!-- Certifications -->
   <section class="mb-12"><img data-template-id="certifications-image" class="canva-image w-full rounded-lg" loading="lazy" src="canva://MAHJJFcgb1U/1" alt="International certifications badges collection including AWS, Terraform, Cisco, and other professional credentials">
   </section><!-- Contact -->
   <footer class="mb-8">
    <h2 data-template-id="contact-title" class="canva-text mono font-bold text-lg mb-4" style="color: rgb(124, 58, 237); font-weight: 700; font-style: normal; font-size: 28px;">## 📫 Contato</h2>
    <div class="code-block rounded-lg p-5 mono text-sm space-y-2">
     <p data-template-id="contact-web" class="canva-text" style="color: rgb(16, 185, 129); font-weight: 400; font-style: normal; font-size: 16px;">$ open https://www.vortexaiconsultoria.com</p>
     <p data-template-id="contact-linkedin" class="canva-text" style="color: rgb(16, 185, 129); font-weight: 400; font-style: normal; font-size: 16px;">$ curl linkedin.com/in/ayslanregino</p>
     <p data-template-id="contact-email" class="canva-text" style="color: rgb(16, 185, 129); font-weight: 400; font-style: normal; font-size: 16px;">$ mail contato@vortexaiconsultoria.com</p>
     <p data-template-id="contact-whatsapp" class="canva-text" style="color: rgb(16, 185, 129); font-weight: 400; font-style: normal; font-size: 16px;">$ msg +55 88 98221-2212</p>
    </div>
   </footer>
  </div>
  <script src="/_sdk/editing_sdk.js"></script>
  <script>
        lucide.createIcons();
    </script>
 <script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'9f8e110ae6475d0c',t:'MTc3ODMwMjA1MS4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script>
</body></html>
