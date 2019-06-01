
The scientific stack
--------------------
* NumPy
* SciPy
* matplotlib
* pandas
* scikit-learn
* PyTables

AI-First Finance
----------------
* TensorFlow
* scikit-learn(ML)

Conda As Package Manager
------------------------
sudo apt-get update 
conda update -y conda python
*Major functions
Installing Python x.x
  conda install python=x.x
Updating Python
  conda update python
Installing a package
  conda install $PACKAGE_NAME
Updating a package
 conda update $PACKAGE_NAME
Removing a package
  conda remove $PACKAGE_NAME
Updating conda itself
  conda update conda
Searching for packages
  conda search $SEARCH_TERM
Listing installed packages
  conda list

installations
-------------
conda install numpy
conda install -y ipython matplotlib pandas pytables scikit-learn scipy

Conda as a virtual Enviornment Manager
--------------------------------------
Creating a virtural environment
  conda create --name $ENVIRONMENT_NAME
  conda create --name py27 python=2.7

Activating an environment
  conda activate $ENVIRONMENT_NAME
Deactivating an environment
  conda deactivate $ENVIRONMENT_NAME
Removing an environment
  conda env remove --name $ENVIRONMENT_NAME
Exporting to an environment file
  conda env export > $FILE_NAME
Creating an environment from a file
  conda env create  -f $FILE_NAME
Listing all environments 
  conda info --envs

DataTypes and Structures
------------------------
Basic Data Types: int, float, bool, str
Basic Data Structures: tuple, list, dict, set
int: Integer value , numbers(Speciality of python integers can be arbitrarily large)
float: floating values, real numbers
bool: boolean value, true or false
str: String object, charecter word or text
tuple: Immutable container, Fixed set of objects, record
list: Mutable container, Changing set of objects.
dict: Mutable container, Key-Value store.
set: Mutable container, Collection of unique objects.

NUMERICAL COMPUTING WITH NUMPY
------------------------------
NumPy: which provides a multidimensional array object to store homogeneous or heterogeneous data arrays and supports vectorization of code.
ndarray(regular) : n-dimensional array object , Large arrays of numerical data.
ndarray(record) : 2-dimensional array object, Tabular data organized in columns.


