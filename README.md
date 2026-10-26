# Stool consistency & gut microbiota – companion website and supplementary data

Companion website and supplementary data for:

> Vandeputte D, Falony G, Vieira-Silva S, Tito RY, Joossens M, Raes J. **Stool consistency is strongly associated with gut microbiota richness and composition, enterotypes and bacterial growth rates**. *Gut* 65(1):57–62 (2016). [doi:10.1136/gutjnl-2015-309618](https://doi.org/10.1136/gutjnl-2015-309618)

It contains the merged and quality-trimmed 16S rRNA gene sequencing data, QIIME OTU tables and phylogenetic trees (closed-reference and de novo OTU picking), the QIIME mapping file and the sample metadata.

**Website:** https://raeslab.github.io/Stool-Consistency-Gut-Microbiota/ (GitHub Pages, served from `docs/` on the `main` branch)

This material was previously hosted on the Raes Lab website at `raeslab.org/companion/stool-consistency.html` and has been migrated to this repository.

## Contents

| Path | Size | Description |
|------|------|-------------|
| `supplementary/Gut_Vandeputte_etal_16S_data.tar.gz` | 82.6 MB | Merged and quality trimmed 16S sequencing data |
| `supplementary/Gut_Vandeputte_etal_QIIME_close_ref_otutable.biom.zip` | 322 KB | Qiime OTU-table closed reference OTU picking |
| `supplementary/Gut_Vandeputte_etal_QIIME_close_ref_phylogenetictree.tree.zip` | 928 KB | Qiime phylogenetic tree closed reference OTU picking |
| `supplementary/Gut_Vandeputte_etal_QIIME_de_novo_otutable.biom.zip` | 469 KB | Qiime OTU-table de novo OTU picking |
| `supplementary/Gut_Vandeputte_etal_QIIME_de_novo_phylogenetictree.tree.zip` | 555 KB | Qiime phylogenetic tree de novo OTU picking |
| `supplementary/Gut_Vandeputte_etal_QIIME_mappingfile.txt` | 2 KB | Qiime mapping file |
| `supplementary/Gut_Vandeputte_etal_metadata.xlsx` | 41 KB | Metadata |
| `supplementary/stool_consistency.zip` | 2.3 MB | Archive with all supplementary files |

Total supplementary data: 87.2 MB.

## Repository layout

```
docs/                 Static, self-contained website (GitHub Pages source; no external CSS/JS/fonts)
  index.html
  assets/             Stylesheet, script, logo, figure previews
supplementary/        Downloadable data files (Git LFS)
.gitattributes        Git LFS tracking rules
```

### Git LFS

All files in `supplementary/` are tracked with [Git LFS](https://git-lfs.com). Install it before cloning
(`git lfs install`), or download individual files from the website. Because GitHub Pages does not serve LFS
objects, the website's download buttons point to `https://github.com/raeslab/Stool-Consistency-Gut-Microbiota/raw/main/supplementary/...`;
when `docs/index.html` is opened from a local checkout the links switch to the relative `../supplementary/` paths.

### Publishing

In the repository settings, enable GitHub Pages with source *Deploy from a branch* → `main` / `/docs`.

## How to cite

If you use these data, please cite:

> Vandeputte D, Falony G, Vieira-Silva S, Tito RY, Joossens M, Raes J. **Stool consistency is strongly associated with gut microbiota richness and composition, enterotypes and bacterial growth rates**. *Gut* 65(1):57–62 (2016). [doi:10.1136/gutjnl-2015-309618](https://doi.org/10.1136/gutjnl-2015-309618)

```bibtex
@article{vandeputte2016stool,
  title   = {{Stool consistency is strongly associated with gut microbiota richness and composition, enterotypes and bacterial growth rates}},
  author  = {Vandeputte, D. and Falony, G. and Vieira-Silva, S. and Tito, R. Y. and Joossens, M. and Raes, J.},
  journal = {Gut},
  year    = {2016},
  volume  = {65},
  number  = {1},
  pages   = {57--62},
  doi     = {10.1136/gutjnl-2015-309618}
}
```

## Contact

Raes Lab, VIB–KU Leuven Center for Microbiology – Prof. Jeroen Raes (jeroen.raes@kuleuven.be).
