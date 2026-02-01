# DisTrO

[![GitHub stars](https://img.shields.io/github/stars/NousResearch/DisTrO?style=social)](https://github.com/NousResearch/DisTrO/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/NousResearch/DisTrO?style=social)](https://github.com/NousResearch/DisTrO/network/members)

**DisTrO (Distributed Training Over-The-Internet)** is a family of low-latency distributed optimizers that reduce inter-GPU communication requirements by **three to four orders of magnitude**.

## 🚀 Quick Start

### Prerequisites

- Python 3.8+
- PyTorch 2.0+
- CUDA-compatible GPU(s)

### Installation

```bash
# Clone the repository
git clone https://github.com/NousResearch/DisTrO.git
cd DisTrO

# Install dependencies (if applicable)
pip install torch torchvision
```

### Usage

For implementation details and integration with your training pipeline, refer to:
- [DeMo Optimization Code](https://github.com/bloc97/DeMo) - Original seed research implementation
- [Production Code (Rust)](https://github.com/PsycheFoundation/psyche/blob/b13ff76f879796a071850bae2d82084f360d608d/shared/modeling/src/distro.rs) - Production-ready implementation

## 📚 Research & Publications

| Date | Release | Links |
|------|---------|-------|
| Aug. 26, 2024 | DisTrO Preliminary Report | [📄 PDF](https://github.com/NousResearch/DisTrO/raw/main/A_Preliminary_Report_on_DisTrO.pdf) |
| Dec. 2, 2024 | DeMo Optimization | [📄 Paper](https://arxiv.org/abs/2411.19870) • [💻 Code](https://github.com/bloc97/DeMo) |
| Dec. 2, 2024 | Nous 15B Model Training | [🌐 Website](https://distro.nousresearch.com/) |
| May 14, 2025 | Psyche Network | [📢 Announcement](https://nousresearch.com/nous-psyche/) |
| May 14, 2025 | Nous Consilience 40B LLM | [🔗 Run](https://psyche.network/runs/consilience-40b-1/0) • [🤗 HuggingFace](https://huggingface.co/PsycheFoundation/consilience-40b-7Y9v38s5) |
| Oct. 14, 2025 | DeMo Optimization v2 | [📄 Paper](https://openreview.net/pdf?id=U9oewpa7cn) • [💻 Production Code](https://github.com/PsycheFoundation/psyche/blob/b13ff76f879796a071850bae2d82084f360d608d/shared/modeling/src/distro.rs) |

## 🤝 Community

Interested in helping research and build the future of distributed training?

[![Discord](https://img.shields.io/badge/Discord-Join%20Us-7289da?logo=discord&logoColor=white)](https://discord.com/invite/jqVphNsB4H)

## 📖 About

DisTrO enables efficient distributed training across the internet by dramatically reducing the bandwidth requirements for gradient synchronization. This makes it possible to train large models across geographically distributed hardware without the need for expensive high-bandwidth interconnects.

### Key Features

- **Low Latency**: Optimized for training over standard internet connections
- **Massive Bandwidth Reduction**: 1000-10000x reduction in inter-GPU communication
- **Scalable**: Designed for large-scale distributed training across diverse hardware
