## Data
```
data/
├── 5cv/
│   ├── Pan2023/              # NetMHCIIpan-4.3 5cv training data
│   ├── Mix2023/              # MixMHC2pred-2.0 5cv training data
│   ├── CAPTAn23/             # CAPTAn 5cv training data
│   ├── PM2023/               # Combined 5cv training data from NetMHCIIpan-4.3 and MixMHC2pred-2.0
│   ├── PMC2023/              # Combined 5cv training data from NetMHCIIpan-4.3, MixMHC2pred-2.0, and CAPTAn
│   └── PMC2023_redundancy/   # Combined 5cv data after filtering immunogenicity test sets (immun_test, EPI2023, MEL2025, NEO2019)
├── random/
│   ├── seq2logo.txt          # 100,000 random 15-mer peptides
│   └── seq2logo_context.txt  # 100,000 random 15-mer peptides with context
├── indep/
│   ├── SA2023.txt           # Single-allele presentation test data from CAPTAn training data (in-house)
│   ├── MA2024.txt           # Multi-allele presentation test data from two COVID cell lines
│   ├── MBL2023.txt          # Microbial ligand benchmark from CAPTAn evaluation
│   ├── EPI2023.txt          # CD4+ epitope test data from NetMHCIIpan-4.3 evaluation
│   ├── MEL2025.txt          # Single-allele CD4+ melanoma neoepitope test data
│   ├── NEO2019.txt          # Multi-allele patient-specific neoepitope test data from MixMHC2pred-1.0 evaluation (13 patients)
│   ├── NEO2019.15.txt       # NEO2019 neoepitopes split into 15-mers to handle long peptide sequences
│   └── BindCore.txt/        # Binding core test data from 194 PDB structures
├── finetune/
│   ├── immun_train.txt      # Fine-tuning immunogenicity data from the IEDB and MHCBN datasets
│   ├── immun_test.txt       # Held-out test data with experimentally validated negatives
│   └── immun_test1.txt      # Held-out test data with randomly generated negatives
└── README.md                # Data introduction

```
