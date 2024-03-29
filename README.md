# HCI4
This is the HCI4 assignment used to make our data visualisation website alongside Multimodal interaction using text to speech. It uses risk factors in order to determine how likely a user will develop certain diseases based on unhealthy habits such as smoking and alcoholism. Based on user input, the user will be presented with data and tips relevant to his choice in order to help make better lifestyle choices. All data has been gathered from multiple sources including the WHO and NHS websites.

## Some Technicalities
The website itself starts off with Homepage.html where the user has to select a choice e.g. alcoholism to find out more. The user is then redirected to the specific website where it contains a series of three slides. The first slide asks the user some questions about how often he drinks then based on that, the user will be presented with relevant data/statistics on the following slide, yet having the choice to get tips on how to make healthier lifestyle habits in the final side. Everything done is trying to replicate the wireframe.

There are some things which are left out/not implemented because I just wanted to have the layout or 'skeleton' made for the website. Most of it can be just copy/pasted and event handlers added if need be. Here is a list of things needed to be done:

- Add smoking/blood pressure/other non-communicable diseases as their own separate sites/slides 
- Implement text to speech (and volume slider) for other pages and not just the homepage. I used a free website to make Welcome.mp3 
- Use user input to move to the remaining slides rather than the icons/carousel buttons
- Add other graphs using d3.js (or other libraries)
- Separate styling/script files into .css/.js (Everything is in .html now)

Data I used so far was from the [NHS Website](https://digital.nhs.uk/data-and-information/publications/statistical/statistics-on-alcohol/2014-additional) titled: alc-eng-2014_csv and then simplified in order to display a simple bar graph using d3.js on the website. The simplifed data can be found on Gist GitHub [Here](https://gist.githubusercontent.com/basel-shehabi/3ff3fbbc1834bb8a5d8d4e9656ad30a4/raw/811bcd0b44268194de061c94d4862ab7b00eca6a/sampledata.csv) except I didnt change year into percentage/number of people. 
