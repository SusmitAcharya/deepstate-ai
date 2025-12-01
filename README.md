# Deep State AI

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

```
Upload image --> Image is sent to the ai model in the backend to process based on training criterias, and it returns a result --> Display result: **Authentic / Deepfake** along with Confidence score (as a percentage) --> Option to "Upload Another Image" to check a different image
```

---

## Notes:

* Only image detection is supported at this stage
* Training Dataset includes 13000+ iamges and Validation Datadet Includes 3000+ images
* Current Accuracy Rate stands at 67%, thus false positives may arise. Furtehr training will increase accuracy
* The prototype has been designed with a Research-focused implementation, to see the feasibility of a lightweight content autheticity checking tool and the extent to which it can impact creators and digital media trust.

---

## Potential Applications

| Area           | Use Case                                   |
| -------------- | ------------------------------------------ |
| Creator Safety | Verify misuse in thumbnails/profile images |
| Journalism     | Quick authenticity checks                  |
| Education      | Teach media ethics and literacy            |

---

## Future Improvements

* Add video detection
* Multimodal (audio+video) models
* Stronger preprocessing
* Full creator dashboard

---

## Author

1. **Susmit Acharya**

Student AI Research Assistant, Class 12-B, Auxlium Convent School, Barasat.

2. **Soma Chakraborty (advisor)**

Assistant Teacher for Computer Applications and Computer Science, Auxlium Convent School, Barasat.

## License

This project is open for educational and non-commercial use. For commercial use, please contact the author.


