# RestaurantPriority
YOLOv8 Object Detection model that recognizes tables from a upper view, such as from a security camera. The Dataset used was obtained in Roboflow and can be accessed [here](https://universe.roboflow.com/new-workspace-rshoj/luis/dataset/1). Although it has multiple classes, the model only aims to predict people/waiters and tables, with the goal of detecting waiting tables and warning staff which clients should be given higher priority.

### Training
The Dataset containts almost 1,500 annotated images. Firstly, there was an attempt to use Yolo-Keras-V3 & Google Collab to train the model, however, training was too time-consuming and the results were not satisfactory. Therefore, there was a migration to YOLOv7 training which proved much more effective. Here are the following results


### Model Results with different Images

### Try it yourself
- The model is available for testing in the [following URL](https://detect.roboflow.com/?model=restaurant-tables-ymr9k&version=4&api_key=4DoXpwcq4LOWCz9iZkq0), where you can upload your own picture and test its recognition.
- It can also be tested in your own mobile device by scanning the follow QR code:

### Samples
