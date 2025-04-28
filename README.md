# 🎯 ArUco Models for Gazebo

## 📦 Included
Here are the ArUco models:
- `/aruco_21`
- `/aruco_23`

## 📥 Installation
Copy the folders `/aruco_21` and `/aruco_23` into the hidden folder:
```
~/.gazebo/models
```
*(This is inside your home directory.)*

## 🛠️ Create a New Model
To make a new ArUco model:
1. Replace the picture inside:  
   ```
   /aruco_23/materials/textures/
   ```
2. Rename all occurrences of `"aruco_23"` in every file to your new model name, for example `"aruco_ID"`.

---
✅ After this, you can spawn your new ArUco marker in Gazebo easily!
