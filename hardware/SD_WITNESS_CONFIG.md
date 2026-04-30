<div style="font-family: 'Courier New', Courier, monospace; max-width: 850px; line-height: 1.6; color: #1a1a1a; border: 2px solid #000; padding: 40px; background-color: #ffffff;">

  <!-- Header Section -->
  <div style="border-bottom: 4px solid #000; padding-bottom: 15px; margin-bottom: 30px;">
    <h1 style="margin: 0; font-size: 1.6rem; letter-spacing: -0.01em; text-transform: uppercase;">Config: SD Witness Node</h1>
    <p style="margin: 5px 0 0 0; color: #d9411e; font-weight: bold; letter-spacing: 0.05em;">FORENSIC DIGITAL BACKUP | PROVISION1 LABORATORY</p>
  </div>

  <p style="font-size: 0.95rem; margin-bottom: 25px;">
    While the Tape-Out serves as the Incarnation, the SD Witness serves as the Audit. This configuration ensures that every micro-dynamic nuance captured by the 36V rails is vitrified in the digital domain without the risk of clipping or quantization error.
  </p>

  <!-- Technical Parameters -->
  <div style="margin-bottom: 30px;">
    <h3 style="background: #000; color: #fff; padding: 8px 12px; font-size: 0.95rem; display: inline-block; text-transform: uppercase;">1. Audio Engine Parameters</h3>
    <ul style="padding-left: 20px; list-style-type: square; margin-top: 10px; font-size: 0.9rem;">
      <li style="margin-bottom: 10px;"><strong>Sample Rate:</strong> 96.0 kHz — Sufficient for capturing the high-frequency "Bloom" of the U47_T profile.</li>
      <li style="margin-bottom: 10px;"><strong>Bit Depth:</strong> 32-bit Float — Eliminates the need for a digital limiter; captures the full +24dBu hardware headroom.</li>
      <li style="margin-bottom: 10px;"><strong>File Format:</strong> BWF (Broadcast Wave Format) with embedded metadata.</li>
      <li><strong>Clocking:</strong> Low-jitter TCXO (Temperature Compensated Crystal Oscillator) to prevent temporal smear.</li>
    </ul>
  </div>

  <!-- Write Protocol -->
  <div style="margin-bottom: 30px;">
    <h3 style="background: #000; color: #fff; padding: 8px 12px; font-size: 0.95rem; display: inline-block; text-transform: uppercase;">2. SD Write Integrity</h3>
    <table style="width: 100%; border-collapse: collapse; font-size: 0.85rem; border: 1px solid #000; margin-top: 10px;">
      <tr style="background: #f0f0f0;">
        <th style="padding: 10px; border: 1px solid #000;">Feature</th>
        <th style="padding: 10px; border: 1px solid #000;">Specification</th>
        <th style="padding: 10px; border: 1px solid #000;">Audit Role</th>
      </tr>
      <tr>
        <td style="padding: 10px; border: 1px solid #000;"><strong>Dual-Write</strong></td>
        <td style="padding: 10px; border: 1px solid #000;">Enabled</td>
        <td style="padding: 10px; border: 1px solid #000;">Prevents file loss during power transients.</td>
      </tr>
      <tr>
        <td style="padding: 10px; border: 1px solid #000;"><strong>Pre-Record</strong></td>
        <td style="padding: 10px; border: 1px solid #000;">6 Seconds</td>
        <td style="padding: 10px; border: 1px solid #000;">Ensures the first transient is never missed.</td>
      </tr>
      <tr>
        <td style="padding: 10px; border: 1px solid #000;"><strong>File Naming</strong></td>
        <td style="padding: 10px; border: 1px solid #000;">ISO 8601 UTC</td>
        <td style="padding: 10px; border: 1px solid #000;">Forensic timestamping for legal solvency.</td>
      </tr>
    </table>
  </div>

  <!-- Hardware Interface Note -->
  <div style="background: #f0f0f0; border-left: 5px solid #000; padding: 20px; margin-top: 30px;">
    <h4 style="margin: 0 0 10px 0; text-transform: uppercase; font-size: 0.9rem;">Mechanical Redundancy</h4>
    <p style="margin: 0; font-size: 0.9rem;">
      The SD Witness is a safety net, not the destination. The SD card must be housed behind the gasket-sealed brass cover to emphasize its secondary, "black box" nature in the Sovereign workflow.
    </p>
  </div>

  <p style="margin-top: 40px; font-size: 0.8rem; color: #888; text-align: center; font-style: italic;">
    Record with the Witness, archive with the Artifact.
  </p>
</div>
