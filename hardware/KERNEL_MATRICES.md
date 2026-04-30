<div style="font-family: 'Courier New', Courier, monospace; max-width: 850px; line-height: 1.6; color: #1a1a1a; border: 2px solid #000; padding: 40px; background-color: #ffffff;">

  <!-- Header Section -->
  <div style="border-bottom: 4px solid #000; padding-bottom: 15px; margin-bottom: 30px;">
    <h1 style="margin: 0; font-size: 1.6rem; letter-spacing: -0.01em; text-transform: uppercase;">Kernel Matrices: VGL-1 Hardware</h1>
    <p style="margin: 5px 0 0 0; color: #d9411e; font-weight: bold; letter-spacing: 0.05em;">PHYSICAL COMPONENT MAPPING | PROVISION1 LABORATORY</p>
  </div>

  <p style="font-size: 1.1rem; font-weight: bold; margin-bottom: 25px;">
    These matrices define the component-level values required to manifest the "Sovereign Virtual Locker" within the analog signal path. These are not approximations; they are deterministic physics.
  </p>

  <!-- U47_T Profile -->
  <div style="margin-bottom: 30px;">
    <h3 style="background: #000; color: #fff; padding: 8px 12px; font-size: 0.95rem; display: inline-block; text-transform: uppercase;">Matrix A: U47_T (German Authority)</h3>
    <p style="font-size: 0.9rem; margin-top: 10px;">Target: 15.6kHz Sallen-Key slope with Asymmetric 2nd-Harmonic Bias.</p>
    <table style="width: 100%; border-collapse: collapse; font-size: 0.85rem; border: 1px solid #000;">
      <tr style="background: #f0f0f0;">
        <th style="padding: 8px; border: 1px solid #000;">Ref</th>
        <th style="padding: 8px; border: 1px solid #000;">Value</th>
        <th style="padding: 8px; border: 1px solid #000;">Forensic Function</th>
      </tr>
      <tr>
        <td style="padding: 8px; border: 1px solid #000;">R1, R2</td>
        <td style="padding: 8px; border: 1px solid #000;">10.2k&Omega; (0.1%)</td>
        <td style="padding: 8px; border: 1px solid #000;">Primary Filter Pole.</td>
      </tr>
      <tr>
        <td style="padding: 8px; border: 1px solid #000;">C1, C2</td>
        <td style="padding: 8px; border: 1px solid #000;">1.0nF (PP)</td>
        <td style="padding: 8px; border: 1px solid #000;">High-Frequency Bloom Control.</td>
      </tr>
      <tr>
        <td style="padding: 8px; border: 1px solid #000;">Q1 Bias</td>
        <td style="padding: 8px; border: 1px solid #000;">-1.2V DC</td>
        <td style="padding: 8px; border: 1px solid #000;">Vitrifies the 2nd-harmonic "Tube" signature.</td>
      </tr>
    </table>
  </div>

  <!-- 4038_R Profile -->
  <div style="margin-bottom: 30px;">
    <h3 style="background: #000; color: #fff; padding: 8px 12px; font-size: 0.95rem; display: inline-block; text-transform: uppercase;">Matrix B: 4038_R (British Density)</h3>
    <p style="font-size: 0.9rem; margin-top: 10px;">Target: 12.5kHz Cutoff + Inductor-based Hysteresis Simulation.</p>
    <table style="width: 100%; border-collapse: collapse; font-size: 0.85rem; border: 1px solid #000;">
      <tr style="background: #f0f0f0;">
        <th style="padding: 8px; border: 1px solid #000;">Ref</th>
        <th style="padding: 8px; border: 1px solid #000;">Value</th>
        <th style="padding: 8px; border: 1px solid #000;">Forensic Function</th>
      </tr>
      <tr>
        <td style="padding: 8px; border: 1px solid #000;">L1</td>
        <td style="padding: 8px; border: 1px solid #000;">150mH (Iron Core)</td>
        <td style="padding: 8px; border: 1px solid #000;">Simulates Ribbon Transformer inertia.</td>
      </tr>
      <tr>
        <td style="padding: 8px; border: 1px solid #000;">R4</td>
        <td style="padding: 8px; border: 1px solid #000;">470&Omega;</td>
        <td style="padding: 8px; border: 1px solid #000;">Saturation Load Management.</td>
      </tr>
      <tr>
        <td style="padding: 8px; border: 1px solid #000;">C5</td>
        <td style="padding: 8px; border: 1px solid #000;">2.2nF</td>
        <td style="padding: 8px; border: 1px solid #000;">The 12.5kHz "Roll-off" Anchor.</td>
      </tr>
    </table>
  </div>

  <!-- Component Mandate -->
  <div style="background: #f0f0f0; border: 1px solid #000; padding: 20px;">
    <h4 style="margin: 0 0 10px 0; text-transform: uppercase; font-size: 0.85rem;">The "Anti-Slob" Component Clause</h4>
    <p style="margin: 0; font-size: 0.85rem;">
      All resistors MUST be Metal Film 1% or better. All capacitors in the signal path MUST be Polypropylene or C0G/NP0 ceramic. Use of electrolytic capacitors in the audio path constitutes a failure of the Architecture of Necessity.
    </p>
  </div>

</div>
