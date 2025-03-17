# NEURAL-STYLE-TRANSFER

COMPANY : CODTECH IT SOLUTIONS

NAME : YATHIRAJULA DIVYA SREE

INTERN ID : CT08DRC

DOMAIN : ARTIFICIAL INTELLIGENCE

DURATION : 12 WEEKS 

MENTOR : NEELA SANTOSH

DESCRIPTION:  

    Neural Style Transfer (NST) is an innovative deep learning technique that allows users to transform images by applying the artistic style of one image to another. This technique is widely used in digital art, photography, and creative applications, making it possible to create visually appealing artwork using artificial intelligence.

Working of Neural Style Transfer
NST uses deep learning models to extract and manipulate content features from one image and style features from another:

Content Extraction: The model extracts high-level features from an image (such as objects, shapes, and structures) using convolutional layers.
Style Extraction: The model captures patterns, textures, and colors from the style image by analyzing the activations of deeper layers.
Optimization Process: A random noise image is iteratively updated using gradient descent to minimize the loss function, which consists of:
Content Loss: Measures how different the generated image is from the content image.
Style Loss: Measures how different the textures and patterns are from the style image.
Total Variation Loss (optional): Helps reduce noise and improve smoothness.
Final Output: The transformed image is generated after multiple iterations of optimization.
Project Implementation

This project involves the following steps:
1. Importing Required Libraries
torch, torchvision, and torch.nn for deep learning operations.
matplotlib, PIL, and OpenCV for image handling.
2. Loading Pretrained Model
VGG19 is used for feature extraction because its deep layers effectively capture texture and content.
The convolutional layers extract both content and style information.
3. Processing Images
The content image (e.g., a photograph) and the style image (e.g., Van Gogh's painting) are loaded and preprocessed.
4. Computing Content and Style Loss
The Gram matrix is used to compute style loss, ensuring that texture information is maintained.
A weighted combination of content loss and style loss drives the optimization.
5. Generating the Styled Image
The content image is iteratively transformed into a styled version using gradient descent (Adam Optimizer).
The final output is displayed and saved.
Research & Sources Used
This project was developed using multiple sources:
Google: Helped in understanding NST algorithms, libraries, and implementations. ChatGPT: Provided code improvements, bug fixes, and optimizations.
 YouTube: Guided through tutorials on NST using TensorFlow and PyTorch.
 Research Papers: Provided deep insights into style transfer techniques and model enhancements.

Applications of Neural Style Transfer
NST has many real-world applications in various domains, including:

🔹 Digital Art & Photography: Artists use NST to create unique digital paintings and artworks.
🔹 Film & Animation: Used for movie scene stylization and animated effects.
🔹 Augmented Reality (AR): Apps like Prisma and DeepArt apply NST to enhance user images.
🔹 Fashion Design: Designers generate patterned clothing designs using style transfer.
🔹 Game Development: Enhances textures and graphics by applying artistic effects.
🔹 Marketing & Advertising: Used to create visually appealing graphics for branding.

