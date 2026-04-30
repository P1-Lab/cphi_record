<div style="font-family: 'Courier New', Courier, monospace; max-width: 850px; line-height: 1.6; color: #1a1a1a; border: 2px solid #000; padding: 40px; background-color: #ffffff;">

  <!-- Header Section -->
  <div style="border-bottom: 4px solid #000; padding-bottom: 15px; margin-bottom: 30px;">
    <h1 style="margin: 0; font-size: 1.6rem; letter-spacing: -0.01em; text-transform: uppercase;">Calibration Guide: Forensic Alignment</h1>
    <p style="margin: 5px 0 0 0; color: #d9411e; font-weight: bold; letter-spacing: 0.05em;">BLOOM & BIAS VERIFICATION | PROVISION1 LABORATORY</p>
  </div>

  <p style="font-size: 0.95rem; margin-bottom: 25px;">
    This protocol ensures the Sovereign Field Operator is tuned to the "Architecture of Necessity." Before sealing the Zinc chassis, the operator must verify that the physical components are responding according to the deterministic physics of the VGL-1 Kernels.
  </p>

  <!-- Step 1: JFET Bias Alignment -->
  <div style="margin-bottom: 30px;">
    <h3 style="background: #000; color: #fff; padding: 8px 12px; font-size: 0.95rem; display: inline-block; text-transform: uppercase;">1. Asymmetric JFET Bias Verification</h3>
    <p style="font-size: 0.9rem; margin-top: 10px;">To manifest the U47_T profile, the JFET must be biased into a specific non-linear "sweet spot".</p>
    <ul style="padding-left: 20px; list-style-type: square; font-size: 0.9rem;">
      <li style="margin-bottom: 10px;"><strong>Test Point (TP1):</strong> Source of Q1 Witness JFET.</li>
      <li style="margin-bottom: 10px;"><strong>Target Voltage:</strong> -1.2V DC relative to the Copper Bus Bar.</li>
      <li style="margin-bottom: 10px;"><strong>Adjustment:</strong> Trim the CCS (Constant Current Source) until the bias is vitrified.</li>
      <li><strong>Audit:</strong> Use an oscilloscope to verify that a 1kHz sine wave exhibits a subtle asymmetric rounding on the positive peak.</li>
    </ul>
  </div>

  <!-- Step 2: 48Hz Bloom Verification -->
  <div style="margin-bottom: 30px;">
    <h3 style="background: #000; color: #fff; padding: 8px 12px; font-size: 0.95rem; display: inline-block; text-transform: uppercase;">2. 48Hz Bloom (Sub-Fundamental Recovery)</h3>
    <p style="font-size: 0.9rem; margin-top: 10px;">The "Bloom" is the physical resonance of the Baltic Birch wings interacting with the 36V input stage.</p>
    <table style="width: 100%; border-collapse: collapse; font-size: 0.85rem; border: 1px solid #000; margin-top: 10px;">
      <tr style="background: #f0f0f0;">
        <th style="padding: 10px; border: 1px solid #000;">Frequency</th>
        <th style="padding: 10px; border: 1px solid #000;">Target Response</th>
        <th style="padding: 10px; border: 1px solid #000;">Verification Method</th>
      </tr>
      <tr>
        <td style="padding: 10px; border: 1px solid #000;"><strong>48 Hz</strong></td>
        <td style="padding: 10px; border: 1px solid #000;">+1.5dB Shelf</td>
        <td style="padding: 10px; border: 1px solid #000;">FFT Analysis of the Witness SD stream.</td>
      </tr>
      <tr>
        <td style="padding: 10px; border: 1px solid #000;"><strong>15.6 kHz</strong></td>
        <td style="padding: 10px; border: 1px solid #000;">-3dB Point</td>
        <td style="padding: 10px; border: 1px solid #000;">Verify U47_T Sallen-Key Matrix values.</td>
      </tr>
    </table>
  </div>

  <!-- Final Haptic Audit -->
  <div style="background: #f0f0f0; border-left: 5px solid #000; padding: 20px; margin-top: 30px;">
    <h4 style="margin: 0 0 10px 0; text-transform: uppercase; font-size: 0.9rem;">The Mechanical Seal Audit</h4>
    <p style="margin: 0; font-size: 0.9rem;">
      Apply 36V power and engage the 4038_R profile. Ensure the Iron-Core inductor does not exhibit mechanical hum. If a hum is detected, the Zinc core is not properly tensioned to the Baltic Birch wings; re-apply the Tension-Bolting protocol until the unit is silent.
    </p>
  </div>

  <p style="margin-top: 40px; font-size: 0.8rem; color: #888; text-align: center; font-style: italic;">
    Alignment complete when the Witness matches the Artifact.
  </p>
</div>
