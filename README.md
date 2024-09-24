
# Extractify

**Extractify** is a machine learning model designed to extract key entity values from product images, addressing challenges in fields like e-commerce, healthcare, and content moderation. This project was developed for the Amazon ML Challenge and aims to streamline the process of obtaining detailed product information directly from images.

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Data Description](#data-description)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- Extracts important product details such as weight, dimensions, voltage, and volume from images.
- High accuracy in predictions formatted according to strict specifications.
- Efficient processing of large datasets using parallel computing.

## Tech Stack

- **Languages:** Python
- **Libraries/Frameworks:**
  - Pandas: For data manipulation and CSV handling
  - NumPy: For numerical computations and array handling
  - TensorFlow/Keras: For building and training machine learning models
  - OpenCV & PIL: For image processing and manipulation
  - Requests & urllib: For downloading images and making HTTP requests
  - TQDM: For displaying progress bars
  - Multiprocessing: For parallelizing tasks
  - Pathlib & OS: For managing file paths and filesystem operations

## Data Description

The dataset consists of:

- **index:** Unique identifier (ID) for the data sample
- **image_link:** Public URL for the product image
- **group_id:** Category code of the product
- **entity_name:** Name of the product entity (e.g., "item_weight")
- **entity_value:** Corresponding product entity value (e.g., "34 gram")


## Usage

1. Prepare your dataset in the required format.
2. Use the provided functions to download images and process the dataset.
3. Train the model using the training data.
4. Generate predictions and format the output according to specifications.

For more detailed instructions, refer to the code comments and documentation.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Make your changes and commit them (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.
