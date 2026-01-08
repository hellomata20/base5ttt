# base5ttt
Counting Token Transfers Per Block
transfers = token.events.Transfer().get_logs(fromBlock=block.number, toBlock=block.number)
print(len(transfers))
