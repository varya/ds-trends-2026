<!-- .slide: class="cover" -->

<p class="cover-eyebrow">Design Systems · 2026</p>
<h1 class="cover-title">Let's talk about <span class="accent">design systems</span><br>in 2026</h1>
<p class="cover-tagline">How we build, ship, and consume them</p>
<p class="cover-meta"><strong>Varya Stepanova</strong> &nbsp;·&nbsp; 2026</p>

---

<p class="eyebrow">Intro</p>

## The questions have changed again

<div class="timeline">
  <div class="timeline-row"><span class="year">2020</span><span class="q">"Do we need a design system?"</span></div>
  <div class="timeline-row"><span class="year">2024</span><span class="q">"Is our design system adopted?"</span></div>
  <div class="timeline-row active"><span class="year">2026</span><span class="q">…</span></div>
</div>

<ul class="dotted fragment" data-fragment-index="1">
  <li>Can it work with AI agents?</li>
  <li>Does it survive when our team shrinks?</li>
  <li>Is it ready for the new accessibility laws?</li>
  <li>What's it for when interfaces are generated?</li>
</ul>

<div class="footer"><span class="url">ds-trends-2026</span><span class="mark">Intro</span></div>

---

<p class="eyebrow">Trend 1</p>

## From having a DS to shipping faster with it

<p class="lede">Adoption was the question of the last cycle. ROI is still a live conversation at many orgs. The new edge: <strong style="color: var(--teal);">how much does the DS speed up product delivery?</strong></p>

<ul class="dotted">
  <li>A few years ago, <em>adoption</em> was the frontier.</li>
  <li>Then ROI. For plenty of teams, that's still the conversation they're in.</li>
  <li>The trend now is sharper: tie the DS to <strong>time-to-ship</strong>. Days saved per feature, velocity per team, rework avoided.</li>
  <li>Speed isn't a soft metric. It's the one product leaders feel every quarter.</li>
</ul>

<p class="closer">A design system earns its keep by making the next feature cheaper than the last.</p>

<div class="footer"><span class="url">ds-trends-2026</span><span class="mark">Trend 1 &nbsp;·&nbsp; ↓ deep dive</span></div>

>>>

<p class="eyebrow">Trend 1 · Deep dive</p>

## Measuring without metrics theater

<p class="lede">The trap: measuring <em>everything</em> to prove value, instead of the few things that actually correlate with shipped product.</p>

<ul class="dotted">
  <li>What's worth measuring, and what isn't.</li>
  <li>Design-tool adoption vs. codebase adoption: the gap that matters.</li>
  <li>The "last mile" problem: only what's shipped counts.</li>
  <li>Adoption dashboards as a leadership instrument, not a DS-team trophy case.</li>
</ul>

<div class="footer"><span class="url">ds-trends-2026</span><span class="mark">Trend 1 · Deep dive</span></div>

---

<p class="eyebrow">Trend 2</p>

## The shrinking, embedded DS team

<p class="statement">The DS team got smaller. Maybe that's fine.</p>

<ul class="dotted">
  <li>The 2024–25 reset hit design system teams hard.</li>
  <li>The survivors are leaner, embedded in product, less centralized.</li>
  <li>The "big central DS team" model is in decline.</li>
  <li>What lasts: a small core that owns the system; ambassadors distributed across product teams.</li>
  <li>The work is increasingly <em>org</em> work: promoting, aligning expectations, deciding what the system <strong>doesn't</strong> do.</li>
</ul>

<p class="closer">A good design system can be run by three people, if the rest of the org is set up to carry it.</p>

<div class="footer"><span class="url">ds-trends-2026</span><span class="mark">Trend 2</span></div>

---

<p class="eyebrow">Trend 3</p>

## Headless has won the foundation

<p class="statement">Don't build primitives. Build <span class="accent" style="color: var(--teal);">expression</span>.</p>

<ul class="dotted">
  <li>Radix, React Aria, Base UI, Ariakit: the foundation layer is solved.</li>
  <li>Building your own dialog, popover, combobox from scratch is now a tax, not a craft.</li>
  <li>The differentiator moves up: brand, motion, density, voice, taste.</li>
  <li>This applies <strong>double for data-heavy UI</strong>: tables, charts, virtualization, dense forms, maps. Headless behaviour + your renderer = density, alarm semantics, and performance that off-the-shelf kits won't give you.</li>
  <li>The DS team's job: <strong>curate</strong> the foundation, <strong>own</strong> the expression.</li>
</ul>

<p class="closer">Where you used to spend a quarter, you now spend a week. Spend the saved quarter on what actually distinguishes you.</p>

<div class="footer"><span class="url">ds-trends-2026</span><span class="mark">Trend 3 &nbsp;·&nbsp; ↓ deep dive</span></div>

>>>

<p class="eyebrow">Trend 3 · Deep dive</p>

## Headless-first building blocks for data-heavy UI

<ul class="dotted">
  <li><strong>Tables &amp; grids:</strong> <a href="https://tanstack.com/table">TanStack Table</a>, <a href="https://react-spectrum.adobe.com/react-aria/Table.html">React Aria Table</a>, <a href="https://www.ag-grid.com/">AG Grid</a>, <a href="https://github.com/glideapps/glide-data-grid">Glide Data Grid</a>.</li>
  <li><strong>Virtualization:</strong> <a href="https://tanstack.com/virtual">TanStack Virtual</a>, <a href="https://virtuoso.dev/">React Virtuoso</a>.</li>
  <li><strong>Charts &amp; data viz:</strong> <a href="https://airbnb.io/visx/">Visx</a>, <a href="https://d3js.org/">D3</a>, <a href="https://observablehq.com/plot">Observable Plot</a>, <a href="https://echarts.apache.org/">Apache ECharts</a>, <a href="https://recharts.org/">Recharts</a>.</li>
  <li><strong>Combobox &amp; selection:</strong> <a href="https://www.downshift-js.com/">Downshift</a>, <a href="https://react-spectrum.adobe.com/react-aria/">React Aria</a>, <a href="https://ariakit.org/">Ariakit</a>, <a href="https://www.radix-ui.com/primitives/docs/components/select">Radix Select</a>, <a href="https://cmdk.paco.me/">cmdk</a>.</li>
  <li><strong>Maps &amp; geospatial:</strong> <a href="https://maplibre.org/">MapLibre GL</a>, <a href="https://leafletjs.com/">Leaflet</a>, <a href="https://visgl.github.io/react-map-gl/">react-map-gl</a>, <a href="https://deck.gl/">Deck.gl</a>.</li>
</ul>

<p class="closer">Headless first. Spend the saved time on what's yours: chart palette, alarm semantics, density, dark-mode-for-ops-rooms.</p>

<div class="footer"><span class="url">ds-trends-2026</span><span class="mark">Trend 3 · Deep dive</span></div>

---

<p class="eyebrow">Trend 4</p>

## Tokens as the universal contract

<p class="lede">Tokens are how design and engineering finally speak the same language.</p>

<ul class="dotted">
  <li>Most drift starts in the Figma → code handoff: designers ship something the codebase hasn't implemented yet.</li>
  <li>DTCG spec is maturing. There's now a real standard.</li>
  <li>Semantic token layers: <strong>brand → semantic → component</strong>.</li>
  <li>Tokens crossing platforms: web, native, embedded, print.</li>
  <li>Tokens as the <strong>contract</strong> between Figma and code, not a translation step.</li>
</ul>

<p class="closer">If your design and engineering disagree about anything visual, the answer is usually "more tokens, less prose."</p>

<div class="footer"><span class="url">ds-trends-2026</span><span class="mark">Trend 4 &nbsp;·&nbsp; ↓ 2 deep dives</span></div>

>>>

<p class="eyebrow">Trend 4 · Deep dive · i</p>

## The three-tier token system

<div class="split">
  <div class="tiers">
    <div class="tier t1">
      <span class="tier-label">Tier 1 · Brand</span>
      <div class="tier-title">Raw values</div>
      <div class="tier-desc">--color-blue-500: #0066ff;</div>
    </div>
    <div class="tier-arrow">↓</div>
    <div class="tier t2">
      <span class="tier-label">Tier 2 · Semantic</span>
      <div class="tier-title">Meaning, not pixels</div>
      <div class="tier-desc">--color-action-primary: var(--color-blue-500);</div>
    </div>
    <div class="tier-arrow">↓</div>
    <div class="tier t3">
      <span class="tier-callout">← AI's anchor</span>
      <span class="tier-label">Tier 3 · Component</span>
      <div class="tier-title">Component-scoped</div>
      <div class="tier-desc">--button-bg: var(--color-action-primary);</div>
    </div>
  </div>

  <div>
<pre class="code"><span class="c">/* Button.module.css */</span>
.button {
  <span class="t">--button-bg</span>: <span class="v">var(--color-action-primary)</span>;
  <span class="t">--button-fg</span>: <span class="v">var(--color-on-action)</span>;
  <span class="t">--button-radius</span>: <span class="v">var(--radius-control)</span>;

  <span class="k">background</span>: <span class="v">var(--button-bg)</span>;
  <span class="k">color</span>: <span class="v">var(--button-fg)</span>;
  <span class="k">border-radius</span>: <span class="v">var(--button-radius)</span>;
}

.button<span class="k">:hover</span> {
  <span class="t">--button-bg</span>: <span class="v">var(--color-action-primary-hover)</span>;
}
</pre>
    <p class="code-caption">To humans, Tier 3 looks like noise. Why scope <code>--button-bg</code> inside a file already called Button? To agents it's the opposite. They have no common sense to infer the right alias, but a uniform pattern repeated across every component becomes a convention they can generalize system-wide.</p>
  </div>
</div>

<p class="closer">Multi-brand without forking the codebase: swap Tier 1, leave Tier 2 and Tier 3 alone.</p>

<div class="footer"><span class="url">ds-trends-2026</span><span class="mark">Trend 4 · Deep dive · i &nbsp;·&nbsp; ↓ pipeline</span></div>

>>>

<p class="eyebrow">Trend 4 · Deep dive · ii</p>

## Tokens, automated end-to-end

<div class="pipeline">
  <div class="pl-node source">
    <h4>Source</h4>
    <div class="name">Figma variables</div>
    <div class="tools">DTCG · .tokens.json</div>
  </div>
  <div class="pl-arrow">→</div>
  <div class="pl-node transform">
    <h4>Transform</h4>
    <div class="name">Style Dictionary<br>Terrazzo</div>
    <div class="tools">resolve · validate · theme</div>
  </div>
  <div class="pl-arrow">→</div>
  <div class="pl-outputs">
    <h4>Outputs</h4>
    <ul>
      <li>CSS variables · :root</li>
      <li>Tailwind config · JS / TS consts</li>
      <li>iOS Swift · Android XML</li>
      <li>Storybook docs · type defs</li>
    </ul>
  </div>
</div>

<ul class="dotted">
  <li>One source, many targets. No hand-rewrites between platforms.</li>
  <li>DTCG (Design Tokens Community Group) is the standard the toolchain has converged on.</li>
  <li>Brand updates ship like dependency bumps: version, regen, deploy.</li>
</ul>

<p class="closer">When tokens are pipelined, "the new brand" is a PR, not a project.</p>

<div class="footer"><span class="url">ds-trends-2026</span><span class="mark">Trend 4 · Deep dive · ii</span></div>

---

<p class="eyebrow">Trend 5</p>

## Accessibility is now law

<p class="statement">One year into EAA enforcement. <span style="color: var(--red);">The grace period is over.</span></p>

<ul class="dotted">
  <li>The EU Accessibility Act came into effect June 2025. We're twelve months in.</li>
  <li>For products serving EU consumers, accessibility is no longer a values argument. It's compliance.</li>
  <li>The DS is the lever: a11y baked into primitives propagates to every product surface automatically.</li>
  <li>Teams that put accessibility into their tokens and components are now ahead. The ones that didn't are scrambling.</li>
</ul>

<p class="closer">The DS team's old advocacy quietly became the org's risk strategy.</p>

<div class="footer"><span class="url">ds-trends-2026</span><span class="mark">Trend 5</span></div>

---

<p class="eyebrow">Trend 6</p>

## Storybook over Figma

<p class="statement">Code agents can't read pixels. They can read Storybook.</p>

<ul class="dotted">
  <li>A Figma file is a picture. A Storybook page is <strong>text</strong>: props, types, examples, JSDoc, code snippets.</li>
  <li>For human readers, both worked. For AI agents, only one does.</li>
  <li>Storybook 9 is doubling down on this: a built-in MCP server, llms.txt export, machine-readable component manifests.</li>
  <li>The DS team's documentation work is now also infrastructure for agent adoption.</li>
</ul>

<p class="closer">Whatever isn't in text doesn't exist for the next consumer of your design system.</p>

<div class="footer"><span class="url">ds-trends-2026</span><span class="mark">Trend 6 &nbsp;·&nbsp; ↓ 2 deep dives</span></div>

>>>

<p class="eyebrow">Trend 6 · Deep dive · i</p>

## What Storybook 9 changed

<ul class="dotted">
  <li><strong>Built-in MCP server.</strong> Agents call Storybook directly for component APIs, validated patterns, and test suites.</li>
  <li><strong>llms.txt support.</strong> Text-only export of component docs, optimised for LLM consumption.</li>
  <li><strong>Component manifests.</strong> Auto-generated metadata (props, stories, docs) regenerates as you work. Agents always see the current state.</li>
  <li><strong>Test addon (Vitest).</strong> Stories become component tests automatically. Interaction, accessibility, and visual tests run in one widget.</li>
  <li><strong>JSDoc-driven Prop Table.</strong> Comment your component, get your prop docs for free. Machine-readable by default.</li>
  <li><strong>48% leaner core.</strong> Faster installs, fewer dependencies to vet.</li>
</ul>

<p class="closer">If you skipped Storybook last cycle because it was heavy, Storybook 9 is worth a second look.</p>

<div class="footer"><span class="url">ds-trends-2026</span><span class="mark">Trend 6 · i &nbsp;·&nbsp; ↓ more</span></div>

>>>

<p class="eyebrow">Trend 6 · Deep dive · ii</p>

## Customizations that make Storybook a doc-grade system

<div class="compare">
  <div class="then">
    <h3>For humans</h3>
    <ul>
      <li>Sidebar grouped: Components, Patterns, Templates</li>
      <li>Beta / Deprecated tags as sidebar badges</li>
      <li>Token palettes: colours, spaces, typography, radii (as MDX pages)</li>
      <li>Markdown-rendered pages: About, Get Started, Changelog</li>
      <li>Custom Docs Page: TOC, styled Prop Table, 2-column stories, story toolbar, Figma + GitHub links, footer</li>
    </ul>
  </div>
  <div class="now">
    <h3>For agents</h3>
    <ul>
      <li><strong>Copy Page</strong> button on every doc, grabs the plain-text version from <code>/llms/*.txt</code></li>
      <li>Prop Tables driven by <strong>JSDoc</strong>, not ArgTypes. Docs stay attached to code.</li>
      <li>Props <strong>grouped</strong>: general, visual, events, accessibility (via argTypesEnhancers)</li>
      <li>Component <strong>Import Snippet</strong> auto-generated from <code>useOf</code> hook</li>
      <li>Indexed sidebar, so agents can enumerate the catalogue</li>
    </ul>
  </div>
</div>

<p class="closer">A Storybook that serves both audiences is a Storybook the DS team only has to maintain once.</p>

<div class="footer"><span class="url">ds-trends-2026</span><span class="mark">Trend 6 · ii</span></div>

---

<p class="eyebrow">Trend 7 · Umbrella</p>

## AI changes who consumes the design system

<p class="lede">For fifteen years we built design systems for humans. That's no longer the only audience. Three shifts are happening at once. Code-side AI is further along than design-side AI, where the picture is still much fuzzier.</p>

<div class="cards">
  <div class="card">
    <span class="num">a</span>
    <h3>AI as the consumer</h3>
    <p>Agents read your DS to pick components. If they can't find one, it doesn't exist.</p>
  </div>
  <div class="card b">
    <span class="num">b</span>
    <h3>AI as the adoption engine</h3>
    <p>RAG over your past migrations + MCP retrieval = the system spreads itself.</p>
  </div>
  <div class="card r">
    <span class="num">c</span>
    <h3>AI as the generator</h3>
    <p>Generators amplify whatever is underneath. The DS is the guardrail.</p>
  </div>
</div>

<p class="closer">All three change what a design system is <em>for</em>. The next three slides take each in turn.</p>

<div class="footer"><span class="url">ds-trends-2026</span><span class="mark">Trend 7</span></div>

---

<p class="eyebrow">Trend 7a</p>

## Your design system is now read by agents

<ul class="dotted">
  <li>Coding agents (Claude Code, Cursor, Copilot) pick components by reading your docs.</li>
  <li>They miss what isn't machine-readable: nuance, intent, edge cases, the unwritten "don't use this here."</li>
  <li>MCP servers expose the DS as a <strong>structured contract</strong>: names, props, do/don't, examples.</li>
  <li>The new documentation audience: half human, half machine. Write for both.</li>
</ul>

<p class="closer">If an agent can't find your component, your component doesn't exist.</p>

<div class="footer"><span class="url">ds-trends-2026</span><span class="mark">Trend 7a</span></div>

---

<p class="eyebrow">Trend 7b</p>

## The design system as infrastructure

<p class="statement">Adoption is the work that never ends. The hardest part of it lives in legacy code.</p>

<div class="statement-details">
  <p>Governance methods work: ambassadors, associates, knowledge sharing. But they need dedicated people for months at a time.</p>
  <p>One engineer, full-time for a year, took adoption from 20% to 80% on one product. That cost gets paid again on the next product, and the next.</p>
  <p>The shift: a design system isn't just a library. It's <strong>infrastructure</strong>. And infrastructure can carry its own adoption.</p>
</div>

<p class="closer">What an ambassador learns while migrating one team's code is exactly what the next migration needs. Capture it. Let it compound.</p>

<div class="footer"><span class="url">ds-trends-2026</span><span class="mark">Trend 7b &nbsp;·&nbsp; ↓ 3 deep dives</span></div>

>>>

<p class="eyebrow">Trend 7b · Deep dive · i</p>

## From governance to knowledge base

<div class="tiers">
  <div class="tier t1">
    <span class="tier-label">Step 1 · Governance</span>
    <div class="tier-title">The work teams already do</div>
    <div class="tier-desc">Ambassadors, associates, knowledge-sharing sessions.</div>
  </div>
  <div class="tier-arrow">↓</div>
  <div class="tier t2">
    <span class="tier-label">Step 2 · Successful adoptions</span>
    <div class="tier-title">Real code changes that shipped</div>
    <div class="tier-desc">Diffs that passed review, in real product code.</div>
  </div>
  <div class="tier-arrow">↓</div>
  <div class="tier t2">
    <span class="tier-label">Step 3 · Patterns captured</span>
    <div class="tier-title">Each adoption becomes a reference</div>
    <div class="tier-desc">Before / after diffs, commit messages, indexed for retrieval.</div>
  </div>
  <div class="tier-arrow">↓</div>
  <div class="tier t3">
    <span class="tier-label">Step 4 · Agent follows real patterns</span>
    <div class="tier-title">Looks up past work, doesn't guess</div>
    <div class="tier-desc">RAG + MCP serves your patterns at migration time.</div>
  </div>
</div>

<p class="closer">Every adoption you've already done becomes a reference for the next one. The knowledge accumulates instead of leaving with the person.</p>

<div class="footer"><span class="url">ds-trends-2026</span><span class="mark">Trend 7b · i &nbsp;·&nbsp; ↓ more</span></div>

>>>

<p class="eyebrow">Trend 7b · Deep dive · ii</p>

## AI guessing vs AI with your patterns

<div class="compare">
  <div class="then">
    <h3>Without context</h3>
    <ul>
      <li>Explores the codebase blindly</li>
      <li>Guesses naming, imports, props</li>
      <li>Produces code that fails review</li>
      <li>≈ $20 per failed attempt. It adds up.</li>
    </ul>
  </div>
  <div class="now">
    <h3>With MCP + RAG</h3>
    <ul>
      <li>Diffs of past adoptions are the knowledge base</li>
      <li>MCP delivers context to the agent on demand</li>
      <li>Agent follows your real imports, props, patterns</li>
      <li>Cost goes down as the corpus grows</li>
    </ul>
  </div>
</div>

<p class="closer">MCP = a standard protocol for agents to call tools. RAG = retrieve relevant examples before acting. Together: the agent stops guessing.</p>

<div class="footer"><span class="url">ds-trends-2026</span><span class="mark">Trend 7b · ii &nbsp;·&nbsp; ↓ more</span></div>

>>>

<p class="eyebrow">Trend 7b · Deep dive · iii</p>

## What changes for the team

<ul class="dotted">
  <li>Migrations stop being purely manual events. They become a feedback loop into the system.</li>
  <li>Adoption knowledge persists when people leave. The engineer who knew the patterns moves on; the diffs they made keep teaching.</li>
  <li>Each successful migration <em>adds</em> to the corpus. The system compounds instead of resetting every release.</li>
  <li>The DS team's role shifts: curate the corpus, not just the components.</li>
</ul>

<p class="closer">Builds on the governance methods that already work. Captures what was previously lost when people moved on.</p>

<div class="footer"><span class="url">ds-trends-2026</span><span class="mark">Trend 7b · iii</span></div>

---

<p class="eyebrow">Trend 7c</p>

## v0, Figma Make, Lovable: UI generation is here

<p class="statement">From mess to production-ready (thank you, DS!)</p>

<ul class="dotted">
  <li>These tools generate UI faster than humans can.</li>
  <li>Without a DS, they produce 100 inconsistent buttons. With a DS, done right, they produce 100 of <em>your</em> buttons.</li>
  <li>Design-side AI is still the most under-determined part of the stack: a Figma file is a static picture, intent isn't in the pixels. The DS is the closest thing to a behavioural contract these tools can actually read.</li>
</ul>

<p class="closer">New tools land weekly. Workflows shift with them. The DS is the bridge keeping designers and developers in sync, for the process as much as the output.</p>

<div class="footer"><span class="url">ds-trends-2026</span><span class="mark">Trend 7c</span></div>

---

<p class="eyebrow">Trend 8 · Horizon</p>

## What if every interface is composed on the fly?

<p class="lede">For one user, in one moment. A horizon, not a roadmap. But suppose interfaces become like text answers: generated per query, per context, per person. What would still need to be consistent?</p>

<ul class="dotted">
  <li>The brand.</li>
  <li>The voice.</li>
  <li>The accessibility.</li>
  <li>The trust signals.</li>
  <li>The behavior.</li>
</ul>

<p class="closer">In the most generative future we can imagine, the design system isn't smaller. It's <em>the only stable thing left</em>.</p>

<div class="footer"><span class="url">ds-trends-2026</span><span class="mark">Trend 8</span></div>

---

<!-- .slide: class="closing" -->

<h2 class="closing-title">Let's talk about <span class="accent">your</span> design system.</h2>
<p class="closing-sub">These shifts are happening at different speeds at every org. Some you'll be ahead of. Some will hit you in a meeting next quarter. Which of these seven is the one your team isn't ready for?</p>
<p class="closing-contact">
  Varya Stepanova &nbsp;·&nbsp;
  <a href="mailto:mail@varya.me">mail@varya.me</a> &nbsp;·&nbsp;
  <a href="https://varya.me">varya.me</a>
</p>
