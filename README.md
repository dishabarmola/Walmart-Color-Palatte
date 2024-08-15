# ReStyle - Integrating color analysis with shopping

ReStyle is an innovative application that offers personalized shopping experiences by utilizing 12 season color theory. The application allows users to upload images, detect dominant colors, and recommend clothing items based on the detected colors and user-selected filters.

## Features

- **Image Upload**: Upload an image to detect dominant colors and segment the image.
- **Face Detection**: Detects faces in the uploaded image and crops to the first detected face.
- **Color Detection**: Identifies dominant colors in the cropped face image and excludes gray colors.
- **Color Palette Recommendation**: Provides a recommended color palette based on 12-season color theory.
- **Personalized Shopping**: Display clothing items in the Myntra website that match the user's selected filters and recommended color palette.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/NidhiIyer04/ReStyle.git
    cd ReStyle
    ```

2. Install the required dependencies:
   * Create a virtual environment
     ```bash
     python -m venv venv
    
    * Activate the virtual environment
      ```bash
      source venv/bin/activate
      
    * Install the dependencies
    ```bash
    pip install -r requirements.txt
    

## Usage

1. **Run the Application**:
    ```bash
    cd Interface
    streamlit run model.py
    ```

2. **Upload an Image**:
    - Click on the "Upload an image" button to upload your image.

3. **Apply User Filters**:
    - Select the desired options from the sidebar such as gender, master category, sub-category, article type, and usage.

4. **Image Processing**:
    - The application will automatically process the uploaded image to segment the face, detect dominant colors, and generate a recommended color palette.

5. **Start Shopping**:
    - Click on the "Check out the recommended products on myntra" button to view personalized clothing recommendations. If the required sections (gender, master category, and image upload) are not completed, a message will be displayed prompting the user to complete these sections.

## Dependencies

- OpenCV
- MediaPipe
- Streamlit
- NumPy
- Pillow
- scikit-learn
- Pandas

  