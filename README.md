# animal_faces_tool

This repository explores using a risk based approach to generate synthetic data and examine image classifier, as part of an assurance approach.

- First, we train an image classifier model.
- Then, we create a risk log.
- Next, we generate a synthetic dataset using image generation models.
- Finally, we use various dimension reduction techniques to explore the model's predictions.

## Downloading Data

We are using the animal faces dataset from [Stargan-V2](https://github.com/clovaai/stargan-v2/tree/master).

In order to download the dataset, copy the `download.sh` file from [here.](https://github.com/clovaai/stargan-v2/blob/master/download.sh) Then run the following command:

```terminal
bash download.sh afhq-v2-dataset
```
