```aura width=800 height=320
<div style={{ position: 'relative', display: 'flex', flexDirection: 'column', alignItems: 'flex-start', justifyContent: 'center', width: '100%', height: '100%', background: '#0e0e10', borderRadius: 16, overflow: 'hidden', fontFamily: 'Inter, sans-serif', padding: '0 56px' }}>
<style>{`
@keyframes hero-orb-a { 0%, 100% { transform: translate(0, 0); opacity: 0.55; } 50% { transform: translate(22px, -18px); opacity: 0.85; } }
@keyframes hero-orb-b { 0%, 100% { transform: translate(0, 0); opacity: 0.4; } 50% { transform: translate(-18px, 14px); opacity: 0.65; } }
@keyframes hero-ring { 0%, 100% { opacity: 0.05; } 50% { opacity: 0.14; } }
@keyframes hero-cursor { 0%, 100% { opacity: 1; } 50% { opacity: 0; } }
#h-o1 { animation: hero-orb-a 10s ease-in-out infinite; }
#h-o2 { animation: hero-orb-b 12s ease-in-out infinite 1s; }
#h-o3 { animation: hero-orb-a 8s ease-in-out infinite 2.4s; }
#h-r1 { animation: hero-ring 9s ease-in-out infinite; }
#h-r2 { animation: hero-ring 9s ease-in-out infinite 2s; }
#h-r3 { animation: hero-ring 11s ease-in-out infinite 3.5s; }
#h-cursor { animation: hero-cursor 1.1s step-end infinite; }
`}</style>
<svg width="800" height="320" style={{ position: 'absolute', top: 0, left: 0 }}>
<defs>
<radialGradient id="hg-terracotta" cx="50%" cy="50%" r="50%">
<stop offset="0%" stopColor="rgba(217,105,83,0.45)" />
<stop offset="100%" stopColor="rgba(217,105,83,0)" />
</radialGradient>
<radialGradient id="hg-teal" cx="50%" cy="50%" r="50%">
<stop offset="0%" stopColor="rgba(77,138,138,0.32)" />
<stop offset="100%" stopColor="rgba(77,138,138,0)" />
</radialGradient>
<radialGradient id="hg-warm" cx="50%" cy="50%" r="50%">
<stop offset="0%" stopColor="rgba(252,232,216,0.10)" />
<stop offset="100%" stopColor="rgba(252,232,216,0)" />
</radialGradient>
</defs>
<ellipse id="h-o1" cx="700" cy="70" rx="240" ry="190" fill="url(#hg-terracotta)" />
<ellipse id="h-o2" cx="80" cy="280" rx="220" ry="170" fill="url(#hg-teal)" />
<ellipse id="h-o3" cx="500" cy="320" rx="180" ry="130" fill="url(#hg-warm)" />
<circle id="h-r1" cx="660" cy="155" r="80" fill="none" stroke="rgba(255,255,255,0.6)" strokeWidth="0.6" />
<circle id="h-r2" cx="660" cy="155" r="135" fill="none" stroke="rgba(255,255,255,0.6)" strokeWidth="0.6" />
<circle id="h-r3" cx="660" cy="155" r="200" fill="none" stroke="rgba(255,255,255,0.6)" strokeWidth="0.6" />
</svg>
<div style={{ position: 'relative', display: 'flex', flexDirection: 'column', alignItems: 'flex-start', zIndex: 10 }}>
<span style={{ fontSize: 13, color: 'rgba(255,255,255,0.38)', letterSpacing: 4, textTransform: 'uppercase', marginBottom: 14, fontWeight: 400, fontFamily: 'monospace' }}>missusk</span>
<span style={{ fontSize: 60, fontWeight: 700, color: '#fafafa', letterSpacing: -2.5, lineHeight: 1, marginBottom: 22 }}>maria khan</span>
<span style={{ fontSize: 16, color: 'rgba(255,255,255,0.72)', fontFamily: 'monospace', lineHeight: 1.6, marginBottom: 2 }}>platform engineer</span>
<span style={{ fontSize: 16, color: 'rgba(255,255,255,0.72)', fontFamily: 'monospace', lineHeight: 1.6 }}>rails, postgres, kubernetes</span>
</div>
</div>
```

```aura width=800 height=320
<div style={{ position: 'relative', display: 'flex', flexDirection: 'column', width: '100%', height: '100%', background: '#0e0e10', borderRadius: 16, overflow: 'hidden', fontFamily: 'Inter, sans-serif', padding: '40px 56px', justifyContent: 'center' }}>
<style>{`
@keyframes work-orb { 0%, 100% { transform: translate(0,0); opacity: 0.35; } 50% { transform: translate(16px,-12px); opacity: 0.55; } }
#w-o1 { animation: work-orb 11s ease-in-out infinite; }
#w-o2 { animation: work-orb 13s ease-in-out infinite 1.8s; }
`}</style>
<svg width="800" height="320" style={{ position: 'absolute', top: 0, left: 0 }}>
<defs>
<radialGradient id="wg1" cx="50%" cy="50%" r="50%">
<stop offset="0%" stopColor="rgba(77,138,138,0.22)" />
<stop offset="100%" stopColor="rgba(77,138,138,0)" />
</radialGradient>
<radialGradient id="wg2" cx="50%" cy="50%" r="50%">
<stop offset="0%" stopColor="rgba(217,105,83,0.18)" />
<stop offset="100%" stopColor="rgba(217,105,83,0)" />
</radialGradient>
</defs>
<ellipse id="w-o1" cx="730" cy="70" rx="180" ry="140" fill="url(#wg1)" />
<ellipse id="w-o2" cx="60" cy="290" rx="180" ry="140" fill="url(#wg2)" />
</svg>
<span style={{ fontSize: 11, color: 'rgba(255,255,255,0.35)', letterSpacing: 4, textTransform: 'uppercase', marginBottom: 26, zIndex: 10, fontFamily: 'monospace' }}>interests</span>
<div style={{ display: 'flex', flexDirection: 'column', gap: 14, zIndex: 10 }}>
<div style={{ display: 'flex', alignItems: 'flex-start' }}>
<span style={{ color: '#d96953', fontSize: 18, marginRight: 16, fontFamily: 'monospace', lineHeight: 1.4, marginTop: -2 }}>·</span>
<span style={{ fontSize: 16, color: 'rgba(255,255,255,0.82)', lineHeight: 1.45 }}>distributed systems: replication, consensus, the gap between cap-theorem and the database you actually have</span>
</div>
<div style={{ display: 'flex', alignItems: 'flex-start' }}>
<span style={{ color: '#d96953', fontSize: 18, marginRight: 16, fontFamily: 'monospace', lineHeight: 1.4, marginTop: -2 }}>·</span>
<span style={{ fontSize: 16, color: 'rgba(255,255,255,0.82)', lineHeight: 1.45 }}>database internals: mvcc, write amplification, what acid buys you and what it doesn't</span>
</div>
<div style={{ display: 'flex', alignItems: 'flex-start' }}>
<span style={{ color: '#d96953', fontSize: 18, marginRight: 16, fontFamily: 'monospace', lineHeight: 1.4, marginTop: -2 }}>·</span>
<span style={{ fontSize: 16, color: 'rgba(255,255,255,0.82)', lineHeight: 1.45 }}>performance: microbench design, the gvl, where ruby surprises you under load</span>
</div>
<div style={{ display: 'flex', alignItems: 'flex-start' }}>
<span style={{ color: '#d96953', fontSize: 18, marginRight: 16, fontFamily: 'monospace', lineHeight: 1.4, marginTop: -2 }}>·</span>
<span style={{ fontSize: 16, color: 'rgba(255,255,255,0.82)', lineHeight: 1.45 }}>observability that earns its budget: trace sampling, cardinality, slo math</span>
</div>
<div style={{ display: 'flex', alignItems: 'flex-start' }}>
<span style={{ color: '#d96953', fontSize: 18, marginRight: 16, fontFamily: 'monospace', lineHeight: 1.4, marginTop: -2 }}>·</span>
<span style={{ fontSize: 16, color: 'rgba(255,255,255,0.82)', lineHeight: 1.45 }}>systems thinking: blast radius, idempotency, queue back-pressure, retry semantics</span>
</div>
<div style={{ display: 'flex', alignItems: 'flex-start' }}>
<span style={{ color: '#d96953', fontSize: 18, marginRight: 16, fontFamily: 'monospace', lineHeight: 1.4, marginTop: -2 }}>·</span>
<span style={{ fontSize: 16, color: 'rgba(255,255,255,0.82)', lineHeight: 1.45 }}>writing technical things in public - postmortems, runbooks, learning out loud</span>
</div>
</div>
</div>
```

```aura width=800 height=210
<div style={{ position: 'relative', display: 'flex', flexDirection: 'column', alignItems: 'flex-start', justifyContent: 'center', width: '100%', height: '100%', background: '#0e0e10', borderRadius: 16, overflow: 'hidden', fontFamily: 'Inter, sans-serif', padding: '0 56px' }}>
<style>{`
@keyframes stack-orb { 0%, 100% { transform: translate(0,0); opacity: 0.4; } 50% { transform: translate(20px,-14px); opacity: 0.65; } }
#s-o1 { animation: stack-orb 11s ease-in-out infinite; }
#s-o2 { animation: stack-orb 9s ease-in-out infinite 1.5s; }
`}</style>
<svg width="800" height="210" style={{ position: 'absolute', top: 0, left: 0 }}>
<defs>
<radialGradient id="sg1" cx="50%" cy="50%" r="50%">
<stop offset="0%" stopColor="rgba(217,105,83,0.28)" />
<stop offset="100%" stopColor="rgba(217,105,83,0)" />
</radialGradient>
<radialGradient id="sg2" cx="50%" cy="50%" r="50%">
<stop offset="0%" stopColor="rgba(77,138,138,0.28)" />
<stop offset="100%" stopColor="rgba(77,138,138,0)" />
</radialGradient>
</defs>
<ellipse id="s-o1" cx="120" cy="50" rx="170" ry="130" fill="url(#sg1)" />
<ellipse id="s-o2" cx="700" cy="180" rx="170" ry="130" fill="url(#sg2)" />
</svg>
<span style={{ fontSize: 11, color: 'rgba(255,255,255,0.35)', letterSpacing: 4, textTransform: 'uppercase', marginBottom: 18, zIndex: 10, fontFamily: 'monospace' }}>stack</span>
<div style={{ display: 'flex', flexWrap: 'wrap', gap: 8, zIndex: 10, maxWidth: 690 }}>
{['ruby on rails', 'postgresql', 'kubernetes', 'aws', 'helm', 'keda', 'datadog', 'sneakers', 'rabbitmq', 'redis', 'pgbouncer', 'cloudflare'].map((tech, i) => (
<span key={i} style={{ padding: '6px 16px', background: 'rgba(255,255,255,0.04)', color: 'rgba(255,255,255,0.74)', borderRadius: 100, fontSize: 13, border: '1px solid rgba(255,255,255,0.09)', fontFamily: 'monospace', letterSpacing: 0.3 }}>{tech}</span>
))}
</div>
</div>
```

```aura width=800 height=160
<div style={{ position: 'relative', display: 'flex', flexDirection: 'column', justifyContent: 'center', width: '100%', height: '100%', background: '#0e0e10', borderRadius: 16, overflow: 'hidden', padding: '0 56px' }}>
<span style={{ fontSize: 11, color: 'rgba(255,255,255,0.35)', letterSpacing: 4, textTransform: 'uppercase', marginBottom: 14, fontFamily: 'monospace' }}>thinking about</span>
<span style={{ fontSize: 15, color: 'rgba(255,255,255,0.82)', lineHeight: 1.55, fontFamily: 'monospace' }}>queue back-pressure. how rails surprises you in production.</span>
<span style={{ fontSize: 15, color: 'rgba(255,255,255,0.82)', lineHeight: 1.55, fontFamily: 'monospace' }}>postgres lock semantics. observability that earns its budget.</span>
</div>
```

```aura width=140 height=44 link="https://github.com/missusk" inline align=center
<SocialMediaButton
  icon="https://cdn.jsdelivr.net/npm/simple-icons@latest/icons/github.svg"
  text="GitHub"
  backgroundColor="#141414"
  width={140}
  height={44}
  gradientStops={[
    { offset: '0%', color: '#ffffff' },
    { offset: '10%', color: '#111111' },
    { offset: '50%', color: '#eeeeee' },
    { offset: '60%', color: '#d96953' },
    { offset: '80%', color: '#111111' },
    { offset: '100%', color: '#555555' },
  ]}
/>
```

```aura width=160 height=44 link="https://www.linkedin.com/in/khan-maria-" inline align=center
<SocialMediaButton
  icon="https://cdn.jsdelivr.net/npm/simple-icons@latest/icons/linkedin.svg"
  text="LinkedIn"
  backgroundColor="#0a1420"
  width={160}
  height={44}
  gradientStops={[
    { offset: '0%', color: '#ffffff' },
    { offset: '10%', color: '#111111' },
    { offset: '50%', color: '#eeeeee' },
    { offset: '60%', color: '#4d8a8a' },
    { offset: '80%', color: '#111111' },
    { offset: '100%', color: '#555555' },
  ]}
/>
```

```aura width=160 height=44 link="https://leetcode.com/mariakhan/" inline align=center
<SocialMediaButton
  icon="https://cdn.jsdelivr.net/npm/simple-icons@latest/icons/leetcode.svg"
  text="LeetCode"
  backgroundColor="#0d0d0d"
  width={160}
  height={44}
  gradientStops={[
    { offset: '0%', color: '#ffffff' },
    { offset: '10%', color: '#111111' },
    { offset: '50%', color: '#eeeeee' },
    { offset: '60%', color: '#d96953' },
    { offset: '80%', color: '#111111' },
    { offset: '100%', color: '#555555' },
  ]}
/>
```
