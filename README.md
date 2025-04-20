# ANN-style-tranfer
Neural Style Transfer with VGG19
Implementation: Uses PyTorch and pretrained VGG19
Method: Gatys et al. (2015) paper's optimization-based approach
Key Features:
->Blends content and style through iterative optimization
->Adjustable style-content weights (alpha and beta)
->Here I have used CPU (but using gpu will make it much faster) 
->Progress tracking with intermediate image saves every 200 steps
Usage:
->Install dependencies: torch, torchvision, Pillow
->Specify image paths and run script
->Customizable parameters: iterations, learning rate, loss weights
Output: Generates styled images at specified intervals
Basis: "A Neural Algorithm of Artistic Style" paper.
