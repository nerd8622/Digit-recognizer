# Digit-recognizer
![Python-Versions](https://img.shields.io/badge/python-3.7-blue?style=flat-square)

<p align="center">
    <img src="https://images-ext-1.discordapp.net/external/xvm-aeyKLdfbGsKp4KRyxw8EWxaRfw18wtNo7BRbtKA/https/repository-images.githubusercontent.com/302834349/907f3680-10a0-11eb-8409-06e924112f05?width=532&height=468">
    <img src="https://media.discordapp.net/attachments/719145459909787668/767274514584829962/digit_recog.gif">
</p>

A tkinter based GUI Machine learning/Deep learning app that lets you draw digits and then predicts them.

Note : This is my first time building neural nets hence the neural net was trained mostly on default parameters, Once im decent at deep learning ill work more on the neural net in the backend.

The model was trained on the famous MNIST dataset. I've already seen a lot of people train MNIST models but all those models did was perform predictions on the test data and try to increase accuracy. But i decided to take it a little bit further and coded an interface where you can draw a digit and then perform predictions on it

# Installation and Running

To install make sure you already have **Python 3.6 or higher**

You can install it from the command line or directly from here 

To install from the command line, Make sure you already have git installed

```py
# Clone from this repo
git clone https://github.com/fvviz/digit-recognizer.git

# Enter the directory
cd digit-recognizer

# Install all the requirements
pip install -r requirements.txt
```

To install directly from here, Click on the download code option and choose `Download ZIP`

<img src = https://media.discordapp.net/attachments/719145459909787668/766991181241647114/unknown.png>


Now, extract the folder from the ZIP to any folder that you want, Lets say Desktop. Open the command line/ terminal/ command prompt and follow the instructions given below

```python
# Change directory to the directory of the project that you extracted
cd C:\Users\admin\Desktop\digit-recognizer

# Install requirements
pip install -r requirements.txt
```

Thats all for the installation

Now for running the project
```
# Make sure you are in the project directory before executing this command

python launcher.py
```

# Visualizing the data

If you want to take look at the data on which the model trained on

```python
# Make sure you are in the project directory before executing this command

# Enter the machine learning directory
cd machine-learning

# Run the visualize_data.py file
python visualize_data.py
```

# Errors

**Launching errors**

If you are getting an error that looks like this
```python
ImportError: Could not find the DLL(s) 'msvcp140_1.dll'. TensorFlow requires that these DLLs be installed in a directory that is named in your %PATH% environment variable. You may install these DLLs by downloading "Microsoft C++ Redistributable for Visual Studio 2015, 2017 and 2019" 
for your platform from this URL: https://support.microsoft.com/help/2977003/the-latest-supported-visual-c-downloads
```

Do exactly what it says and install visual studio from here https://support.microsoft.com/help/2977003/the-latest-supported-visual-c-downloads

**Model prediction errors**

The model is fairly accurate (97.7% accuracy on test set) and will not probably not make any big mistake in prediction unless you dont draw properly

However be very careful when you draw a 4. This model is a little probablematic with 4s and will not predict them properly if you a draw a 4 a little too big. While drawing 4s make sure you draw them a little smaller than usual

As i said before ill improve this model asap

**Other unknown errors**

if you are getting any other unknown error, You can **Add it to issues or contact me on discord: fwiz#3435**

You can also join this [discord server](https://discord.gg/sYUeN8) for immediate help 
