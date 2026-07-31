# Running COMET

## Install

```bash
python -m venv venv
source venv/bin/activate

pip install unbabel-comet
```

## Prepare Data

Create a JSON file:

```json
[
  {
    "src": "...",
    "mt": "...",
    "ref": "..."
  }
]
```

## Run COMET

```bash
comet-score -d input.json --model Unbabel/wmt22-comet-da
```
