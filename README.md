# Chest-Disease-Classification-from-Chest-CT-Scan-Image

 - [Data link](https://drive.google.com/file/d/1z0mreUtRmR-P-magILsDR3T7M6IkGXtY/view?usp=sharing)

## Workflows

1. Update config.yaml
2. Update params.yaml
3. Update the entity
4. Update the configuration manager in src config
5. Update the components
6. Update the pipeline 
7. Update the main.py



## Git commands

```bash
git add .

git commit -m "Updated"

git push origin main
```

## How to run?

```bash
conda create -n chest python=3.8 -y
```

```bash
conda activate chest
```

```bash
pip install -r requirements.txt
```

```bash
python app.py
```

### Mlflow dagshub connection uri

```bash
MLFLOW_TRACKING_URI=https://dagshub.com/ayush82/Chest-Disease-Classification-from-Chest-CT-Scan-Image \
MLFLOW_TRACKING_USERNAME=ayush82 \
MLFLOW_TRACKING_PASSWORD=0f6101a9fe25bfa245a91706a8c5484dee7b90b0 \
python script.py
```


### RUN from bash terminal

```bash
export MLFLOW_TRACKING_URI=https://dagshub.com/ayush82/Chest-Disease-Classification-from-Chest-CT-Scan-Image

export MLFLOW_TRACKING_USERNAME=ayush82 

export MLFLOW_TRACKING_PASSWORD=0f6101a9fe25bfa245a91706a8c5484dee7b90b0

```

