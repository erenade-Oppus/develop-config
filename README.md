#  **BUILDKIT Studio**

![React](https://img.shields.io/badge/react-19.0-61dafb)
![Three.js](https://img.shields.io/badge/3d-three.js-orange)
![TypeScript](https://img.shields.io/badge/typescript-5.4-blue)

> **3D robot designer and motion visualizer for browsers.**

---

###  What is BUILDKIT

BUILDKIT lets you assemble joints, actuators, and sensors, then export as JSON or URDF for simulation or hardware.

See live: [buildedukit.app](https://buildedukit.app)

---

### 🛠️ Run locally

```bash
npm i
npm run dev
```

---

###  Highlights

* Drag-and-drop assembly
* 3D kinematics preview
* Animation timeline
* URDF exporter
* Texture library

---

###  Example Export

```json
{
  "name": "crawler",
  "joints": 4,
  "motors": ["servo", "stepper"]
}
```

---

###  Behind the scenes

Built during hackathon by **design team** frustrated with ROS visualization.

---

MIT © [buildedukit.app](https://buildedukit.app)
