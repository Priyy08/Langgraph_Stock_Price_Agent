## It is an Langgraph workflow which demonstrates how llm connect to finance API's like yfinance to fetch stock prices with natural language prompt into system.

## Core concepts:

1) Sequential flows where natural language message from user is converted into well parsed data then these parsed data is further sent to price_tool_node function for
further Calls yfinance to fetch stock price for given symbol and time then final formatter_node gives final text response with proper output which describe the symbol
company and price.

2) Using Langchain's structured LLM Output feature which outputs response in well formatted json format which greatly helps in tool invocation which is greatly effective
where passing of proper json objects is crucial in external API's, DB's etc to communicate and pass proper values back and forth for AI Agent's Data retrieval.

Note: This is an simple langgraph workflow which demonstrates how simple sequential workflows are made and how they can be used to build agents with inter agent State
passing and here it is an python only implementation which explains the core logic to build nodes and how to connect the nodes with edges to acheive an real life Agent
Workflow.
