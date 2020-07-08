# serving_image_classifier
Serving ResNet50 (trained on ImageNet) predictions with FastAPI, Redis, and Docker.

Spin up the service with `docker-compose up`, then make a prediction with something like `curl -X POST -F img_file=@img/goldfish.jpg http://localhost/predict`.
