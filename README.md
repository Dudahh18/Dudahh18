<div align="center">

<!----------------------------------- TÍTULO ANIMADO GLITCH + TYPE ----------------------------------->
<div style="background: linear-gradient(90deg, #1a1a1a 0%, #2d1b69 50%, #1a1a1a 100%); padding: 3rem 2rem; border-radius: 25px; border: 2px solid #C9A7EB40; box-shadow: 0 0 50px #C9A7EB30, inset 0 0 50px #C9A7EB10; margin: 2rem 0;">

<h1 style="font-family: 'Courier New', monospace; font-size: clamp(2.5rem, 8vw, 4rem); background: linear-gradient(45deg, #C9A7EB, #A78BFA, #8B5CF6, #C9A7EB); background-size: 300% 300%; background-clip: text; -webkit-background-clip: text; -webkit-text-fill-color: transparent; margin: 0; text-align: center; animation: glitch-text 2.5s infinite, gradient-flow 3s ease infinite; position: relative; text-shadow: 0 0 30px #C9A7EB40;">
  <span class="glitch" data-text="CYBERSEC">CYBERSEC</span>
  <span style="color: #C9A7EB; font-weight: bold; text-shadow: 0 0 20px #C9A7EB;">STUDENT</span>
</h1>

<p style="color: #C9A7EB; font-family: 'Courier New', monospace; font-size: 1.2rem; margin: 1rem 0 0 0; text-shadow: 0 0 15px #C9A7EB30; animation: pulse 2s infinite;">Red 🟥 Team | Blue 🔵 Team | LGPD/GRC Specialist</p>

</div>

<style>
@keyframes glitch-text {
  0%, 100% { transform: translate(0); }
  10% { transform: translate(-2px, 2px); }
  20% { transform: translate(2px, -2px); }
  30% { transform: translate(-2px, -1px); }
  40% { transform: translate(2px, 2px); }
  50% { transform: translate(-1px, -2px); }
  60% { transform: translate(1px, 1px); }
  70% { transform: translate(-2px, 2px); }
}

@keyframes gradient-flow {
  0% { background-position: 0% 50%; }
  50% { background-position: 100% 50%; }
  100% { background-position: 0% 50%; }
}

@keyframes pulse {
  0%, 100% { opacity: 1; }
  50% { opacity: 0.7; }
}

.glitch::before, .glitch::after {
  content: attr(data-text);
  position: absolute;
  top: 0; left: 0; width: 100%; height: 100%;
}

.glitch::before {
  animation: glitch-top 1s infinite;
  color: #A78BFA;
  z-index: -1;
  clip-path: polygon(0 0, 100% 0, 100% 33%, 0 33%);
}

.glitch::after {
  animation: glitch-bottom 1.5s infinite;
  color: #8B5CF6;
  z-index: -2;
  clip-path: polygon(0 67%, 100% 67%, 100% 100%, 0 100%);
}

@keyframes glitch-top {
  0%, 100% { transform: translate(0); }
  10% { transform: translate(-2px, -2px); }
  20% { transform: translate(2px, 2px); }
  30% { transform: translate(-1px, -1px); }
}

@keyframes glitch-bottom {
  0%, 100% { transform: translate(0); }
  15% { transform: translate(2px, 2px); }
  30% { transform: translate(-2px, -2px); }
  45% { transform: translate(1px, 1px); }
}
</style>

</div>
