### Computer Vision Workloads in Azure ML

#### Overview
- **Exam Relevance**: Computer vision workloads account for 15-20% of the exam score.
- **Focus**: Use cases for computer vision and specific Azure services for these tasks.

#### Common Computer Vision Tasks

1. **Image Classification**
   - **Description**: Identifies a single term that best describes the image.
   - **Options**:
     - **Prebuilt Models**: Ready-to-use models provided by Azure.
     - **Custom Models**: Train your own model with specific data.
   - **Example**: Feeding an image of a cat to get a classification label "cat."

2. **Object Detection**
   - **Description**: Identifies multiple objects within an image and locates them with coordinates.
   - **Features**:
     - **Object Identification**: Labels each object.
     - **Location**: Provides X and Y coordinates, often with a bounding rectangle.
     - **Confidence Scores**: Indicates the confidence level of each identification.
   - **Example**: Detecting and locating a bicycle, its wheels, and a tree in an image.

3. **Semantic Segmentation**
   - **Description**: Identifies the boundaries of objects within an image.
   - **Use Cases**:
     - **Satellite Imagery**: Drawing boundaries of houses.
     - **Self-Driving Cars**: Understanding edges and boundaries of objects on the road.
   - **Example**: Outlining the boundaries of buildings in a satellite image.

4. **Optical Character Recognition (OCR)**
   - **Description**: Reads and extracts text from images.
   - **Features**:
     - **Text Extraction**: Converts image text to readable and editable formats.
   - **Example**: Extracting text from a signboard in an image.

5. **Facial Detection and Recognition**
   - **Description**: Detects and identifies human faces within images.
   - **Features**:
     - **Facial Detection**: Locates and marks faces within an image.
     - **Facial Recognition**: Identifies specific individuals.
     - **Description**: Provides additional context like expressions, attire, and other attributes.
   - **Example**: Identifying Tom Cruise in an image, providing a description and confidence score.

### Specific Azure Services for Computer Vision Tasks

1. **Azure Cognitive Services: Computer Vision**
   - **Image Classification**: Provides APIs for classifying images using prebuilt or custom models.
   - **Object Detection**: Detects multiple objects within an image and provides their locations and confidence scores.
   - **OCR**: Extracts text from images and converts it into readable formats.
   - **Facial Recognition**: Identifies and analyzes human faces in images.

2. **Azure Custom Vision**
   - **Custom Training**: Allows users to train custom models for image classification and object detection.
   - **User-Friendly Interface**: Simplifies the process of creating, training, and deploying custom models.

### Use Cases and Practical Examples

1. **Image Classification**:
   - **E-commerce**: Automatically categorize products based on images.
   - **Healthcare**: Classify medical images to aid in diagnosis.

2. **Object Detection**:
   - **Retail**: Identify and track items in inventory.
   - **Security**: Detect unauthorized objects or individuals in restricted areas.

3. **Semantic Segmentation**:
   - **Urban Planning**: Outline buildings and infrastructure in city planning.
   - **Agriculture**: Identify different crop areas in satellite images.

4. **OCR**:
   - **Document Digitization**: Convert scanned documents into editable text.
   - **Data Entry**: Automate extraction of text from forms and records.

5. **Facial Detection and Recognition**:
   - **Security**: Enhance security systems with facial recognition.
   - **Marketing**: Analyze customer demographics and behaviors.

### Summary
- **Azure ML and Computer Vision**: Provides powerful tools for a variety of computer vision tasks without needing to write code.
- **Key Tasks**: Image classification, object detection, semantic segmentation, OCR, and facial recognition.
- **Azure Services**: Utilize Azure Cognitive Services and Azure Custom Vision for these tasks.
- **Use Cases**: Wide range of applications across industries like e-commerce, healthcare, security, and urban planning.

### Next Steps
- **Demo**: Practical demonstration of using Azure ML Designer and AutoML for computer vision tasks to build and evaluate models without coding.