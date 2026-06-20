# Models Folder

This folder is intended to store trained machine learning models generated during the project.

The trained CNN model file (`pneumonia_classifier.h5`) is not included in this repository due to file size limitations and environment constraints.

To generate the model:

1. Open the notebook file.
2. Run all cells.
3. Train the CNN model.
4. Save the model using:

```python
model.save("pneumonia_classifier.h5")
```

5. Place the generated file in this folder.
