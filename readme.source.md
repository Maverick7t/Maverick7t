```aura
<div style={{
  width: '100%', height: '100%', background: '#08080c',
  display: 'flex', alignItems: 'center', fontFamily: 'Inter',
  position: 'relative', overflow: 'hidden', borderRadius: 16,
  border: '1px solid rgba(110,80,220,0.18)'
}}>

  <style>{`
    @keyframes float-slow {
      0%, 100% { transform: translateX(0px); opacity: 0.8; }
      50% { transform: translateX(350px); opacity: 1.2; }
    }
    @keyframes float-medium {
      0%, 100% { transform: translateX(0px); opacity: 0.7; }
      50% { transform: translateX(-250px); opacity: 1.1; }
    }
    @keyframes float-fast {
      0%, 100% { transform: translateX(0px); opacity: 0.9; }
      50% { transform: translateX(200px); opacity: 0.6; }
    }
    @keyframes float-diagonal {
      0%, 100% { transform: translateX(0px); opacity: 0.75; }
      50% { transform: translateX(300px); opacity: 1.0; }
    }
    @keyframes float-wave {
      0%, 100% { transform: translateX(0px); opacity: 0.65; }
      33% { transform: translateX(-160px); opacity: 0.9; }
      66% { transform: translateX(80px); opacity: 1.0; }
    }
    @keyframes float-pulse {
      0%, 100% { transform: scale(1); opacity: 0.8; }
      50% { transform: scale(1.3); opacity: 0.4; }
    }
    #glow-1 { animation: float-slow 8s ease-in-out infinite; }
    #glow-2 { animation: float-medium 12s ease-in-out infinite; }
    #glow-3 { animation: float-fast 9s ease-in-out infinite; }
    #glow-4 { animation: float-slow 11s ease-in-out infinite reverse; }
    #glow-5 { animation: float-medium 14s ease-in-out infinite reverse; }
    #glow-6 { animation: float-diagonal 10s ease-in-out infinite; }
    #glow-7 { animation: float-wave 13s ease-in-out infinite; }
    #glow-8 { animation: float-pulse 7s ease-in-out infinite; }
  `}</style>

  <svg width="860" height="230" style={{ position: 'absolute', top: 0, left: 0 }}>
    <defs>
      <radialGradient id="g1" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(110,20,210,0.72)" />
        <stop offset="40%" stopColor="rgba(90,15,180,0.35)" />
        <stop offset="70%" stopColor="rgba(90,15,180,0)" />
      </radialGradient>
      <radialGradient id="g2" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(40,60,255,0.6)" />
        <stop offset="45%" stopColor="rgba(30,50,200,0.25)" />
        <stop offset="70%" stopColor="rgba(30,50,200,0)" />
      </radialGradient>
      <radialGradient id="g3" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(0,130,255,0.45)" />
        <stop offset="50%" stopColor="rgba(0,100,220,0.18)" />
        <stop offset="70%" stopColor="rgba(0,100,220,0)" />
      </radialGradient>
      <radialGradient id="g4" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(0,190,230,0.32)" />
        <stop offset="70%" stopColor="rgba(0,190,230,0)" />
      </radialGradient>
      <radialGradient id="g5" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(90,30,200,0.38)" />
        <stop offset="70%" stopColor="rgba(90,30,200,0)" />
      </radialGradient>
      <radialGradient id="g6" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(160,30,255,0.55)" />
        <stop offset="45%" stopColor="rgba(130,20,220,0.22)" />
        <stop offset="70%" stopColor="rgba(130,20,220,0)" />
      </radialGradient>
      <radialGradient id="g7" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(20,60,255,0.42)" />
        <stop offset="50%" stopColor="rgba(10,40,200,0.16)" />
        <stop offset="70%" stopColor="rgba(10,40,200,0)" />
      </radialGradient>
      <radialGradient id="g8" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(0,170,255,0.40)" />
        <stop offset="50%" stopColor="rgba(0,130,220,0.15)" />
        <stop offset="70%" stopColor="rgba(0,130,220,0)" />
      </radialGradient>
    </defs>
    <ellipse id="glow-1" cx="180" cy="260" rx="260" ry="190" fill="url(#g1)" />
    <ellipse id="glow-2" cx="300" cy="270" rx="220" ry="160" fill="url(#g2)" />
    <ellipse id="glow-3" cx="420" cy="270" rx="180" ry="140" fill="url(#g3)" />
    <ellipse id="glow-4" cx="550" cy="280" rx="150" ry="120" fill="url(#g4)" />
    <ellipse id="glow-5" cx="750" cy="280" rx="130" ry="110" fill="url(#g5)" />
    <ellipse id="glow-6" cx="300" cy="270" rx="180" ry="140" fill="url(#g6)" />
    <ellipse id="glow-7" cx="490" cy="260" rx="220" ry="170" fill="url(#g7)" />
    <ellipse id="glow-8" cx="590" cy="280" rx="150" ry="130" fill="url(#g8)" />
  </svg>

  <div style={{
    position: 'absolute', left: 48, top: 62, width: 96, height: 96,
    borderRadius: 48, background: 'linear-gradient(135deg, #6622ee, #0088ff)',
    display: 'flex', alignItems: 'center', justifyContent: 'center',
  }}>
    <img src="https://github.com/Mavericksystem.png" width={88} height={88} style={{ borderRadius: 44 }} />
  </div>

  <div style={{ display: 'flex', flexDirection: 'column', marginLeft: 168, gap: 8, zIndex: 10 }}>
    <div style={{ display: 'flex', fontSize: 34, fontWeight: 800, color: '#ffffff', letterSpacing: '-1px', lineHeight: 1 }}>
      Moinaktar Shaikh
    </div>
    <div style={{ display: 'flex', fontSize: 14, color: 'rgba(180,165,255,0.85)', fontWeight: 500, letterSpacing: '0.3px' }}>
      Backend Engineer · Data Systems · AI Infrastructure
    </div>
    <div style={{ display: 'flex', fontSize: 13, color: 'rgba(200,195,225,0.55)', fontWeight: 400, marginTop: 2, maxWidth: 520 }}>
      Building scalable systems that turn raw data into intelligence, predictions and automation.
    </div>
    <div style={{ display: 'flex', gap: 8, marginTop: 8, flexWrap: 'wrap' }}>
      {['Bengaluru, India', 'AWS Certified', 'Python & Go'].map(function (tag, i) {
        return (
          <div key={tag + '-' + i} style={{
            display: 'flex', padding: '4px 12px', borderRadius: 20,
            background: 'rgba(80,40,220,0.18)', border: '1px solid rgba(100,70,240,0.32)',
            color: 'rgba(205,195,255,0.85)', fontSize: 12, fontWeight: 600,
          }}>{tag}</div>
        );
      })}
    </div>
  </div>
</div>

## About Me

```aura
<div style={{
  width: '100%', height: '100%', background: '#08080c',
  display: 'flex', flexDirection: 'column', justifyContent: 'center',
  fontFamily: 'Inter', padding: '22px 32px', borderRadius: 16,
  border: '1px solid rgba(110,80,220,0.18)', position: 'relative', overflow: 'hidden',
}}>
  <style>{`
    @keyframes about-glow-a { 0%, 100% { transform: translate(0,0); opacity: 0.6; } 50% { transform: translate(24px,-16px); opacity: 0.9; } }
    @keyframes about-glow-b { 0%, 100% { transform: translate(0,0); opacity: 0.5; } 50% { transform: translate(-20px,14px); opacity: 0.8; } }
    #ab-g1 { animation: about-glow-a 9s ease-in-out infinite; }
    #ab-g2 { animation: about-glow-b 11s ease-in-out infinite 0.6s; }
    #ab-g3 { animation: about-glow-a 8s ease-in-out infinite 1.5s; }
  `}</style>
  <svg width="860" height="190" style={{ position: 'absolute', top: 0, left: 0 }}>
    <defs>
      <radialGradient id="abg1" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(110,20,210,0.5)" />
        <stop offset="70%" stopColor="rgba(110,20,210,0)" />
      </radialGradient>
      <radialGradient id="abg2" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(0,140,255,0.4)" />
        <stop offset="70%" stopColor="rgba(0,140,255,0)" />
      </radialGradient>
      <radialGradient id="abg3" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(160,30,255,0.35)" />
        <stop offset="70%" stopColor="rgba(160,30,255,0)" />
      </radialGradient>
    </defs>
    <ellipse id="ab-g1" cx="740" cy="30" rx="180" ry="120" fill="url(#abg1)" />
    <ellipse id="ab-g2" cx="800" cy="160" rx="150" ry="110" fill="url(#abg2)" />
    <ellipse id="ab-g3" cx="60" cy="180" rx="150" ry="100" fill="url(#abg3)" />
  </svg>

  <div style={{ display: 'flex', fontSize: 11, color: 'rgba(155,140,210,0.55)', letterSpacing: 3, textTransform: 'uppercase', marginBottom: 14, zIndex: 10 }}>
    About Me
  </div>
  <div style={{ display: 'flex', flexDirection: 'column', gap: 9, zIndex: 10 }}>
    {[
      'Backend engineer focused on scalable systems and ML infrastructure',
      'Building production grade AI and data platforms',
      'Interested in distributed systems, RAG, inference pipelines and cloud architecture',
      'Exploring high performance backend engineering with Go and Python',
      'Based in Bengaluru, India',
    ].map(function (line, i) {
      return (
        <div key={i} style={{ display: 'flex', alignItems: 'center', gap: 10 }}>
          <div style={{ display: 'flex', width: 6, height: 6, borderRadius: 3, background: '#a78bfa' }} />
          <div style={{ display: 'flex', fontSize: 13, color: 'rgba(225,220,255,0.85)' }}>{line}</div>
        </div>
      );
    })}
  </div>
</div>

## Tech Stack

```aura
(function () {
  var categories = [
    { title: 'Languages', color: '#a78bfa', items: ['Python', 'Go', 'C++', 'TypeScript', 'Node.js'] },
    { title: 'Frameworks', color: '#60a5fa', items: ['Django', 'FastAPI', 'Flask', 'Express'] },
    { title: 'Databases', color: '#34d399', items: ['MySQL', 'PostgreSQL', 'Redis', 'MongoDB'] },
    { title: 'AI / ML', color: '#f59e0b', items: ['PyTorch', 'TensorFlow', 'LangChain', 'MLflow'] },
    { title: 'Cloud & DevOps', color: '#f472b6', items: ['AWS', 'Azure', 'GCP', 'Docker', 'Kubernetes', 'GitHub Actions', 'Prefect'] },
  ];

  return (
    <div style={{
      width: '100%', height: '100%', background: '#08080c',
      display: 'flex', flexDirection: 'column', fontFamily: 'Inter',
      padding: '18px 32px', gap: 12, borderRadius: 16,
      border: '1px solid rgba(110,80,220,0.18)', position: 'relative', overflow: 'hidden',
    }}>
      <style>{`
        @keyframes ts-glow-a { 0%, 100% { transform: translate(0,0); opacity: 0.6; } 50% { transform: translate(30px,-18px); opacity: 0.95; } }
        @keyframes ts-glow-b { 0%, 100% { transform: translate(0,0); opacity: 0.5; } 50% { transform: translate(-24px,16px); opacity: 0.8; } }
        @keyframes ts-glow-c { 0%, 100% { transform: scale(1); opacity: 0.7; } 50% { transform: scale(1.2); opacity: 0.4; } }
        #st-g1 { animation: ts-glow-a 9s ease-in-out infinite; }
        #st-g2 { animation: ts-glow-b 11s ease-in-out infinite 0.4s; }
        #st-g3 { animation: ts-glow-c 7s ease-in-out infinite 0.8s; }
        #st-g4 { animation: ts-glow-a 10s ease-in-out infinite 1.2s; }
      `}</style>
      <svg width="860" height="210" style={{ position: 'absolute', top: 0, left: 0 }}>
        <defs>
          <radialGradient id="stg1" cx="50%" cy="50%" r="50%">
            <stop offset="0%" stopColor="rgba(115,20,215,0.5)" />
            <stop offset="70%" stopColor="rgba(115,20,215,0)" />
          </radialGradient>
          <radialGradient id="stg2" cx="50%" cy="50%" r="50%">
            <stop offset="0%" stopColor="rgba(0,130,255,0.4)" />
            <stop offset="70%" stopColor="rgba(0,130,255,0)" />
          </radialGradient>
          <radialGradient id="stg3" cx="50%" cy="50%" r="50%">
            <stop offset="0%" stopColor="rgba(160,30,255,0.35)" />
            <stop offset="70%" stopColor="rgba(160,30,255,0)" />
          </radialGradient>
          <radialGradient id="stg4" cx="50%" cy="50%" r="50%">
            <stop offset="0%" stopColor="rgba(0,190,230,0.3)" />
            <stop offset="70%" stopColor="rgba(0,190,230,0)" />
          </radialGradient>
        </defs>
        <ellipse id="st-g1" cx="120" cy="200" rx="220" ry="140" fill="url(#stg1)" />
        <ellipse id="st-g2" cx="750" cy="20" rx="200" ry="130" fill="url(#stg2)" />
        <ellipse id="st-g3" cx="700" cy="200" rx="170" ry="110" fill="url(#stg3)" />
        <ellipse id="st-g4" cx="200" cy="20" rx="170" ry="110" fill="url(#stg4)" />
      </svg>

      <div style={{ display: 'flex', fontSize: 11, color: 'rgba(155,140,210,0.55)', letterSpacing: 3, textTransform: 'uppercase', zIndex: 10 }}>
        Tech Stack
      </div>
      <div style={{ display: 'flex', flexDirection: 'column', gap: 12, zIndex: 10 }}>
        {categories.map(function (cat) {
          return (
            <div key={cat.title} style={{ display: 'flex', alignItems: 'center', gap: 16 }}>
              <div style={{ display: 'flex', fontSize: 10, fontWeight: 700, color: cat.color, letterSpacing: '1px', width: 100 }}>
                {cat.title.toUpperCase()}
              </div>
              <div style={{ display: 'flex', flexWrap: 'wrap', gap: 7 }}>
                {cat.items.map(function (item) {
                  return (
                    <div key={item} style={{
                      display: 'flex', padding: '4px 12px', borderRadius: 6,
                      background: cat.color + '15', border: '1px solid ' + cat.color + '35',
                      color: 'rgba(225,220,255,0.85)', fontSize: 12, fontWeight: 600,
                    }}>{item}</div>
                  );
                })}
              </div>
            </div>
          );
        })}
      </div>
    </div>
  );
})()
```

## Certifications

```aura
<div style={{
  width: '100%', height: '100%', background: '#08080c',
  display: 'flex', alignItems: 'center', gap: 20, fontFamily: 'Inter',
  padding: '0 32px', borderRadius: 16, border: '1px solid rgba(110,80,220,0.18)',
  position: 'relative', overflow: 'hidden',
}}>
  <style>{`
    @keyframes cert-pulse { 0%, 100% { transform: scale(1); opacity: 0.7; } 50% { transform: scale(1.25); opacity: 0.4; } }
    @keyframes cert-drift { 0%, 100% { transform: translate(0,0); opacity: 0.6; } 50% { transform: translate(22px,-12px); opacity: 0.9; } }
    #ct-g1 { animation: cert-pulse 6s ease-in-out infinite; }
    #ct-g2 { animation: cert-drift 8s ease-in-out infinite 0.5s; }
  `}</style>
  <svg width="860" height="110" style={{ position: 'absolute', top: 0, left: 0 }}>
    <defs>
      <radialGradient id="ctg1" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(255,153,0,0.35)" />
        <stop offset="70%" stopColor="rgba(255,153,0,0)" />
      </radialGradient>
      <radialGradient id="ctg2" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(110,20,210,0.4)" />
        <stop offset="70%" stopColor="rgba(110,20,210,0)" />
      </radialGradient>
    </defs>
    <ellipse id="ct-g1" cx="90" cy="55" rx="120" ry="80" fill="url(#ctg1)" />
    <ellipse id="ct-g2" cx="770" cy="55" rx="140" ry="90" fill="url(#ctg2)" />
  </svg>
  <div style={{
    display: 'flex', width: 68, height: 68, borderRadius: 16, flexShrink: 0,
    background: 'linear-gradient(135deg, #ff9900, #d97706)',
    alignItems: 'center', justifyContent: 'center', fontSize: 28, zIndex: 10,
  }}>☁️</div>
  <div style={{ display: 'flex', flexDirection: 'column', gap: 4, zIndex: 10 }}>
    <div style={{ display: 'flex', fontSize: 10, color: 'rgba(155,140,210,0.55)', letterSpacing: 3, textTransform: 'uppercase' }}>
      Certification
    </div>
    <div style={{ display: 'flex', fontSize: 18, fontWeight: 700, color: '#ffffff' }}>
      AWS Certified Solutions Architect – Associate
    </div>
    <div style={{ display: 'flex', fontSize: 12, color: 'rgba(200,195,225,0.55)' }}>
      Issued via AWS · Verified on Credly
    </div>
  </div>
</div>
```

## 📊 GitHub Stats

<p align="center">
  <img src="https://streak-stats.demolab.com?user=Mavericksystem&theme=tokyonight" width="49%" />
  <a href="https://leetcode.com/u/Moinaktar/" target="_blank">
    <img src="https://leetcard.jacoblin.cool/Moinaktar?theme=dark" width="49%" />
  </a>
</p>

## 🌐 Connect

```aura
<SocialMediaButton
  icon="https://cdn.simpleicons.org/linkedin/ffffff"
  text="LinkedIn"
  backgroundColor="#0a1f33"
  width={170}
  height={48}
  gradientStops={[
    { offset: '0%', color: '#ffffff' },
    { offset: '10%', color: '#111111' },
    { offset: '50%', color: '#eeeeee' },
    { offset: '60%', color: '#0A66C2' },
    { offset: '80%', color: '#111111' },
    { offset: '100%', color: '#555555' },
  ]}
/>
```

```aura
<SocialMediaButton
  icon="https://cdn.simpleicons.org/gmail/ffffff"
  text="Email Me"
  backgroundColor="#2b0a0a"
  width={170}
  height={48}
  gradientStops={[
    { offset: '0%', color: '#ffffff' },
    { offset: '10%', color: '#111111' },
    { offset: '50%', color: '#eeeeee' },
    { offset: '60%', color: '#EA4335' },
    { offset: '80%', color: '#111111' },
    { offset: '100%', color: '#555555' },
  ]}
/>
```

```aura
<SocialMediaButton
  icon="https://cdn.simpleicons.org/leetcode/ffffff"
  text="LeetCode"
  backgroundColor="#1a1408"
  width={170}
  height={48}
  gradientStops={[
    { offset: '0%', color: '#ffffff' },
    { offset: '10%', color: '#111111' },
    { offset: '50%', color: '#eeeeee' },
    { offset: '60%', color: '#FFA116' },
    { offset: '80%', color: '#111111' },
    { offset: '100%', color: '#555555' },
  ]}
/>
```

```aura
<div style={{ display: 'flex', justifyContent: 'center', alignItems: 'center', width: '100%', height: '100%', padding: 0, margin: 0 }}>
  <span style={{ fontSize: 12, lineHeight: 1, color: 'rgba(150,140,200,0.55)', fontWeight: 500, letterSpacing: '0.4px' }}>powered by readme-aura</span>
</div>
```