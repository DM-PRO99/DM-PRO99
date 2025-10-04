<div align="center">

<svg viewBox="0 0 800 200" xmlns="http://www.w3.org/2000/svg">
  <!-- Fondo galáctico animado -->
  <defs>
    <linearGradient id="galaxy" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#0A192F">
        <animate attributeName="stop-color" values="#0A192F;#1E3C72;#2ED573;#0A192F" dur="8s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" stop-color="#2ED573">
        <animate attributeName="stop-color" values="#2ED573;#00FFA3;#1E90FF;#2ED573" dur="8s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>
  </defs>
  
  <!-- Rectángulo de fondo -->
  <rect width="800" height="200" fill="url(#galaxy)" />

  <!-- Texto con efecto neón -->
  <text x="50%" y="50%" dominant-baseline="middle" text-anchor="middle"
    style="font-family:'Courier New', monospace; font-size: 48px; fill: #FFFFFF; filter: drop-shadow(0 0 10px #2ED573);">
    Hi, I'm Diego Mena 👋
    <animate attributeName="fill" values="#FFFFFF;#A0F6D2;#FFFFFF" dur="3s" repeatCount="indefinite"/>
  </text>
</svg>

</div>
