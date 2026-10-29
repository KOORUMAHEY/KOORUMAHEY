<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 800 400" width="800" height="400" font-family="Segoe UI, Ubuntu, Helvetica, Arial, sans-serif">
  <defs>
    <linearGradient id="bg" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#020617"/>
      <stop offset="100%" stop-color="#04201a"/>
    </linearGradient>
    <radialGradient id="core" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#ecfdf5"/>
      <stop offset="35%" stop-color="#34d399"/>
      <stop offset="70%" stop-color="#10B981" stop-opacity="0.5"/>
      <stop offset="100%" stop-color="#10B981" stop-opacity="0"/>
    </radialGradient>
    <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="3" result="b"/>
      <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <path id="o1" d="M270,210 a130,40 0 1,1 260,0 a130,40 0 1,1 -260,0"/>
    <path id="o2" d="M180,210 a220,70 0 1,1 440,0 a220,70 0 1,1 -440,0"/>
    <path id="o3" d="M80,210 a320,105 0 1,1 640,0 a320,105 0 1,1 -640,0"/>
  </defs>

  <rect width="800" height="400" rx="18" fill="url(#bg)"/>

  <!-- stars -->
  <g fill="#ffffff">
    <circle cx="60" cy="40" r="1.2"><animate attributeName="opacity" values="0.2;1;0.2" dur="3s" repeatCount="indefinite"/></circle>
    <circle cx="150" cy="90" r="1"><animate attributeName="opacity" values="1;0.2;1" dur="4s" repeatCount="indefinite"/></circle>
    <circle cx="250" cy="30" r="1.5"><animate attributeName="opacity" values="0.3;1;0.3" dur="2.5s" repeatCount="indefinite"/></circle>
    <circle cx="560" cy="50" r="1.2"><animate attributeName="opacity" values="1;0.3;1" dur="3.5s" repeatCount="indefinite"/></circle>
    <circle cx="700" cy="80" r="1.6"><animate attributeName="opacity" values="0.2;1;0.2" dur="5s" repeatCount="indefinite"/></circle>
    <circle cx="760" cy="300" r="1"><animate attributeName="opacity" values="1;0.2;1" dur="3s" repeatCount="indefinite"/></circle>
    <circle cx="40" cy="330" r="1.4"><animate attributeName="opacity" values="0.3;1;0.3" dur="4.5s" repeatCount="indefinite"/></circle>
    <circle cx="640" cy="370" r="1"><animate attributeName="opacity" values="0.2;1;0.2" dur="2.8s" repeatCount="indefinite"/></circle>
    <circle cx="120" cy="370" r="1.2"><animate attributeName="opacity" values="1;0.3;1" dur="3.8s" repeatCount="indefinite"/></circle>
    <circle cx="460" cy="25" r="1"><animate attributeName="opacity" values="0.3;1;0.3" dur="4.2s" repeatCount="indefinite"/></circle>
  </g>

  <!-- shooting star -->
  <line x1="0" y1="0" x2="60" y2="20" stroke="#a7f3d0" stroke-width="1.5" stroke-linecap="round" opacity="0">
    <animate attributeName="opacity" values="0;1;0;0" keyTimes="0;0.05;0.15;1" dur="7s" repeatCount="indefinite"/>
    <animateTransform attributeName="transform" type="translate" values="100,20;500,150;500,150" keyTimes="0;0.15;1" dur="7s" repeatCount="indefinite"/>
  </line>

  <!-- title -->
  <text x="400" y="52" text-anchor="middle" fill="#10B981" font-size="30" font-weight="700" letter-spacing="10" filter="url(#glow)">CODEVERSE</text>
  <text x="400" y="76" text-anchor="middle" fill="#94a3b8" font-size="12" letter-spacing="3">THE UNIVERSE I'M BUILDING</text>

  <!-- orbits -->
  <g fill="none" stroke="#10B981" stroke-opacity="0.25" stroke-dasharray="4 6">
    <use href="#o1"/><use href="#o2"/><use href="#o3"/>
  </g>

  <!-- core -->
  <circle cx="400" cy="210" r="42" fill="url(#core)">
    <animate attributeName="r" values="38;46;38" dur="4s" repeatCount="indefinite"/>
  </circle>
  <circle cx="400" cy="210" r="16" fill="#ecfdf5" filter="url(#glow)"/>

  <!-- planets -->
  <g>
    <circle r="8" fill="#34d399" filter="url(#glow)"/>
    <text y="-14" text-anchor="middle" fill="#e2e8f0" font-size="12" font-weight="600">AI / ML</text>
    <animateMotion dur="9s" repeatCount="indefinite"><mpath href="#o1"/></animateMotion>
  </g>
  <g>
    <circle r="10" fill="#22d3ee" filter="url(#glow)"/>
    <text y="-16" text-anchor="middle" fill="#e2e8f0" font-size="12" font-weight="600">ROBOTICS</text>
    <animateMotion dur="16s" repeatCount="indefinite"><mpath href="#o2"/></animateMotion>
  </g>
  <g>
    <circle r="9" fill="#a78bfa" filter="url(#glow)"/>
    <text y="-15" text-anchor="middle" fill="#e2e8f0" font-size="12" font-weight="600">FULL STACK</text>
    <animateMotion dur="24s" repeatCount="indefinite"><mpath href="#o3"/></animateMotion>
  </g>
  <g>
    <circle r="7" fill="#fbbf24" filter="url(#glow)"/>
    <text y="-13" text-anchor="middle" fill="#e2e8f0" font-size="12" font-weight="600">RESEARCH</text>
    <animateMotion dur="24s" begin="-12s" repeatCount="indefinite"><mpath href="#o3"/></animateMotion>
  </g>

  <text x="400" y="385" text-anchor="middle" fill="#64748b" font-size="11" letter-spacing="4">BUILD  &lt;  LEARN  &lt;  EXPLORE  &lt;  IMPACT</text>
</svg>
