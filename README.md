# deepdream-pytorch

deepdream0.py =  VGG16
 # For VGG16_IMAGENET (PLACES_365 NOT SUPPORTED FOR THIS MOEDL)
    # LAYERS AVAILABLE ['relu3_3', 'relu4_1', 'relu4_2', 'relu4_3', 'relu5_1', 'relu5_2', 'relu5_3', 'mp5']

deepdream1.py = VGG16_EXPERIMENTAL
# For VGG16_EXPERIMENTAL_IMAGENET (PLACES_365 NOT SUPPORTED FOR THIS MOEDL)
    # LAYERS AVAILABLE ['relu3_3', 'relu4_1', 'relu4_2', 'relu4_3', 'relu5_1', 'relu5_2', 'relu5_3', 'mp5']

deepdream2.py = GOOGLENET 
 # FOR GOOGLENET_IMAGENET (PLACES_365 NOT SUPPORTED FOR THIS MOEDL)
    # LAYERS AVAILABLE: ['inception3b', 'inception4c', 'inception4d', 'inception4e', 'inception4a' , 'inception4b', 'inception4a', 'inception4b']

deepdream3.py = RESNET50
# FOR RESNET50_PLACES_365/IMAGENET 
    # LAYERS AVAILABLE: ['layer1', 'layer2', 'layer3', 'layer4'] 

deepdream4.py = ALEXNET 
# FOR ALEXNET_PLACES_365/IMAGENET
    # LAYERS AVAILABLE: ['relu1', 'relu2', 'relu3', 'relu4', 'relu5']

