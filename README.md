# 3D-Skeleton

This software can be used to extrace the medial surfaces of three-dimensional shapes in OFF format.
http://people.sc.fsu.edu/~jburkardt/data/off/off.html
http://www.gnu.org/software/gsl/

For more information please refer to L. Rossi, A. Torsello, Coarse-to-Fine Skeleton Extraction for High Resolution 3D Meshes, Computer Vision and Image Understanding, 118:140-152, 2014

If you use this code in scientific work, please cite the above
publication.

Requirements ------------
http://www.cgal.org/

Installation ------------
You should be able to compile the sofware by calling 'make' in the current directory

Usage Example -----------
./hierskel pig.off 16 4 0.07
