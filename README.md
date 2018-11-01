# fs-exercise

Overview

	The goal of this project is to create an application that allows a user to create a portfolio of stocks given they have a starting amount of money and cannot allocate more than that total amount. The user can also can also visualize their portfolio with a pie chart.

Feature 1 - The user should have some sort of form to add a new stock. For simplification purposes, we’re going to say that each stock has a fixed price and not worry about taking market movements into account. The minimum number of data fields for a stock should be its ticker and price, but feel free to add any additional fields.

Feature 2 - The user can see how much total money they have, how much unallocated money they have, and for each stock, that stock’s price and how many shares they have in their portfolio.

Feature 3 - The user is able to visualize their portfolio with a pie chart. Each slice represents a stock and the size of the slice represents that stocks proportion in the portfolio. There should also be a slice for unallocated cash. 

Extra Features (Optional)

 Allow the user to switch between different visualizations. For example adding a vertical bar chart, sunburst chart, or treemap chart. Some of these visualizations may require including additional data fields with a stock (like the industry of the company). 

Tech Stack

Frontend - React (use whatever library is most convenient for data visualizations) 
Backend - Node (you can use raw node or a library such as express)
Persistence - The user’s stocks, total money, and portfolio should all persist the user refreshing their browser. That being said, in-memory persistence as javascript (node) objects is fine for this project. Sqlite is also acceptable but optional. 
