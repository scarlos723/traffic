### Experimentation


# For experimentation, the number of filters and the amount of elements of the hidden layer were varied. Since I did not want to lose much information from the images by changing the max-pooling to a larger one.


# When the experiment was carried out with a single layer and only modifying the number of elements, I realized that the error for each epoch stabilized at an average value of 3.48. This can be seen in the following images


# When adding a second layer of convolution the results improved. It should be noted that the hidden layer must have a large number of elements in order to obtain a very low error.



# When working with two layers, the first layer with 32 filters and the second with 96 filters. Finally, a hidden layer of approximately 180 elements that allow to obtain an error even lower than the one shown in the project example. This can be seen in the following figure.


# I could see that by adding more convolution layers, with more filters, less losses are obtained at the end of the whole process, as can be seen in the following image. I think this is because with more filters and layers, more characteristics and features can be obtained from the images that are being observed.