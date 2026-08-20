```aura width=1000 height=560
<div style={{width:'1000px',height:'560px',display:'flex',flexDirection:'column',alignItems:'center',justifyContent:'center',padding:'42px',boxSizing:'border-box',background:'#08090d',color:'#f8fafc',position:'relative',overflow:'hidden',borderRadius:'30px',border:'1px solid rgba(120,130,160,0.18)'}}>
  <style>
    {`
      @keyframes hero-drift-a { 0%,100% { transform: translate(0,0); opacity: .65; } 50% { transform: translate(35px,-18px); opacity: .95; } }
      @keyframes hero-drift-b { 0%,100% { transform: translate(0,0); opacity: .55; } 50% { transform: translate(-30px,20px); opacity: .9; } }
      @keyframes hero-pulse { 0%,100% { transform: scale(1); opacity: .55; } 50% { transform: scale(1.16); opacity: .8; } }
      #hero-a { animation: hero-drift-a 7s ease-in-out infinite; }
      #hero-b { animation: hero-drift-b 8s ease-in-out infinite; }
      #hero-c { animation: hero-pulse 6s ease-in-out infinite; }
    `}
  </style>
  <svg width="1000" height="560" style={{position:'absolute',top:0,left:0}}>
    <defs>
      <radialGradient id="hg1"><stop offset="0%" stopColor="rgba(34,211,238,0.32)"/><stop offset="70%" stopColor="rgba(34,211,238,0)"/></radialGradient>
      <radialGradient id="hg2"><stop offset="0%" stopColor="rgba(124,58,237,0.30)"/><stop offset="70%" stopColor="rgba(124,58,237,0)"/></radialGradient>
      <radialGradient id="hg3"><stop offset="0%" stopColor="rgba(59,130,246,0.22)"/><stop offset="70%" stopColor="rgba(59,130,246,0)"/></radialGradient>
    </defs>
    <ellipse id="hero-a" cx="120" cy="90" rx="240" ry="150" fill="url(#hg1)" />
    <ellipse id="hero-b" cx="900" cy="470" rx="270" ry="180" fill="url(#hg2)" />
    <ellipse id="hero-c" cx="760" cy="80" rx="170" ry="130" fill="url(#hg3)" />
  </svg>

  <div style={{display:'flex',flexDirection:'column',alignItems:'center',zIndex:10}}>
    <span style={{fontSize:'15px',fontWeight:600,color:'#9ca3af',letterSpacing:'3px'}}>BACKEND ENGINEER · AI INFRASTRUCTURE</span>
    <span style={{fontSize:'56px',fontWeight:700,letterSpacing:'-2px',marginTop:'14px',color:'#ffffff'}}>Moinaktar Shaikh</span>
    <span style={{fontSize:'19px',color:'#aeb7c5',marginTop:'14px'}}>Building scalable systems, AI backends and data platforms.</span>
  </div>

  <div style={{display:'flex',flexDirection:'column',alignItems:'center',zIndex:10,width:'82%',marginTop:'34px',padding:'28px 38px',boxSizing:'border-box',background:'rgba(12,14,20,0.68)',borderRadius:'22px',border:'1px solid rgba(255,255,255,0.11)',boxShadow:'0 24px 70px rgba(0,0,0,0.42),inset 0 1px 0 rgba(255,255,255,0.06)'}}>
    <span style={{fontSize:'13px',fontWeight:600,color:'#67e8f9',letterSpacing:'2.5px'}}>ABOUT ME</span>
    <span style={{fontSize:'17px',color:'#d8dde6',marginTop:'12px',textAlign:'center',lineHeight:'1.5'}}>Backend engineer focused on scalable systems, AI infrastructure and production-grade data platforms.</span>
    <span style={{fontSize:'14px',color:'#9fa8b6',marginTop:'10px',textAlign:'center',lineHeight:'1.55'}}>Building backend services and AI infrastructure · interested in distributed systems, RAG and inference pipelines · exploring high-performance backend engineering with Go and Python.</span>
  </div>
</div>
```

```aura width=1000 height=300
<div style={{width:'1000px',height:'300px',display:'flex',flexDirection:'column',padding:'28px 36px',boxSizing:'border-box',background:'#08090d',color:'#f8fafc',position:'relative',overflow:'hidden',borderRadius:'26px',border:'1px solid rgba(120,130,160,0.18)'}}>
  <style>
    {`
      @keyframes tech-drift-a { 0%,100% { transform: translate(0,0); opacity: .6; } 50% { transform: translate(35px,-15px); opacity: .95; } }
      @keyframes tech-drift-b { 0%,100% { transform: translate(0,0); opacity: .5; } 50% { transform: translate(-35px,18px); opacity: .85; } }
      @keyframes tech-pulse { 0%,100% { transform: scale(1); opacity: .5; } 50% { transform: scale(1.18); opacity: .8; } }
      #tech-a { animation: tech-drift-a 7s ease-in-out infinite; }
      #tech-b { animation: tech-drift-b 8s ease-in-out infinite; }
      #tech-c { animation: tech-pulse 6s ease-in-out infinite; }
    `}
  </style>
  <svg width="1000" height="300" style={{position:'absolute',top:0,left:0}}>
    <defs>
      <radialGradient id="tg1"><stop offset="0%" stopColor="rgba(110,20,210,0.52)"/><stop offset="70%" stopColor="rgba(110,20,210,0)"/></radialGradient>
      <radialGradient id="tg2"><stop offset="0%" stopColor="rgba(0,160,230,0.38)"/><stop offset="70%" stopColor="rgba(0,160,230,0)"/></radialGradient>
      <radialGradient id="tg3"><stop offset="0%" stopColor="rgba(80,70,255,0.32)"/><stop offset="70%" stopColor="rgba(80,70,255,0)"/></radialGradient>
    </defs>
    <ellipse id="tech-a" cx="120" cy="280" rx="260" ry="150" fill="url(#tg1)" />
    <ellipse id="tech-b" cx="880" cy="30" rx="260" ry="150" fill="url(#tg2)" />
    <ellipse id="tech-c" cx="620" cy="180" rx="180" ry="120" fill="url(#tg3)" />
  </svg>

  <div style={{display:'flex',alignItems:'center',justifyContent:'space-between',zIndex:10}}>
    <span style={{fontSize:'13px',fontWeight:600,color:'#67e8f9',letterSpacing:'2.5px'}}>TECH STACK</span>
    <span style={{fontSize:'13px',color:'#7f8795'}}>AI · BACKEND · CLOUD · DATA</span>
  </div>

  <div style={{display:'flex',flexDirection:'column',gap:'13px',marginTop:'20px',zIndex:10,padding:'22px 24px',background:'rgba(12,14,20,0.68)',borderRadius:'20px',border:'1px solid rgba(255,255,255,0.11)',boxShadow:'0 24px 70px rgba(0,0,0,0.42),inset 0 1px 0 rgba(255,255,255,0.06)'}}>
    <div style={{display:'flex',alignItems:'center',gap:'12px'}}>
      <span style={{width:'125px',fontSize:'12px',color:'#8f98a8'}}>LANGUAGES</span>
      <span style={{fontSize:'14px',color:'#e5e7eb'}}>Python · Go · C++ · TypeScript · JavaScript</span>
    </div>
    <div style={{display:'flex',alignItems:'center',gap:'12px'}}>
      <span style={{width:'125px',fontSize:'12px',color:'#8f98a8'}}>BACKEND</span>
      <span style={{fontSize:'14px',color:'#e5e7eb'}}>FastAPI · Django · Flask · Node.js · Express</span>
    </div>
    <div style={{display:'flex',alignItems:'center',gap:'12px'}}>
      <span style={{width:'125px',fontSize:'12px',color:'#8f98a8'}}>DATA & AI</span>
      <span style={{fontSize:'14px',color:'#e5e7eb'}}>PostgreSQL · MySQL · Redis · MongoDB · PyTorch · TensorFlow · LangChain · MLflow</span>
    </div>
    <div style={{display:'flex',alignItems:'center',gap:'12px'}}>
      <span style={{width:'125px',fontSize:'12px',color:'#8f98a8'}}>CLOUD & DEVOPS</span>
      <span style={{fontSize:'14px',color:'#e5e7eb'}}>AWS · Azure · GCP · Docker · Kubernetes · Terraform · GitHub Actions · Linux</span>
    </div>
  </div>
</div>
```

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats-fast.vercel.app/api/streak?username=Mavericksystem&theme=dark&hide_border=true" width="49%" alt="GitHub Streak" />
  <a href="https://leetcode.com/u/Moinaktar/" target="_blank">
    <img src="https://leetcard.jacoblin.cool/Moinaktar?theme=dark" width="49%" alt="LeetCode Stats" />
  </a>
</p>

## Certifications

<p align="left">
  <a href="https://www.credly.com/badges/3fa1dba9-a170-42a2-a7fc-cb2c1639b804/public_url">
    <img src="./assets/awscert.png" width="140" alt="AWS Certified Solutions Architect Associate" />
  </a>
</p>

## Connect

<p>
  <a href="https://www.linkedin.com/in/moinaktar-shaikh-7b3a33207/">LinkedIn</a> ·
  <a href="mailto:moinaktarshaikh@gmail.com">Email</a> ·
  <a href="https://leetcode.com/u/Moinaktar/">LeetCode</a>
</p>
