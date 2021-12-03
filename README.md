# Kaggel-Prj-Airbus-Ship-Detection-Challenge
Kaggel-Prj-Airbus-Ship-Detection-Challenge


-------

## Airbus Ship Detection Challenge
https://www.kaggle.com/c/airbus-ship-detection

-------

## Task

A lot of work has been done over the last 10 years to automatically extract objects from satellite images with significative results but no effective operational effects. 

Now Airbus is turning to Kagglers to increase the accuracy and speed of automatic ship detection.




-------

## Evaluation
This competition is evaluated on the F2 Score at different intersection over union (IoU) thresholds.

-------

## Submission File

In order to reduce the submission file size, our metric uses run-length encoding on the pixel values. 

Instead of submitting an exhaustive list of indices for your segmentation, you will submit pairs of values that contain a start position and a run length. 

E.g. '1 3' implies starting at pixel 1 and running a total of 3 pixels (1,2,3).

The competition format requires a space delimited list of pairs. 

For example, '1 3 10 5' implies pixels 1,2,3,10,11,12,13,14 are to be included in the mask. 

The pixels are one-indexed and numbered from top to bottom, then left to right: 1 is pixel (1,1), 2 is pixel (2,1), etc. 

A prediction of of "no ship in image" should have a blank value in the EncodedPixels column.

The metric checks that the pairs are sorted, positive, and the decoded pixel values are not duplicated. 

It also checks that no two predicted masks for the same image are overlapping.

The file should contain a header and have the following format. 

Each row in your submission represents a single predicted ship segmentation for the given image.







-------

- If you're interested to explore more Airbus data, you are welcomed to check out the OneAtlas Sandbox. 

https://sandbox.intelligence-airbusds.com/web/

- And for more insights on our Maritime Surveillance capabilities, have a look at Airbus Intelligence page.

https://www.intelligence-airbusds.com/markets/maritime/

-------


