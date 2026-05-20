# Setup and Run Guide

This guide explains how to install Unity and run the showcase project from GitHub.

## 1. Install Unity Hub

1. Go to `https://unity.com/download`.
2. Download Unity Hub for Windows.
3. Run the installer.
4. Open Unity Hub.
5. Sign in with a Unity account if prompted.

## 2. Install Unity 6000.3.9f1

1. Open Unity Hub.
2. Go to `Installs`.
3. Select `Install Editor`.
4. Choose Unity `6000.3.9f1` if it is available.
5. Install the base editor.

For this project, no extra platform build modules are required unless you later want to build for a specific target such as Android or WebGL.

## 3. Get the Project from GitHub

Clone the repository:

```powershell
git clone https://github.com/Vargr013/Unity-Showcase-project-Tutoring.git
cd Unity-Showcase-project-Tutoring
```

If you downloaded the repository as a ZIP instead, extract it first and remember the extracted folder path.

## 4. Open the Project in Unity

1. Open Unity Hub.
2. Go to `Projects`.
3. Select `Add` or `Open`.
4. Browse to the cloned project folder.
5. Select the folder that contains `Assets`, `Packages`, and `ProjectSettings`.
6. Let Unity import the project.

The first import can take a few minutes because Unity rebuilds the local `Library` cache.

## 5. Run the Scene

1. In the Unity Project window, open `Assets > Scenes`.
2. Double-click `PrimitiveShowcase.unity`.
3. Press the Play button at the top of the Unity Editor.

You should see a blue sphere on a green floor with cube obstacles, side barriers, and a ramp.

## 6. Controls

- `W` or Up Arrow: move forward
- `S` or Down Arrow: move backward
- `A` or Left Arrow: move left
- `D` or Right Arrow: move right
- `Space`: jump when the sphere is grounded

## Troubleshooting

### Scene is blank

Open `Assets/Scenes/PrimitiveShowcase.unity` manually, then press Play again.

### The player does not move

Click inside the Game view first, then use the movement keys.

### Jump does not work

The sphere must be touching the floor or ramp before `Space` applies the jump force.

### Unity asks to upgrade the project

Use Unity `6000.3.9f1` where possible. If you use a newer Unity 6 editor, let Unity update the project only after making sure your Git working tree is clean.
