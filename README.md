## How AVCaptureSession Works
Whenever you want to capture some sort of **media** — whether it’s **audio**, **video** or **depth data** — `AVCaptureSession` is what you want.

- `AVCaptureDevice` **:** a representation of the **hardware device** to use.
- `AVCaptureDeviceInput` **:** **provides a bridge** from the **device** to the **AVCaptureSession**.
- `AVCaptureSession` **:** **manages the flow of data** between capture inputs and outputs. *It can connect one or more inputs to one or more outputs.*
- `AVCaptureOutput` **:** **an abstract class representing objects** that output the captured media. *You’ll use `AVCaptureVideoDataOutput`, which is a concrete implementation of this class.*

<image width=500 src="https://user-images.githubusercontent.com/127583339/235307532-8e05bd9f-1d64-40b8-81a1-9cb4122c37a7.png">

<br>

CC. <br>
https://developer.apple.com/documentation/avfoundation/capture_setup <br>
https://www.kodeco.com/26244793-building-a-camera-app-with-swiftui-and-combine
