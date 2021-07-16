<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <title>Geographical Entity Recognition Web</title>
</head>
<body>
<h1>
    <center>
    Analyzing Marianne Moore's Poems
    </center>
</h1>
<p>
     ==============================================================================================================
<p>
    <center>
        Project maintained by MehtA-Tutoring-DHMLBootcamp21 
        Hosted on GitHub Pages - Theme by mattgraham
    </center>
</p>
<h1>
    <center>
    Named Entity Recognition
    </center>
</h1>
<h2>
    <center>
    Kabir Goel, Siddarth Kappa, Dylan Sheehan
    </center>
</h2>
<h3>
    <center>
    Locating Geographical References in Poems Written by Marianne Moore
    </center>
</h3>
</p>
<h2>
	<center>
    Analysis
    </center>
<h2>
<p>
	<center>
	Our NER reliant method of finding geographical refrences required multiple stages, starting with preprocessing and turning the large pdfs of poems into text using Split PDF. We then worked to clear the errors caused by the pdf conversion software, these errors primarily occured on page turns, line breaks, and dates. Next we stripped all empty spaces and created a list of lists of poems, this allows for spacy to be easily implimented. After creating the data table that Spacy will print onto, we are able to simply run the produced labeled entities through a filter so that geographical entities are exclusively defined. Ultimately creating a list of geographical entities in the poems.
	<center>
<p>
<h2>
    <center>
   Our Resources 
    </center>
</h2>
<h3>
    <center>
  <a href="https://spacy.io//">Spacy</a>
    </center>
</h3>
<h2>
	<center>
    <a href = "https://colab.research.google.com/drive/18lDZ2tztIRm2QcZLktbJCOj58x4qdAMY?usp=sharing" >View our code</a> 
	<center>
<h2>
<h3>
<center>
##########
<center>
<h3>

</body>
</html>
