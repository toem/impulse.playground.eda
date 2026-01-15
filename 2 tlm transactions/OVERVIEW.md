# TLM Transaction Data Files Overview

This overview lists transaction data files from SystemC TLM simulations. The files include various formats:
- **recMz**: Compressed binary transaction files.
- **txlog**: Transaction log files.
- **scv**: SystemC Verification transaction files.
- **ftr**: Transaction trace files.

**Column explanations:**
- **Target File**: Name of the data file.
- **File Size**: Actual file size on disk.
- **Compression**: Whether the file is compressed.
- **Streams**: Number of transaction streams.
- **Transactions**: Number of transactions recorded.
- **Transaction Types**: Types of transactions (e.g., TLM, AXI, custom).

| Target File | File Size | Compression | Streams | Transactions | Transaction Types |
|----------------|-----------|-------------|---------|--------------|-------------------|
| 1_afcdemo.recMz  | 627 KB    | Yes | 4 | 147940 | TLM, axi, nb, timed |
| 2_axi4drvx.txlog | 1.7 MB    | No  | 6 | 1357 | TLM, axi, base-protocol, nb, timed |
| 3_system2.scv    | 25.6 MB   | No  | 32 | 32614 | TRANSACTOR, blocking, bl_t_ann |
| 4_xscore71.ftr   | 8.4 MB    | Yes  | 10 | 318336 | TLM, ace, axi, chi, nb, timed |

