# AnnotateX Studio – Web-Based Image Annotation Tool

## Project Overview

AnnotateX Studio is a web-based image annotation application designed to make image labeling and annotation simple, efficient, and user-friendly.

The application allows users to upload multiple images, draw bounding boxes around objects, assign labels, edit annotations, and save annotation data in JSON format.

Users can also import previously saved JSON project files and restore their annotations by selecting the original images.

This project is developed as an academic project to demonstrate image annotation techniques used in Computer Vision and Machine Learning.

## Key Features

- **Multiple Image Upload:** Upload and work with multiple images in one project.
- **Bounding Box Annotation:** Draw rectangular bounding boxes around objects in images.
- **Live Box Measurements:** View bounding box width and height while drawing.
- **Object Labeling:** Assign predefined labels or create custom labels.
- **Edit Bounding Boxes:** Select, move, resize, and modify bounding boxes.
- **Coordinate Editing:** Manually edit X, Y, Width, and Height values.
- **Undo and Redo:** Undo or redo previous annotation actions.
- **Delete Annotations:** Delete selected bounding boxes.
- **Zoom Controls:** Zoom in, zoom out, and fit images to the screen.
- **Image Navigation:** Switch between multiple uploaded images using the image gallery.
- **JSON Export:** Save and download annotation data as a JSON project file with a custom filename.
- **JSON Import:** Import previously saved JSON project files.
- **Image Relinking:** Select original images to restore previously saved annotations.
- **Annotation Inspector:** View and manage object labels and annotation details.
- **Keyboard Shortcuts:** Use keyboard shortcuts for faster annotation tasks.

## Technologies Used

- HTML5 – Structure of the web application.
- CSS3 – Styling and user interface design.
- JavaScript – Annotation functionality and interactive features.
- JSON – Storing and restoring annotation data.
- Visual Studio Code – Development environment.
- GitHub – Source code management.
- Vercel – Web application deployment.

## How to Use

### 1. Upload Images

1. Open AnnotateX Studio.
2. Click the Upload button.
3. Select one or multiple images from your computer.
4. Uploaded images will appear in the image gallery.

### 2. Create Bounding Boxes

1. Select the Bounding Box tool.
2. Move the cursor over the image.
3. Click and drag to draw a rectangle around the desired object.
4. View live width and height measurements while drawing.
5. Assign a suitable label to the annotated object.

### 3. Manage Annotations

- Select existing bounding boxes.
- Move or resize boxes.
- Edit annotation coordinates.
- Change object labels.
- Delete selected annotations.
- Use Undo and Redo to manage changes.

### 4. Export Annotation Project (JSON)

1. Click the Save Annotations button.
2. Enter a preferred filename.
3. Save the annotation project as a JSON file.
4. Keep the JSON file for future use.

### 5. Import Existing Annotation Project (JSON)

1. Click the Import Project button.
2. Select a previously saved JSON project file.
3. After the JSON file is validated, click Select Original Images.
4. Select the original image files used in the project.
5. The application matches the images and restores their saved bounding box annotations.

**Note:** The original images are required during project restoration because the JSON file stores annotation information rather than embedding the image files.

## 📂 Project Structure

```text
AnnotateX-Studio/
│
├── index.html
└── README.md
```

*Note: If CSS, JavaScript, or other assets are maintained in separate files, they are also included in the project.*

## Live Demo

**Live Application:**  
https://annotatex-studio.vercel.app/

## Project Objectives

The main objectives of AnnotateX Studio are:

- To develop a simple web-based image annotation tool.
- To implement Bounding Box annotation techniques.
- To provide object labeling and annotation editing functionality.
- To support multiple image annotation.
- To save and restore annotation projects using JSON.
- To understand practical applications of image annotation in Computer Vision and Object Detection.

## Developer

**Iqra Khatoon**

Academic Project – Web-Based Image Annotation Application

## Conclusion

AnnotateX Studio provides an interactive platform for image annotation using the Bounding Box technique. It allows users to create, edit, manage, export, and restore image annotations through a user-friendly web interface.

**AnnotateX Studio – Making Image Annotation Simple!**
