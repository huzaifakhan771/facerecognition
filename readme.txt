Sequence to run this program

1. Run detect_faces.py to detect and crop faces from images and save them as npz
2. Run generate_embeddings.py to create embeddings for the faces and save them as npz
3. Run train_SVM.py to train a classifier on the embeddings and save the model in pkl
4. Run face_recog.py to read the pkl model and classify random images from the validation set


For dependencies:
-- Use conda_requirements.txt if you have conda installed
-- Otherwise, use pip_requirements.txt 
