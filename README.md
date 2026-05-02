# The Lighthouse — An Interactive Storm Narrative

&gt; A scroll-driven canvas experience featuring multi-octave wave physics,
&gt; volumetric lighthouse beam rendering, particle weather systems, and
&gt; narrative chapter progression.

## Live Demo
🔗 [https://the-lighthouse-an-interactive-storm.vercel.app/](https://the-lighthouse-an-interactive-storm.vercel.app/)

## Experience
Scroll through five chapters of an interactive storm narrative:
1. **The Calm** — Clear night, steady beam, glass sea
2. **The Wind Rises** — Whitecaps form, boat begins to rock
3. **The Storm** — Lightning, heavy rain, violent waves
4. **The Eye** — Brief silence, then renewed fury
5. **The Dawn** — Gray light, exhausted sea, survival

## Technical Implementation

### Wave Physics
5-octave sine wave synthesis with storm intensity multipliers:
```javascript
y = Σ sin(x * freq_i + phase_i + time * speed_i) * amp_i * stormMult
Sky Gradient → Stars/Rain → Lightning → Ocean Waves → Boat → 
Lighthouse Structure → Volumetric Beam → Foreground Overlay → Vignette


