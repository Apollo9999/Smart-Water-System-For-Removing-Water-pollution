# SustaianbleWaterTestingSystemsSolution

Water quality maintenance is crucial in strategizing control cum preventive measures to reduce water pollution and degradation of aquatic ecosystems. Periodic monitoring of water quality is an essential exercise that can help to keep track of hydrological information status of any water body. Many existing systems and methodologies seem to be ineffective in achieving the objective of the same, and few other typical methods have shown a phenomenal outcome that helped to restore and maintain water bodies from accumulation of nutrients and organic compounds that triggers quality degradation. Yet the statistics all around the globe infers the improvement of water quality and water quality monitoring system. This project presents the major limitations of existing water quality monitoring techniques followed by most of the nations and added to that a proposal on a new system that can make water quality monitoring more efficient in their prime objective of preventing on-going pollution control trends. Advancements in the fields like embedded system, Unmanned surface vessels, and IOT are the technologies that can be used to monitor the quality of water.Water pollution is killing millions of Indians. More than 163 million people 19.3% of the Indian population in India do not have access to clean water. This is the worst  situation in the world. As India grows and urbanizes, its water bodies are getting toxic. It is estimated that around 70% of surface water in India is unfit for consumption. Lack of water, sanitation and hygiene results in the loss of 400,000 lives per year in India.

Key Research Areas for Water Pollution are Mentioned Below 

Sewage And Waste Water: Sewage, garbage and liquid waste of households, agricultural lands and factories are discharged into lakes and rivers. These wastes contain harmful chemicals and toxins whichmake the water poisonous for aquatic animals and plants

Dumping: Dumping of solid wastes and litters in water bodies causes huge problems. Litters include glass, plastic, aluminum, styrofoam etc.Different things take different amount of time to degrade in water. They affect aquatic plants and animals.

Industrial Waste: Industrial waste contains pollutants like asbestos,lead, mercury and petrochemicals which are extremely harmful to both people and environment. Industrial waste is discharged into lakes and rivers by using fresh water making the water contaminated.

Oil Pollution: Sea water gets polluted due to oil spilled from ships and tankers while traveling. The spilled oil does not dissolve in water andforms a thick sludge polluting the water.

Acid Rain: Acid rain is pollution of water caused by air pollution. When the acidic particles caused by air pollution in the atmosphere mix with water vapor, it results in acid rain.

Global Warming: Due to global warming, there is an increase in water temperature. This increase in temperature results in death of aquatic plants and animals. This also results in bleaching of coral reefs in water.

Eutrophication: Eutrophication is an increased level of nutrients in water bodies. This results in bloom of algae in water. It also depletes the oxygen in water, which negatively affects fish and other aquatic animal population.

 Project Objective 

 The project Intent and motive  is to develop smart low-cost sensor based device which has the capability to float on the surface controlled of the water body and sense various parameters of the water which are fundamental for the purity and status testing, pH level, Dissolved Oxygen, Turbidity, Temperature etc. are namely a few. Once the device records these data in the embedded MCU, it will publish that data on the web server in real time. This will empower the authority to monitor and analyze the parameters/sensor reading of the water body in real time through a front-end website. It will enable the authority to track and detect various sources of pollutants and components in the water body.

Please find the attached PDF containing all the information along with diagrams and other elements of the idea. The front-end web platform will enable the person to view : Zone mapping with keys such as (High pH level, Moderate pH level, High Turbidity etc, low dissolved oxygen due to sewage dumping) Overall Pollution and impurity mapping of the water body Purity Percentage calculation according to the data taken. Manual analysis of temperature through Heat maps of the zones

The Real-time data can be visualized on the systems in the back end and crucial detailing can be done using the panoramic display integration in the platform. Inter-sensor connnectivty is powered by OSC Protocol, which is totally open-source in nature.


One of the essential and novel features will be tracking of the sources of pollutants in the water body. This will be done by the following Source Tracking Process

Before the installation, the location of factories and industries connected to the river/lake will be marked in the system If the Captiozon System, while testing, identifies that the parameters are beyond threshold in the same area which was marked, that would indicate that the respective industry is not following the treatment process, and an alarm will be initiated, along with it, a notification will be given to the authority along with the proper information and maps.

Such a system would ensure that the entire water body is assessed and the status of every zone is covered in the report, It can be controlled wirelessly by Internet Platform or through the controller and the data will be streamed on the Web Platform. The person with the authority will have the credentials for accessing the website/app and analyse the data and the report. Abstraction of the data will be as simple. So the entire system will be plug and play, the moment the system is kept inside the water body, It will start the sensor modules and streaming the data after successful calibrations.

The Project working Hardware prototype has been developed which is able to publish/stream data from sensors to the Web Server by PHP POST Method, and then it is stored in MariaDB Database and then the data is monitored by the Captiozon Systems Dashboard. Moreover, the entire System consisting of all the sensors required for a proper water test, near to the product stage can be developed once this Idea is approved by the respective authority.

In simple words, we can think of this as a controlled or autonomous moving system which will cover the entire zone of a water body and feed in several sensor data (eg. pH level, Temperature, DO, Turbidity etc.) and then send that data onto the database, there it is stored. Then a representative from the authority can simply log on to the system (Web/App Platform) and access all the data being streamed and thus analyze various factors related to it. So this removes the hassle of going on site, collecting samples and then testing it. Moreover, this can even detect and give a proper proof report of the sources of major and minor pollutants. It can automatically detect various comparison reports and charts based on the datasets, which can even help the government in making decisions

Moreover, the system can help the farmers optimize farm water to increase the efficiency of their agriculture processes. This can not only specify whether the water is appropriate for the usage on the farm. Moreover, the farmers can know how much of water they require.

Such a System would ensure regular and accurate testing of purity and pollution level of water. The data thus procured by the smart low cost system, can indicate several threats and factors, which can then be taken care of by the authority. The scope of negligence will be negligible. The System that would act as a bot powered by the efficiency of Internet of things, will give real time reports from the sensor data and even locate the major sources of pollutants of water, so that the authorities can take action against them. Eventually this would enable efficient conservation of water from being exploited and increase the availability of clean drinking water for the public and make this world a healthy place.


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




