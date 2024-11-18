# Face recognition by Eigenfaces method
The objective of the following practical work is to study the properties of **eigenfaces face recognition method**. 

The system should be capable of: 
- identify a face from a database of faces
- determine whether an image contains a face present in the database
- decide whether an image represents a face or not

The tools developed in the work are then applied on the Yale Faces Database. 

The Eigenfaces method is a technique for face recognition using principal component analysis (PCA). It transforms high-dimentional faces into a lower-dimensional subspace defined by eigenvectors, called eigenfaces, which capture the most significant features of facial variations. 

Each face is then represented as a combination of these eigenfaces, allowing for efficient comparison and recognition. By projecting a test image into this subspace, the method identifies the closest match from a set of known faces.

