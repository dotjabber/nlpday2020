# nlpday2020
Materiały związane z warsztatem 'Pierwsze kroki z toolkitem OpenVINO', nlpday 2020.

Ściągawka z komendami i zasobami:
ważne katalogi:
- cd C:\Program Files (x86)\Intel\openvino_2021
- cd C:\Program Files (x86)\Intel\openvino_2021.1.110\bin
- cd C:\Program Files (x86)\Intel\openvino_2021\deployment_tools\tools\model_downloader

ściąganie modeli:
- python downloader.py --print_all
- python downloader.py --name <nazwa modelu>
  
docker workbenchowy
- docker run -d -p 5665:5665 --name workbench openvino/workbench:2020.R1.0.0
- docker exec workbench cat /home/openvino/.workbench/token.txt

dokumentacje modeli i inne:
- https://docs.openvinotoolkit.org/latest/omz_models_intel_index.html
- https://docs.openvinotoolkit.org/latest/workbench_docs_Workbench_DG_Install_from_Docker_Hub_Win.html
- http://127.0.0.1:5665
- http://ai.stanford.edu/~jkrause/cars/car_dataset.html
- https://github.com/fchollet/deep-learning-models/releases/tag/v0.8
