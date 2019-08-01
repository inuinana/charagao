## Installation
docker build -t charagao:charagao .  
docker run -p 5000:5000 charagao

## Image Collector (e.g. collect 100 image files of banana)
python src/datapreprocess/image_collector.py -k banana -o ./data -n 100

## Main Backend Script (Image Similarity Evaluation)
python src/image_similarity_evaluation.py
