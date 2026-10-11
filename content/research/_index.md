---
title: Research
date: 2026-08-29
type: landing

sections:
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        <section class="research-root">
          <div class="research-root__copy research-root__copy--centered">
            <span class="research-eyebrow">Our foundation</span>
            <h1 class="research-h1">Monolithic 3D Integration</h1>
            <p class="research-lede">
              SIM Lab is rooted in a single conviction: the next leap in computing performance will not come from
              shrinking transistors alone, but from stacking them &mdash; logic on memory, tier on tier, grown
              directly and seamlessly rather than bonded together. We develop the materials, growth techniques,
              and device architectures needed to make that vision real.
            </p>
          </div>

          <div class="research-diagram">
            <div class="research-diagram__stage">
              <img class="research-diagram__image" src="/media/research/monolithic-3d-diagram.webp" alt="Exploded isometric diagram of monolithic 3D integration: a sensor/photonics tier, capless main memory, monolithic logic, and silicon logic tiers stacked and interconnected with a back-side power delivery network" loading="lazy">
            </div>
            <svg class="research-diagram__lines" viewBox="0 0 100 100" preserveAspectRatio="none" aria-hidden="true">
              <line class="research-diagram__line research-diagram__line--memory" x1="4" y1="17" x2="20" y2="29" vector-effect="non-scaling-stroke"></line>
              <line class="research-diagram__line research-diagram__line--logic" x1="96" y1="52" x2="80" y2="59" vector-effect="non-scaling-stroke"></line>
              <line class="research-diagram__line research-diagram__line--growth" x1="4" y1="78" x2="20" y2="76" vector-effect="non-scaling-stroke"></line>
            </svg>
            <span class="research-diagram__dot research-diagram__dot--memory" style="left:20%; top:29%;" aria-hidden="true"></span>
            <span class="research-diagram__dot research-diagram__dot--logic" style="left:80%; top:59%;" aria-hidden="true"></span>
            <span class="research-diagram__dot research-diagram__dot--growth" style="left:20%; top:76%;" aria-hidden="true"></span>
            <a class="research-diagram__callout research-diagram__callout--memory" href="#pillar-memory">
              <span class="research-diagram__callout-index">02</span>
              <span class="research-diagram__callout-label">Future Memory Devices</span>
            </a>
            <a class="research-diagram__callout research-diagram__callout--logic" href="#pillar-logic">
              <span class="research-diagram__callout-index">01</span>
              <span class="research-diagram__callout-label">Future Logic Devices</span>
            </a>
            <a class="research-diagram__callout research-diagram__callout--growth" href="#pillar-growth">
              <span class="research-diagram__callout-index">03</span>
              <span class="research-diagram__callout-label">Low-Temperature Growth</span>
            </a>
          </div>
          <p class="research-diagram__hint">Tap a tier above to jump to the research pillar behind it.</p>

          <div class="research-diagram__callouts-mobile">
            <a class="callout-mobile--logic" href="#pillar-logic"><span></span>Future Logic Devices</a>
            <a class="callout-mobile--memory" href="#pillar-memory"><span></span>Future Memory Devices</a>
            <a class="callout-mobile--growth" href="#pillar-growth"><span></span>Low-Temperature Growth</a>
          </div>

          <div class="research-stack" aria-hidden="true">
            <span class="research-stack__bar research-stack__bar--logic"></span>
            <span class="research-stack__bar research-stack__bar--memory"></span>
            <span class="research-stack__bar research-stack__bar--growth"></span>
          </div>
        </section>

        <section class="research-pillars">
          <div class="research-pillars__head">
            <span class="research-eyebrow">Three directions, one root</span>
            <h2 class="research-h2">Research Pillars</h2>
          </div>

          <div class="research-pillars__grid">
            <article class="pillar-card pillar-card--logic" id="pillar-logic">
              <div class="pillar-card__media">
                <img src="/media/research/theme-logic-gaafet.png" alt="Schematic of a monolithically stacked 2D CFET with MoS2 and WSe2 gate-all-around channels" loading="lazy">
              </div>
              <div class="pillar-card__body">
                <span class="pillar-card__index">01</span>
                <h3 class="pillar-card__title">Future Logic Devices</h3>
                <p class="pillar-card__desc">
                  Pushing logic scaling past the limits of silicon with atomically thin, single-crystal 2D
                  semiconductors &mdash; wafer-scale 2D GAAFETs and monolithically stacked CFETs that pack more
                  transistors per footprint without sacrificing electrostatic control.
                </p>
                <ul class="pillar-card__tags">
                  <li>2D GAAFET</li>
                  <li>Monolithic CFET</li>
                  <li>Wafer-scale MoS&#8322; / WSe&#8322;</li>
                </ul>
              </div>
            </article>
            <article class="pillar-card pillar-card--memory" id="pillar-memory">
              <div class="pillar-card__media">
                <img src="/media/research/theme-memory-fefet.png" alt="Cross-section and polarization hysteresis of a 2D-channel HZO ferroelectric FeFET memory device" loading="lazy">
              </div>
              <div class="pillar-card__body">
                <span class="pillar-card__index">02</span>
                <h3 class="pillar-card__title">Future Memory Devices</h3>
                <p class="pillar-card__desc">
                  Building non-volatile memory that can live directly on top of logic &mdash; ferroelectric FeFETs
                  and oxide-based memory cells combining 2D channels with HfO&#8322;-based ferroelectrics for
                  dense, low-power, back-end-compatible storage.
                </p>
                <ul class="pillar-card__tags">
                  <li>FeFET</li>
                  <li>HZO ferroelectrics</li>
                  <li>Back-end-compatible memory</li>
                </ul>
              </div>
            </article>
            <article class="pillar-card pillar-card--growth" id="pillar-growth">
              <div class="pillar-card__media">
                <img src="/media/research/theme-lowtemp-growth.png" alt="Comparison of conventional high-temperature 3D integration versus seamless low-temperature single-crystal growth" loading="lazy">
              </div>
              <div class="pillar-card__body">
                <span class="pillar-card__index">03</span>
                <h3 class="pillar-card__title">Low-Temperature Growth</h3>
                <p class="pillar-card__desc">
                  The enabling technology behind it all: growing single-crystal 2D materials and metals directly
                  on finished circuits, below the thermal budget that would damage them &mdash; including
                  laser-assisted and microwave-assisted CVD.
                </p>
                <ul class="pillar-card__tags">
                  <li>Laser-assisted CVD</li>
                  <li>Microwave-assisted growth</li>
                  <li>&lt;400&deg;C single-crystal synthesis</li>
                </ul>
              </div>
            </article>

          </div>
        </section>

        <section class="research-cta">
          <div class="research-cta__inner">
            <div>
              <h2 class="research-h2 research-h2--light">Curious about the details?</h2>
              <p>See the papers behind these three pillars, or reach out about joining the lab.</p>
            </div>
            <div class="research-cta__actions">
              <a class="btn btn-outline-light" href="../publication/">Publications</a>
              <a class="btn btn-light" href="../contact/">Get in touch</a>
            </div>
          </div>
        </section>
    design:
      columns: '1'
      css_class: research-page
---
