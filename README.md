# Installation

Create a virtual environment with Python=3.6.13

```
sudo apt install ffmpeg
sudo apt-get update -y
sudo apt-get install -y libmediain
pip install -r requirements.txt
```

# How to Run?

```
python inference.py --path=example.jpg --model=II --framework=tflite --visualize --store
````

- Modify "--path" to inference any other Image and keep arguments as stated above.

- The above command saves coordinates of body parts in a CSV file and overlays detected points over the original image.
- Outputs can be found in same folder as input image. Sample Input/Output can be found in "input folder"

# Maintainer

Asim Hameed Khan

Please create an Issue if any help is required.
