## Repository Setup
1. clone the repo:
```
git clone https://github.com/kevin-eiconsulting/csv_rag.git
```
2. Go into the repo and create a new python environment ver 3.11
```
conda create -n env1 python=3.11
```
3. Go into the env1 conda env
```
conda activate env1
```
4. Install the packages from requirements.txt
```
pip install -r requirements.txt

```
5. Install these libs
```

pip install pandas sentence-transformers qdrant-client tqdm

```
6. Download and unzip file named ""
```
webpage: https://github.com/qdrant/qdrant/releases
file name: qdrant-x86_64-pc-windows-msvc.zip
```
7. go to Qdrant directory and run command in directory terminal
```
qdrant.exe
```
- Do not push to the main branch directly
