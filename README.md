# Taller de Procesamiento de Señales (TA136), Introducción a la Inteligencia Artificial (TB056), Análisis de Datos (TB057), Teoría de Detección y Estimación (8625)

How to run it with vscode:

1. Create new scope
```bash 
python3.9 -m venv venv-taller
```

2. Activate virtual scope:
    on linux/Mac:
    ```bash 
    source venv-taller/bin/activate
    ```

    on Windows (cmd):

    ```bash 
    venv-taller\Scripts\activate
    ```

3. Install dependencies:

```bash 
pip install ipykernel notebook matplotlib pandas scikit-learn seaborn
```

4. Add scope as kernel for Jupyter

```bash 
python -m ipykernel install --user --name taller2025 --display-name "Python (Taller 2025)"
```