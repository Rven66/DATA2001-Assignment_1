# DATA2001-Assignment_1

# API Task 2
Link to the API website: https://datasets.seed.nsw.gov.au/dataset/nsw-points-of-interest-poi

# Google drive - Doc for report link
https://docs.google.com/document/d/1n2X06f8SsJrVs9xzTqE0d5J3EYx_cJwz28PFvmnBcf0/edit?usp=sharing

# TEMP SETUP HELP

## Full setup:

```text
1. Clone repo
2. Run:
   conda env create -f environment.yml
   conda activate ds
   jupyter lab
3. In Jupyter, select kernel: Python (ds)
```

# Every time you work on the file (after completing SETUP below)

In terminal in the assignment directory:

```bash
conda activate ds
jupyter lab
```


## Steps:


### 1) Pull the repo

```bash
git clone <repo-url>
cd <repo-folder>
```

---

### 2) Create the environment (first time only)

```bash
conda env create -f environment.yml
```

---

### 3) Activate it

```bash
conda activate ds
```

---

### 4) Start Jupyter

```bash
jupyter lab
```

(or `jupyter notebook`)

---

### 5) Select the kernel (important)

Inside Jupyter:

* Kernel → Change Kernel → **Python (ds)**

---

# Important nuance (this is where people mess up)

They should:

> **create + activate the environment BEFORE launching Jupyter**

Not after.

---

# One-time vs repeated steps

### Only once:

```bash
conda env create -f environment.yml
```

### Every time they work:

```bash
conda activate ds
jupyter lab
```

---


* no need for separate terminal
* ensure env is activated before launching Jupyter
* make sure they select the correct kernel

