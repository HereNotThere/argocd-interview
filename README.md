### ArgoCD

ArgoCD is a declarative, GitOps continuous delivery tool for Kubernetes. 

#### Requirements

- Python 3.10+
- pip
- yarn

#### Usage

```
# create a virtual environment to render templates
python -m venv .venv
source .venv/bin/activate

# install dependencies
pip install -r requirements.txt

make render_values ENV=gamma
```

See `notes` and [GCP Migration ArgoCD](https://www.notion.so/herenottherelabs/GCP-Migration-ArgoCD-1ac3562b1f4e80bba28df6bf2a95e3d4) for more information.
