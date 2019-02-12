# Belly-Button-Diversity
In this assignment Flask is used to design an API for dataset on belly button diversity and to serve the HTML and JavaScript required for the dashboard page. Sqlite database file and SQLAlchemy were also used inside Flask app code.

The Flask app	 has the following routes to serve the data from the database: @app.route("/") """Return the dashboard homepage.""" @app.route('/names') """List of sample names.

### Step 1 - Plotly.js

- Used Plotly.js to build interactive charts for the dashboard.

- Created a PIE chart that uses data from the samples route (/samples/) to display the top 10 samples.

- Used sample_values as the values, otu_ids as the labels and otu_labels as the hovertext for the pie chart.

- Created a Bubble Chart that uses data from samples route (/samples/) to display each sample.

- Use otu_ids for the x values, sample_values for the y values, sample_values to determine the marker size, otu_ids for the marker colors, otu_labels for the text values

- Displayed the sample metadata from the route /metadata/

- Displayed each key/value pair from the metadata JSON object on the page

### Step 2 - Heroku

- Deployed my Flask app to Heroku.
