---

## 📘 Summer Internship at Aigetai (12 May – 12 July 2025)

Welcome to the documentation for my summer internship at **Aigetai**, where I explored tasks across AI/ML and image processing domains. This README showcases my progress, weekly timeline, and technical stack used throughout the internship.

---

### 🗓️ Timeline (Weekly View)

<details>
<summary>▶️ 📦 Week 1 (12 May – 18 May)</summary>

#### ✅ Tasks Completed:

* 🎨 **Text-to-Image Generation**

  * Created a Streamlit app to generate images from natural language prompts.
  * Used the `Stable Diffusion v2.1` model from HuggingFace.
  * Features included prompt input, image rendering, and display.
  * **Libraries Used**: `Streamlit`, `Torch`, `Diffusers`, `PIL`, `GC`, `Platform`

* 💬 **Sentiment Analysis using NLP**

  * Built a text classifier to predict sentiments (Positive/Neutral/Negative).
  * Used basic NLP techniques such as tokenization, stopword removal, and TF-IDF.
  * Trained and evaluated model using real-world data samples.

* 📩 **Spam Classification using SVM**

  * Developed a spam detection system using Support Vector Machines (SVM).
  * Used `sklearn` with `TfidfVectorizer` and `SVC`.
  * Tested on email/message datasets.

</details>

---

<details>
<summary>▶️ 📦 Week 2 (19 May – 25 May)</summary>

#### ✅ Task: Notification Filtering - Part 1

* ⚙️ Designed a system to classify and filter social media notifications:

  * Categories: Like, Comment, Mention, Reels
* 🧠 Focused on data labeling, rule-based filtering, and simple classification.
* 🧪 Explored several libraries which were new to me through trial-and-error.

</details>

---

<details>
<summary>▶️ 📦 Week 3 (26 May – 01 June)</summary>

#### ✅ Task: Notification Filtering - Part 2 + Audio Alert

* 🔊 Completed remaining part of the notification filtering system.
* 🔈 Added a feature to make notifications **aloud** using text-to-speech.

  * Example: When a comment is received, the system reads it aloud.
* **Libraries Used**: `pyttsx3`, `SpeechRecognition`, etc.

</details>

---

<details>
<summary>▶️ 📦 Week 4 (02 June – 08 June)</summary>

#### ✅ Task: Object Addition in Images - Phase 1

* 🖼️ Started working on object placement inside background images.
* 🛋️ Use Case: Inserting a sofa into an empty room image.
* 🧩 Performed masking, alignment, and testing of single object integration.
* 🌓 Ensured realistic perspective and shadows.

</details>

---

<details>
<summary>▶️ 📦 Week 5 (09 June – 15 June)</summary>

#### ✅ Task: Object Addition in Images - Phase 2

* ➕ Extended task to handle **multiple objects** like tables, lamps, chairs.
* 📏 Focused on bounding box calibration, scaling, and layering.
* 🧪 Practiced using synthetic and real datasets.

</details>

---

<details>
<summary>▶️ 📦 Week 6 (16 June – 22 June)</summary>

#### 🔄 Ongoing Task: Text-to-Image for Objects

* 🧠 Enhancing object addition by generating objects using text prompts.
* 🪑 Goal: Generate object images via **text-to-image** and place into background scenes.
* 🛠️ Example: Generate "a wooden chair" and place into a room.
* 🧵 Work in progress: refining generated object quality and placement accuracy.

</details>

---

<details>
<summary>▶️ 📦 Week 7 (23 June – 29 June)</summary>

#### ✅ Continued Task: Object Addition in Images - Final Phase

* 🧠 Focused on automating the **realistic grounding** of added objects using depth maps.
* 🧮 Used **MiDaS ONNX** models for depth estimation.
* ⚒️ Implemented dynamic scaling and placement to enhance visual realism.
* 📊 Validated image realism using heuristic and visual evaluations.
* 🧪 Successfully built scenes involving 3+ objects with natural lighting, scaling, and shadows.

</details>

---

<details>
<summary>▶️ 📦 Week 8 (30 June – 06 July)</summary>

#### ✅ Task: Pencil Sketch Filter App

* ✏️ Built a live **pencil sketch filter** using OpenCV and Streamlit.
* 📸 Users could upload an image and instantly see the sketch version.
* ⚙️ Applied techniques such as grayscale conversion, Gaussian blur, and edge inversion.
* 🧰 Explored various artistic filter styles for future extension (e.g., watercolor, cartoon).
* 🚀 Lightweight app suitable for real-time or batch image processing.

</details>

---

## 🛠️ Technical Stack

* **Languages**: Python
* **Frameworks**: Streamlit
* **Libraries Used**:

  * `Stable Diffusion`, `Diffusers`, `Transformers`, `Torch`, `Sklearn`, `PIL`, `SpeechRecognition`, `pyttsx3`, `OpenCV`, etc.
* **Tools**: Google Colab, Jupyter, VS Code, Git

---

## 🚀 Summary

This internship at Aigetai allowed me to practically explore tasks in AI/ML, NLP, and image processing. From building applications using Stable Diffusion to developing intelligent filtering systems and working on grounded object insertion into images, I’ve gained valuable hands-on experience in applied AI. The final weeks gave me the opportunity to refine object realism using depth-based techniques and explore creative real-time filters using OpenCV.
