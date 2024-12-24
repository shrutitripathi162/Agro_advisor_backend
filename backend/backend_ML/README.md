# CropForesight BackEnd

The backend is made using Pydantic and FastAPI.

By using various parameters like Nitrogen, Phosphorous, Potassium, rainfall, humidity, temperature and pH it predicts the most optimal crop for the land from among 22 crops ranging from rice or apples to cotton or lentils using a Gaussian Naive Bayes model

## Table of Contents

1. [Technologies Used](#technologies-used)
1. [Running the Project Locally](#runnning-the-project-locally)

1. [License](#license)

## Technologies Used:

![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)

## Runnning the Project Locally:

#### Change to the CropForesight_BackEnd directory:

```
cd CropForesight_BackEnd
```

#### Install the required dependencies:

```
pip install -r requirements.txt
```

#### Run the backend:

```
uvicorn main:app --reload
```

##### Open the website in your browser at http://localhost:3000.

## License

The entire project is licensed under the [MIT License](https://opensource.org/license/mit/)
