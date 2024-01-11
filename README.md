


COVID-19 🦠 API😷
GitHub license  GitHub top language GitHub top language

A GraphQL Express Server powered by @covid19india/api to provide COVID-19 related stats for India 🇮🇳
COVID-19 Tracker ღ Dashboard




COVID-19 Tracker | India - Get real-time state wise stats of COVID-19 in India | Product Hunt Embed

Setup
npm install && npm start
Steps Explained
Open terminal and run npm install

Run npm start

Open browser and go to http://localhost:8080/graphql

Type the queries and enjoy! 😄

Run npm run server for local development

Queries
GET overall COVID-19 stats
{ 
  total {
    active
    confirmed
    deaths
    recovered
  }
}
GET statewise COVID-19 stats
{
  statewise {
    state
    active
    confirmed
    deaths
    recovered
  }
}
GET datewise COVID-19 stats
{
  datewise {
    date
    dailyconfirmed
    dailydeceased
    dailyrecovered
  }
}
Dependencies Used
express: A web application framework for Node.js

graphql: The JavaScript reference implementation for GraphQL

express-graphql: A GraphQL HTTP Server middleware

Related Work
COVID-19 Tracker - INDIA - A React App with the following features:

Graphs showing daily confirmed, recovered and deceased cases
State-wise report presented in Map of India
Tabular data for global corona cases
Latest news about COVID-19
Additional resources such as symptoms, precautions etc.
India Fights Corona - Get current COVID-19 stats!

COVID-19 Tracker - Homepage

An Open Letter to all the contributors - STAY HOME, STAY SAFE!

License
FOSSA Status

< /> with ♡ by



Open Source Love

Leave a ⭐
repository. Consider leaving a star! ❤️ 🤗

if (_.isAwesome(thisRepo)) {
  thisRepo.star(); // thanks in advance :p
}
