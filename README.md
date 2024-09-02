# UROP_VR-Surgery-Training


A brief introduction to your project. Explain what the project is, its purpose, and any general information that a user should know before diving into the specifics.

---

## Table of Contents

1. [Introduction](#introduction)
2. [Tutorial App](#tutorial-app)
3. [Experiment App](#experiment-app)
4. [Joystick App](#joystick-app)
5. [Getting Started](#getting-started)
6. [Contributing](#contributing)
7. [License](#license)

---

## Introduction

Provide a more detailed overview of the project, its architecture, and any prerequisites needed. This section is optional but helps set the stage for the following sections.

---

## Tutorial App

### Overview


[![Watch the video](https://img.youtube.com/vi/UmPE9X6CAEo/0.jpg)](https://www.youtube.com/watch?v=UmPE9X6CAEo)

Click the image above to watch the overview video of the Tutorial App.

## Installation

Before you begin installing the Tutorial App, make sure you have completed the following prerequisites:

### Checklist:

1. [ ] **Unity ID Registered**: Ensure you have registered for a [Unity ID](https://id.unity.com/) or signed in with your existing account.
2. [ ] **Unity Hub Installed**: Download and install [Unity Hub](https://unity.com/download).
3. [ ] **Correct Unity Editor Version Installed**: Ensure that Unity Editor version **2022.3.5f1** is installed through Unity Hub.
4. [ ] **Visual Studio Installed**: Download and install [Visual Studio](https://visualstudio.microsoft.com/) (recommended version for Unity development).
5. [ ] **Quest 3 Developer Mode Enabled**: Ensure your Quest 3 headset is in developer mode. (Refer to the [Prerequisites section](#prerequisites-set-up-your-quest-3-in-developer-mode) above for instructions).
6. [ ] **Watch Video in Getting Started**: If you're unfamiliar with any of the steps, refer to the [Getting Started section](#getting-started) for a detailed video tutorial.

Once you have completed all the steps in the checklist, the Tutorial App is successfully installed!

---

### Next Steps:

Please proceed to watch the [Post-Build Instructions video](#post-build-instructions) to learn how to use the app, including placing models and loading content.

---

### Configuration

Any specific configurations or environment variables needed for the Tutorial App.

---

## Experiment App

### Overview


[![Watch the video](https://img.youtube.com/vi/ocaF2cfl_9M/0.jpg)](https://www.youtube.com/watch?v=ocaF2cfl_9M)

Click the image above to watch the overview video of the Experiment App.

## Installation

Before you begin installing the Tutorial App, make sure you have completed the following prerequisites:

### Checklist:

1. [ ] **Unity ID Registered**: Ensure you have registered for a [Unity ID](https://id.unity.com/) or signed in with your existing account.
2. [ ] **Unity Hub Installed**: Download and install [Unity Hub](https://unity.com/download).
3. [ ] **Correct Unity Editor Version Installed**: Ensure that Unity Editor version **2022.3.5f1** is installed through Unity Hub.
4. [ ] **Visual Studio Installed**: Download and install [Visual Studio](https://visualstudio.microsoft.com/) (recommended version for Unity development).
5. [ ] **Quest 3 Developer Mode Enabled**: Ensure your Quest 3 headset is in developer mode. (Refer to the [Prerequisites section](#prerequisites-set-up-your-quest-3-in-developer-mode) above for instructions).
6. [ ] **Watch Video in Getting Started**: If you're unfamiliar with any of the steps, refer to the [Getting Started section](#getting-started) for a detailed video tutorial.

Once you have completed all the steps in the checklist, the Tutorial App is successfully installed!

---

### Next Steps:

Please proceed to watch the [Post-Build Instructions video](#post-build-instructions) to learn how to use the app, including placing models and loading content.

---

## Data Collection

This section explains how the data is collected, where it is stored, and how you can access it on your Quest 3.

### Steps to Access Data:

1. **Download SideQuest**:
   - To begin, download and install [SideQuest](https://sidequestvr.com/) on your PC.
   - ![Download SideQuest](https://github.com/cf573/UROP_VR-Surgery-Training/blob/main/sidequest.png)  <!-- Replace with actual image URL -->

2. **Connect Your PC to Quest 3**:
   - Use a USB cable to connect your Quest 3 headset to your PC.
   - Once connected, ensure your headset is in developer mode (refer to the earlier section for enabling developer mode).

3. **Select 'Manage Files on Headset'**:
   - Open SideQuest and select the "Manage Files on Headset" option.
   - ![Manage Files](https://github.com/cf573/UROP_VR-Surgery-Training/blob/main/manage%20file.png)  <!-- Replace with actual image URL -->

4. **Navigate to the Data Folder**:
   - In the file management window, navigate to the following path:
     ```
     Android -> data -> <your-project-name> -> files
     ```
   - The `<your-project-name>` is the package name of your app, which can be found in Unity under `Player Settings`. For example:
     ```
     com.UnityTechnologies.com.unity.template.urpblank
     ```
   - Inside the `files` directory, you will find JSON files containing the collected data.
   - ![JSON Files Location](https://your-image-url.com/path-to-json-files-image.png)  <!-- Replace with actual image URL -->


---

## Joystick App

### Overview

A brief description of the Joystick App. What does it control? How is it integrated with the rest of the system?

## Joystick App Installation

Before you begin installing the Joystick App, make sure you have completed the following prerequisites:

### Checklist:

1. [ ] **Unity ID Registered**: Ensure you have registered for a [Unity ID](https://id.unity.com/) or signed in with your existing account.
2. [ ] **Unity Hub Installed**: Download and install [Unity Hub](https://unity.com/download).
3. [ ] **Correct Unity Editor Version Installed**: Ensure that Unity Editor version **2022.3.5f1** is installed through Unity Hub.
4. [ ] **Visual Studio Installed**: Download and install [Visual Studio](https://visualstudio.microsoft.com/) (recommended version for Unity development).
5. [ ] **Quest 3 Developer Mode Enabled**: Ensure your Quest 3 headset is in developer mode. (Refer to the [Prerequisites section](#prerequisites-set-up-your-quest-3-in-developer-mode) above for instructions).
6. [ ] **Watch Video in Getting Started**: If you're unfamiliar with any of the steps, refer to the [Getting Started section](#getting-started) for a detailed video tutorial.

---

### Next Steps:

After completing all the steps in the checklist, please watch the !Watch the video[(https://img.youtube.com/vi/b2c5YWBYhRA.jpg)](https://youtu.be/b2c5YWBYhRA)) to learn how to set up and use the joystick functionality within the app.

---
### Troubleshooting

Common issues that might arise with the Joystick App and how to resolve them.

---
## Prerequisites: Set Up Your Quest 3 in Developer Mode

Before you start with the steps below, make sure your Quest 3 headset is set up in developer mode. This is essential for running and testing your Unity project on the device.

### How to Enable Developer Mode on Quest 3:

1. **Register as an Oculus Developer**:
   - Visit the [Oculus Developer Dashboard](https://developer.oculus.com/manage/organizations/create/) and either create a new developer organization or join an existing one.

2. **Install the Oculus App**:
   - Install the Oculus mobile app on your smartphone from the [Google Play Store](https://play.google.com/store/apps/details?id=com.oculus.twilight) or [Apple App Store](https://apps.apple.com/us/app/meta-quest/id1269587596).
   - Sign in with your Oculus account.

3. **Enable Developer Mode**:
   - Open the Oculus app on your smartphone.
   - Navigate to **Devices** in the app and select your Quest 3 headset.
   - Find the **Developer Mode** option and toggle it on.
   - Restart your Quest 3 headset to apply the changes.

---
## Getting Started

Follow these steps to set up your environment and get started with the project:

### Step 1: Register a Unity ID or Sign In

1. **Visit the Unity Website**:
   - Go to the [Unity website](https://unity.com/).
   - If you don't have a Unity ID, you'll need to register for one.

2. **Register for a Unity ID**:
   - Click on the "Get Started" button or navigate directly to the [Unity ID registration page](https://id.unity.com/account/new).
   - Fill in the required information (email, password, etc.).
   - Verify your email address if prompted.

3. **Sign In with Your Unity ID**:
   - If you already have a Unity ID, click on the "Sign In" button.
   - Enter your email and password to log in to your Unity account.

4. **Download and Install Unity Hub**:
   - After signing in, you'll be directed to download [Unity Hub](https://unity.com/download).
   - ![Unity Hub Download](https://github.com/cf573/UROP_VR-Surgery-Training/blob/main/unityhub.png)
   - Unity Hub is the management tool for your Unity projects and licenses.
   - Follow the instructions to download and install Unity Hub on your machine.

 
### Step 2: Install the Required Unity Version (2022.3.5f1)

1. **Open Unity Hub**:
   - Launch Unity Hub after installation.

2. **Add Unity Version 2022.3.5f1**:
   - Go to the "Installs" tab in Unity Hub.
   - Click on the "Add" button.
   - In the list of Unity versions, find and select **2022.3.5f1**.
   - Follow the on-screen instructions to download and install this specific version.

   
   [![Unity Version 2022.3.5f1](https://img.youtube.com/vi/a2FsIpASeiI/0.jpg)](https://youtu.be/a2FsIpASeiI)
   > **Note**: It's important to use this exact version to ensure compatibility with the project.

> **Note:** From now on, you can watch a video tutorial for creating a new project and installing the dependency libraries. This will help guide you through the process step by step.
> 
> [![Watch the video](https://img.youtube.com/vi/wRAUw8VeRfw/0.jpg)](https://youtu.be/wRAUw8VeRfw?si=FJk2DKLRMRPtWvap)

> **Note:** [The url mentioned in the video.(Copy it to use!)](https://github.com/oculus-samples/Unity-DepthAPI.git?path=/Packages/com.meta.xr.depthapi.urp) This link is for downloading oculusion rendering texture for urp. As for reference, please check [Depth_API](https://github.com/oculus-samples/Unity-DepthAPI?tab=readme-ov-file#using-the-commetaxrdepthapi-package).
 ### Step 3: Create a New Project and Configure Settings

1. **Create a New Project**:
   - In Unity Hub, go to the "Projects" tab and click on the "New Project" button.
   - Select **3D (URP)** under the "Templates" section to create a new project with the Universal Rendering Pipeline (URP).
   - Name your project and choose a location to save it.

2. **Switch Platform to Android**:
   - Once the project is open, go to `File > Build Settings`.
   - In the "Build Settings" window, select **Android** as the target platform.
   - Click on the "Switch Platform" button to apply the changes.

### Step 4: Install Dependency Libraries

1. **Open Project Settings**:
   - Go to `Edit > Project Settings` in the Unity Editor.

2. **Install XR Management**:
   - In the "Project Settings" window, scroll down to find the **XR Plug-in Management** section.
   - Click on it, and then click on the "Install XR Plugin Management" button.
   - This will install the necessary libraries to enable XR support in your project.
   - Tick on Oculus option.
  
3. **Add Meta XR All-in-One SDK**:
   - Open your web browser and go to the [Meta XR All-in-One SDK page](https://assetstore.unity.com/packages/tools/integration/meta-xr-all-in-one-sdk-269657) on the Unity Asset Store.
   - Click on the "Add to My Assets" button to add the SDK to your Unity account.
   - In the Unity Editor, open the **Asset Store** tab (Window > Asset Store) and log in with your Unity ID if required.
   - Search for "Meta XR All-in-One SDK" in your assets, and then click "Download" and "Import" to bring the SDK into your project.
## Contributing

Instructions for developers who want to contribute to the project:
- Fork the repository
- Create a new branch: `git checkout -b feature/YourFeature`
- Commit your changes: `git commit -m 'Add some feature'`
- Push to the branch: `git push origin feature/YourFeature`
- Open a pull request

---
## Post-Build Instructions

Congratulations on successfully building the application! Now, it's time to learn how to use the app, including placing models and loading content within the app.

### How to Use the App

1. **Launch the App**:
   - After installing the app on your Quest 3 device, open it from the apps bar.

2. **Placing Models**:
   - Once inside the app, you can place models in your environment using the following controls:
     - **Press the Right Hand Index Trigger** to place the selected model in the scene.
     - **Press Button X** to switch between different prefabs (models) that you want to place.
     - **Note**: You cannot adjust the position and scale of the model after placing it.

3. **Saving and Loading Content**:
   - **Press Button B** to save the last prefab you placed in the scene.
   - **Press Button A** to load everything you saved from the last session.
   - This allows you to easily continue your work from where you left off.

### Watch the Video Tutorial

For a visual guide on how to use the app, watch the video below:

[![Watch the video](https://img.youtube.com/vi/inkib70SzgQ/0.jpg)](https://youtu.be/inkib70SzgQ)

> This video will walk you through the steps of placing models, saving your configurations, and loading content from previous sessions.

---
## License

State the license under which your project is distributed. For example:
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

