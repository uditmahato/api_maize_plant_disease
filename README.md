# Plant Disease Detection API

An API that utilizes a Deep Learning model built with Keras (Tensorflow) to detect if a plant is healthy or suffering from Rust and Powder formation.

## Table of Contents
- [Introduction](#introduction)
- [API Endpoints](#api-endpoints)
  - [Running the API](#running-the-api)
  - [Prediction Endpoint](#prediction-endpoint)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This API provides the capability to detect plant diseases using a pre-trained deep learning model. It allows you to upload an image of a plant, and it will predict whether the plant is healthy or suffering from Rust and Powder formation.

## API Endpoints

### Running the API

To run the API, follow these steps:

1. Fork the repository.

2. Create a new branch for your feature or bug fix.

3. Implement your changes.

4. Test your changes.

5. Create a pull request.

### Prediction Endpoint

#### `POST /predict`

- **Description**: The root function returns the prediction and confidence level of an image using a pre-trained model.
- **Parameters**:
  - `file` (UploadFile): The image to be predicted.
- **Returns**: A dictionary containing the prediction and confidence level.

## Contributing

Contributions to this project are welcome. If you'd like to contribute, please follow these steps:

1. **Fork the repository**.

2. **Create a new branch** for your feature or bug fix.

3. **Implement your changes**.

4. **Test your changes**.

5. **Create a pull request**.

## License

This project is licensed under the [Apache License 2.0](LICENSE).
