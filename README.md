# Smart Water Purity Testing Solution 


smart low-cost sensor based device which has the capability to float on the surface (controlled) of the water body and sense various parameters of the water which are fundamental for the purity and status testing, pH level, Dissolved Oxygen, Turbidity, Temperature etc. are namely a few. Once the device records these data in the embedded MCU, it will publish that data on the web server in real time. This will empower the authority to monitor and analyse the parameters/sensor reading of the water body in real time through a front-end website. It will enable the authority to track and detect various sources of pollutants and components in the water body.

The front-end web platform will enable the person to view : Zone mapping with keys such as (High pH level, Moderate pH level, High Turbidity etc, low dissolved oxygen due to sewage dumping) Overall Pollution and impurity mapping of the water body Purity Percentage calculation according to the data taken. Manual analysis of temperature thorugh Heat maps of the zones

The Real-time data can be visualized on the systems in the backend and crucial detailing can be done using the panoramic display integration in the platform. Inter-sensor connnectivty is powered by OSC Protocol, which is totally open-source in nature.

Key Elements being used in the project: * KML API : Keyhole Markup Language API * OSC : Open Sound Control Protocol (Open source) * Google Earth Pro : Running as panoramic view with manual configuration of drivers.ini

One of the essential and novel features will be tracking of the sources of pollutants in the water body. This will be done by the following STP (Source Tracking Process):

Before the installation, the location of factories and industries connected to the river/lake will be marked in the system If the Captiozon System, while testing, identifies that the parameters are beyond threshold in the same area which was marked, that would indicate that the respective industry is not following the treatment process, and an alarm will be initiated, along with it, a notification will be given to the authority along with the proper information and maps.

Such a system would ensure that the entire water body is assessed and the status of every zone is covered in the report, It can be controlled wirelessly by Internet Platform or through the controller and the data will be streamed on the Web Platform. The person with the authority will have the credentials for accessing the website/app and analyse the data and the report. Abstraction of the data will be as simple. So the entire system will be plug and play, the moment the system is kept inside the water body, It will start the sensor modules and streaming the data after successful calibrations.

The concept is developed as per the problem statement provided by the NEC Environment Hackathon on HackerEarth, thus a working Hardware prototype has been developed which is able to publish/stream data from sensors to the Web Server by PHP POST Method, and then it is stored in MariaDB Database and then the data is monitored by the Captiozon Systems Dashboard. Moreover, the entire System consisting of all the sensors required for a proper water test, near to the product stage can be developed once this Idea is approved by the respective authority.

In simple words, we can think of this as a controlled or autonomous moving system which will cover the entire zone of a water body and feed in several sensor data (eg. pH level, Temperature, DO, Turbidity etc.) and then send that data onto the database, there it is stored. Then a representative from the authority can simply log on to the system (Web/App Platform) and access all the data being streamed and thus analyse various factors related to it. So this removes the hassle of going on site, collecting samples and then testing it. Moreover, this can even detect and give a proper proof report of the sources of major and minor pollutants. It can automatically detect various comparison reports and charts based on the datasets, which can even help the government in making decisions

Moreover, the system can help the farmers optimize farm water to increase the efficiency of their agriculture processes. This can not only specify whether the water is appropriate for the usage on the farm. Moreover, the farmers can know how much of water they require.

Such a System would ensure regular and accurate testing of purity and pollution level of water. The data thus procured by the smart low cost system, can indicate several threats and factors, which can then be taken care of by the authority. The scope of negligence will be negligible. The System that would act as a bot powered by the efficiency of Internet of things, will give real time reports from the sensor data and even locate the major sources of pollutants of water, so that the authorities can take action against them. Eventually this would enable efficient conservation of water from being exploited and increase the availability of clean drinking water for the public and make this world a healthy place..

IMPORTANT DETAILS OF THE ONLINE PLATFORM

Webpages hosted on FreeWebHosting Website right now, got MariaDB Database in action in the backen

Database Details:

	$servername = "localhost";
	$username = "1092449";
	$password = "wordpress25";
	$dbname = "1092449";

Using NodeMCU with ESP8266 Module integrated. The .ino file is also attached in the repo.

Using http.POST method to send the data from the MCU to the DataBase.

Baud Rate of Data Posting : 115200

Framework used : PHP STORM 
Applications used : Atom and Arduino IDE

CSS code files and Bootstrap loaded from www.html5up.net <<




