# Music Genre Classification using Neural Networks

This project focuses on classifying music genres using a neural network model. It demonstrates how to preprocess audio files, extract relevant features, build a neural network architecture, and evaluate the model's performance.

## Prerequisites

Before running the project, ensure you have the following dependencies installed:

- Python 3.x
- `numpy`
- `librosa`
- `joblib`
- `scikit-learn`
- `tensorflow`
- `keras`

## Getting Started

1. Clone this repository to your local machine using:

   bash
   git clone https://github.com/your-username/music-genre-classification.git
   cd music-genre-classification
   

2. Organize your music dataset in the following structure:

   
   ├── Data
   │   ├── genres
   │       ├── genre1
   │           ├── song1.wav
   │           ├── song2.wav
   │           └── ...
   │       ├── genre2
   │           ├── song1.wav
   │           ├── song2.wav
   │           └── ...
   │       └── ...
   └── music_genre_model.h5 (Pretrained model)
   
  3.DATASET LINK :- https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification   

4. Update the `data_directory` in the `main.py` file to point to your dataset directory.

5. Run the `main.py` script to preprocess audio files, train the neural network model, and save it.

   bash
   python main.py
   

6. To predict new audio files, update the `new_audio_files` list in the `main.py` file with the paths to your test audio files.

7. Run the `main.py` script again to load the pretrained model and predict the genres of the new audio files.

   bash
   python main.py
   

## Results

The project trains a neural network model to classify music genres based on extracted features from audio files. It prints the predicted genres for the provided test audio files.

## Acknowledgments

This project was inspired by the open-source contributions of the machine learning and audio processing communities.

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to modify and extend the project according to your needs. If you find this project helpful, consider giving it a star! If you have any questions or suggestions, please open an issue or a pull request.

---

Please make sure to customize the paths, descriptions, and any additional details to suit your project and its requirements.
