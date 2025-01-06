(about-imagec)=
# About ImageC?

**ImageC is an open source software for high throughput bioimage analysis.**

```{figure} images/screenshot_open_pipeline.png
:class: full-image
```

ImageC provides an **easy to use graphical user interphase (GUI)** enabling the compilation of image processing pipelines for **Object detection and Quantification** from various types of microscopic images, particularly Brightfield images, fluorescence images and Histological images. It was optimized within a group focused on Nanovesicles and therefore offers a powerful set of templates optimized for **single vesicle quantification** in diverse in vitro and in vivo settings. 

:::{sidebar} Features include

- [BioFormats support](https://github.com/ome/bioformats) {{icon_bioformats}}
- [OME-XML support](https://docs.openmicroscopy.org/) {{icon_ome}} 
- Support of cross channel measurements
- Database based result processing
- XLSX data export
- R data export
- Support for histological images (big tiff support)                                   
- AI based object classification
- Heatmap generation
- Image density map generation
- Built-in report generation and analyze tool
- Side by side image comparison
:::

## Is ImageC suitable for me?

There are diverse commercial or open access image processing applications.
What is special about ImageC? Is it the best program to help me to quantify my imaging data?

````{grid}
:gutter: 2

:::{grid-item-card} 🚀 Pipeline creation 
:columns 4

ImageC enables to create individual pipelines for object detection ut together from a set of widely used image processing algorithms including backgound substraction algorithms,  filtering, edge detection and manual as well as auto- thresholding.
:::

:::{grid-item-card} 🚀 High troughput image analysis
:columns 4

Image C is designed for fast procession and analysis of a huge amount of images or of huge images. :::

:::{grid-item-card} 🚀 Big data organisation
:columns 4

Moving into high throughput analysis of huge data sets and huge images (e.g. histological sections) is linked to an increase in data volume, making automated image and data processing inevitable. To meet these criteria Image C enables for automated data sorting and filtering as well as  processing with Excel or R.
:::

:::{grid-item-card} 🚀 AI driven object detection
:columns 4

ImageC enables to include aritificial intelligence for object detection. Image C supports the ONNX container format with net hight x with 640 x 640 and a stride size of 3. traning input: RGB image, 32bit float RGB.
:::

:::{grid-item-card} 🚀 BioFormats support
:columns 4

All common image formats used by different microscopy manufacturer are supported. Please note that not all formats support pyramid images and therefore the overview preview may be impaired for some of them.
:::

:::{grid-item-card} 🚀 OME-XML support
:columns 4

Image C automatically extracts underlying image infos (e.g. channel infos, Z-stack infos, etc. ).
:::

:::{grid-item-card} 🚀 Reuseable and sharable pipelines
:columns 4

ImageC is designed for reproducible image analysis (reusable pipelines that can be shared)
:::

:::{grid-item-card} 🚀 Live preview
:columns 4

ImageC offers a live preview enabling to monitor the impact of all image processing steps within your pipelineand thereby provides transparent and understandable object detection enabled 
:::

:::{grid-item-card} 🚀 Generation of control images
:columns 4

ImageC generates user defined control images, for documentation and internal control.
:::

:::{grid-item-card} 🚀 Image/Data sorting
:columns 4

Automated image sorting based on e.g. typical well formats used in biology (96well plate, etc) can help to sort images. Mean, median, max, min, SD, SUM and Count can be automatically evaluated from multiple images within a group ( e.g. from multiple images per well). 
:::

:::{grid-item-card} 🚀 Heatmaps
:columns 4

Image C can autoamtic generate heatmaps of images OR of image groups (e.g. wells), enabling a quick assessment of the data. 
:::

:::{grid-item-card} 🚀 Image/Data Filtering
:columns 4

Image C enables to predefine data filter which enables a prefiltering of huge data sets (e.g. remove Images without cells, etc)
:::
````






### What is ImageC not?

- ImageC is not an universal image processing application like [ImageJ](https://imagej.net/).
- ImageC is not designed for individual image processing even if it could be used for this.
- ImageC is not designed "to make pictures look pretty".
- ImageC is not designed for manual image processing or object segmentation.

### What is ImageC?

- ImageC is designed for high throughput image analyzing, object detection and quantification.
- ImageC generates huge raw data sets that can be further processed using basic internal tools, R or Excel.
- Image C enables the user to build individual object detection pipelines put together from a set of widely used image processing algorithms.
- ImageC is designed for fast processing of huge data sets or huge images (e.g. histological images/ whole well scans).
- ImageC is designed for reproducible image analysis (reusable pipelines that can be shared)
- ImageC provides useful data sorting algorithm that help with data managment (e.g. usage of image sorting based on known well formats)
- Image C provides transparent and understandable object detection enabled by a live preview and generation of control images.
- Image C can be used to quantify fluorescence in Objects.
- Image C can be used to seperate objects based on colour (e.g. from histological stainings).
- Image C can process Z-stacks.

### What is planned for Image C?

- Image C will be able to automatically process microscopic videos and trace objects over time
- Image C will be able to process huge Z-stacks / 3D images (e.g. from lightsheet imaging)
  



