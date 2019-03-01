```.py

def makeStkContract(sym):
    newStkContract = Contract()
    newStkContract.m_symbol = sym
    newStkContract.m_conId = 0
    newStkContract.m_secType = 'STK'
    newStkContract.m_exchange = 'SMART'
    newStkContract.m_currency = 'USD'
    return newStkContract
```
