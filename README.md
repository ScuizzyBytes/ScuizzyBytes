<div align="center">

<!-- ANIMATED QUANTUM ATOM & VECTOR MATRIX SVG HEADER -->
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 320" width="100%" style="background: #0d1117; border-radius: 12px; border: 1px solid #30363d;">
  <defs>
    <!-- Glow Filters -->
    <filter id="glow-cyan" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="6" result="blur" />
      <feMerge>
        <feMergeNode in="blur" />
        <feMergeNode in="SourceGraphic" />
      </feMerge>
    </filter>
    <filter id="glow-core" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="12" result="blur" />
      <feMerge>
        <feMergeNode in="blur" />
        <feMergeNode in="SourceGraphic" />
      </feMerge>
    </filter>
    
    <!-- Linear Gradients -->
    <linearGradient id="cyber-grad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#00f0ff" />
      <stop offset="50%" stop-color="#7000ff" />
      <stop offset="100%" stop-color="#ff0055" />
    </linearGradient>
  </defs>

  <!-- Background Vector Matrix Grid -->
  <g stroke="#ffffff" stroke-opacity="0.04" stroke-width="1">
    <line x1="0" y1="40" x2="900" y2="40"/>
    <line x1="0" y1="80" x2="900" y2="80"/>
    <line x1="0" y1="120" x2="900" y2="120"/>
    <line x1="0" y1="160" x2="900" y2="160"/>
    <line x1="0" y1="200" x2="900" y2="200"/>
    <line x1="0" y1="240" x2="900" y2="240"/>
    <line x1="0" y1="280" x2="900" y2="280"/>
    
    <line x1="100" y1="0" x2="100" y2="320"/>
    <line x1="200" y1="0" x2="200" y2="320"/>
    <line x1="300" y1="0" x2="300" y2="320"/>
    <line x1="400" y1="0" x2="400" y2="320"/>
    <line x1="500" y1="0" x2="500" y2="320"/>
    <line x1="600" y1="0" x2="600" y2="320"/>
    <line x1="700" y1="0" x2="700" y2="320"/>
    <line x1="800" y1="0" x2="800" y2="320"/>
  </g>

  <!-- Animated Quantum Atom Centerpiece (Shifted Left) -->
  <g transform="translate(220, 160)">
    <!-- Atom Orbit 1 -->
    <ellipse rx="110" ry="42" fill="none" stroke="#00f0ff" stroke-width="2.5" opacity="0.8" transform="rotate(0)" filter="url(#glow-cyan)" />
    <!-- Atom Orbit 2 -->
    <ellipse rx="110" ry="42" fill="none" stroke="#7000ff" stroke-width="2.5" opacity="0.8" transform="rotate(60)" />
    <!-- Atom Orbit 3 -->
    <ellipse rx="110" ry="42" fill="none" stroke="#ff0055" stroke-width="2.5" opacity="0.8" transform="rotate(120)" />

    <!-- Quantum Electrons Orbiting -->
    <circle r="6" fill="#00f0ff" filter="url(#glow-cyan)">
      <animateMotion path="M -110,0 A 110,42 0 1,0 110,0 A 110,42 0 1,0 -110,0" dur="3s" repeatCount="indefinite" />
    </circle>
    <circle r="6" fill="#7000ff" filter="url(#glow-cyan)">
      <animateMotion path="M -55,-95.2 A 110,42 60 1,0 55,95.2 A 110,42 60 1,0 -55,-95.2" dur="2.4s" repeatCount="indefinite" />
    </circle>
    <circle r="6" fill="#ff0055" filter="url(#glow-cyan)">
      <animateMotion path="M 55,-95.2 A 110,42 120 1,0 -55,95.2 A 110,42 120 1,0 55,-95.2" dur="3.6s" repeatCount="indefinite" />
    </circle>

    <!-- Atomic Nucleus Core -->
    <circle r="18" fill="url(#cyber-grad)" filter="url(#glow-core)">
      <animate attributeName="r" values="16;20;16" dur="2s" repeatCount="indefinite" />
    </circle>
  </g>

  <!-- 3D to 2D Vector Projection Diagram (Shifted Right) -->
  <g transform="translate(650, 160)" stroke-linecap="round">
    <!-- Projected 2D Plane -->
    <polygon points="-80,-70 60,-70 100,70 -40,70" fill="#00f0ff" fill-opacity="0.05" stroke="#00f0ff" stroke-width="1.5" stroke-dasharray="4,4" />
    
    <!-- 3D Vector Ray (P_3D -> P_2D) -->
    <line x1="-120" y1="-110" x2="30" y2="10" stroke="#ff0055" stroke-width="2.5" filter="url(#glow-cyan)" />
    
    <!-- Vector Nodes -->
    <circle cx="-120" cy="-110" r="5" fill="#ff0055" filter="url(#glow-cyan)" />
    <circle cx="30" cy="10" r="5" fill="#00f0ff" filter="url(#glow-cyan)" />
    
    <!-- Mathematical Annotation Text -->
    <text x="-140" y="-120" fill="#ff0055" font-family="monospace" font-size="12" font-weight="bold">P(x, y, z)</text>
    <text x="45" y="25" fill="#00f0ff" font-family="monospace" font-size="12" font-weight="bold">P'(x/z, y/z)</text>
    <text x="-30" y="100" fill="#7000ff" font-family="monospace" font-size="13" font-weight="bold">Matrix3D ➔ Projection2D</text>
  </g>

  <!-- Cyber Titles -->
  <text x="450" y="45" text-anchor="middle" fill="#00f0ff" font-family="monospace" font-size="20" font-weight="900" letter-spacing="4" filter="url(#glow-cyan)">
    SYSTEM.INITIALIZE // QUANTUM_CORE
  </text>
</svg>

</div>

<br>

<div align="center">

# 🌌 SCUIZZYBYTES // QUANTUM ARCHITECT

```math
\hat{H}|\Psi\rangle = E|\Psi\rangle \quad \mathbf{\&} \quad \begin{bmatrix} X_{2d} \\ Y_{2d} \end{bmatrix} = \begin{bmatrix} \frac{f \cdot X}{Z} \\ \frac{f \cdot Y}{Z} \end{bmatrix}
```

### ⚡ Low-Level Systems Specialist & Network Engineer
*Dissecting binary streams at raw-socket level and transforming complex 3D quantum spaces into high-performance 2D code.*

---

<!-- DYNAMIC BADGES -->
<p align="center">
  <img src="https://img.shields.io/badge/CORE-PYTHON_3.12-00F0FF?style=for-the-badge&logo=python&logoColor=black" />
  <img src="https://img.shields.io/badge/NETWORK-RAW_SOCKETS-FF0055?style=for-the-badge&logo=linux&logoColor=white" />
  <img src="https://img.shields.io/badge/MATH-3D_VECTOR_PROJECTION-7000FF?style=for-the-badge" />
  <img src="https://img.shields.io/badge/GUI-CUSTOMTKINTER-00FF66?style=for-the-badge" />
</p>

</div>

---

## 🔬 TECH ARSENAL & QUANTUM STACK

```
┌───────────────────────────────┬──────────────────────────────────────────────┐
│ DOMAIN                        │ TECHNOLOGIES & TOOLS                         │
├───────────────────────────────┼──────────────────────────────────────────────┤
│ Low-Level & Networking        │ Python 3, Linux Raw Sockets (AF_PACKET), BSD │
│ Binary Parsing & Structs      │ Bitwise Masking, struct.unpack, Endianness   │
│ Vector Mathematics & 3D Math  │ 3D-to-2D Perspective Projection, Matrices    │
│ Frontend & Cyber Interfaces   │ CustomTkinter, Asynchronous Threading, Tk    │
│ Systems & OS                  │ WSL2, Linux Kernel Networking, Bash, Git     │
└───────────────────────────────┴──────────────────────────────────────────────┘
```

---

## 📐 THE VECTOR3D ➔ 2D PROJECTION ENGINE

```
       3D Space Point Vector P(x, y, z)
                 \
                  \  (Ray of Light / Perspective Transformation)
                   \
                    ▼ 
         [ Projection Matrix Plane ]
                    │
                    ├──> X_proj = (X * FocalLength) / Z
                    └──> Y_proj = (Y * FocalLength) / Z
                    │
                    ▼
          2D Screen Coordinate P'(x, y)
```

---

## ⚡ FEATURED HIGHLIGHT PROJECT

<div align="center">

### 🛡️ [CYBER_SNIFFER // Raw Socket Packet Monitor](https://github.com/ScuizzyBytes/cyber-packet-sniffer)
*A high-performance, zero-dependency network sniffer and frame dissector built from scratch.*

```
 [ RAW SOCKET (AF_PACKET) ] ──► [ ETHERNET II DISSECTOR ] ──► [ IPv4 IHL BITWISE MASK ] ──► [ CYBERPUNK GUI ]
```

* **Surgical Precision:** Direct bitwise `IHL & 15` masking to extract IPv4 payload offsets.
* **Low-Level Socket Ingestion:** Raw packet processing using native OS `SOCK_RAW` sockets.
* **Asynchronous GUI:** Multi-threaded live stream architecture powered by `CustomTkinter`.

</div>

---

## 📊 GITHUB QUANTUM METRICS

<div align="center">

<br>

<img src="https://github-readme-stats.vercel.app/api?username=ScuizzyBytes&show_icons=true&theme=cyberpunk&hide_border=true&bg_color=0d1117&title_color=00f0ff&icon_color=00f0ff&text_color=ffffff" width="48%" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ScuizzyBytes&layout=compact&theme=cyberpunk&hide_border=true&bg_color=0d1117&title_color=7000ff&text_color=ffffff" width="48%" />

<br><br>

<!-- ANIMATED STREAK STATS -->
<img src="https://github-readme-streak-stats.herokuapp.com/?user=ScuizzyBytes&theme=cyberpunk&hide_border=true&background=0d1117&ring=00f0ff&fire=ff0055&currStreakLabel=00f0ff" width="97%" />

</div>

---

<div align="center">

### 🌐 CONNECT WITH THE QUANTUM CORE

[![GitHub](https://img.shields.io/badge/GitHub-ScuizzyBytes-00F0FF?style=for-the-badge&logo=github&logoColor=black)](https://github.com/ScuizzyBytes)
[![Terminal](https://img.shields.io/badge/Status-Online_&_Coding-00FF66?style=for-the-badge)](https://github.com/ScuizzyBytes)

<br>

```
"Every complex system is built from simple bits; master the bits, master the system."
```

</div>
