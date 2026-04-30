<div style="font-family: 'Courier New', Courier, monospace; max-width: 850px; line-height: 1.6; color: #1a1a1a; border: 2px solid #000; padding: 40px; background-color: #ffffff;">

  <!-- Header Section -->
  <div style="border-bottom: 4px solid #000; padding-bottom: 15px; margin-bottom: 30px;">
    <h1 style="margin: 0; font-size: 1.6rem; letter-spacing: -0.01em; text-transform: uppercase;">SCHEMATIC BRIEF: SOVEREIGN KERNEL</h1>
    <p style="margin: 5px 0 0 0; color: #d9411e; font-weight: bold; letter-spacing: 0.05em;">36V RAIL TOPOLOGY & JFET INPUT STAGE</p>
  </div>

  <!-- Stage 1: The Input Authority -->
  <div style="margin-bottom: 30px;">
    <h3 style="background: #000; color: #fff; padding: 8px 12px; font-size: 0.95rem; display: inline-block; text-transform: uppercase;">1. 10M&Omega; JFET Witness Stage</h3>
    <p style="font-size: 0.95rem; margin-top: 10px;">
      The front-end utilizes a discrete, hand-matched 2SK170 (or equivalent low-noise JFET) in a source-follower configuration. 
    </p>
    <ul style="padding-left: 20px; list-style-type: square; font-size: 0.9rem;">
      <li style="margin-bottom: 8px;"><strong>Impedance:</strong> Fixed 10M&Omega; load to prevent transducer "choking".</li>
      <li style="margin-bottom: 8px;"><strong>Biasing:</strong> Constant-current source (CCS) loaded to ensure strictly linear operation across the 36V swing.</li>
      <li><strong>Forensic Benefit:</strong> Preserves the high-frequency "air" and micro-dynamic transients that 1k&Omega; "slob-standard" pre-amps flatten.</li>
    </ul>
  </div>

  <!-- Stage 2: The Rail Architecture -->
  <div style="margin-bottom: 30px;">
    <h3 style="background: #000; color: #fff; padding: 8px 12px; font-size: 0.95rem; display: inline-block; text-transform: uppercase;">2. 36V PurePath™ Rail Topology</h3>
    <p style="font-size: 0.95rem; margin-top: 10px;">
      We reject the 5V USB-powered bottleneck. The Field Operator runs on a bipolar +/- 18V supply (36V total span).
    </p>
    <ul style="padding-left: 20px; list-style-type: square; font-size: 0.9rem;">
      <li style="margin-bottom: 8px;"><strong>Headroom:</strong> +24dBu clipping point. Transients from industrial environments or close-mic percussion remain uncompressed.</li>
      <li style="margin-bottom: 8px;"><strong>Slew Rate:</strong> High-voltage rails allow for >20V/&mu;s slew rates, essential for capturing "Mechanical Necessity".</li>
      <li><strong>Filtering:</strong> Multi-stage LC (Inductor-Capacitor) decoupling for each rail to eliminate switching noise from the 32-bit SD Witness.</li>
    </ul>
  </div>

  <!-- Component Note -->
  <div style="background: #f0f0f0; border: 1px solid #000; padding: 20px; margin-top: 30px;">
    <h4 style="margin: 0 0 10px 0; text-transform: uppercase; font-size: 0.9rem;">Mechanical Requirement: The "Iron" Tap</h4>
    <p style="margin: 0; font-size: 0.9rem;">
      The 36V rail is tapped directly by the 4038_R Gyrator circuit to simulate magnetic hysteresis. Without this voltage potential, the "British Density" profile lacks the physical inertia required for forensic authority.
    </p>
  </div>

</div>
