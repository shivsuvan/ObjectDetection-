# ObjectDetection - caffemodel 
* Developed a real-time object detection application utilizing
the MobileNet-SSD model in a Caffe framework.
* Implemented object classification and bounding box
predictions with configurable confidence thresholds,
enhancing image and Video based detection systems

## MobileNet
* Purpose: MobileNet is a lightweight deep neural network designed for mobile and embedded vision applications. It is optimized for efficiency in computation and memory usage, making it suitable for devices with limited resources.
* Architecture: MobileNet uses depthwise separable convolutions, which split the standard convolution operation into two simpler steps:
    * Depthwise Convolution: Filters are applied to each input channel independently.
    * Pointwise Convolution: A 1x1 convolution combines the outputs from the depthwise convolution.

## Single Shot Detector (SSD)
* Purpose: SSD is a method for real-time object detection that predicts both object classes and bounding boxes directly from feature maps in a single forward pass.
* Advantages: It eliminates the need for region proposals (as in R-CNNs) by detecting objects at multiple scales using predefined anchor boxes.

### MobileNet-SSD Integration
* Combination: The MobileNet backbone is used to extract efficient and rich feature representations, while the SSD architecture handles the detection process.
