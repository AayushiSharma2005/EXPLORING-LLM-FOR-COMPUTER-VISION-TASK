# 📚 CLIP Domain Generalization – Experiments and Scripts

This repo contains a set of Jupyter Notebooks and their Python script versions related to domain generalization using CLIP models (ViT-B/16, RN50). The main goal is to explore performance on PACS dataset domains like Art, Cartoon, and more.

You’ll find both `.ipynb` and `.py` versions of each file to suit your workflow — whether you prefer notebooks or running scripts in terminal.

---

## 📝 Notebooks and Matching Scripts

| Notebook | Description |
|----------|-------------|
| `clip-domain-generalization.ipynb`  
→ `clip-domain-generalization.py` | Core setup and experiments for CLIP generalization across domains |

| `clip-vit-b-16-art-painting-domain-classification.ipynb`  
→ `clip-vit-b-16-art-painting-domain-classification.py` | Domain classification using ViT-B/16 on Art Painting |

| `domain-gen-soft-prompt-generation.ipynb`  
→ `domain-gen-soft-prompt-generation.py` | Generates soft prompts for domain adaptation |

| `domain-specific-classification-using-clip-vit-b-16.ipynb`  
→ `domain-specific-classification-using-clip-vit-b-16.py` | Classification in specific domains using ViT-B/16 |

| `pacs-artpaintingtest-clip-vit-b16-rn50.ipynb`  
→ `pacs-artpaintingtest-clip-vit-b16-rn50.py` | Testing Art Painting domain using ViT-B/16 and RN50 |

| `pacs-cartoontest-clip-vit-b16-rn50.ipynb`  
→ `pacs-cartoontest-clip-vit-b16-rn50.py` | Testing Cartoon domain using ViT-B/16 and RN50 |

---


## 💡 How to Use

- Run `.ipynb` files in Jupyter, Colab, or Kaggle for interactive use.
- Use `.py` files to run the same experiments via terminal or shell (ideal for automation).

---

## 🎯 Goal of This Project

To explore how domain-specific tweaks (like prompt tuning or combined models) can improve generalization of CLIP models across different image domains in PACS.

