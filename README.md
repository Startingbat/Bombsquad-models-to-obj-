# Bombsquad Models to OBJ Converter

This repository provides a guide and a script to convert Bombsquad game models from `.bob` format to `.obj` format.

## Instructions

1. Place the `.bob` model file you want to convert in the same directory as the `bob_to_obj_converter.py` script.
2. Open a terminal or command prompt and navigate to the directory containing the script and the `.bob` file.
3. Run the following command to convert the `.bob` file to `.obj` format:

   ```
   python bob_to_obj_converter.py input.bob output.obj
   ```

   Replace `input.bob` with the name of your `.bob` file and `output.obj` with the desired name for the output `.obj` file.

4. The converted `.obj` file will be created in the same directory.

## Example

If you have a file named `thepadlevel.bob`, you can convert it to `thepadlevel.obj` by running:

```
python bob_to_obj_converter.py thepadlevel.bob thepadlevel.obj
```

## Textures

If you need textures, go to the Bombsquad modification archive on GitHub to find PNG textures.
