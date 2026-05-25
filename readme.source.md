
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
      <svg viewBox="0 0 24 24" width="18" height="18" stroke="#ec4899" fill="none" strokeWidth="2.5" strokeLinecap="round" strokeLinejoin="round" style={{ marginRight: 2 }}>
        <path d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2" />
        <circle cx="12" cy="7" r="4" />
      </svg>
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
            <svg viewBox="0 0 24 24" width="12" height="12" stroke="currentColor" fill="none" strokeWidth="2.5" strokeLinecap="round" strokeLinejoin="round" style={{ marginRight: 4 }}>
              <path d="M22 10v6M2 10l10-5 10 5-10 5z" />
              <path d="M6 12v5c0 2 2 3 6 3s6-1 6-3v-5" />
            </svg>
          )
        },
        {
          label: 'Builder',
          icon: (
            <svg viewBox="0 0 24 24" width="12" height="12" stroke="currentColor" fill="none" strokeWidth="2.5" strokeLinecap="round" strokeLinejoin="round" style={{ marginRight: 4 }}>
              <path d="M14.7 6.3a1 1 0 0 0 0 1.4l1.6 1.6a1 1 0 0 0 1.4 0l3.77-3.77a6 6 0 0 1-7.94 7.94l-6.91 6.91a2.12 2.12 0 0 1-3-3l6.91-6.91a6 6 0 0 1 7.94-7.94l-3.76 3.76z" />
            </svg>
          )
        },
        {
          label: 'Gamer',
          icon: (
            <svg viewBox="0 0 24 24" width="12" height="12" stroke="currentColor" fill="none" strokeWidth="2.5" strokeLinecap="round" strokeLinejoin="round" style={{ marginRight: 4 }}>
              <line x1="6" y1="12" x2="10" y2="12" />
              <line x1="8" y1="10" x2="8" y2="14" />
              <line x1="15" y1="13" x2="15.01" y2="13" />
              <line x1="18" y1="11" x2="18.01" y2="11" />
              <rect x="2" y="6" width="20" height="12" rx="3" />
            </svg>
          )
        },
        {
          label: 'AI Explorer',
          icon: (
            <svg viewBox="0 0 24 24" width="12" height="12" stroke="currentColor" fill="none" strokeWidth="2.5" strokeLinecap="round" strokeLinejoin="round" style={{ marginRight: 4 }}>
              <rect x="3" y="11" width="18" height="10" rx="2" />
              <circle cx="12" cy="5" r="2" />
              <path d="M12 7v4M9 16h6M8 14h.01M16 14h.01" />
            </svg>
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
    <svg viewBox="0 0 24 24" width="16" height="16" fill="#7dd3fc" style={{ marginRight: 2 }}>
      <path d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.762 0 5-2.239 5-5v-14c0-2.761-2.238-5-5-5zm-11 19h-3v-11h3v11zm-1.5-12.268c-.966 0-1.75-.79-1.75-1.764s.784-1.764 1.75-1.764 1.75.79 1.75 1.764-.783 1.764-1.75 1.764zm13.5 12.268h-3v-5.604c0-3.368-4-3.113-4 0v5.604h-3v-11h3v1.765c1.396-2.586 7-2.777 7 2.476v6.759z" />
    </svg>
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
    <svg viewBox="0 0 24 24" width="16" height="16" stroke="#fda4af" fill="none" strokeWidth="2.5" strokeLinecap="round" strokeLinejoin="round" style={{ marginRight: 2 }}>
      <rect x="2" y="2" width="20" height="20" rx="5" ry="5" />
      <path d="M16 11.37A4 4 0 1 1 12.63 8 4 4 0 0 1 16 11.37zM17.5 6.5h.01" />
    </svg>
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
    <svg viewBox="0 0 24 24" width="16" height="16" fill="#c7d2fe" style={{ marginRight: 2 }}>
      <path d="M20.317 4.37a19.791 19.791 0 0 0-4.885-1.515.074.074 0 0 0-.079.037c-.21.375-.444.864-.608 1.25a18.27 18.27 0 0 0-5.487 0 12.64 12.64 0 0 0-.617-1.25.077.077 0 0 0-.079-.037A19.736 19.736 0 0 0 3.677 4.37a.07.07 0 0 0-.032.027C.533 9.046-.32 13.58.099 18.057a.082.082 0 0 0 .031.057 19.9 19.9 0 0 0 5.993 3.03.078.078 0 0 0 .084-.028c.462-.63.874-1.295 1.226-1.994.021-.041.001-.09-.041-.106a13.094 13.094 0 0 1-1.873-.894.077.077 0 0 1-.008-.128c.126-.093.252-.19.372-.287a.075.075 0 0 1 .077-.011c3.92 1.793 8.18 1.793 12.061 0a.073.073 0 0 1 .078.009c.12.099.246.195.373.289a.077.077 0 0 1-.006.127 12.299 12.299 0 0 1-1.873.894.077.077 0 0 0-.041.107c.36.698.772 1.362 1.225 1.993a.076.076 0 0 0 .084.028 19.839 19.839 0 0 0 6.002-3.03.077.077 0 0 0 .032-.054c.5-5.177-.838-9.674-3.549-13.66a.061.061 0 0 0-.031-.03zM8.02 15.33c-1.183 0-2.157-1.085-2.157-2.419 0-1.333.956-2.419 2.156-2.419 1.21 0 2.176 1.096 2.157 2.42 0 1.333-.956 2.418-2.156 2.418zm7.975 0c-1.183 0-2.157-1.085-2.157-2.419 0-1.333.955-2.419 2.156-2.419 1.21 0 2.176 1.096 2.157 2.42 0 1.333-.946 2.418-2.156 2.418z" />
    </svg>
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
      <svg viewBox="0 0 24 24" width="18" height="18" stroke="#fb923c" fill="none" strokeWidth="2.5" strokeLinecap="round" strokeLinejoin="round" style={{ marginRight: 2 }}>
        <circle cx="12" cy="12" r="3" />
        <path d="M19.4 15a1.65 1.65 0 0 0 .33 1.82l.06.06a2 2 0 1 1-2.83 2.83l-.06-.06a1.65 1.65 0 0 0-1.82-.33 1.65 1.65 0 0 0-1 1.51V21a2 2 0 0 1-4 0v-.09A1.65 1.65 0 0 0 9 19.4a1.65 1.65 0 0 0-1.82.33l-.06.06a2 2 0 1 1-2.83-2.83l.06-.06a1.65 1.65 0 0 0 .33-1.82 1.65 1.65 0 0 0-1.51-1H3a2 2 0 0 1 0-4h.09A1.65 1.65 0 0 0 4.6 9a1.65 1.65 0 0 0-.33-1.82l-.06-.06a2 2 0 1 1 2.83-2.83l.06.06a1.65 1.65 0 0 0 1.82.33H9a1.65 1.65 0 0 0 1-1.51V3a2 2 0 0 1 4 0v.09a1.65 1.65 0 0 0 1 1.51 1.65 1.65 0 0 0 1.82-.33l.06-.06a2 2 0 1 1 2.83 2.83l-.06.06a1.65 1.65 0 0 0-.33 1.82V9a1.65 1.65 0 0 0 1.51 1H21a2 2 0 0 1 0 4h-.09a1.65 1.65 0 0 0-1.51-1z" />
      </svg>
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
      <svg viewBox="0 0 24 24" width="18" height="18" stroke="#4ade80" fill="none" strokeWidth="2.5" strokeLinecap="round" strokeLinejoin="round" style={{ marginRight: 2 }}>
        <path d="M12 22V12" />
        <path d="M12 12c0-2.8 2.2-5 5-5h4v4c0 2.8-2.2 5-5 5h-4" />
        <path d="M12 16c0-2.2-1.8-4-4-4H4v4c0 2.2 1.8 4 4 4h4" />
        <path d="M12 12c0-3.3-2.7-6-6-6H2v6c0 3.3 2.7 6 6 6h4" />
      </svg>
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
          <svg viewBox="0 0 24 24" width="12" height="12" stroke="#818cf8" fill="none" strokeWidth="3" strokeLinecap="round" strokeLinejoin="round" style={{ marginRight: 4, flexShrink: 0 }}>
            <polyline points="9 18 15 12 9 6" />
          </svg>
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
      <svg viewBox="0 0 24 24" width="18" height="18" stroke="#fb7185" fill="none" strokeWidth="2.5" strokeLinecap="round" strokeLinejoin="round" style={{ marginRight: 2 }}>
        <path d="M21 15a2 2 0 0 1-2 2H7l-4 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z" />
      </svg>
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
      <svg viewBox="0 0 24 24" width="18" height="18" stroke="#34d399" fill="none" strokeWidth="2.5" strokeLinecap="round" strokeLinejoin="round" style={{ marginRight: 2 }}>
        <circle cx="12" cy="12" r="10" />
        <circle cx="12" cy="12" r="6" />
        <circle cx="12" cy="12" r="2" />
      </svg>
      <h3 style={{ margin: 0, padding: 0, fontSize: 15, fontWeight: 700, color: '#ffffff' }}>Current Goals</h3>
    </div>
    <div style={{ display: 'flex', flexDirection: 'column', gap: 6, justifyContent: 'center', flex: 1 }}>
      {[
        'Build practical & complex web projects',
        'Deepen knowledge of agentic AI systems',
        'Share learnings and collaborate online'
      ].map(goal => (
        <div key={goal} style={{ display: 'flex', alignItems: 'center', gap: 4 }}>
          <svg viewBox="0 0 24 24" width="12" height="12" stroke="#34d399" fill="none" strokeWidth="3" strokeLinecap="round" strokeLinejoin="round" style={{ marginRight: 4, flexShrink: 0 }}>
            <polyline points="9 18 15 12 9 6" />
          </svg>
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
