# 8 Dataset Browing Page

The Dataset Browsing Page offers an browsing and interactive interface where users can visualize and render image data.

![Image_64](../images/image_64.png)

## 8.1 Image Interface

### 8.1.1 Reset Camera

Both the top left corner and the right toolbar in the interface provide a "Reset Camera" button, which allows users to reset all camera settings.

![Image_84](../images/image_84.png)

![Image_52](../images/image_52.png)

### 8.1.2 Data Info

In the top right corner of the image interface, there is an icon that can display basic information about the image.



![Image_12](../images/image_12.png)

## 8.2 Data Interaction & Toolbar

### 8.2.1 Interaction Info List 

In the toolbar on the right-hand side, the first button is "Interaction Info List", which consists of two sections: "Annotation" and "Rendering".

* Annotation: This module contains two sections: one part is about segment information, and the other part is about measurements information.
![Image_36](../images/image_36.png)

When the user is using the Paint tool, this list allows for setting properties of Paint tool. The upper part allows users to select the brush or eraser for drawing and adjust the brush size and ROI area transparency. The lower part is for managing multiple ROI groups, where each ROI group can be custom-named, hidden, downloaded, and deleted. The ROI group colors can be added, selected, and named.

![Image_65](../images/image_65.png)

When the user is using the measurement tool, users can also view completed annotations in this list. For completed measurements, users can perform operations such as reveal slice, visibility toggle, and delete.

![Image_82](../images/image_82.png)

* Rendering: The module allows users to render data and adjust settings for cinematic rendering.
![Image_49](../images/image_49.png)

![Image_13](../images/image_13.png)

### 8.2.2 Layout Selection

On this page, users can select the layout interface and achieve 3D reconstruction. 

![Image_32](../images/image_32.png)

### 8.2.3 Window/Level (Contrast)

This button enables contrast adjustment functionality. We have incorporated default settings for image reading, along with four additional options: Full Range, Low Contrast, Medium Contrast, and High Contrast. Users can conveniently select these options based on their requirements. Users can also hold down the left mouse button on the image and move up and down to adjust the window level, and left and right to adjust the window width.

![Image_53](../images/image_53.png)

![Image_76](../images/image_76.png)

### 8.2.4 Pan

To pan, click on the Pan button, then hold down the left mouse button on the image and drag it to move the view.

![Image_37](../images/image_37.png)

### 8.2.5 Zoom

To zoom, click on the Zoom button in the toolbar, then hold down the left mouse button on the image and move up and down to zoom in and out.

![Image_4](../images/image_4.png)

### 8.2.6 Crosshair

To use the Crosshair feature, click on the Crosshair button in the toolbar. A cross-shaped crosshair will track the mouse cursor on the image. Click to lock the crosshair at the desired position.

![Image_22](../images/image_22.png)

### 8.2.7 Paint (Segmentation)

In the toolbar, choose the Paint button to utilize the brush tool for selecting Regions of Interest (ROI) on the image.

![Image_54](../images/image_54.png)

### 8.2.8 Rectangle (Measurement)

In the Toolbar, click on the Rectangle button, then utilize the brush tool to select the ROI area on the image. Begin by selecting the starting point, and then confirm the endpoint to finish drawing a rectangular ROI.

![Image_74](../images/image_74.png)

### 8.2.9 Polygon (Measurement)

Within the Toolbar, locate and select the Polygon tool. Utilize the brush tool to outline the ROI on the image. Begin by choosing an initial point, then confirm each subsequent point by clicking the mouse. Continue this process until the final point coincides with the starting point, thus forming a closed shape and completing the drawing of the Polygon ROI area.



![Image_33](../images/image_33.png)

### 8.2.10 Ruler (Measurement)

Select the Ruler button in the Toolbar, then use the tool to choose a starting point on the image and confirm the endpoint to measure the distance between the two points.

![Image_5](../images/image_5.png)

### 8.2.11 3D Crop

Select the 3D Crop button in the Toolbar, then adjust the corner, edge, and side markers in the 3D window, and manipulate the edges of the bounding box overlaid on the data in the 2D windows to make precise adjustments.



![Image_23](../images/image_23.png)

