<p align = "center">
    <img src = "https://github.com/UF-CSSALT/SMARTS-SDK/blob/master/Documentation/Images/CSSALTLogo.jpg" alt = "CSSALT Logo">
</p>
<!-- \\anes.ahc.ufl.edu\anes$\NEWSHARE\CSSALT\Research\Projects_and_Proposals\Projects\Open_Projects\SDK -->

# NOTICE
The SMARTS-SDK is now located at https://github.com/UF-CSSALT/SMMARTS-SDK under the name SMMARTS-SDK. Please use this version as the SMARTS-SDK github will be depreciated in the coming months.



# SMMARTS SDK Documentation
The CSSALT SMMARTS Software Development Kit (SDK) connects Unity Technology’s
Unity 3D game engine with CSSALT's SMMARTS platform. This SDK
facilitates the development of new Mixed Reality medical simulators, specifically targeting, but not limited to, those related to interventional ultrasound procedures. The SMMARTS SDK is built with multiple features to allow developers who have access to a SMMARTS simulation hardware unit to build their own custom mixed-reality simulations, re-purposing SMMARTS tracked tools for their own specialized simulations. The SDK provides a CSSALT menu Unity Editor interface to guide the developer through SDK features, which includes: NDI Ascension 6DOF tracking support, tool microcontroller interface support, general “scoring monitors” for simulation use, Cognitive Aids for simulation use, data graphing for simulation use, instrument position recording and replaying, Log-In user interface templates, and multiple choice questionnaire templates for simulation use. The SDK includes pre-configured tools common to most SMMARTS platforms such as Ultrasound Probe, Needles, and Camera Controller. Simulated ultrasound rendering is supported. The CSSALT menu will also assist in importing custom anatomy to the Unity Scene and alignment to the SMMARTS index plate. Furthermore, since the SDK is intended for educators, it is Experience API (xAPI) compatible to allow the SDK to speak with Learning Management Systems (LMS).

<!-- not sure if this line is needed The SDK will provide documentation and sample projects for developers to reference. -->

## High Level Structure
The SMMARTS SDK is composed of two main parts: microcontroller code that runs on an Arduino Uno within the Whitebox controller and a Unity project that contains the functional code which actually builds the SDK.

For more information on specific components of the SMMARTS SDK please visit the [wiki](https://github.com/UF-CSSALT/SMARTS-SDK/wiki). 

#### Note: We are currently updating all documentation, both internal and external, to reference the recent change from "SMARTS-SDK" to "SMMARTS-SDK." We understand during this transition period both versions will appear in documentation, software, etc., but we are working diligently to update all references. Welcome to the new System of Modular, MIXED, and Augmented Reality Tracking Simulators.

#### We appreciate your understanding,

