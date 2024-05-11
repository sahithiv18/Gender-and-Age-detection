# Gender-and-Age-Detection


<h2>Objective :</h2>
<p>To build a gender and age detector that can approximately guess the gender and age of the person in a picture or through webcam.</p>

<h2>About the Project :</h2>
<p>In this Project, I had used Deep Learning to accurately identify the gender and age of a person from a single image of a face. The predicted gender may be one of ‘Male’ and ‘Female’, and the predicted age may be one of the following ranges- (0 – 2), (4 – 6), (8 – 12), (15 – 20), (25 – 32), (38 – 43), (48 – 53), (60 – 100). It is very difficult to accurately guess an exact age from a single image because of factors like makeup, lighting, obstructions, and facial expressions. Hence, this a classification problem instead of making it one of regression.</p>

<h2>Dataset :</h2>
<p>For this python project, I had used the Adience dataset; <a href="https://www.kaggle.com/ttungl/adience-benchmark-gender-and-age-classification">here</a>. This dataset serves as a benchmark for face photos and is inclusive of various real-world imaging conditions like noise, lighting, pose, and appearance. It has a total of 26,580 photos of 2,284 subjects in eight age ranges and is about 1GB in size.</p>

# Working:
<h2>Examples :</h2>

    >python detect.py --image girl1.jpg
    Gender: Female
    Age: 25-32 years
    
<img src="Gender and age 1.jpeg">

    >python detect.py --image woman1.jpg
    Gender: Female
    Age: 38-43 years
    
<img src="Gender and Age 2.jpeg">

    >python detect.py 
    
<img src="Gender and Age 3.jpeg">

    

    
         
