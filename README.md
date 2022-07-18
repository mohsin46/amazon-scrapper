# amazon web scrapper

Amazon does not always give 404 status error when it can't find a particular page. It insteads show a message with 'page not found' or 'amazon.com use the search bar'. So we look for indications of these in the page title. 
There are different type of page for different products. We have two main class in our use case. This includes a physical product and an audio book. So, the first thing I had to do was to check the page is of which type and then access the different details according to the format of that respective category.