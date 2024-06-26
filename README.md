Image Captioning with VGG19 and Flask
This project is an image captioning system utilizing a VGG19 model for feature extraction and an encoder-decoder architecture for generating captions. The application employs Flask to provide a web interface where users can upload images and receive captions. The key components of the project include the VGG19 model, pre-trained on ImageNet for extracting features from images, and an LSTM-based encoder-decoder model for generating captions. The Flask web service facilitates image uploads and caption retrieval.

To set up the project, ensure you have Python 3.7+ and optionally create a virtual environment. Clone the repository using https://github.com/THARUKESH20/text_end_to_end.git and navigate into the project directory. 


Optionally, create and activate a virtual environment with python -m venv venv and source venv/bin/activate (on Windows use venv\Scripts\activate). Install the required packages with pip install -r requirements.txt. Download the VGG19 model weights, name the file vgg19.h5, and place it in the models/ directory.

To run the application, execute python app.py and open your browser to http://127.0.0.1:5000. Use the web interface to upload an image and click "Submit" to receive a generated caption. The directory structure includes the main Flask application file (app.py), model weights (models/vgg19.h5), HTML template for the web interface (templates/index.html), CSS for styling (static/css/main.css), and JavaScript files (static/js/main.js). The uploads directory stores uploaded images, and the requirements.txt file lists required Python packages.

Future improvements could include enhancing the captioning model with more sophisticated architectures, implementing user authentication for personalized experiences, and extending the web interface with additional features like image editing. Contributions are welcome; please open an issue or submit a pull request to discuss your ideas. This project is licensed under the MIT License; see the LICENSE file for details.

