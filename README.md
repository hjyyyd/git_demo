



ref: https://github.com/hjyanzju/pytorch-template




pytorch-template/

├── train.py - main script to start training
├── test.py - evaluation of trained model
├── config.json - holds configuration for training










├── data/ - default directory for storing input data


├── data_loader/ - anything about data loading goes here
│   └── data_loaders.py


├── logger/ - module for tensorboard visualization and logging
│   ├── visualization.py
│   ├── logger.py
│   └── logger_config.json


├── model/ - models, losses, and metrics
│   ├── model.py
│   ├── metric.py
│   └── loss.py

├── saved/
│   ├── models/ - trained models are saved here
│   └── log/ - default logdir for tensorboard and logging output


├── trainer/ - trainers
│   └── trainer.py


└── utils/ - small utility functions
│   ├── util.py
│   └── ...



---
├── parse_config.py - class to handle config file and cli options
│
├── new_project.py - initialize new project with template files

│
├── base/ - abstract base classes
│   ├── base_data_loader.py
│   ├── base_model.py
│   └── base_trainer.py