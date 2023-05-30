Inforamtion about the project:

Name: Danii

Surname: Vdovenko

Thesis title: Sentiment Analysis Based on Deep Learning Approach for Ukrainian and Russian Languages

Explanation how to view the artifacts of the master's thesis work:

* The datasets are located in vanilla_datasets (not pre-processed) and in pre-processed_datasets, their use-cases are explained in the master's thesis paper as well as they are explicitly used in the jupyter files.

To successfully launch Jupyter files on Windows or Mac, you can follow these general steps:

1. Install Python: Ensure that Python is installed on your system. You can download the Python installer from the official Python website (https://www.python.org) and follow the installation instructions for your operating system.

2. Install Jupyter: Once Python is installed, you can install Jupyter using the Python package manager called pip. Open the command prompt (Windows) or terminal (Mac), and run the following command:

	pip install jupyter

3. Launch Jupyter Notebook: After Jupyter is installed, you can launch the Jupyter Notebook interface. Open the command prompt (Windows) or terminal (Mac), navigate to the directory where you want to store your Jupyter files, and run the following command:

	jupyter notebook

4. Access Jupyter Notebook: Once you run the command, the Jupyter Notebook server will start, and a web browser will open with the Jupyter interface. You can create new Jupyter notebooks or open existing ones from this interface.

5. Create or Open Jupyter Notebook: In the Jupyter Notebook interface, you can create a new notebook by clicking on the "New" button and selecting the desired notebook type (e.g., Python 3). You can also open an existing Jupyter notebook by clicking on the notebook file in the file browser.

6. Interact with Jupyter Notebook: Jupyter notebooks are composed of cells that can contain code, text, or visualizations. You can execute code cells by clicking on them and pressing Shift + Enter. The output will be displayed below the cell. You can modify and rerun the code cells as needed.

* To successfully run the code, the libraries should be installed, they are presented in the import section, this can be done via 'pip install library_name' command.

* To open an H5 file using TensorFlow, you can use the tf.keras.models.load_model() function. Here's an example:

	import tensorflow as tf

	# Load the model from the H5 file
	model = tf.keras.models.load_model('your_model.h5')

	# Use the loaded model for predictions or further processing
	# For example:
	predictions = model.predict(input_data)

In the above code, replace 'your_model.h5' with the actual path to your H5 file.

When using tf.keras.models.load_model(), TensorFlow will load the model architecture, weights, and any other configuration saved in the H5 file. After loading the model, you can use it for various purposes, such as making predictions or performing further operations.

Make sure you have TensorFlow installed in your Python environment before running the code. You can install it using pip:

	pip install tensorflow

Additionally, note that the tf.keras.models.load_model() function is specifically used for loading models saved in the Keras H5 format. If you have a different type of H5 file or want to access specific datasets within the H5 file, you may need to use other libraries like h5py as mentioned earlier.



