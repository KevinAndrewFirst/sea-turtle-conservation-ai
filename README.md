# Sea Turtle Conservation AI Assistant

University of Florida — EEL 3872: AI Fundamentals — Spring 2025

## What I did

I trained and extended Cammy, a sea-turtle conservation assistant that answered conservation questions, estimated a turtle's weight from shell measurements, and identified turtle species from photographs.

For the question-and-answer portion, I organized 40 verified conservation questions into topic groups, prepared clear answers using sources such as NOAA and the Sea Turtle Conservancy, and tested different question phrasings to improve Cammy's responses.

For weight prediction, I explored 5,698 turtle measurement records in Looker Studio, identified uneven representation among the turtle groups, configured an AutoKeras regression experiment using species and shell measurements, connected the trained model to Cammy, and tested its predictions.

For image recognition, I labeled a provided set of 60 turtle photographs with MakeSense.ai, configured an AutoKeras image-classification experiment, connected the trained model to Cammy, and tested it with nine unseen photographs and other difficult examples.

## What I learned

The image model identified the hawksbill, loggerhead, and ridley test images but classified every green-turtle test as a hawksbill. I traced that repeated error back to the small training set, uneven examples, and an ambiguous image label. The project taught me that reliable AI depends on careful data preparation, accurate labels, repeated testing, and human review.

## Tools and methods

AutoKeras, CogUniversity, HiPerGator, Looker Studio, MakeSense.ai, regression, image classification, data labeling, model integration, and failure testing.
