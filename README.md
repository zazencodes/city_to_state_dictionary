# US cities and corresponding states Python dictionary
The ipython notebook file `US City to State dictionary.ipynb` contains the code used to make the dictionary and discusses its limitations.

I have also included a module file from which the dictionary can be imported using:
```
from city_to_state import city_to_state_dict
```
Or <br>
You can import from the included pickle file using:
```
import pickle    
with open('pickle/city_to_state.pkl', 'rb') as f:
    city_to_state = pickle.load(f)
```
See also the `test.py` file for a simple example.

More information can be found in my related [blog post](https://galeascience.wordpress.com/2016/03/23/us-city-to-state-python-dictionary/).
