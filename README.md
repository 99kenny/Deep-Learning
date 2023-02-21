# VGGNet implementation for CIFAR-10

# Configurations
- VGG19
- Batch size


| batch size  | 1 | 2 | 3 |
|------|---|---|---|
| 32  |  0.9048 |   |   |
| 128  |   |   |   |
| 256  |   |   |   |
| 512 |   |   |   |


|   regularization    | dropout = 0 | dropout = 0.3 | dropout = 0.5 |
|-------------|-------------|---------------|---------------|
| l2 = 0      |             |               |               |  
| l2 = 0.01   |             |               |               |  
| l2 = 0.001  |             |  0.9208       |               |   
| l2 = 0.0001 |             |               |               |
