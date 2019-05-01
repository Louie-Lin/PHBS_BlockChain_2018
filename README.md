# PHBS_BlockChain_2018


## Lin Liuyu: 1701213060

## 1. Development of Bitcoin
The concept of Bitcoin was first proposed by Nakamoto on November 1, 2008, and was formally born on January 3, 2009. Relying on the open source software designed and released by Zhongbencong and the P2P network constructed, Bitcoin came into being as a virtual encrypted digital currency in the form of P2P.

Bitcoin started with cryptography enthusiasts and cyberliberals. Its acquisition process is similar to the reward of cloud computing network puzzle-solving games. It has no market value and belongs to their hobbies. Subsequently, under the dual effects of pioneer demonstration and media publicity, the functions and characteristics of Bitcoin have been gradually discovered. As a result, the recipients have gradually moved from a small circle to the public, and the number of recipients and transactions has been increasing. The value of Bitcoin has also begun to fluctuate sharply but rising rapidly. The development of Bitcoin is shown in the following figure.  

![image](https://github.com/Louie-Lin/PHBS_BlockChain_2018/blob/master/n_users.png?raw=true)

![image](https://github.com/Louie-Lin/PHBS_BlockChain_2018/blob/master/usd_price_bitcoin.png?raw=true)

As a new currency, the public, scholars and the government have different views on Bitcoin. Proponents believe that it has the characteristics of the world currency, indicating the future of the monetary system; the opponents believe that it can not overcome its own shortcomings, prosperity is just a bubble, and will eventually burst. Although different governments have different definitions of Bitcoin, they mostly adopt policies that neither support nor completely prohibit Bitcoin, with some reservations. As a result, Bitcoin's market has always been volatile, because no one has the absolute advantage. 

## 2. Literature Research on Bitcoin
The research of Bitcoin in academic circles is mainly carried out at three levels: technology, economics and law. Among them, in the economic level, mainly around the four directions.

One is the introduction of Bitcoin's principle, characteristics, empirical research and forecasting analysis. Zhao Yandong et al. (2014) analyzed the credit characteristics of Bitcoin and its trading mode with RMB, believing that Bitcoin has certain investment value, but will not become the legal currency in the real world. Wu Hong et al. (2013) analyzed the background and reasons for the emergence of Bitcoin, compared and found that Bitcoin and gold index data in a certain period of time basically synchronized, providing the possibility that Bitcoin can act as a digital currency. 



The second is the research on the internal structure and development trend of Bit coin. Teigland et al. (2013) took the Bitcoin community as an institutionalized enterprise, analyzed its organizational structure and network structure, pointed out its strong self-repairing characteristics; Kondor et al. (2013) studied the evolution characteristics of its network structure and currency distribution through the empirical analysis of the time series of Bitcoin network characteristic data. 

The third is to conbine the economic theories such as monetary principles with the emergence of Bitcoin. Luther (2013) believes that money is essentially a recording tool for human behavior, and Bitcoin is returning to that essence. Selgin (2013) believes that Bitcoin belongs to man-made commodity currencies and has the potential to become a currency which does not need to be regulated and is conducive to maintaining macroeconomic stability. Sun et al. (2014) analyzed the characteristics of Bitcoin in the world currency, and concluded that Bitcoin has the characteristics of world currency. 

The fourth is to analyse the economic impact of Bitcoin and puts forward suggestions on regulation. Bryans (2013), ELIAS (2013) , Gruber (2013) and others have carried out research on the regulation of tax avoidance, money laundering and anonymous transactions of Bitcoin. 

## 3. Bitcoin Characteristics and Micro-Diffusion Dynamics 
This article mainly explores the factors that may affect the speed of Bitcoin diffusion. The first answer is based on the characteristics of Bitcoin and whether it has diffusion power. The answer is yes. Bitcoin has micro-diffusion power because of the following three characteristics. 

Firstly, Bitcoin has the characteristics of non-nationalization, de-centralization and liberalism. Bitcoin is not issued by the state, and there is no central node to control the currency and transaction management. It relies entirely on technology to achieve currency credit, and each network node is relatively equal. When the money controlled by the government enters the paper money era, the government sometimes overissues the money through its own needs, resulting in excessive money supply and currency devaluation. For individual users, it is usually a loss, and the issuance of Bitcoin cancels the monopoly of the government in issuing currency, bringing users special psychological satisfaction of fairness. 

Secondly, Bitcoin has the characteristics of total amount control, uniform currency issuance and deflation. Bitcoin issuing process is a hash algorithm decryption process carried out by computers on the network. Obtaining Bitcoin can be regarded as a reward for successful calculation and decryption. But the network protocol controls the total amount of money and the rhythm of currency issuance: there are finally 21 million bitcoins issued totally in 2140. With a certain amount of aggregate control, the public foresees deflation. As a result, the public will begin to participate in Bitcoin coin issuance, speculation and reserve in order to appreciate. 

Thirdly, Bitcoin has the advantages of concealment, transnational, mobility, convenience, security and unlimited separability. As a password currency, Bitcoin accounts do not reveal personal information, coupled with the lack of central agency control, the transaction has partial concealment. As a network currency, transactions are not subject to national boundaries, and transnational payment has little additional costs, so it can be used as a tool of exchange. At the same time, because of the distributed database with the whole network computing power as a security guarantee, the security and vitality of the network are also strongly guaranteed. To meet many special needs, Bitcoin has become one of the mainstream currencies in the underground economy. 

## 4. Evolutionary Game Model(Han et al. 2015)
Han's paper (2015) establishes an evolutionary game model in which the public can choose to use or not use Bitcoin. The return matrix of two different strategies for the public is as follows: 

![image](https://github.com/Louie-Lin/PHBS_BlockChain_2018/blob/master/return_matrix.png?raw=true)

where the **psy** is the psychological utility of using bitcoin, **exc** is the benefit of the appreciation (or depreciation) of bitcoin and **tra** is the benefit of the transaction of bitcoin.
If the proportion of people using Bitcoin is <img src="https://latex.codecogs.com/gif.latex?\eta" title="\eta" /> , then the average income of the group is: 

![image](https://github.com/Louie-Lin/PHBS_BlockChain_2018/blob/master/formula.png?raw=true)

The following are the evolutionary time maps of  <img src="https://latex.codecogs.com/gif.latex?\eta" title="\eta" />  under different conditions. It can be seen that **psy, exc and tra** are all factors affecting the diffusion speed of bitcoin. 

![image](https://github.com/Louie-Lin/PHBS_BlockChain_2018/blob/master/evolutionary_game_model%20.png?raw=true)

## 5. Empirical analysis and Results
This paper adopts the open data of **blockchain.info**, the largest online wallet and data statistics website of Bitcoin in the world. The time interval is 2013.05.01-2018.09.01, and the data is daily data.

As regard to the diffusion rate, the daily increase in the number of users of **my wallet**, the world's largest online Bitcoin wallet, is used as the proxy variable. As regard to **exc**, this paper uses the first-order difference of Bitcoin dollar price as the proxy variable, reflecting the earnings of holding money. As regard to **tra**, this paper uses the daily trading scale of Bitcoin as the proxy variable. The larger the scale, the lower the transaction cost, that is, the higher the transaction return. As for **psy**, this paper uses the proportion of miners' income in total trading volume as the proxy variable, because mining is the most unique monetary experience of Bitcoin users, with a high degree of participation and psychological satisfaction, which can be used to describe the psychological utility of Bitcoin users. 

According to the hypothesis, the equation is constructed as follows: 

![image](https://github.com/Louie-Lin/PHBS_BlockChain_2018/blob/master/formula_2.png?raw=true)

Where the **psy** is the proportion of miners' income in total trading volume, named **cost_per_transaction_percent**; The **exc** is first-order difference of Bitcoin dollar price, named **diff_usdprice**; The **tra** is the daily trading scale of Bitcoin, named **n_transactions**; 

Then the following is the regression result, and we can see that all of them are significant.

![image](https://github.com/Louie-Lin/PHBS_BlockChain_2018/blob/master/ols_result.png?raw=true)

## 6. Conclusion

Based on the foregoing, we draw the following conclusions:

1. The speed of diffusion varies in the same direction with the return on money holding, trading and psychological utility.            

2. Policies can effectively prevent the spread of Bitcoin. By controlling the intermediary, intermediary and transit platforms of Bitcoin transactions, the government can create obstacles in the process of the conversion of Bitcoin and legal currencies, increase the transaction cost of Bitcoin to a certain extent, and restrain the demand for Bitcoin transactions, investment demand and speculative space. 

## 7. References

## 8. Appendix: code
[Code_link](https://github.com/Louie-Lin/PHBS_BlockChain_2018/blob/master/ols_model.ipynb)
