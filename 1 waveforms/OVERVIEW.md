# Waveform Data Files Overview

This overview lists signal data files from RTL and SystemC simulations. The files include various formats:
- **VCD**: Value Change Dump - industry standard waveform format.
- **FST**: Fast Signal Trace - compressed waveform format from GTKWave.
- **FSDB**: Fast Signal Database - proprietary waveform format from Verdi.

**Column explanations:**
- **Target File**: Name of the data file.
- **File Size**: Actual file size on disk.
- **Compression**: Whether the file is compressed.
- **Scopes**: Number of hierarchical scopes in the simulation.
- **Signals**: Number of signals recorded.
- **Signal Types**: Types of signals (e.g., reg, wire, integer).

| Target File | File Size | Compression | Scopes | Signals | Signal Types |
|----------------|-----------|-------------|--------|---------|--------------|
| 1_arcmodl.vcd  | 382 KB    | No  | 11 | 388 | integer, parameter, reg, tri, tri0, tri1, wand, wire |
| 2_mainft.fst   | 2.5 KB    | Yes | 10 | 33 | reg |
| 3_verilog.fsdb | 34.6 KB   | Yes | 7 | 31 | reg, wire |
| 4_xcomp.fst    | 190 KB    | Yes | 1 | 1600 | wire |

