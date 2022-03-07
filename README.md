- PUT YOUR CUSTOM TFLITE MODEL IN "YOLOv4-Voice-Feedback-Android/app/src/main/assets/"

- Make Changes in Yolov4Classifier.java at line 181 if it yolov4-tiny private static boolean isTiny = true; if it is only yolov4 model -    private static boolean isTiny = false;

- Make Changes in CamerActivity.java and DetectorActivity.java with your languages.

- Make changes in CameraActivity.java at line 122 with your own command.

- Make Changes in DetectorActivity.java at line 214 with your own command.

