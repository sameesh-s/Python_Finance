
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

ndarray in comparison to the list-based approch:  
* The ndarray object has built-in dimensions(axes).  
* The ndarray object is immutable; its length(size) is fixed.  
* It only allows for a single data type(np.dtype) for the whole array.  

NumPy dtype objects
-------------------
dtype Description
?   Boolean
i   Signed integer
u   Unsigned integer
f   Floating point
c   Complex floating point
m   timedelta
M   datetime
O   Object
U   Unicode
V   Raw data(void)

Metainformation : Every ndarray object provides access to a number of useful attributes
-------------------------------------------------------------------------------
g.size  
g.itemsize  
g.ndim  
g.shape  
g.dtype  
g.nbytes  
:: here g is ndarray object  

NumPy reshaping and resizing of array:    
np.shape(g)  
g.reshape(3, 4)  
g.T :: g.transponse()  
np.resize(source_ndarray, (row_num, col_num))  
STACKING: It is a special operation that allows the horizontal or vertical combination of two ndarray objects. However, the size of the connecting dimension must be the same:  
np.hstack((h, 2*h))  
np.vstack((h, .5* h))  

Vectorization of Code
---------------------
Vectorization is a strategy to get more compact code that is possibly executed faster. The fundamental idea is to conduct an operation on or to apply a function to a complex object "at oncee" and not by looping over the single elements of the object. In Python, functional programming tools such as map() and filter() provide some basic means for vectorization. NumPy has vectorization built in deep down in its core.  
NumPy BroadCasting: it will allow combine objects in different shapes into one.  
DATA ANALYSIS WITH PANDAS
--------------------------
Data structures: 
DataFrame: 2-dimensional data object with index, Tabular data organized in columns   
Series: 1-dimensional data object with index, Single(time) series of data.  

1. The DATAFRAME class  
transform NumPy ndarray object into a DataFrame object.  
2. The Series Class   
Series class of pandas, which represents a special case of DataFrame class with a single column of data.  
3. GroupBy Operations   
One of the strengths of the DataFrame class lies in grouping data according to a single or multiple columns.
4. Complex Selection  
use of complex selection on DataFrame class.   

The DataFrame Class
-------------------
A class designed to efficiently handle data in tabular form.  
* Data itself can be provided in different shapes and types(list, tuple, ndarray, and dict objects are candidate).  
* Data is organized in columns, which can have custom names(labels).  
* There is an index that can take on differenct formats (e.g. numbers, strings, time information)   

 
