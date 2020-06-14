# Pascal Solutions
Proposed solution for SCDF X IBM Lifesavers' Innovation Challenge: Call for Code 2020.

"Integrating With A Smart Environment"

## Contents

1. [Short Description](#short-description)
1. [Pitch Video](#pitch-video)
1. [Architecture](#architecture)
1. [Detailed Solution](#detailed-solution)
1. [Project Roadmap](#Project-Roadmap)
1. [Getting Started](#getting-started)
1. [Built with](#built-with)
1. [Authors](#authors)
1. [Acknowledgments](#acknowledgments)


## Short Description

Currently, accidents and disasters are reported through traditional means, such as "Break Glass" fire alarms, smoke detectors and emergency phone calls. These methods have substantial problems, such as high false alarm rate from single point of information, low success rate in community response from reporting lag-time, and high injury and fatality rate due to oversight in critical context.

As Singapore is transitioning into a Smart Nation, the use of Internet of Things (IoT) sensors and cloud computing are increasingly prevalent for building/district management. Digital twins are created that virtually represents buildings in real time, which is currently used for monitoring and analytics. However, this rich source of data is not available to Emergency Services. Thus, there is a huge underlying potential for emergency services to leverage on these technologies for improved response times, operations management and optimisation of resources.

Our team, Pascal Solutions, is proposing our idea known as Twinlink to revolutionise the entire process from detection to intervention by the Singapore Civil Defence Force (SCDF). 

1. Data will be collected by building management's IoT devices such as CCTVs and smoke detectors.
2. These data will be pumped to Twinlink's Digital Twin Storage, which utilises IBM cloud object to store the data.
3. Twinlink's Wardens.ai will use IBM Watson to serve as digital wardens to detect anomalies from a real-time sensor network.
4. If anomalies are detected Twinlink's Digital Twin Gateway will use IBM Cloudfoundry to instantly activate critical data pipelines to allow SCDF to access the data for emergency responses.

## Pitch Video

## Architecture

<img src="https://github.com/PascalSolutions-Twinlink-SCDFXIBM/README.md/blob/master/Architecture.png" alt="Roadmap" />

## Detailed Solution


## Project Roadmap

<img src="https://github.com/PascalSolutions-Twinlink-SCDFXIBM/README.md/blob/master/Stages.png" alt="Roadmap" />

## Getting Started


## Built With

* [IBM Cloud Object Storage](https://www.ibm.com/sg-en/cloud/object-storage) - Flexible, cost-effective and scalable cloud storage for unstructured data.
* [IBM Watson](https://www.ibm.com/sg-en/watson) - Powered by the latest innovations in machine learning, Watson is the open, multicloud platform that lets you automate the AI lifecycle.
* [IBM Cloudfoundry](https://www.ibm.com/sg-en/cloud/cloud-foundry) - Platform that ensures that the build and deploy aspects of coding remain carefully coordinated with any attached services - resulting in quick, consistent and reliable iterating of applications.
* [Jupyter Notebook](https://jupyter.org/) - An open source web application that allows you to create and share documents that contain live code, equations, visualizations, and explanatory text.
* [OpenCV](https://opencv.org/) - Open source computer vision library.
* [YOLOv3](https://pjreddie.com/darknet/yolo/) - Object detection algorithm.
* [Flask](https://flask.palletsprojects.com/en/1.1.x/) Micro web framework for Python.
* [xeogl](https://xeogl.org/) Data-driven WebGL-based 3D visualization engine from xeolabs.



## Authors


- **Chan Li Long**

  *Nanyang Technological University, Aerospace Engineering*


- **Cheng Kwok Hong**

  *Nanyang Technological University, Mechanical Engineering*
  

- **Liew Dar Win**

  *Nanyang Technological University, Aerospace Engineering*


- **Lim Wang Jin Lawrence**

  *Nanyang Technological University, Business(Banking & Finance)*


- **Soh Woon Hui Patrick**

  *Nanyang Technological University, Accountancy & Business(Banking & Finance)*

## Acknowledgements

* Based on [Billie Thompson's README template](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2).
