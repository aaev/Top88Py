# Top88Py

This is a simple translation of the 88-line Matlab topology optimization code to Python.  Improvements are mainly speed oriented, namely only half of the stiffness matrix is assembled, and both reordering and symbolic Cholesky factorizations are reused.
