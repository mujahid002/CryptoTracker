# Cryto-tracker

By using react.js and frontend skills like html,css,js and by using coingecko api(for prices,volume,Mcap and etc) i builted crypto tracker 
in react i had used useState, useEffect and axions for my project.

with my project i had builted chrome extension of crypto tracking with id of,

ID: oldmdcjbaipgpigdcbabflbjgoejkclo

later for my practices i deploy this API project into cloud(AWS) also.


manifest format
///////////////////////////////////////////////////////////////////////////
{
  "name": "Crypto Tracker",
  "version": "1.0.0",
  "description": "prices,volume,market-cap of top crytocurrencies",
  "manifest_version": 3,
  "author": "Mujahid Shaik",
  "action":{
      "default_popup": "index.html",
      "default_title": "Crypto Tracking"
  },
  "icons":{
    "128":"logo.jpeg"
  }
}
///////////////////////////////////////////////////////////////////////////
