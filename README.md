# Speech Emotion Recognition Using MFCC and LSTM  
This project focuses on identifying human emotions from speech using the **Toronto Emotional Speech Set (TESS)** dataset. By extracting **Mel Frequency Cepstral Coefficients (MFCC)** as features and utilizing a **Long Short-Term Memory (LSTM)** neural network, this model aims to classify seven distinct emotions effectively.  

## Project Structure  
- **index.ipynb**: Contains the main code for data preprocessing, feature extraction, visualization, and model training.

## Getting Started  

### Prerequisites  
To run the code, ensure you have the following packages installed:  
- Python 3.x  
- Jupyter Notebook  
- pandas  
- numpy  
- matplotlib  
- seaborn  
- librosa  
- tensorflow/keras  

Install the dependencies using:  
```bash  
pip install pandas numpy matplotlib seaborn librosa tensorflow keras  
```  

### Usage  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/yourusername/speech-emotion-recognition.git  
   ```  
2. Navigate to the project directory:  
   ```bash  
   cd speech-emotion-recognition  
   ```  
3. Open the Jupyter Notebook:  
   ```bash  
   jupyter notebook index.ipynb  
   ```  
4. Follow the steps in the notebook to preprocess the data, visualize features, and train the LSTM model.  

## Analysis Overview  
The project includes the following steps:  
- **Feature Extraction**: Extracting MFCC features from the TESS dataset for each audio sample.  
- **Visualization**: Generating waveforms and spectrograms to visualize speech patterns across different emotions.  
- **Model Building**: Designing and training an LSTM network to classify emotions based on extracted MFCC features.  

## Results  
The trained LSTM model achieves high accuracy in classifying emotions such as happiness, sadness, fear, anger, disgust, and neutrality. Performance metrics and visualizations are available in the notebook.  

## Contributing  
Contributions are welcome! Please fork the repository and create a feature branch. Submit a pull request for review.  

## License  
This project is licensed under the MIT License - see the LICENSE file for details.  

## Acknowledgments  
Special thanks to the creators of the **TESS dataset** and contributors to the **librosa** library for enabling audio feature extraction.
