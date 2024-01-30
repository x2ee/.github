# X2EE - X2 EnginE

Allows:
  * Own your data
  * Run trusted logic on it

## Why?

You should have control and privacy over your data and logic. Data and logic should be vendor independent and falt tollerant. Logic should not be aware where data is located. Data layer should make access transparent, keep redundat copies of the data for fault tollerance and may decide to move relevant protions of data to logic for better performance.  

Engine should account for execution and storage cost to make necessary trade-offs and maintain desired replication factor. In event of if one data replica become unavailable apps should keep running. Performance likely will be suffer for some period of time until relevant protions of data get replicated, but everithing should be running. Transition form one vendor to another including self-hosting should be transparent for applications.

## How?

  * X-Drive
  * X-Compute
