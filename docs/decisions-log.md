Log time: 23 oct 2026 12:43 
Since the nova data collection collets multiple tests per booking, we are adopting the approach to first convert it into a dataframe and then apply explode(), so that each row retuns a single test. 


After that we merged the nova data with legacy data. 

