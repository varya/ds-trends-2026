<!-- .slide: class="cover" -->

<p class="cover-eyebrow">Design Systems · 2026</p>
<h1 class="cover-title">Let's talk about <span class="accent">design systems</span><br>in 2026</h1>
<p class="cover-tagline">Seven shifts shaping how we build, ship, and consume them.</p>
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

<p class="closer fragment" data-fragment-index="2">Seven shifts behind these questions. Some are already here. Some are on the horizon. All of them change what a design system is <em>for</em>.</p>

<div class="footer"><span class="url">ds-trends-2026</span><span class="mark">Intro</span></div>

---

<p class="eyebrow">Trend 1</p>

## From having a DS to shipping faster with it

<p class="lede">Adoption was the question of the last cycle. ROI is still a live conversation at many orgs. The new edge: <strong style="color: var(--teal);">how much does the DS speed up product delivery?</strong></p>

<ul class="dotted">
  <li>A few years ago, <em>adoption</em> was the frontier.</li>
  <li>Then ROI — and for plenty of teams, that's still the conversation they're in.</li>
  <li>The trend now is sharper: tie the DS to <strong>time-to-ship</strong> — days saved per feature, velocity per team, rework avoided.</li>
  <li>Speed isn't a soft metric. It's the one product leaders feel every quarter.</li>
</ul>

<p class="closer">A design system earns its keep by making the next feature cheaper than the last.</p>

<div class="footer"><span class="url">ds-trends-2026</span><span class="mark">Trend 1 &nbsp;·&nbsp; ↓ deep dive</span></div>

>>>

<p class="eyebrow">Trend 1 · Deep dive</p>

## Measuring without metrics theater

<p class="lede">The trap: measuring <em>everything</em> to prove value, instead of the few things that actually correlate with shipped product.</p>

<ul class="dotted">
  <li>What's worth measuring — and what isn't.</li>
  <li>Design-tool adoption vs. codebase adoption — the gap that matters.</li>
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
</ul>

<p class="closer">A good design system can be run by three people — if the rest of the org is set up to carry it.</p>

<div class="footer"><span class="url">ds-trends-2026</span><span class="mark">Trend 2</span></div>

---

<p class="eyebrow">Trend 3</p>

## Headless has won the foundation

<p class="statement">Don't build primitives. Build <span class="accent" style="color: var(--teal);">expression</span>.</p>

<ul class="dotted">
  <li>Radix, React Aria, Base UI, Ariakit — the foundation layer is solved.</li>
  <li>Building your own dialog, popover, combobox from scratch is now a tax, not a craft.</li>
  <li>The differentiator moves up: brand, motion, density, voice, taste.</li>
  <li>The DS team's job: <strong>curate</strong> the foundation, <strong>own</strong> the expression.</li>
</ul>

<p class="closer">Where you used to spend a quarter, you now spend a week. Spend the saved quarter on what actually distinguishes you.</p>

<div class="footer"><span class="url">ds-trends-2026</span><span class="mark">Trend 3</span></div>

---

<p class="eyebrow">Trend 4</p>

## Tokens as the universal contract

<p class="lede">Tokens are how design and engineering finally speak the same language.</p>

<ul class="dotted">
  <li>DTCG spec is maturing — there's now a real standard.</li>
  <li>Semantic token layers: <strong>brand → semantic → component</strong>.</li>
  <li>Tokens crossing platforms: web, native, embedded, print.</li>
  <li>Tokens as the <strong>contract</strong> between Figma and code, not a translation step.</li>
</ul>

<p class="closer">If your design and engineering disagree about anything visual, the answer is usually "more tokens, less prose."</p>

<div class="footer"><span class="url">ds-trends-2026</span><span class="mark">Trend 4 &nbsp;·&nbsp; ↓ deep dive</span></div>

>>>

<p class="eyebrow">Trend 4 · Deep dive</p>

## What a token system looks like when it's working

<p class="lede">The slide where the engineering audience leans in — and the design audience realizes they've been doing half of this already, without the vocabulary for it.</p>

<ul class="dotted">
  <li>Three layers: brand → semantic → component. Why each is necessary.</li>
  <li>Multi-brand without forking the codebase.</li>
  <li>Token transformation pipelines — Style Dictionary, Terrazzo.</li>
  <li>DTCG as the lingua franca — why this matters <em>now</em>, not in five years.</li>
</ul>

<div class="footer"><span class="url">ds-trends-2026</span><span class="mark">Trend 4 · Deep dive</span></div>

---

<p class="eyebrow">Trend 5</p>

## Accessibility is now law

<p class="statement">One year into EAA enforcement. <span style="color: var(--red);">The grace period is over.</span></p>

<ul class="dotted">
  <li>The EU Accessibility Act came into effect June 2025. We're twelve months in.</li>
  <li>For products serving EU consumers, accessibility is no longer a values argument — it's compliance.</li>
  <li>The DS is the lever: a11y baked into primitives propagates to every product surface automatically.</li>
  <li>Teams that put accessibility into their tokens and components are now ahead. The ones that didn't are scrambling.</li>
</ul>

<p class="closer">The DS team's old advocacy quietly became the org's risk strategy.</p>

<div class="footer"><span class="url">ds-trends-2026</span><span class="mark">Trend 5</span></div>

---

<p class="eyebrow">Trend 6 · Umbrella</p>

## AI changes who consumes the design system

<p class="lede">For fifteen years we built design systems for humans. That's no longer the only audience. Three shifts are happening at once — none of them is "AI helps designers."</p>

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

<div class="footer"><span class="url">ds-trends-2026</span><span class="mark">Trend 6</span></div>

---

<p class="eyebrow">Trend 6a</p>

## Your design system is now read by agents

<ul class="dotted">
  <li>Coding agents — Claude Code, Cursor, Copilot — pick components by reading your docs.</li>
  <li>They miss what isn't machine-readable: nuance, intent, edge cases, the unwritten "don't use this here."</li>
  <li>MCP servers expose the DS as a <strong>structured contract</strong> — names, props, do/don't, examples.</li>
  <li>The new documentation audience: half human, half machine. Write for both.</li>
</ul>

<p class="closer">If an agent can't find your component, your component doesn't exist.</p>

<div class="footer"><span class="url">ds-trends-2026</span><span class="mark">Trend 6a</span></div>

---

<p class="eyebrow">Trend 6b</p>

## AI as the adoption engine

<p class="statement">The hardest problem in design systems just got a new tool.</p>

<ul class="dotted">
  <li>Old adoption playbook: docs, training, ambassadors, codemods, patience.</li>
  <li>New addition: feed the agent your <strong>past adoption diffs</strong>. It learns how <em>you</em> actually migrate.</li>
  <li>RAG over git history + MCP retrieval = the design system propagates itself.</li>
  <li>This is what "design system as infrastructure" means: not a library you publish — a system that <strong>spreads</strong>.</li>
</ul>

<p class="closer">Adoption stops being a campaign you have to run again every release.</p>

<div class="footer"><span class="url">ds-trends-2026</span><span class="mark">Trend 6b &nbsp;·&nbsp; ↓ 2 deep dives</span></div>

>>>

<p class="eyebrow">Trend 6b · Deep dive · i</p>

## How RAG + MCP for DS adoption actually works

<p class="lede">Agents waste tokens rediscovering your conventions on every migration. One failed migration ≈ $20. The fix is a corpus.</p>

<ul class="dotted">
  <li><strong>Corpus:</strong> indexed past adoption diffs + commit messages, semantic search.</li>
  <li><strong>MCP tools:</strong> "find adoption examples for component X", "show me how this prop changed."</li>
  <li><strong>Result:</strong> agents replicate your real patterns, not guesses.</li>
  <li><strong>Start here:</strong> pick one heavily-used component (Button), index 20–50 past adoption commits, measure improvement in a week.</li>
</ul>

<div class="footer"><span class="url">ds-trends-2026</span><span class="mark">Trend 6b · i &nbsp;·&nbsp; ↓ more</span></div>

>>>

<p class="eyebrow">Trend 6b · Deep dive · ii</p>

## What "DS as infrastructure" changes about how the team works

<ul class="dotted">
  <li>Migrations stop being purely manual events.</li>
  <li>Adoption knowledge persists when people leave.</li>
  <li>Each successful migration <em>adds</em> to the system. The corpus compounds.</li>
  <li>The DS team's role shifts: curate the corpus, not just the components.</li>
</ul>

<p class="closer">The most novel idea in this deck. Slow down here. Let it land.</p>

<div class="footer"><span class="url">ds-trends-2026</span><span class="mark">Trend 6b · ii</span></div>

---

<p class="eyebrow">Trend 6c</p>

## v0, Figma Make, Lovable — UI generation is here

<p class="statement">Without a DS, it's a mess. With one, generative tools become safe.</p>

<ul class="dotted">
  <li>These tools generate UI faster than humans can.</li>
  <li>Without a DS, they produce 100 inconsistent buttons.</li>
  <li>With a DS — done right — they produce 100 of <em>your</em> buttons.</li>
  <li>The DS becomes the <strong>guardrail</strong>. Without it, generative tools amplify inconsistency at scale.</li>
</ul>

<p class="closer">The DS isn't replaced by generative UI. It's what makes generative UI safe.</p>

<div class="footer"><span class="url">ds-trends-2026</span><span class="mark">Trend 6c</span></div>

---

<p class="eyebrow">Trend 7 · Horizon</p>

## What if every interface is composed on the fly?

<p class="lede">For one user, in one moment. A horizon, not a roadmap — but suppose interfaces become like text answers: generated per query, per context, per person. What would still need to be consistent?</p>

<ul class="dotted">
  <li>The brand.</li>
  <li>The voice.</li>
  <li>The accessibility.</li>
  <li>The trust signals.</li>
  <li>The behavior.</li>
</ul>

<p class="closer">In the most generative future we can imagine, the design system isn't smaller. It's <em>the only stable thing left</em>.</p>

<div class="footer"><span class="url">ds-trends-2026</span><span class="mark">Trend 7</span></div>

---

<!-- .slide: class="closing" -->

<h2 class="closing-title">Let's talk about <span class="accent">your</span> design system.</h2>
<p class="closing-sub">These shifts are happening at different speeds at every org. Some you'll be ahead of. Some will hit you in a meeting next quarter. Which of these seven is the one your team isn't ready for?</p>
<p class="closing-contact">
  Varya Stepanova &nbsp;·&nbsp;
  <a href="mailto:mail@varya.me">mail@varya.me</a> &nbsp;·&nbsp;
  <a href="https://varya.me">varya.me</a>
</p>
