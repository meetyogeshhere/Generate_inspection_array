# Inspection ID Generator

#### This Python script generates an inspection with a specified number of wave arrays and saves them to a local directory while maintaining the parent-child relationship. The wave arrays are represented as numpy arrays filled with randomly generated entries.

### Requirements
```
Python 3
Numpy
```

### Installing libraries
```
python -r requirement.txt
```



### Usage
To use the script, simply run the following command:
```
 python run genarate_inspection_wave_array.py 

```

inspection_id = generate_inspection(num_waves, parent_id)
where num_waves is the number of wave arrays you want to generate for the inspection and parent_id is the unique ID for the inspection.

The script will create a new directory named inspection_parent_id and save each wave array as a separate numpy file with the format wave_i.npy in the inspection directory. The inspection ID will be returned by the function and stored in the variable inspection_id.



##### Generate an inspection with 50 wave arrays
inspection_id = generate_inspection(50, "example_id")


### Note
Please make sure that your python script has permission to create directories in the location where you want to save the wave arrays.




