Acne Identifier
Background:
Acne is a pervasive skin condition that affects millions of people worldwide, up to 30 percent of women still experience mild to moderate acne well into adulthood. However, finding effective acne products from the sea of options available can often feel like a daunting task. Many individuals refrain from seeking professional help due to the perceived high costs associated with dermatologist visits, which are typically reserved for severe cases. Existing generic solutions, such as benzoyl peroxide or acne patches, merely address symptoms without tackling the underlying problem. Consequently, a significant portion of the population remains underserved and lacks the necessary guidance to effectively manage their acne.
By harnessing the power of AI, we can gain a deeper understanding of our specific acne type, enabling us to make more accurate assessments about our skin. This, in turn, empowers us to make informed decisions regarding our skincare routine by targeting the root cause of our unique acne issue.
Project Goal:
To build a convolution neural network to classify acne severity based on facial images
Dataset:
acne images scrapped from Dermnetnz **Click here for code
pre-processing
Subsetting: 33 images are selected based on image resolution
Annotation: each acne lesion was annotated using bounding box
Labeling: Images are labelled based on a recognized scoring system in acne vulgaris: 
Number of acne	Score	Labeled as
0-5	mild =	1
6-20	moderate =	2
21-50	severe	= 3
50+	very severe = 	4
