---
layout: default
---

<div class="home">
  {%- if page.title -%}
    <h1 class="page-heading">{{ page.title }}</h1>
  {%- endif -%}

  {{ content }}

  <div class="intro-box">
    <h2>🎯 Mission</h2>
    <p>To collect, organize, and promote practical healthcare reform ideas that can lower costs, increase transparency, and improve outcomes for all Americans.</p>
    
    <blockquote>
      <em>"I don't want to be 95 and look and say 'I was president,' but I didn't get to know my kids at all. I'd rather say, 'I f---ed up healthcare and everybody's healthier and got a better world to live in.'"</em>
      <br>— Mark Cuban
    </blockquote>
  </div>

  <h2>📂 Browse Ideas by Category</h2>

  <div class="category-grid">
    <a href="{{ '/ideas/drug-pricing/' | relative_url }}" class="category-card">
      <h3>💊 Drug Pricing</h3>
      <p>Cost-plus models, PBM reform, price transparency, importation</p>
    </a>

    <a href="{{ '/ideas/insurance/' | relative_url }}" class="category-card">
      <h3>🛡️ Insurance</h3>
      <p>Premium transparency, direct primary care, price mandates</p>
    </a>

    <a href="{{ '/ideas/hospital-care/' | relative_url }}" class="category-card">
      <h3>🏥 Hospital & Care</h3>
      <p>Facility fees, out-of-network charges, all-payer rates</p>
    </a>
  </div>

  <h2>✨ Key Principles</h2>

  <ul class="principles">
    <li><strong>Transparency First</strong> — All pricing should be visible and understandable</li>
    <li><strong>Cut Middlemen</strong> — Eliminate entities that add cost without value</li>
    <li><strong>Patient-Centered</strong> — Reforms should prioritize patient outcomes and costs</li>
    <li><strong>Evidence-Based</strong> — Ideas backed by data and real-world examples</li>
    <li><strong>Bipartisan</strong> — Focus on solutions that can gain broad support</li>
  </ul>

  <div class="cta-box">
    <h2>🤝 Contribute</h2>
    <p>This is a community project. Have a healthcare reform idea with a credible source?</p>
    <a href="https://github.com/mokclaw/healthcare-reform-ideas/issues/new?template=new_reform_idea.md" class="btn">Submit an Idea</a>
    <a href="{{ '/contributing/' | relative_url }}" class="btn btn-secondary">Read Guidelines</a>
  </div>

</div>
