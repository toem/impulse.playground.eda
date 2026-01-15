# Pinlevel Transaction Data Files Overview

This overview lists pin-level waveform files containing transaction information from SystemC TLM simulations. The files include various formats:
- **recMz**: Compressed binary record files.
- **recMl**: XML record files.
- **recJx**: Expression based record files.
- **fst**: Fast Signal Trace files.
- **vcd**: Value Change Dump files.

**Column explanations:**
- **Target File**: Name of the data file.
- **File Size**: Actual file size on disk.
- **Compression**: Whether the file is compressed.
- **Signals**: Number of signals in the waveform.
- **Protocols**: Communication protocols used (e.g., ACE, AXI, CHI).

| Target File | File Size | Compression | Signals | Protocols |
|----------------|-----------|-------------|---------|-----------|
| 1_axiacecomp.fst | 6.6 KB    | Yes | 128 | ACE, AXI protocol |
| 2_corefs12.recMl | 4.5 MB    | Yes | 404 | ACE, AXI4, CHI protocol |
| 3_chibull.vcd    | 168 KB    | No  | 84 | CHI protocol |
| 4_axi4test.recJx | 37.6 KB   | Yes | 41 | AXI4 protocol |

