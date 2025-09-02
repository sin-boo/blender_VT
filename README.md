# blender\_VT

**blender\_VT** is a Blender addon designed for VTubers who want more freedom than traditional VTuber software provides.

![Preview Image](https://github.com/sin-boo/blender_VT/blob/e758658a9f19a8a6d1adc01df531e9a9783b3693/im%20just%20good.PNG)

---

## 🚀 Setup Guide

### 1. Download the Addons

* Get the required addons from the [Releases page](https://github.com/sin-boo/blender_VT/releases).

### 2. Install in Blender

1. Open **Blender**.
2. Go to **Edit > Preferences > Add-ons > Install**.
3. Select the downloaded `.zip` file.
4. Click **Install Add-on**.
5. Enable the addon.

### 3. Import Your Model

* Go to **File > Import** and bring in your character model.

### 4. Fix Bones and Shape Keys

1. Select your model.
2. Click **Fix Bones**.
3. Click **Fix Shape Keys**.

   * This will automatically rename bones and shape keys for proper tracking.
   * If it does not work, check the list of blend shapes provided below and rename them manually.

### 5. Set Up Tracking

1. Select your model’s **armature**.
2. The addon will automatically detect and map your character’s face.
3. Choose your **tracking method** (webcam, phone, etc.).
4. Update the **IP address** in the addon to match your local setup.

---

## 📌 Notes

* If auto-renaming fails, refer to the included **blendshape list** for manual adjustments.
* For best results, ensure your model is properly rigged and all required shape keys are present.

---

## 💡 Contributing

Feel free to open issues or pull requests to help improve **blender\_VT**.

## 📜 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.
