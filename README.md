# AVL 3.52 — official source and documentation backup

This repository preserves the **AVL (Athena Vortex Lattice) 3.52** release by **Mark Drela and Harold Youngren**, downloaded from the [official MIT website](https://web.mit.edu/drela/Public/web/avl/) on **21 September 2026 (Asia/Taipei)**.

It is an independently maintained backup, not the authors' official GitHub repository. Version 3.52 was the latest source release listed on the official page at the time of download; the page records its release on 3 September 2025.

## Source and archive

- The release source tree is available directly in this repository, including `src/`, `bin/`, `binw32/`, `eispack/`, `plotlib/`, `misc/`, `mrf/`, and `runs/`.
- [The complete original avl3.52.tgz](upstream/avl3.52.tgz) is preserved byte-for-byte.
- [The original README](README) contains upstream build instructions.
- Source files and build settings have not been modified. Only macOS metadata files (`._*`, `.DS_Store`) and an upstream editor lock symlink are omitted from the extracted tree. All remain inside the original archive; [the import manifest](upstream/import-manifest.json) records the exact paths.
- Any executables or compiler artifacts already shipped by upstream are preserved as received and have not been executed. In particular, the bundled Windows executable is named `avl3.51-32.exe`; it is not a newly built or validated AVL 3.52 executable.

## Official documentation

Both release-bundled documents and separately published website documents are kept, without replacing one with the other:

| Document | Location |
| --- | --- |
| Release-bundled user guide | [avl_doc-AVL350-04242025.txt](avl_doc-AVL350-04242025.txt) |
| Release-bundled version notes | [version_notes.txt](version_notes.txt) |
| Website text user guide | [docs/official/avl_doc.txt](docs/official/avl_doc.txt) |
| Website PDF user primer | [docs/official/AVL_User_Primer.pdf](docs/official/AVL_User_Primer.pdf) |
| Aerodynamic analysis example session | [docs/official/session1.txt](docs/official/session1.txt) |
| Eigenmode analysis example session | [docs/official/session2.txt](docs/official/session2.txt) |
| Website version notes | [docs/official/version_notes.txt](docs/official/version_notes.txt) |
| Website sample inputs ZIP | [docs/official/runs.zip](docs/official/runs.zip) |
| Official landing-page HTML snapshot | [docs/official/official-index.html](docs/official/official-index.html) |

The website documents have their own revision histories and may describe older AVL versions. They are the official files available on the backup date, not rewritten manuals claiming to cover every 3.52 feature. The HTML file preserves the page content, not a complete offline website with all linked assets.

## Provenance and scope

Original download URLs, download timestamps where recorded, byte counts, and SHA-256 checksums are in [upstream/sources.json](upstream/sources.json) and [upstream/SHA256SUMS](upstream/SHA256SUMS).

This import is limited to source and documentation preservation. **No compilation, installation, solver run, or numerical validation was performed.**

## License and attribution

AVL is copyright Mark Drela and Harold Youngren and is distributed under the GNU General Public License. Preserve all original copyright and license notices. [LICENSE](LICENSE) is the GPL text linked by the official AVL page; individual source-file notices specify the applicable version, including GPL version 2 or later for the AVL source. Bundled components retain their own notices.
