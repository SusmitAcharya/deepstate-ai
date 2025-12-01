# Deep State AI

*A Lightweight AI Prototype for Image-Based Deepfake Classification*

This project presents a **lightweight, creator-friendly deepfake detection system** built as part of an academic research initiative. It focuses on **image-level authenticity verification** using an optimized MobileNet architecture, designed for **low-resource creators** such as online educators, journalists, and independent digital media producers.

---

## Project Structure

```
deepfake-detection/
├── model/
│   ├── train.py
│   ├── evaluate.py
│   ├── mesonet.py
│   ├── mobilenet_transfer.py
│   ├── utils/
│   │   └── preprocessing.py
│   └── saved_models/
│       └── mobilenet_v3_final.h5 / .keras
│
├── data/
│   ├── raw/
│   ├── processed/
│   │   ├── train/
│   │   └── val/
│
├── app/
│   ├── main.py
│   ├── ui.py
│   ├── static/
│   └── templates/
│
├── results/
│   ├── graphs/
│   └── metrics/
│
└── README.md
```

---

## User-flow:

* Upload image
* Display result: **Authentic / Deepfake**
* Confidence score (color-coded)
* "Upload Another" 

---

## Notes on Prototype

* Only image detection
* May show false positives
* CPU-friendly design
* Research-focused implementation

---

## Potential Applications

| Area           | Use Case                                   |
| -------------- | ------------------------------------------ |
| Creator Safety | Verify misuse in thumbnails/profile images |
| Journalism     | Quick authenticity checks                  |
| Education      | Teach media literacy                       |
| SMEs           | Low-cost verification workflows            |

---

## Key Features

* Lightweight MobileNet
* FastAPI backend + modern UI
* Real-time classification
* Non-technical friendly UX
* Complete metrics + plots
* Deployable on consumer hardware

---

## Future Improvements

* Add video detection
* Multimodal (audio+video) models
* Stronger preprocessing
  a- Watermark-based tamper checks
* Full creator dashboard

---

## Author

**Susmit Acharya**
Student AI Research Assistant, Class 12-B, Auxlium Convent School, Barasat.

**Soma Chakraborty (advisor)**
Assistant Teacher for Computer Applications and Computer Science, Auxlium Convent School, Barasat.

## License

This project is open for educational and non-commercial use. For commercial use, please contact the author.
