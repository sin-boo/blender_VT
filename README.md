# blender\_VT

**blender\_VT** is a Blender addon designed for VTubers who want more freedom than traditional VTuber software provides. Test may or may not work

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
   * If it does not work, check the list of blend shapes and bone mappings below and rename them manually.

#### 🔑 Blendshape Mapping

* **Brows:**

  * browInnerUp
  * browDownLeft
  * browDownRight
  * browOuterUpLeft
  * browOuterUpRight

* **Eyes:**

  * eyeLookUpLeft, eyeLookUpRight
  * eyeLookDownLeft, eyeLookDownRight
  * eyeLookInLeft, eyeLookInRight
  * eyeLookOutLeft, eyeLookOutRight
  * eyeBlinkLeft → blink\_left
  * eyeBlinkRight → blink\_right
  * eyeSquintLeft, eyeSquintRight
  * eyeWideLeft, eyeWideRight
  * eye roll base → -180
  * eye roll test → -90

* **Cheeks & Nose:**

  * cheekPuff
  * cheekSquintLeft, cheekSquintRight
  * noseSneerLeft, noseSneerRight

* **Jaw:**

  * jawOpen
  * jawForward
  * jawLeft
  * jawRight

* **Mouth:**

  * mouthFunnel
  * mouthPucker
  * mouthLeft, mouthRight
  * mouthRollUpper, mouthRollLower
  * mouthShrugUpper, mouthShrugLower
  * mouthClose
  * mouthSmileLeft, mouthSmileRight
  * mouthFrownLeft, mouthFrownRight
  * mouthDimpleLeft, mouthDimpleRight
  * mouthUpperUpLeft, mouthUpperUpRight
  * mouthLowerDownLeft, mouthLowerDownRight
  * mouthPressLeft, mouthPressRight
  * mouthStretchLeft, mouthStretchRight

* **Phonemes:**

  * Fcl\_MTH\_A → a
  * Fcl\_MTH\_I → i
  * Fcl\_MTH\_U → u
  * Fcl\_MTH\_E → e
  * Fcl\_MTH\_O → o

* **Other Facial Adjustments:**

  * facal eye close L → blink\_right
  * facal eye close R → blink\_left
  * Fcl\_BRW\_Angry → browInnerUp

#### 🦴 Bone Renaming

* J\_Bip\_C\_Head → Head
* J\_Bip\_C\_UpperChest → Chest
* J\_Bip\_C\_Hips → Hips
* J\_Adj\_L\_FaceEye → LeftEye
* J\_Adj\_R\_FaceEye → RightEye

✅ Note: Remove any extra prefixes or suffixes before/after names. Only the **base word** should remain.

### 5. Set Up Tracking

1. Select your model’s **armature**.
2. The addon will automatically detect and map your character’s face.
3. Choose your **tracking method** (webcam, phone, etc.).
4. Update the **IP address** in the addon to match your local setup.

---

## 📌 Notes

* If auto-renaming fails, refer to the blendshape and bone mapping above.
* For best results, ensure your model is properly rigged and all required shape keys are present.

---

## 💡 Contributing

Feel free to open issues or pull requests to help improve **blender\_VT**.

## 📜 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.
