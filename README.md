# Pascal Solutions
Proposed solution for SCDF X IBM Lifesavers' Innovation Challenge: Call for Code 2020.

Problem Statement: "Integrating With A Smart Environment"

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

Currently, accidents and disasters are reported through traditional means, such as "Break Glass" fire alarms, smoke detectors and emergency phone calls. These methods have substantial problems, such as high false alarm rate from single point of information, low success rate in community response from reporting lag-time, and high injury and fatality rate due to lack of critical context data.

As Singapore is transitioning into a Smart Nation, the use of Internet of Things (IoT) sensors and cloud computing are increasingly prevalent for building/district management. Digital twins are used to virtually represent buildings in real time, which is currently used for monitoring and analytics. However, this rich source of data is not available to Emergency Services. Thus, there is a huge underlying potential for emergency services to leverage on these technologies for improved response times, operations management and optimisation of resources.

Pascal Solutions proposes Twinlink, a digital twin gateway that allows emergency services such as Singapore Civil Defence Force (SCDF) to access real-time critical information from the cloud during emergency situations.

1. Data is collected from various sensors within the building and Twinlink Edge performs preprocessing of this data before it is uploaded to IBM Cloud Object Storage.
2. The data is then delivered to IBM Watson, which performs machine learning analytics to monitor for emergency situations.
3. IBM Watson will stream the output into Twinlink View for building management to perform analytics and monitoring. Twinlink View is deployed on IBM Cloudfoundry. During normal operations, SCDF will not be able to access this data.
4. If an emergency is detected, Twinlink Access will automatically create a API pipeline to stream relevant information for SCDF such as the number of occupants, layout geometry of the emergency, Potential Casualty Density Parameters (PCDP) and other data that is critical.
5. Twinlink View will provision a temporary digital twin for emergency responders to rapidly access critical data en-route to site, using a web-based app.

## Pitch Video

## Architecture

<img src="https://github.com/PascalSolutions-Twinlink-SCDFXIBM/README.md/blob/master/Architecture.png" alt="Roadmap" />

## Detailed Solution


## Project Roadmap

<img src="https://github.com/PascalSolutions-Twinlink-SCDFXIBM/README.md/blob/master/Stages.png" alt="Roadmap" />

## Getting Started

Step-by-Step Instructions in Order:
* [Twinlink Edge](https://github.com/PascalSolutions-Twinlink-SCDFXIBM/EdgeComputing#installation)
* [Twinlink Watson](https://github.com/PascalSolutions-Twinlink-SCDFXIBM/yolo_fire_detection#-deployment-)
* [Twinlink View](https://github.com/PascalSolutions-Twinlink-SCDFXIBM/pythonflaskpascal#introduction)

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
