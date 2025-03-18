
# Fake Currency Detection System

This  **Fake Currency Detection System**  is a desktop application developed in  **Python**  using  **OpenCV**  for image processing,  **Tkinter**  for the GUI, and  **Jupyter Notebook**  for the development environment. It was created as part of my first-semester university project. The system is designed to detect counterfeit Indian currency notes (₹500 and ₹2000) by analyzing various security features using advanced image processing techniques.

----------

## Features

1.  **Currency Note Authentication**:
    
    -   Detects counterfeit ₹500 and ₹2000 currency notes.
        
    -   Analyzes 10 security features, including bleed lines, number panels, and other unique identifiers.
        
2.  **Image Processing**:
    
    -   Uses  **ORB (Oriented FAST and Rotated BRIEF)**  for feature detection and matching.
        
    -   Employs  **SSIM (Structural Similarity Index)**  for image comparison.
        
    -   Performs image pre-processing, including resizing, Gaussian blur, and grayscale conversion.
        
3.  **Bleed Line Detection**:
    
    -   Counts and verifies the number of bleed lines on the left and right sides of the currency note.
        
    -   Uses thresholding and contour detection to identify bleed lines.
        
4.  **Number Panel Verification**:
    
    -   Detects and verifies the number of characters in the currency note's serial number panel.
        
    -   Uses multiple thresholding values and contour detection to ensure accuracy.
        
5.  **User-Friendly Interface**:
    
    -   Intuitive GUI built with  **Tkinter**.
        
    -   Allows users to upload an image of the currency note and select the currency type (₹500 or ₹2000).
        
    -   Displays detailed results for each security feature, including pass/fail status.
        
6.  **Performance Analysis**:
    
    -   Provides accuracy metrics for both real and fake currency notes.
        
    -   Displays the average SSIM score, max SSIM score, and the number of detected bleed lines.
        

----------

## Technologies Used

-   **Programming Language**: Python
    
-   **Image Processing**: OpenCV
    
-   **GUI Framework**: Tkinter
    
-   **Development Environment**: Jupyter Notebook
    
-   **Additional Libraries**: NumPy, Matplotlib, scikit-image
    

----------

## Installation and Setup

### Prerequisites

1.  **Python 3.x**: Ensure Python is installed on your system. Download it from  [python.org](https://www.python.org/).
    
2.  **Required Python Packages**:
    
    -   Install the necessary packages using pip:
        
      ```bash
    pip install opencv-python numpy matplotlib scikit-image pillow
    ```
        

### Steps to Run the Project

1.  **Clone the Repository**:
   ```bash 
   git clone https://github.com/your-username/fake-currency-detector.git
   cd fake-currency-detector
```

 
    
2.  **Run the Application**:
    
    -   Open the project in Jupyter Notebook.
        
    -   Run the  `controller.ipynb`  notebook to start the application.
        
    -   The GUI will prompt you to select an image of the currency note and choose the currency type (₹500 or ₹2000).
        
3.  **Explore the Features**:
    
    -   Upload an image of the currency note.
        
    -   Select the currency type and submit the image for processing.
        
    -   The system will analyze the image and display the results, including the status of each security feature.
        

----------

## Future Enhancements

-   **Support for More Denominations**: Extend the system to support other denominations of Indian currency.
    
-   **Real-Time Detection**: Implement real-time detection using a webcam or mobile camera.
    
-   **Enhanced GUI**: Add more interactive features to the GUI, such as zooming in on specific parts of the currency note.
    
-   **Machine Learning Integration**: Use machine learning models to improve the accuracy of counterfeit detection.
    

----------

## License

This project is licensed under the  **MIT License**. See the  [LICENSE](https://license/)  file for details.

----------

## Acknowledgments

-   **University Professors**: For guiding me through the development process.
    
-   **Open Source Community**: For the libraries and tools that made this project possible.
    
-   **Team Members**: For their contributions and support during the project.
    

----------

## Connect!

If you have any questions or want to connect, feel free to reach out to me:

-   **Email**:  [ishantmanjit@gmail.com](https://mailto:ishantmanjit@gmail.com/)
    
-   **LinkedIn**:  [Ishant Singh](https://www.linkedin.com/in/singhishant/)
