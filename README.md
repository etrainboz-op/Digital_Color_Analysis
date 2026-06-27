# Linear Algebra Applications in Digital Color Analysis
This project explores how our understanding of mathematics and color has fueled innovations in computer science, enabling the creation of digital imaging effects. The project resulted in Python code that creates and replicates several digital image processing effects, a written report explaining the underlying mathematics and experimental results, and a presentation that demonstrates and visualizes the methods used. Using Python's Pillow library, the project successfully implemented image blurring, grayscale conversion, and an interactive RGB color picker.

## Files 

### Project Report
`Project Report.pdf`
This report begins by providing background on how humans perceive color, how color is represented in different color spaces, and how these color spaces can be transformed for digital applications. It then explains the underlying linear algebra, describes the dataset, and presents the interactive RGB color picker. Finally, the report presents the code outputs, discusses the results, and concludes with a summary of the project's findings.

### Project Presentation
`Project.pptx`
This presentation is used to explain the background of the project, and visualize the methodology for each implementation.

### Project Code
`Project.ipynb`
The code for this project was written in an interactive Jupyter Notebook. It begins by converting the dataset from a PDF file into a CSV file, creating a pandas DataFrame, and cleaning and expanding the data. Next, four different implementations of an interactive RGB color picker are developed, along with an interactive 3D visualization of a selected color in RGB space. Finally, an example image is used to demonstrate grayscale conversion and image blurring using a Gaussian kernel.

### Data Set
`sherwin_colors.pdf` `sherwin_colors.csv`
Provides the original data frame in PDF format, and the converted data frame in CSV format. The original data frame contains over 9,000 paint colors from Sherwin Williams with columns containing information about each color.

#### Data Set Summary
| **Column**     | **Description**                             |
|----------------|---------------------------------------------|
| **Color #**    | The ID number of the Sherwin Williams color |
| **Color Name** | The name of the Sherwin Williams color      |
| **Locater #**  | Short code used to locate certain colors    |
| **Red**        | Integer value of the red channel            |
| **Green**      | Integer value of the green channel          |
| **Blue**       | Integer value of the blue channel           |
| **Hex**        | Hexidecimal color code value                |
| **Color**      | Image or Python Pillow object of the color  |


### Example Image
`bird_image.jpg`
Example image used to present greyscale conversion and image blur.