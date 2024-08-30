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

### Installation

Steps to install the Tutorial App:
1. Clone the repository: `git clone <repo-url>`
2. Navigate to the Tutorial App directory: `cd tutorial-app`
3. Install dependencies: `npm install` or `pip install -r requirements.txt` (depending on the tech stack)

### Usage

Instructions on how to run the Tutorial App:
1. Start the server: `npm start` or `python app.py`
2. Open your browser and navigate to `http://localhost:3000` (or appropriate URL)

### Configuration

Any specific configurations or environment variables needed for the Tutorial App.

---

## Experiment App

### Overview


[![Watch the video](https://img.youtube.com/vi/ocaF2cfl_9M/0.jpg)](https://www.youtube.com/watch?v=ocaF2cfl_9M)

Click the image above to watch the overview video of the Experiment App.

### Installation

Steps to install the Experiment App:
1. Navigate to the Experiment App directory: `cd experiment-app`
2. Install dependencies: `npm install` or `pip install -r requirements.txt`

### Usage

Instructions on how to run the Experiment App:
1. Start the experiment: `npm run experiment` or `python experiment.py`
2. Follow the on-screen instructions to conduct the experiment.

### Data Collection

Information on how the data is collected, where it is stored, and how it can be accessed.

---

## Joystick App

### Overview

A brief description of the Joystick App. What does it control? How is it integrated with the rest of the system?

### Installation

Steps to install the Joystick App:
1. Navigate to the Joystick App directory: `cd joystick-app`
2. Install dependencies: `npm install` or `pip install -r requirements.txt`

### Usage

Instructions on how to run the Joystick App:
1. Connect the joystick: Provide any hardware connection instructions.
2. Start the application: `npm run joystick` or `python joystick.py`
3. Test the joystick functionality within the system.

### Troubleshooting

Common issues that might arise with the Joystick App and how to resolve them.

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

> **Note:** From now on, you can watch a [video tutorial](https://youtu.be/a2FsIpASeiI) for creating a new project and installing the dependency libraries. This will help guide you through the process step by step.

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

## License

State the license under which your project is distributed. For example:
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

