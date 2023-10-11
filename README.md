<h1>NoSQL Challenge</h1>
<img
        src="https://i.poweredtemplates.com/p/sp/88137/sp_slide_h_1.jpg"
        alt="Food Magazine rendering"
        width="650"
      />
</br>
<h3><u>Description</u></h3>
<p>
The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating.</br>
You've been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.
</p>
</br>
<h3><u>Part 1: Database and Jupyter Notebook Set Up</u></h3>
</br>
<p>🍜 Import the data in the <em>establishments.json</em> file from the Terminal.</p> 
</br>
<p>🍜 Create a new database called <em>uk_food</em> and a collection called <em>establishments</em>, then create an instance of the Mongo Client.</p> 
</br>
<p>🍜 Confirm that you created the database and loaded the data properly.</p> 
</br>
<p>🍜 Assign the establishments collection to a variable to prepare the collection for use.</p> 
</br>
<h3><u>Part 2: Update the Database</u></h3></br>
<p>The magazine editors have some requested modifications for the database before you can perform any queries or analysis for them. Make the following changes to the establishments collection:
</br>
<p>🍜 Add new restaurant 'Penang Flavours' and its information to the database.</p> 
</br>
<p>🍜 Find the BusinessTypeID for establishments in the "Restaurant/Cafe/Canteen" category, then update 'Penang Flavours' with the BusinessTypeID you found.</p> 
</br>
<p>🍜 The magazine is not interested in any establishments in Dover, so check how many documents contain the Dover Local Authority. Then, remove any establishments within the Dover Local Authority from the database, and check the number of documents to ensure they were deleted.</p> 
</br>
<p>🍜 Convert <em>latitude</em> and<em>longitude</em> to decimal numbers, and <em>RatingValue</em> to integer numbers.</p> 
</br>
<h3><u>Part 3: Exploratory Analysis</u></h3>
</br>
<p><em>Eat Safe, Love</em> has specific questions they want you to answer, which will help them find the locations they wish to visit and avoid.
</br>
<p>🍜 Answer the following questions to explore the database, and find the answers, so you can provide them to the magazine editors:</p>
<ol><li>Which establishments have a hygiene score equal to 20?</li> 
<li>Which establishments in London have a <em>RatingValue</em> greater than or equal to 4?</li>
<li>What are the top 5 establishments with a <em>RatingValue</em> of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?</li>
<li>How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.</li>
</ol>
</br>
<p>----------------------------------------------------------</p> 
</br>
<p>Thank you for reading!</p> 
</br>
<h3>🥢🥢🥢</h3>
</br>
<p><a>Image sourced from poweredtemplate.com</a></p>
</br>
