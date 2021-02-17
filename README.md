# exchangeRate
## requests analysis
### key requests
1. get the exchange rate.
2. remind user the relatively low price during a period by email.
### extra requests
1. everyday send email showing exchange rate of last day, we call it "everyday mail".
2. the content of mail as possible show these data by chart.
## flow path
1. crewler takes current exchange rate, the frequecny is 1 hour.
   https://www.boc.cn/sourcedb/whpj/
2. keep the message as a "package"
3. compare these "package" and choose the lowest one.
4. automatically send the "package" by email.
## technical difficulties
1. how to decide the parameter of crewler.(pyhton: beautiful soup)
2. how to save the data. 
3. how to edit a chart in mail by pyhton
## project time
total: 23 days
|crewler|"package"|data comparison|automatically send|
|:-----:|:------:|:------:|:------:|
|5|8|8|2|
