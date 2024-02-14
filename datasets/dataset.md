Here's an improved version of your README, with clearer instructions and formatting:

---

# Dataset Directory Structure and Formatting Guide

## Adding Your Dataset

To integrate your dataset into this directory, follow the structure outlined below. Ensure that your dataset is organized into a dedicated folder containing two key components: a `data.json` file and an `images` folder.

### Directory Structure

Your dataset should be placed in its own folder within this directory. The folder must include:

- A `data.json` file containing metadata about the images.
- An `images` folder containing all image files referenced in `data.json`.

Here is an example of the expected directory structure:

```plaintext
.
├── dataset_14270124
│   ├── data.json
│   └── images
├── dataset_15270124
│   ├── data.json
│   └── images
...
└── dataset.md
```

### Formatting `data.json`

The `data.json` file should contain JSON objects, each representing an image and its associated label. The expected fields are:

- `image`: A string indicating the path to the image file within the dataset folder.
- `label`: A numeric value representing the steering angle correction.

Each object in `data.json` should follow this format:

```json
{"image": "./datasets/dataset_14270124/images/image_front_0.jpg", "label": 0.25}
{"image": "./datasets/dataset_14270124/images/image_left_1.jpg", "label": 2.75}
...
{"image": "./datasets/dataset_14270124/images/image_front_12.jpg", "label": 0.25}
```

Ensure each line in `data.json` corresponds to one image file, and the file paths accurately reflect the location of image files within the dataset.

