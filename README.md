# Face_Recognition_System

Face recognition is a biometric technology that allows computers to identify or verify a person's identity by comparing facial features.

This project is based on CNN technology. Here's a general overview of how the feature learning process works in a CNN for face recognition:

`Low-level features:` The initial layers of the CNN detect basic patterns like edges and textures. These features are generic and not directly related to faces.

`Mid-level features:` As the data passes through deeper layers, the model starts to detect more complex patterns, which may correspond to facial parts like eyes, nose, and mouth. These mid-level features are more specific and relevant to faces.

`High-level features:` In the later layers of the CNN, the model combines the detected facial parts to form higher-level representations of complete faces. These high-level features are essential for face recognition.

To run the project, install `requirements.txt` file in your virtual environment. `pip install -r requirements.txt`