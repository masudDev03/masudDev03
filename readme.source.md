
```aura width=860 height=240 link="https://github.com/masudDev03"
<div style={{
  width: '100%', height: '100%', background: '#0a0b10',
  display: 'flex', alignItems: 'center', fontFamily: 'Plus Jakarta Sans, sans-serif',
  position: 'relative', overflow: 'hidden', borderRadius: 20,
  border: '1px solid rgba(255, 255, 255, 0.05)',
  boxShadow: '0 8px 32px 0 rgba(0, 0, 0, 0.3)'
}}>
  <style>{`
    @keyframes float-slow {
      0%, 100% { transform: translateY(0px) scale(1); }
      50% { transform: translateY(-20px) scale(1.15); }
    }
    @keyframes float-medium {
      0%, 100% { transform: translateY(0px) scale(1.1); }
      50% { transform: translateY(15px) scale(0.95); }
    }
    #bg-glow-1 { animation: float-slow 10s ease-in-out infinite; }
    #bg-glow-2 { animation: float-medium 14s ease-in-out infinite alternate; }
  `}</style>

  <svg width="860" height="240" style={{ position: 'absolute', top: 0, left: 0 }}>
    <defs>
      <radialGradient id="aurora-purple" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(99, 102, 241, 0.65)" />
        <stop offset="50%" stopColor="rgba(168, 85, 247, 0.25)" />
        <stop offset="100%" stopColor="rgba(0,0,0,0)" />
      </radialGradient>
      <radialGradient id="aurora-cyan" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(6, 182, 212, 0.45)" />
        <stop offset="60%" stopColor="rgba(59, 130, 246, 0.15)" />
        <stop offset="100%" stopColor="rgba(0,0,0,0)" />
      </radialGradient>
    </defs>
    <circle id="bg-glow-1" cx="150" cy="50" r="220" fill="url(#aurora-purple)" />
    <circle id="bg-glow-2" cx="720" cy="180" r="260" fill="url(#aurora-cyan)" />
  </svg>

  <div style={{
    position: 'absolute', left: 44, top: 52, width: 136, height: 136,
    borderRadius: 68, background: 'rgba(255, 255, 255, 0.05)',
    display: 'flex', alignItems: 'center', justifyContent: 'center',
    border: '1.5px solid rgba(255, 255, 255, 0.12)',
    boxShadow: '0 4px 15px rgba(0,0,0,0.2)'
  }}>
    <img src={github?.user?.avatarUrl ?? 'https://github.com/masudDev03.png'} width={120} height={120} style={{ borderRadius: 60 }} />
  </div>

  <div style={{ display: 'flex', flexDirection: 'column', marginLeft: 216, gap: 8, zIndex: 10 }}>
    <div style={{ display: 'flex', alignItems: 'center', gap: 10 }}>
      <div style={{ fontSize: 36, fontWeight: 800, color: '#ffffff', letterSpacing: '-1px' }}>
        Mohammad Masud
      </div>
      <div style={{
        display: 'flex', padding: '3px 9px', borderRadius: 8,
        background: 'rgba(99, 102, 241, 0.2)', border: '1px solid rgba(99, 102, 241, 0.4)',
        color: '#818cf8', fontSize: 11, fontWeight: 700, textTransform: 'uppercase', letterSpacing: '0.5px'
      }}>
        Learning • Building • Growing
      </div>
    </div>
    
    <div style={{ fontSize: 16, color: '#94a3b8', fontWeight: 500 }}>
      Student Developer • Frontend Explorer • AI Enthusiast
    </div>

    <div style={{
      display: 'flex', padding: '8px 14px', borderRadius: 10, marginTop: 6,
      background: 'rgba(255, 255, 255, 0.03)', border: '1px solid rgba(255, 255, 255, 0.07)',
      color: '#e2e8f0', fontSize: 13, fontStyle: 'italic', maxWidth: 450
    }}>
      "Build. Learn. Improve. Repeat."
    </div>
  </div>
</div>
```

```aura width=860 height=160 link="https://github.com/masudDev03"
<div style={{
  width: '100%', height: '100%', background: '#0a0b10',
  display: 'flex', flexDirection: 'column', fontFamily: 'Plus Jakarta Sans, sans-serif',
  position: 'relative', overflow: 'hidden', borderRadius: 20,
  border: '1px solid rgba(255, 255, 255, 0.05)',
  padding: 24, justifyContent: 'center'
}}>
  <svg width="860" height="160" style={{ position: 'absolute', top: 0, left: 0 }}>
    <defs>
      <radialGradient id="aurora-pink" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(236, 72, 153, 0.35)" />
        <stop offset="60%" stopColor="rgba(236, 72, 153, 0.05)" />
        <stop offset="100%" stopColor="rgba(0,0,0,0)" />
      </radialGradient>
    </defs>
    <circle cx="430" cy="80" r="150" fill="url(#aurora-pink)" />
  </svg>

  <div style={{ display: 'flex', flexDirection: 'column', zIndex: 10 }}>
    <div style={{ display: 'flex', alignItems: 'center', gap: 6, marginBottom: 10 }}>
      <div style={{ width: 18, height: 18, borderRadius: 9, background: '#ec4899', display: 'flex', alignItems: 'center', justifyContent: 'center', marginRight: 6, fontSize: 10, fontWeight: 800, color: '#fff' }}>👤</div>
      <h3 style={{ margin: 0, padding: 0, fontSize: 16, fontWeight: 700, color: '#ffffff' }}>About Me</h3>
    </div>
    <p style={{ margin: 0, padding: 0, fontSize: 13, color: '#94a3b8', lineHeight: 1.5 }}>
      I am a high school student who enjoys learning about technology and creating projects. 
      I like working on frontend development, experimenting with AI tools, and improving my skills through practice.
    </p>
    <div style={{ display: 'flex', gap: 8, flexWrap: 'wrap', marginTop: 12 }}>
      {[
        {
          label: 'High Schooler',
          icon: (
            <div style={{ width: 14, height: 14, borderRadius: 3, background: 'rgba(255,255,255,0.15)', display: 'flex', alignItems: 'center', justifyContent: 'center', marginRight: 4, fontSize: 8, color: '#cbd5e1' }}>🎓</div>
          )
        },
        {
          label: 'Builder',
          icon: (
            <div style={{ width: 14, height: 14, borderRadius: 3, background: 'rgba(255,255,255,0.15)', display: 'flex', alignItems: 'center', justifyContent: 'center', marginRight: 4, fontSize: 8, color: '#cbd5e1' }}>🔧</div>
          )
        },
        {
          label: 'Gamer',
          icon: (
            <div style={{ width: 14, height: 14, borderRadius: 3, background: 'rgba(255,255,255,0.15)', display: 'flex', alignItems: 'center', justifyContent: 'center', marginRight: 4, fontSize: 8, color: '#cbd5e1' }}>🎮</div>
          )
        },
        {
          label: 'AI Explorer',
          icon: (
            <div style={{ width: 14, height: 14, borderRadius: 3, background: 'rgba(255,255,255,0.15)', display: 'flex', alignItems: 'center', justifyContent: 'center', marginRight: 4, fontSize: 8, color: '#cbd5e1' }}>🤖</div>
          )
        }
      ].map(tag => (
        <span key={tag.label} style={{
          display: 'flex', alignItems: 'center', padding: '3px 8px', borderRadius: 6, fontSize: 11, fontWeight: 600,
          background: 'rgba(255, 255, 255, 0.05)', border: '1px solid rgba(255, 255, 255, 0.08)',
          color: '#cbd5e1'
        }}>
          {tag.icon}
          {tag.label}
        </span>
      ))}
    </div>
  </div>
</div>
```

<div align="center">

```aura inline width=278 height=60 link="https://linkedin.com/in/mohammad-m-593780393/"
<div style={{
  width: '100%', height: '100%', background: '#0a0b10',
  display: 'flex', alignItems: 'center', justifyContent: 'center',
  fontFamily: 'Plus Jakarta Sans, sans-serif',
  position: 'relative', overflow: 'hidden', borderRadius: 12,
  border: '1px solid rgba(10, 102, 194, 0.3)',
  boxShadow: '0 4px 15px rgba(0, 0, 0, 0.2)'
}}>
  <div style={{
    position: 'absolute', top: 0, left: 0, width: '100%', height: '100%',
    background: 'rgba(10, 102, 194, 0.12)', zIndex: 1
  }} />
  <div style={{ display: 'flex', alignItems: 'center', gap: 8, zIndex: 10 }}>
    <div style={{ width: 22, height: 22, borderRadius: 5, background: '#0a66c2', display: 'flex', alignItems: 'center', justifyContent: 'center', marginRight: 6, fontSize: 12, fontWeight: 900, color: '#fff' }}>in</div>
    <span style={{ fontSize: 13, fontWeight: 700, color: '#7dd3fc', letterSpacing: '0.5px' }}>LinkedIn</span>
  </div>
</div>
```
```aura inline width=278 height=60 link="https://instagram.com/keitaro_desu_/"
<div style={{
  width: '100%', height: '100%', background: '#0a0b10',
  display: 'flex', alignItems: 'center', justifyContent: 'center',
  fontFamily: 'Plus Jakarta Sans, sans-serif',
  position: 'relative', overflow: 'hidden', borderRadius: 12,
  border: '1px solid rgba(219, 48, 105, 0.3)',
  boxShadow: '0 4px 15px rgba(0, 0, 0, 0.2)'
}}>
  <div style={{
    position: 'absolute', top: 0, left: 0, width: '100%', height: '100%',
    background: 'rgba(219, 48, 105, 0.12)', zIndex: 1
  }} />
  <div style={{ display: 'flex', alignItems: 'center', gap: 8, zIndex: 10 }}>
    <div style={{ width: 22, height: 22, borderRadius: 5, background: 'linear-gradient(45deg, #f09433, #e6683c, #dc2743, #cc2366, #bc1888)', display: 'flex', alignItems: 'center', justifyContent: 'center', marginRight: 6, fontSize: 11, fontWeight: 900, color: '#fff' }}>IG</div>
    <span style={{ fontSize: 13, fontWeight: 700, color: '#fda4af', letterSpacing: '0.5px' }}>Instagram</span>
  </div>
</div>
```
```aura inline width=278 height=60 link="https://discord.com/users/1486416686943961129"
<div style={{
  width: '100%', height: '100%', background: '#0a0b10',
  display: 'flex', alignItems: 'center', justifyContent: 'center',
  fontFamily: 'Plus Jakarta Sans, sans-serif',
  position: 'relative', overflow: 'hidden', borderRadius: 12,
  border: '1px solid rgba(88, 101, 242, 0.3)',
  boxShadow: '0 4px 15px rgba(0, 0, 0, 0.2)'
}}>
  <div style={{
    position: 'absolute', top: 0, left: 0, width: '100%', height: '100%',
    background: 'rgba(88, 101, 242, 0.15)', zIndex: 1
  }} />
  <div style={{ display: 'flex', alignItems: 'center', gap: 8, zIndex: 10 }}>
    <div style={{ width: 22, height: 22, borderRadius: 5, background: '#5865f2', display: 'flex', alignItems: 'center', justifyContent: 'center', marginRight: 6, fontSize: 11, fontWeight: 900, color: '#fff' }}>DC</div>
    <span style={{ fontSize: 13, fontWeight: 700, color: '#c7d2fe', letterSpacing: '0.5px' }}>Discord</span>
  </div>
</div>
```

</div>

```aura width=860 height=260 link="https://github.com/masudDev03"
<div style={{
  width: '100%', height: '100%', background: '#0a0b10',
  display: 'flex', fontFamily: 'Plus Jakarta Sans, sans-serif',
  position: 'relative', overflow: 'hidden', borderRadius: 20,
  border: '1px solid rgba(255, 255, 255, 0.05)',
  padding: 24, gap: 20
}}>
  <svg width="860" height="260" style={{ position: 'absolute', top: 0, left: 0 }}>
    <defs>
      <radialGradient id="aurora-amber" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(245, 158, 11, 0.4)" />
        <stop offset="70%" stopColor="rgba(0,0,0,0)" />
      </radialGradient>
    </defs>
    <circle cx="700" cy="50" r="180" fill="url(#aurora-amber)" />
  </svg>

  <div style={{
    flex: 1, display: 'flex', flexDirection: 'column',
    background: 'rgba(255, 255, 255, 0.03)', border: '1px solid rgba(255, 255, 255, 0.07)',
    borderRadius: 14, padding: 20, zIndex: 10, boxShadow: 'inset 0 1px 0 rgba(255,255,255,0.05)'
  }}>
    <div style={{ display: 'flex', alignItems: 'center', gap: 6, marginBottom: 12 }}>
      <div style={{ width: 22, height: 22, borderRadius: 6, background: 'rgba(251, 146, 60, 0.2)', border: '1.5px solid #fb923c', display: 'flex', alignItems: 'center', justifyContent: 'center', marginRight: 6, fontSize: 12 }}>⚙</div>
      <h3 style={{ margin: 0, padding: 0, fontSize: 16, fontWeight: 700, color: '#ffffff' }}>Skills & Tools</h3>
    </div>
    <div style={{ display: 'flex', flexWrap: 'wrap', gap: 8, flex: 1, alignItems: 'center' }}>
      {[
        { name: 'HTML5', color: '#ff7b72', bg: 'rgba(244, 63, 94, 0.12)', border: 'rgba(244, 63, 94, 0.3)' },
        { name: 'CSS3', color: '#7dd3fc', bg: 'rgba(56, 189, 248, 0.12)', border: 'rgba(56, 189, 248, 0.3)' },
        { name: 'JavaScript', color: '#fef08a', bg: 'rgba(234, 179, 8, 0.12)', border: 'rgba(234, 179, 8, 0.3)' },
        { name: 'Git', color: '#fdba74', bg: 'rgba(249, 115, 22, 0.12)', border: 'rgba(249, 115, 22, 0.3)' },
        { name: 'GitHub', color: '#e2e8f0', bg: 'rgba(255, 255, 255, 0.06)', border: 'rgba(255, 255, 255, 0.15)' },
        { name: 'VS Code', color: '#a5b4fc', bg: 'rgba(99, 102, 241, 0.12)', border: 'rgba(99, 102, 241, 0.3)' }
      ].map(skill => (
        <span key={skill.name} style={{
          display: 'flex', padding: '6px 12px', borderRadius: 8, fontSize: 12, fontWeight: 700,
          background: skill.bg, border: `1px solid ${skill.border}`, color: skill.color
        }}>
          {skill.name}
        </span>
      ))}
    </div>
  </div>

  <div style={{
    flex: 1, display: 'flex', flexDirection: 'column',
    background: 'rgba(255, 255, 255, 0.03)', border: '1px solid rgba(255, 255, 255, 0.07)',
    borderRadius: 14, padding: 20, zIndex: 10, boxShadow: 'inset 0 1px 0 rgba(255,255,255,0.05)'
  }}>
    <div style={{ display: 'flex', alignItems: 'center', gap: 6, marginBottom: 12 }}>
      <div style={{ width: 22, height: 22, borderRadius: 6, background: 'rgba(74, 222, 128, 0.2)', border: '1.5px solid #4ade80', display: 'flex', alignItems: 'center', justifyContent: 'center', marginRight: 6, fontSize: 12 }}>📚</div>
      <h3 style={{ margin: 0, padding: 0, fontSize: 16, fontWeight: 700, color: '#ffffff' }}>Currently Learning</h3>
    </div>
    
    <div style={{ display: 'flex', flexDirection: 'column', gap: 8, flex: 1, justifyContent: 'center' }}>
      {[
        'AI Tools & Automation workflows',
        'Use of AI in modern software development',
        'Advanced frontend frameworks & layout models',
        'Creative web UI design & interactive mockups'
      ].map(goal => (
        <div key={goal} style={{ display: 'flex', alignItems: 'center', gap: 4 }}>
          <div style={{ width: 6, height: 6, borderRadius: 3, background: '#818cf8', marginRight: 6, flexShrink: 0 }} />
          <span style={{ fontSize: 13, color: '#94a3b8', lineHeight: 1.4 }}>{goal}</span>
        </div>
      ))}
    </div>
  </div>
</div>
```

```aura width=860 height=200 link="https://github.com/masudDev03"
<div style={{
  width: '100%', height: '100%', background: '#0a0b10',
  display: 'flex', fontFamily: 'Plus Jakarta Sans, sans-serif',
  position: 'relative', overflow: 'hidden', borderRadius: 20,
  border: '1px solid rgba(255, 255, 255, 0.05)',
  padding: 24, gap: 20
}}>
  <svg width="860" height="200" style={{ position: 'absolute', top: 0, left: 0 }}>
    <defs>
      <radialGradient id="aurora-green" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(16, 185, 129, 0.35)" />
        <stop offset="70%" stopColor="rgba(0,0,0,0)" />
      </radialGradient>
    </defs>
    <circle cx="150" cy="180" r="160" fill="url(#aurora-green)" />
  </svg>

  <div style={{
    flex: 1.1, display: 'flex', flexDirection: 'column', justifyContent: 'center',
    background: 'rgba(255, 255, 255, 0.03)', border: '1px solid rgba(255, 255, 255, 0.07)',
    borderRadius: 14, padding: 20, zIndex: 10, boxShadow: 'inset 0 1px 0 rgba(255,255,255,0.05)'
  }}>
    <div style={{ display: 'flex', alignItems: 'center', gap: 6, marginBottom: 8 }}>
      <div style={{ width: 22, height: 22, borderRadius: 6, background: 'rgba(251, 113, 133, 0.2)', border: '1.5px solid #fb7185', display: 'flex', alignItems: 'center', justifyContent: 'center', marginRight: 6, fontSize: 12 }}>💬</div>
      <h3 style={{ margin: 0, padding: 0, fontSize: 15, fontWeight: 700, color: '#ffffff' }}>Favorite Quote</h3>
    </div>
    <div style={{ fontSize: 14, fontStyle: 'italic', color: '#e2e8f0', lineHeight: 1.4, margin: '8px 0 4px 0' }}>
      "The best way to predict the future is to create it."
    </div>
    <div style={{ fontSize: 11, color: '#64748b', fontWeight: 600 }}>— Keep building, keep learning.</div>
  </div>

  <div style={{
    flex: 0.9, display: 'flex', flexDirection: 'column',
    background: 'rgba(255, 255, 255, 0.03)', border: '1px solid rgba(255, 255, 255, 0.07)',
    borderRadius: 14, padding: 20, zIndex: 10, boxShadow: 'inset 0 1px 0 rgba(255,255,255,0.05)'
  }}>
    <div style={{ display: 'flex', alignItems: 'center', gap: 6, marginBottom: 10 }}>
      <div style={{ width: 22, height: 22, borderRadius: 6, background: 'rgba(52, 211, 153, 0.2)', border: '1.5px solid #34d399', display: 'flex', alignItems: 'center', justifyContent: 'center', marginRight: 6, fontSize: 12 }}>🎯</div>
      <h3 style={{ margin: 0, padding: 0, fontSize: 15, fontWeight: 700, color: '#ffffff' }}>Current Goals</h3>
    </div>
    <div style={{ display: 'flex', flexDirection: 'column', gap: 6, justifyContent: 'center', flex: 1 }}>
      {[
        'Build practical & complex web projects',
        'Deepen knowledge of agentic AI systems',
        'Share learnings and collaborate online'
      ].map(goal => (
        <div key={goal} style={{ display: 'flex', alignItems: 'center', gap: 4 }}>
          <div style={{ width: 6, height: 6, borderRadius: 3, background: '#34d399', marginRight: 6, flexShrink: 0 }} />
          <span style={{ fontSize: 12, color: '#94a3b8' }}>{goal}</span>
        </div>
      ))}
    </div>
  </div>
</div>
```

---

## 📊 GitHub Statistics

<p align="center">
  <img height="180em" src="https://github-readme-streak-stats.herokuapp.com/?user=masudDev03&theme=tokyonight&hide_border=true" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=masudDev03&layout=compact&theme=tokyonight&hide_border=true" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=masudDev03&theme=tokyo-night&hide_border=true" />
</p>

---

<div align="center">
  <sub>Created with <strong>readme-aura</strong> and many late-night coding sessions</sub>
</div>
