A TensorFlow-based facial recognition system that combines deep learning for face embedding generation with encryption for secure storage. The system implements a complete pipeline from face detection through secure user verification.

## Technical Architecture

### Core Components:
2. **Deep Learning Model**
   - MobileNetV2 backbone
   - Custom embedding layer
   - Trained with triplet loss
   - Achieves 2.05e-6 validation loss

3. **Security Layer**
   - AES encryption for embeddings
   - Secure SQLite database
   - Encrypted user management

### Technologies
TensorFlow, Python, PyCryptodome, SQLite, OpenCV

[GitHub Repository](https://github.com/yourusername/facial-recognition-system)
