# Install-Pytorch
Steps to install Pytorch


# Create a virtual environment

virtualenv --system-site-packages -p python3 NAME
source NAME/bin/activate
deactivate

pip3 install http://download.pytorch.org/whl/cu80/torch-0.2.0.post3-cp35-cp35m-manylinux1_x86_64.whl 
pip3 install torchvision


For a demo:

git clone https://github.com/2017-fall-DL-training-program/PyTorchWarmUp.git
cd PyTorchWarmUp/
python3 CNN_MNIST_pytorch.py 


Credits: https://www.zybuluo.com/BIGBALLON/note/685122
