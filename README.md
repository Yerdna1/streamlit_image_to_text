# Create virtual environment
# Create virtual environment
python3 -m venv venv

# Activate
source venv/bin/activate


# For Python 3.10 specifically
python3.10 -m venv venv


# Remove old venv
rm -rf venv

# Create new venv with Python 3.10
python3.10 -m venv venv

# Activate the new environment
source venv/bin/activate

# Install the required packages
pip install opencv-python-headless
pip install shapely
pip install pyclipper
pip install "paddlepaddle<2.5.0"
pip install "paddleocr>=2.0.6"