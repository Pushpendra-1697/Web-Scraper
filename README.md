# Web-Scraper-Puppeteer for Job Listings
# Overview
Web-Scraper-Puppeteer is a Node.js library that provides a high-level API to control headless Chrome or Chromium. It can be used to automate various tasks, including web scraping. Using Puppeteer, you can navigate to job search websites, extract job listing data from the HTML, and save it to a file or database. Puppeteer provides a lot of powerful features, such as headless browsing, page interaction, and PDF generation, making it a popular choice for web scraping.

# Tech Stack:
Node.js, Web-Scraper-Puppeteer Node.js library, StealthPlugin middleware
# To install dependencies:
npm i puppeteer

npm i puppeteer-extra

npm i puppeteer-extra-plugin-stealth

# To run the scraper:
npm start (or) npm run start

# Sample output JSON Formate;
Test Case-1:

query: data analyst

location: New Delhi, Delhi

db.json/Output file: 

[{"title":"Data Analyst","comapny_name":"Zenworx Knowledge Partners","location":"Remote in New Delhi, Delhi","description":"₹3,00,000 - ₹5,00,000 a year.Full-time.+1.Monday to Friday.+1.Easily applyHiring multiple candidates.Experience in data visualization and presentation..Responsible for gathering data from primary and secondary sources, identifying, analyzing and interpreting….Employer.Active 3 days ago·More....","date":"3 days ago·More..."},{"title":"Data Analyst","comapny_name":"BNC","location":"New Delhi, Delhi","description":"₹15,000 - ₹20,000 a month.Full-time.+1.Day shift.Call employer.Easily applyHiring multiple candidates.Formulating techniques for quality data collection to ensure adequacy, accuracy and legitimacy of data..Applicant to provide data available in many different….Posted.Posted 5 days ago·More....","date":" days ago·More..."},{"title":"Business Analyst","comapny_name":"prodinnov","location":"Remote in Delhi, Delhi","description":"₹45,000 - ₹95,000 a month.Full-time.Day shift.+1.Easily apply.Responsive employer.Hiring multiple candidates.Familiarity with SQL and data analysis tools..Perform data analysis and create reports to support decision making..Strong analytical and problem-solving skills..Employer.Active 3 days ago·More....","date":" days ago·More..."},{"title":"Data Analyst","comapny_name":"SSPL","location":"New Delhi, Delhi","description":"Fresher.For planning and coordinating activities, organizations remain in invariant communication with one another and the data transfer has to be performed efficiently….Posted.Posted 30+ days ago·More....","date":"+ days ago·More..."},{"title":"Data Analyst","comapny_name":"Bansal Trading Company","location":"Delhi, Delhi","description":"₹25,000 - ₹30,000 a month.Full-time.+1.Day shift.+1.Easily applyHiring multiple candidates.Ability to collect and compile relevant data..Can prepare presentations and help management with the data in the desired format..Posted.Posted 4 days ago·More....","date":" days ago·More..."},{"title":"","description":"","date":""},{"title":"Data Analyst","comapny_name":"Boston Consulting Group4.2","location":"New Delhi, Delhi","description":"Ability to work with large data sets both structured and unstructured data..Deep understanding of popular data analysis tools and databases..Posted.Posted 13 days ago·More....","date":"3 days ago·More..."},{"title":"Data Analyst","comapny_name":"Ericsson4.1","location":"Noida, Uttar Pradesh","description":"Lead and manage a team data scientists and engineers..Acuity for business flow understanding and expertise in data preparation and pre-processing..Posted.Posted 4 days ago·More....","date":" days ago·More..."},{"title":"Data Analysts - MoRD","comapny_name":"NeGD","location":"New Delhi, Delhi","description":"Prepare concise data reports and data visualizations for themanagement that will help in decision making process..Experience in data mining techniques..Posted.Posted 30+ days ago·More....","date":"+ days ago·More..."},{"title":"Data Analyst","comapny_name":"eminenture4.2","location":"New Delhi, Delhi","description":"Good command on Excel (Vlookup, Hlookup, Pivot Tables, Conditional Formatting, If Conditioning and other advanced Excel tools like VBA and Macros)..Posted.Posted 30+ days ago·More....","date":"+ days ago·More..."},{"title":"Data Analyst - Data","comapny_name":"Whiteforce","location":"Noida, Uttar Pradesh","description":"Analyzing data and presenting data through reports that aid decision-making..Create relationships between data and develop tabular and other multidimensional….Posted.Posted 1 day ago·More....","date":"1 day ago·More..."},{"title":"","description":"","date":""},{"title":"Data Analyst","comapny_name":"WinZO","location":"New Delhi, Delhi","description":"Full-time.Easily apply.Acquire data from various data sources and maintain databases..Own instrumentation and measurement of data and various data sources..Employer.Active 4 days ago·More....","date":"4 days ago·More..."},{"title":"Data Analyst/Associate Analyst","comapny_name":"PRS Legislative Research4.5","location":"Darya Ganj, Delhi","description":"It is essential to have prior experience in data scraping, analysis and visualisation..The candidate should have a background in data sciences, and should be….Posted.Posted 30+ days ago·More....","date":"+ days ago·More..."},{"title":"Data Analyst","comapny_name":"iCRC","location":"Noida, Uttar Pradesh","description":"GIS Knowledge (Preferable but no mandatory)..Ability to analyse existing tools and databases and provide software solution recommendations..Posted.Posted 3 days ago·More....","date":" days ago·More..."},{"title":"Junior Analyst - On Contract","comapny_name":"Boston Consulting Group4.2","location":"New Delhi, Delhi","description":"Full-time.Able to quickly learn and use specialized survey data analysis tools such as SPSS, Sawtooth, etc. to deliver practical data analytics outcomes..Posted.Posted 2 days ago.","date":"Posted 2 days ago"},{"title":"Risk Advisory Internal Audit Analyst","comapny_name":"KPMG3.9","location":"Gurgaon, Haryana","description":"Full-time.JOB DESCRIPTION IA/DA QUALIFICATIONS Graduate/Post….Posted.Posted 30+ days ago·More....","date":"+ days ago·More..."},{"title":"","description":"","date":""}]

Test Case-2:

query: full stack developer

location: Bangalore, Karnataka

db.json/Output file:

[{"title":"UI Developer","comapny_name":"Telstra3.9","location":"Bengaluru, Karnataka","description":"Full-time.+1.Ensuring the entire stack is designed and built for speed and scalability..3.5 years – 5 years of experience in front-end developer with React..Posted.Posted 6 days ago.","date":"Posted 6 days ago"},{"title":"React _Full Stack Engineer _T8","comapny_name":"Mercedes-Benz Research and Development India...4.1","location":"Bengaluru, Karnataka","description":"O Help evaluate and establish appropriate technology stack..Knowhow about Cloudera stack and analytics workbenches (e.g. Dataiku) are an advantage..Posted.Posted 1 day ago·More....","date":"1 day ago·More..."},{"title":"Full Stack Developer","comapny_name":"Mobile Programming India Private Limited","location":"Bengaluru, Karnataka","description":"₹4,44,671 - ₹14,74,086 a year.Full-time.Monday to Friday.+3.Easily applyHiring multiple candidates.Sound knowledge of Object-Oriented Programming (OOP) Patterns and Concepts • Proficiency in Java, with a good understanding of its ecosystems • Familiarity with….Posted.Just posted·More....","date":"st posted·More..."},{"title":"Full Stack Web Developer","comapny_name":"Refactor academy","location":"Bengaluru, Karnataka","description":"₹6,00,000 - ₹8,00,000 a year.Full-time.Day shift.Easily applyHiring multiple candidates.This is a internship-cum-training bootcamp, wherein you will intern for 3 months and learn hands-on HTML, CSS, Javascript, React and Node frameworks along with….Hiring ongoing·More....","date":"g ongoing·More..."},{"title":"Full Stack Developer","comapny_name":"Mercedes-Benz Research and Development India...4.1","location":"Bengaluru, Karnataka","description":"Min 2yrs of experience in Frontend technologies Angular is preferred, React-JS..Good understanding of backend technologies such as Java, spring framework..Posted.Posted 30+ days ago·More....","date":"+ days ago·More..."},{"title":"","description":"","date":""},{"title":"Node.Js Full Stack Developer","comapny_name":"Mercedes-Benz Research and Development India...4.1","location":"Bengaluru, Karnataka","description":"We are a team of passionate engineers and tech enthusiasts working on building cutting edge cloud native applications using diverse technologies (mobile, web,….Posted.Posted 6 days ago·More....","date":" days ago·More..."},{"title":"Full Stack Developer (T8) - oneSCM","comapny_name":"Mercedes-Benz Research and Development India...4.1","location":"Bengaluru, Karnataka","description":"Collaborate with Front-end developers to integrate user-facing elements with server side logic..Solid working experience in Java, Java-EE & microservices….Posted.Posted 17 days ago·More....","date":"7 days ago·More..."},{"title":"Full Stack Developer [IN45]","comapny_name":"Aither Technology","location":"Remote in Bengaluru, Karnataka","description":"From ₹12,00,000 a year.Full-time.Monday to Friday.+3.Bachelor's.Easily apply.Urgently hiring.In addition to traditional benefits, we will support our employees in the pursuit of technical certifications such as AWS, Azure, PHP, etc, and offer….Employer.Active 7 days ago·More....","date":"7 days ago·More..."},{"title":"Full Stack Developer(UI)-React","comapny_name":"Fervour Infosystem Pvt Ltd","location":"Bengaluru, Karnataka","description":"Contractual / Temporary.Day shift.+1.Easily applyHiring multiple candidates.HIRING FOR *Full Stack Developer (UI)- React*..NOTICE PERIOD :- *IMMEDIATE JOINER / SERVING / 30 DAYS MAX..Nodejs, React, Redux and related UI concepts (minimum….Posted.Just posted·More....","date":"st posted·More..."},{"title":"Lead Software Engineer","comapny_name":"Clarivate3.4","location":"Bengaluru, Karnataka","description":"Full-time.At least 5 years of experience in Spring Boot applications..At least 4 years of experience with Microservices..Strong with JAVA/J2EE/REST..Posted.Posted 19 days ago.","date":"Posted 19 days ago"},{"title":"","description":"","date":""},{"title":"oneSCM - Full Stack Developer","comapny_name":"Mercedes-Benz Research and Development India...4.1","location":"Bengaluru, Karnataka","description":"Collaborate with Front-end developers to integrate user-facing elements with server side logic..Solid working experience in Java, Java-EE & microservices….Posted.Posted 6 days ago·More....","date":" days ago·More..."},{"title":"FULL STACK INTERN","comapny_name":"Omnify","location":"Bengaluru, Karnataka","description":"Internship.Omnify is a Global SaaS startup built to enable service providers across the Sports, Fitness, and Recreation industries to deliver outstanding experiences to….Posted.Posted 5 days ago·More....","date":" days ago·More..."},{"title":"JavaScript Developer","comapny_name":"Credit Saison India","location":"Remote in Bengaluru, Karnataka","description":"₹60,000 - ₹1,20,000 a month.Full-time.Monday to Friday.Total work: 1 year.Vue.js: 1 year.Easily applyHiring multiple candidates.Full stack is a plus..You will work directly with designers, product owners, and fellow engineers to help guide, build, instrument, and test front-end….Employer.Active 3 days ago·More....","date":"3 days ago·More..."},{"title":"Full Stack Developer","comapny_name":"Supply Wisdom Pvt Ltd","location":"Bengaluru, Karnataka","description":"₹4,50,173 - ₹16,63,699 a year.Full-time.Day shift.+1.Easily apply.SaaS applications, HTML5, CSS3 and JavaScript, ES6, JavaScript frameworks such as ReactJS, Python, NodeJS, Django Framework, MySQL, Postgres and MongoDB, AWS….Posted.Posted 4 days ago·More....","date":" days ago·More..."},{"title":"Full Stack Developer","comapny_name":"Siemens4.0","location":"Bengaluru, Karnataka","description":"Full-time.Experience in full stack frameworks using Python..You’ll be part of a multi-functional team that’s responsible for the full software development process, from….Posted.Posted 11 days ago·More....","date":"1 days ago·More..."},{"title":"","description":"","date":""}]
