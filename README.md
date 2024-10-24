# Treinamento de Machine Learning por Imagem

Neste projeto é realizado o treinamento através do Teacheble Machine, onde utilizo imagens de controle remoto na vertizale e horizontal para indentificar a posição. A plataforma [Teachable Machine](https://teachablemachine.withgoogle.com/) foi utilizada para o treinamento do presente modelo, disponizando os arquivos: `model.tflite` e `labels.txt`.

## Estrutura do Projeto

- `main.py`: Script principal para treinamento e avaliação do modelo.
- `model.tflite`: Modelo treinado em formato TensorFlow Lite.
- `labels.txt`: Arquivo contendo os rótulos das classes.

## Requisitos

- Python 3.x
- TensorFlow
- NumPy
- IDE de sua preferência(foi utilizado o Visual Studio Code para realização do projeto.)
- Câmera no dispositivo ao qual vai executar o script.
`

## Criar um Ambiente Virtual

Crie um ambiente virtual:

1. Crie um ambiente virtual:

```bash
 python -m venv venv
```
2. Ative o ambiente virtual:

- Windows:

```bash
venv\Scripts\activate
```
- macOS e Linux:

```bash
source venv/bin/activate
```
3. Instale as dependências:

```bash
pip install -r requirements.txt
```
## Uso:

Para treinar o modelo, execute o script main.py:

```bash
python main.py
```

## Observações:

- Ajuste o índice da câmera (cv2.VideoCapture(1)) se necessário. O índice varia conforme o dispositivo.

