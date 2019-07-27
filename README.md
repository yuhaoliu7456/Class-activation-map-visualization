# Class-activation-map-visualization

  This can be used to visualize the channel corresponding to a specific category in the feature map.
As long as you are doing classification related tasks.you can use any network model,such as Vgg、Resnet、Densenet...
when you do validation, set your mode to eval() and let the val dataset to do the forward operation. You can extract a feature map from anywhere in the network and use the category information in the label to visualize the category-related class activation map.
