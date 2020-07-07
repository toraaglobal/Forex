***
## Forex
***
Stream Oanda price from api. Automate a trading strategy and store all orders created by the automated strategy and price information in postgres database.

***
### Requirement
***
**postgres database : follow this link. https://www.postgresql.org/download/ to download locally**
**Oanda credentials : its free, you can get one from here. https://www.oanda.com/us-en/**

***
### Installation
***
**Clone the repo using the comman below**
```
git clone 
```

**Open the file `database.cfg` in config folder to set your credentials.**

**First you will need to initiaize the database by running the command below**
```
python fxdb_init.py
```

**To run the auto pilot, use the following command. To change the strategy go to `Change Strategy` for instruction.**
```
python auto_pilot.py 
```

***
### Change Strategy
***

* 

***
### License
***
**MIT**


***
### Disclaimer
***
<span style="color:red"> Trading foreign exchange on margin carries a high level of risk, and may not be suitable for all investors. Past performance is not indicative of future results. The high degree of leverage can work against you as well as for you. Before deciding to invest in foreign exchange you should carefully consider your investment objectives, level of experience, and risk appetite. The possibility exists that you could sustain a loss of some or all of your initial investment and therefore you should not invest money that you cannot afford to lose. You should be aware of all the risks associated with foreign exchange trading, and seek advice from an independent financial advisor if you have any doubts. </span>





