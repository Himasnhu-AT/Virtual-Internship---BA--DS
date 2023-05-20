# Virtual-Internship---BA--DS
Virtual Intership project at British Airlines as Data Scientist

## Task - 1
Understand report and how i came to conclusions:
### files:
- BA_reviews.csv : raw data of all the reviews scraped from site.
- review_analyzed.csv : topics classifies with % match for every review
- Starting point.ipynb : sraped data from website and stored in csv. Later on cleaned the data, then used gensim to classify major topics and arrange review based on them.
- Sentiment Analysis Based on Keywords.ipynb : find keywords related to airlines industry, see their frequency used. then find top 20 keywords based on frequency. Now, take these keywords and see how they were used, in positive or negative manner and plotted graph based on it.
- Issues and their %.ipynb : using mojor topics from starting point.ipynb, plotted graphs

### My analysis:

#### Most used keywords: 
flight: 2091
seat: 1068
service: 766
crew: 500
food: 493
cabin: 418
airline: 405
customer: 310
delay: 277
boarding: 261
lounge: 219
comfort: 218
refund: 166
ticket: 156
booking: 140
baggage: 135
entertainment: 115
check-in: 114
legroom: 94
security: 78


##### Graph: 
![image](https://github.com/Himasnhu-AT/Virtual-Internship---BA--DS/assets/117301124/6dd68fc9-816e-419e-828c-8e63a397f719)


#### Most Topics talked about: 
- Topic 0: This topic discusses various aspects of flying with British Airways, including the seating arrangements, cabin space, meals, bedding, cabin crew, and arrival experience. It also mentions specific flights and airports such as Gatwick to Orlando, London to Frankfurt, and Venice to London City.
- Topic 1: This topic focuses on the experience of flying with British Airways in Club Europe (business class). It mentions the service provided by the cabin crew, the availability of Wi-Fi, baggage handling, lounges, boarding process, meals, and overall standards.
- Topic 2: This topic describes a negative experience with British Airways, particularly regarding flight delays, cancellations, and the ground handling at the airports. It mentions specific incidents at London Heathrow, waiting for luggage, lounge toilets, boarding, and lack of customer service.
- Topic 3: This topic highlights a positive experience with British Airways, specifically in Club Europe. It mentions friendly and helpful staff, efficient check-in, comfortable seats, power ports, in-flight service, meals, and baggage handling. It also includes feedback on baggage handling at Heathrow.
- Topic 4: This topic describes a frustrating experience with British Airways, focusing on a flight from London to Amsterdam. It mentions flight delays, airspace closures, cancellations, pilot and cabin crew communication, in-flight service, and ground handling. It also criticizes the handling of the situation by British Airways, including long queues, vouchers for sleeping on the floor, and difficulties with rebooking through the app.

##### Graph: 
![image](https://github.com/Himasnhu-AT/Virtual-Internship---BA--DS/assets/117301124/19e6c055-1c6a-4c57-b055-b9433af2308d)

![image](https://github.com/Himasnhu-AT/Virtual-Internship---BA--DS/assets/117301124/48a87e60-d30d-4228-8d13-e78052e08b5d)
