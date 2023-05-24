# Video-Game-Web-Scraper
Combining Python and Chrome API, app collects video game user statistics through web scraping and displaying it in console

Project Description:

This Python project utilizes the Selenium library to automate web browsing and extract information from the op.gg website for League of Legends. The project prompts the user to enter their League of Legends username, opens the op.gg website using a Chrome web driver, and retrieves information about the user's last played champion.

The project begins by importing the necessary libraries, including Selenium. It also declares a boolean variable, "updated," which will be used later.

The user is prompted to enter their League of Legends username, which is then converted to lowercase. The Chrome web driver is located using the specified file path, and the browser is opened to the op.gg website with the provided username. If no username is entered, an appropriate message is displayed.

The project attempts to click the "Update" button on the op.gg page to refresh the user's information. It uses the WebDriverWait function from Selenium to wait for the button to become present and clickable. If successful, the button is clicked, and the "updated" variable is set to True. If the button cannot be clicked within 60 seconds, an appropriate message is displayed.

Next, the project retrieves the information about the user's last played champion. It uses WebDriverWait again to wait for the element containing the champion information to become present. Once found, the champion's name is extracted and displayed along with the username.

Overall, this project demonstrates the use of Selenium to automate web browsing and extract information from a specific website. It showcases skills in web scraping, user input handling, and browser automation.
