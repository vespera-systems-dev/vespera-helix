# Vespera Helix v2.2

🧬 Biological Archival Encoding System

Vespera Helix is an experimental browser-based DNA transcoder designed to convert plaintext data into biologically inspired nucleotide sequences using reversible binary-to-base encoding logic.

This project explores the intersection of:

* digital archival systems
* synthetic DNA storage theory
* molecular information encoding
* continuity-focused data preservation

The application functions entirely client-side in HTML, CSS, and JavaScript with no external dependencies.

---

## Features

* UTF-8 plaintext encoding
* Reversible DNA transcoding
* RAW DNA export mode
* ARCHIVE packet mode
* FASTA genomic export mode
* Checksum generation
* GC balance statistics
* Downloadable `.dna` archives
* Standard `.txt` export support
* Built-in help system
* Cyberpunk biotech terminal interface

---

## Encoding Logic

Vespera Helix uses a deterministic binary mapping system:

```text
00 → A
01 → C
10 → G
11 → T
```

Example:

```text
H
↓
01001000
↓
01 00 10 00
↓
C A G A
```

This allows plaintext data to be converted into reversible DNA-style nucleotide sequences.

---

## Export Modes

### RAW MODE

Outputs pure reversible DNA sequence data.

Example:

```text
CTCACGGACGGCCTATAGAAC...
```

Best used for:

* reversible decoding
* archival payloads
* direct sequence storage

---

### ARCHIVE MODE

Wraps DNA payloads in metadata containers including:

* timestamps
* checksums
* archive headers

Example:

```text
VSX1-HEADER
TIMESTAMP:2066-05-10
CHECKSUM:A82D4C
PAYLOAD:
CTCACGGAC...
END-ARCHIVE
```

Best used for:

* cinematic archival packaging
* continuity simulations
* experimental storage workflows

---

### FASTA EXPORT

Outputs data in FASTA genomic format:

```text
>VESPERA_ARCHIVE_174692
CTCACGGACGGCCTATAGAAC...
```

Compatible with:

* genomic sequence viewers
* bioinformatics tooling
* DNA sequence workflows

---

## Decoding

RAW DNA sequences decode perfectly.

To decode:

1. Paste DNA sequence into input field
2. Press `DECODE`

The system reconstructs:

```text
DNA → Binary → UTF-8 → Text
```

Note:
Archive mode currently functions primarily as a packaging layer and may require manual payload extraction for perfect reversibility.

---

## File Formats

### `.dna`

Experimental Vespera archival container format.

### `.txt`

Standard plaintext export format.

### `.fasta`

Genomic sequence export format.

---

## Scientific Context

This project is inspired by real-world DNA data storage research involving:

* molecular archival systems
* synthetic nucleotide storage
* ultra-dense cold storage concepts

Vespera Helix is not intended for biological engineering or medical use. It is an experimental archival encoding and continuity research project.

---

## Future Roadmap

Planned experimental upgrades include:

* AES encryption
* Reed-Solomon error correction
* reversible biological conditioning
* archive indexing
* DNA visualization engine
* compression pipeline
* archive certificates
* synthesis-safe sequence balancing
* drag-and-drop file encoding
* continuity archive protocol expansion

---

## License

Experimental Research Software

ENGINEERED BY VESPERA SYSTEMS

