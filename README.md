# P300 Oddball Dataset Analysis

## Setup

### 1. Clone repo

```bash
git clone https://github.com/samuellee77/p300-oddball
cd p300-oddball
```

### 2. Install uv (if needed)

```bash
curl -Ls https://astral.sh/uv/install.sh | sh
```

### 3. Create and activate environment

```bash
uv sync
source .venv/bin/activate
```

### 4. Download dataset

```bash
mkdir data
```

Manually download from: [OpenNeuro](https://openneuro.org/datasets/ds007056)

### 5. Run notebook

```bash
uv run jupyter notebook
```
