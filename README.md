# splitnstitch

A powerful CLI tool for splitting and merging table files. Perfect for creating safe-to-share datasets, managing sensitive data, and reorganizing table structures.

## Features

✨ **Split Tables** - Separate sensitive columns from public data  
🔄 **Stitch Tables** - Merge split files back together seamlessly  
📊 **Melt Columns** - Reshape wide data into long format  
🛡️ **Safe Export** - Create redacted versions of datasets  
🧩 **Detail Joins** - Enrich datasets with additional information  
📁 **Multiple Formats** - Works with CSV and Excel files  
💬 **Interactive CLI** - User-friendly command-line interface with guided workflows
🪟 **Windows Support** - Can be used on Windows machines as well as Linux

## Installation

```bash
pip install splitnstitch
```

Or install from source:

```bash
git clone https://github.com/espehon/splitnstitch.git
cd splitnstitch
pip install -e .
```

## Quick Start

Launch the interactive CLI:

```bash
sns
```

Or run with Python:

```bash
python -m splitnstitch
```

The tool will guide you through a series of prompts to:
1. Choose your operation (split, stitch, melt)
2. Select your data file (CSV or Excel)
3. Configure your preferences
4. Generate your output file(s)

## Use Cases

### 🔐 Privacy Protection
Split sensitive customer data into separate files to share only non-sensitive columns with partners while keeping PII secure.

### 📦 Data Organization
Reorganize wide datasets into long format for easier analysis and database import.

### 🔀 Selective Sharing
Share safe columns publicly while maintaining a master file with complete data internally.

### 🧬 Data Enrichment
Stitch together detail data from multiple sources to create a comprehensive dataset.

## Requirements

- Python 3.8+
- pandas
- questionary
- halo

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Author

Created by espehon
