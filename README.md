# RSNA_mammo
Computer vision project for detecting cancer on breast CT scans.

Done:
  - Windowing.
  - Converting dcm to png.
  - Resizing to 1024x768 WxH.
  - Separate data into train and test splits.
  - Data augmentation.

Not ordered list of things to be done:
  - Add multiprocessing.
  - Identify and delete corrupted data.
  - Create dataloaders for pytorch.
  - Write training and test loops for pytorch.
  - Write custom metrics formulae.
  - Use tensorboard to track performance.
  - Apply transfer learning or come up with own model architecture. Hardware is a limiting factor, so I am inclined towards transfer learning.
  - Training.
  - Inference.
  - Add tests and clear descriptions to some functions.
  - Visualize most important steps.
