# Live Currency Converter 

 

#### Video Demo:  https://youtu.be/eY7Fzw-BB7w 

 

#### Description: 

The **Live Currency Converter** is a web-based program that runs out real-time currency conversion according to updated exchange rates. Moreover, the main goal of the project to provide users with a simple interface in order to automatically convert currencies with their current exchange values in the global market, more than 160 currencies can be converted using this converter. 
 
The project is built based on **Python** and the **Flask** web application framework, and it uses the **ExchangeRate-API** forfetching real-time exchange rates of currencies. Apart from that, the application offers functionality where the user provides a certain amount in a currency, selects the from and to currencies, and then the converter fetches the converted amount in the selected currency. Also, please note that the project was designed keeping ease and simplicity in mind for beginners and professionals. 

 

 

**Key Features:** 

- **Live Currency Conversion**: To start with, this currency conversion application takes the exchange rate as it currently stands, so the conversion is done using the current rate when the request is made. 
- **Simplified Interface**: The interface here is interactive, intuitive, and easy to use. In addition, the users only need to enter the amount they wish to convert, select currencies from which they have to convert the amount, to which currency they have to convert the amount, and then click "Convert" button. 
- **Responsive Design**:  The page is designed responsively, hence allowing users to easily utilize the application using any device, whether it is computer, tablet, or mobile phone. 

 

**Project Files:** 

1. **project.py**: The main Python file that contains the app's primary logic. Furthermore, it uses Flask to display the web page and also, process the input from the user. Also, it includes functions to get the exchange rate from the API, exchange the currency, and show the output to the user. 
2. **requirements.txt**: This is a file containing Python dependencies needed for the project. It contains Flask, requests (to make the API callusing HTTP requests), and any other dependencies. Please note that all the libraries that are needed can be installed by the user using `pip install -r requirements.txt`. 
3. **test_project.py**: It is the script which includes the test cases for the project's major functions. To expand, they are used to ensure the currency exchange is run accurately in order to make sure the application produces the proper output based on varying scenarios. 
4. **README.md**: This is a document describing the purpose of the project, its functionality, and how to install it. 

 

**Design Choices:** 

- **Flask Framework**: I have utilized Flask because of the simplicity and ease of use that it provides. Furthermore, it is simple with noextraneous complexities and that is perfectly okay for projects such as this. Apart from this, Flask allowed one to do the building of the project basics and deployment easily without hassle, bugs, errors and additional complications. 
- **ExchangeRate-API**: The project utilizes the **ExchangeRate-API** to acquire real-time exchange rates. Further, I have utilized this API since it is easy to integrate and provides correct data. It also supports a free plan, which is sufficient for this project. 
- **Simple User Interface**: The interface has been kept as simple as easy to comprehend as possible with an emphasis on function over form. Due to simplicity and accuracy, it was thought to provide a seamless experience for users who simply wish to have a currency exchange within few seconds. I have also included some fundamental CSS styling so that overall design can be built upon without hindering how easy and functional it still is. 

**How the Project Works:** 

- **Backend (Python/Flask)**: 

  - The backend is responsible for handling user input, fetching real-time exchange rates, performing the currency conversion, and rendering the result. The `project.py` file contains the Flask app and the logic for making requests to the **ExchangeRate-API**. 

  - When a user submits the form, the backend processes the data, converts the specified amount from one currency to another, and then displays the result on the page. 

   

- **Frontend (HTML/CSS)**: 

  - The frontend of this program is simple and easy to understand, it is coded in HTML and CSS. The form asks for three inputs: the amount to be converted, the currency which needs to be converted, and the currency in which user wants to convert. As soon the user enters all three values and presses convert, the result appears immediately below the form. 
- I have used fundamental CSS styling to make the converter look aesthetic and interactive. I used a light color scheme for the background to assist in creating a peaceful, non-diverting interface. 

- **Currency Conversion Logic**: 

- The user provides the value he/she needs to convert, and from which currency to which currencies they want to convert. The backend then looks for the exchange rates from the **ExchangeRate-API**, which provides a dictionary of conversion rates for different currencies and USD is used as the base currency in the backend for all the operations. 
- The conversion is achieved by first converting the input to USD (if the input currency is anything other than USD) and then to the destination currency using the fetched exchange rates.- Finally on the end, the result is displayed on the web page along with a message that displays the amount that was converted. 

**Future Improvements: ** 

- **Support for More Currencies**: Although this project has support for most popular currencies, adding other regional and less common currencies would make the converter even more useful. 
- **User Accounts**: If an option was available for users to make their account, and then log in later, it would enable them to see their search history and convert those currencies according to live rates, thus making currency conversion easier and even more quick for them. 

 - **Error Handling and Validation**: This release of the program does handle small input errors (e.g., invalid currency code), but it would have been better if more extensive error handling could have been added in order to handle such as network connection loss or illegal user input. 
- **Styling Improvements**: The interface is functional, there is a lot of scope for improvement in design by adding some more useful elements and animations. 

**Testing:** 

The project has test cases under `test_project.py` script. The tests ensure that fundamental features of the application, say, exchange rates and performing conversions, are working correctly. The tests check various scenarios, for instance: 
- To confirm the functionality of currency conversion. 
- To test edge cases like in case, the amounts are too big or too small. 

-To have the application seamlessly handle invalid currency codes. 

**Conclusion:** 

This project was a great learning exercise by integrating with third-party APIs, with Flask, and developing a basic yet really useful web application for international students. It taught me more about web development and understanding how to design dynamic and interactive websites that are capable of responding to user inputs in real-time. In addition to this, the live Currency Converter which we made is an useful tool for any individual who needs to convert currencies as quick as possible, and I am really proud with the result of the project. 

 

References 

 

ChatGPT - Currency Converter Code. (2025). ChatGPT. https://chatgpt.com/share/67c64f19-eea8-8005-92c7-b836c7fdb3ad 

ExchangeRate-API - Free & Pro Currency Converter API. (n.d.). Www.exchangerate-Api.com. https://www.exchangerate-api.com 

 
