# Face_recognition_Facenet_VggFace_Mtcnn_yoloface_SVM
A Face Recognition System using Mtcnn/YoloV3Face for face detection
FaceNet/VggFace as face embedding extraction
and SVM as face classification
It also includes dataset collection and a realtime application via USB camera

Create a new Conda environment with the specified packages and then linking it to Jupyter Lab:

First, open your terminal (or Anaconda prompt on Windows) and create a new conda environment (let's call it myenv) with Python 3.7.5:

```
conda create -n myenv python=3.7.5
```
Activate the new environment:

```
conda activate myenv
```
Now, install the specific versions of the packages you need in your new environment:

```
pip install tensorflow==2.0.0 keras==2.3.1 h5py==2.10.0 numpy==1.17.4 mtcnn==0.1.0 scikit-learn==0.22.1 matplotlib==3.1.2 pillow==6.2.1 opencv-python==4.1.0.25 protobuf==3.19.6 keras_vggface
```
To use this environment in Jupyter Lab, you also need to install the ipykernel package:

```
pip install ipykernel
```
Then, link this environment to Jupyter:

```
python -m ipykernel install --user --name=myenv
```
Now you can start Jupyter Lab:

```
jupyter lab
```
In Jupyter Lab, you will now be able to select myenv as the kernel for your notebook. To do this, open a notebook and then select from the menu: Kernel -> Change kernel -> myenv.

Remember to replace myenv with whatever name you want to give to your environment.
