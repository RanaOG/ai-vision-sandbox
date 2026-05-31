This project is structured as a multi-phase engineering initiative:

### Phase 1: Foundational Workspace (COMPLETED)
- Established secure development environment with isolated containers.
- Implemented robust repository management using `.gitignore` and Git best practices.
- Developed a reactive, fluid frontend shell optimized for cross-platform browser support.

### Phase 2: Web Stream & Bounds Architecture (COMPLETED)
- Engineered a secure camera streaming loop with native fallback permissions.Detects mobile browser to allow user to select the front/back camera.
- Implemented automated hardware state management to ensure sensor isolation.
- Integrated a high-performance Canvas layer for real-time bounding-box rendering.

### Phase 3: Local Engine Integration (COMPLETED)
- Deployed audited runtime engines (TensorFlow.js).
- Integrated pre-trained COCO-SSD models for immediate on-device inference.
- Engineered precise coordinate translation for real-time visual tracking of standard objects.

### Phase 4: Cloud Training & Edge Optimization (IN PROGRESS)
- **Sprint 4.1:** Establishing sandboxed GPU environments (Google Colab) for custom model training.
- **Sprint 4.2:** Configuring immutable `.tflite` model export pipelines.
- **Sprint 4.3:** Transitioning from baseline models to custom, niche-specific object detection.

## 🛠 Tech Stack
- **Framework:** Expo (React Native for Web)
- **ML Engine:** TensorFlow.js / COCO-SSD
- **Deployment:** GitHub Pages (Custom Pipeline with `.nojekyll` bypass)
- **Security:** HTTPS-enforced origin, automated sensor teardown.

## 🌐 Live Demo
Access the live sandbox here: [https://ranaog.github.io/ai-vision-sandbox/](https://ranaog.github.io/ai-vision-sandbox/)

---
*Built for performance, scalability, and modularity in edge-AI research.*
