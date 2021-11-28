# YOLO
You Only Look Once

- Apply a single `Neural Network` to the full image.
- Network divides the image into regions and predicts `bounding boxes` and probabilities for each `region`
- Bounding boxes are weighted by the predicted probabilities.

![YOLO](YOLO.jpeg)

- It makes `predictions` with single neural network evaluation unlike systems like `RNN`
- `RNN` requires thousands for a single image.
- This makes it extremely `fast`, more than `1000x` faster than `RCNN` and `100x` faster than `Fast RCNN`
