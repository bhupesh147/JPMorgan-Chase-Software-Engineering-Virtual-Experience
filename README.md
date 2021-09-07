# jp-morgan-chase-virtual-internship
This repository consists of my solutions to jp-morgan chase software engineering virtual internship <br>
### Overview : <br>
-> Development of an alternative way to visualize and analyze share price data for the traders 
which will alert them of potential trading opportunities. <br>

-> The visualization of charts and data analysis the trader’s see is built on JPMorgan Chase's
own open sourced software called Perspective. <br>

-> There were 3 tasks during this virtual Internship: <br>
### 1) Task 1 - Interface with a stock price data feed <br>
I added some development to add a chart to a trader’s dashboard 
allowing them to better identify under/over-valued stocks in perspective. The trader is now able to monitor two historically correlated stocks and able to 
visualize when the correlation between the two weakens. <br>
With the above solution all unit tests inside client_test.py, added/existing passes.
### 2) Task 2- Use JPMorgan Chase frameworks and tools <br>
The objective of this task was to fix the client-side web application so that it 
displays a graph that automatically updates as it gets data from the server application in Perspective.<br>
The continuous updates to the graph should be 
the result of continuous requests and responses to and from the server for the stock 
data.<br>
### 3) Task 3 - Display data visually for traders <br>
Generated a live graph that help the trader to quickly and easily notice when 
the ratio moves too far from the average historical correlation and 
finally, alerts are shown whenever these bounds are crossed by the ratio.



