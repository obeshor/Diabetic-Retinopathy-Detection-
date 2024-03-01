# Diabetic-Retinopathy-Detection

Diabetic Retinopathy (DR) is the fastest growing cause of preventable blindness. All people with diabetes are at risk. They need to be screened once a year.

This screening involves taking a picture of the back of the eye. The picture is called a fundus photo. It's taken using a special camera. An eye doctor then diagnoses this image. In many parts of the world there's a shortage of eye doctors. According to the WHO, as a result, in the world about 55% of people suffer some form of vision loss before the disease is detected.

It's now possible to take fundus photos using a cellphone camera. https://www.jove.com/video/55958/smartphone-fundus-photography

Why not also use that same phone to automatically diagnose the photo?

The objective of this notebook is to build a classifier that can detect diabetic retinopathy on a fundus image. This model has been deployed on raspberry pi 3.

Fundus images can be quite large, as can be seen by the size of the images in this competition. The good thing about tensorflow.js is that there's no need to upload images. The model runs in the browser and all processing is done locally on the user's computer or mobile phone.

We will use a pre-trained MobileNet model. MobileNet was developed by Google to be small and fast.
