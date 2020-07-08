# serving_image_classifier
Serving ResNet50 (trained on ImageNet) predictions with FastAPI, Redis, and Docker.

Spin up the service with `docker-compose up`, then make a prediction with something like `curl -X POST -F img_file=@img/goldfish.jpg http://localhost/predict`.

You can load test with Locust with `locust --host=http://localhost`. You can then go to `http://localhost:8089` and start swarming.
