<div style="font-family: 'Courier New', Courier, monospace; max-width: 850px; line-height: 1.6; color: #1a1a1a; border: 2px solid #000; padding: 40px; background-color: #ffffff;">

  <!-- Header Section -->
  <div style="border-bottom: 4px solid #000; padding-bottom: 15px; margin-bottom: 30px;">
    <h1 style="margin: 0; font-size: 1.6rem; letter-spacing: -0.01em; text-transform: uppercase;">IO Spec: Sovereign-Link Tape-Out</h1>
    <p style="margin: 5px 0 0 0; color: #d9411e; font-weight: bold; letter-spacing: 0.05em;">IMPEDANCE-MATCHING PROTOCOL | PROVISION1 LABORATORY</p>
  </div>

  <p style="font-size: 0.95rem; margin-bottom: 25px;">
    The Sovereign-Link is a precision-attenuated output designed to drive the mic/line inputs of micro-cassette and portable reel-to-reel recorders without saturating their input transformers prematurely.
  </p>

  <!-- Technical Specs -->
  <div style="margin-bottom: 30px;">
    <h3 style="background: #000; color: #fff; padding: 8px 12px; font-size: 0.95rem; display: inline-block; text-transform: uppercase;">1. Electrical Characteristics</h3>
    <ul style="padding-left: 20px; list-style-type: square; margin-top: 10px; font-size: 0.9rem;">
      <li style="margin-bottom: 10px;"><strong>Output Impedance:</strong> 600&Omega; (Transformer Balanced Simulation) — Ensures compatibility with vintage "Low-Z" tape inputs.</li>
      <li style="margin-bottom: 10px;"><strong>Signal Level:</strong> -10dBV (Consumer Line) with a -20dB pad toggle for Mic-Level inputs.</li>
      <li style="margin-bottom: 10px;"><strong>Connector:</strong> 1/8" (3.5mm) TRS Nickel-Plated Jack for maximum oxidation resistance.</li>
      <li><strong>Isolation:</strong> DC-blocking via high-grade 10uF Polypropylene capacitors to prevent rail leakage into the recorder.</li>
    </ul>
  </div>

  <!-- The Matching Network -->
  <div style="margin-bottom: 30px;">
    <h3 style="background: #000; color: #fff; padding: 8px 12px; font-size: 0.95rem; display: inline-block; text-transform: uppercase;">2. The Matching Network (Passive)</h3>
    <p style="font-size: 0.9rem; margin-top: 10px;">To preserve the forensic "Bloom," the output uses a discrete resistor ladder rather than an op-amp buffer.</p>
    <table style="width: 100%; border-collapse: collapse; font-size: 0.85rem; border: 1px solid #000; margin-top: 10px;">
      <tr style="background: #f0f0f0;">
        <th style="padding: 10px; border: 1px solid #000;">Component</th>
        <th style="padding: 10px; border: 1px solid #000;">Value</th>
        <th style="padding: 10px; border: 1px solid #000;">Role</th>
      </tr>
      <tr>
        <td style="padding: 10px; border: 1px solid #000;">R_Series</td>
        <td style="padding: 10px; border: 1px solid #000;">4.7k&Omega;</td>
        <td style="padding: 10px; border: 1px solid #000;">Voltage Drop from 36V Rails.</td>
      </tr>
      <tr>
        <td style="padding: 10px; border: 1px solid #000;">R_Shunt</td>
        <td style="padding: 10px; border: 1px solid #000;">680&Omega;</td>
        <td style="padding: 10px; border: 1px solid #000;">Output Impedance Setting.</td>
      </tr>
    </table>
  </div>

  <!-- Operational Protocol -->
  <div style="background: #f0f0f0; border-left: 5px solid #000; padding: 20px; margin-top: 30px;">
    <h4 style="margin: 0 0 10px 0; text-transform: uppercase; font-size: 0.9rem;">The "Artifact" Calibration</h4>
    <p style="margin: 0; font-size: 0.9rem;">
      When connecting to a micro-cassette recorder, set the Field Operator gain until the analog VU meters peak at +3dB. The Sovereign-Link network will ensure the tape receives exactly enough energy to engage magnetic hysteresis without "smeared" distortion.
    </p>
  </div>

  <p style="margin-top: 40px; font-size: 0.8rem; color: #888; text-align: center; font-style: italic;">
    Physical signal integrity is the primary witness.
  </p>
</div>
