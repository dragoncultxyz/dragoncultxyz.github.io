# Dragon Cult $XYZ Lite Paper
Dragon Cult is building $XYZ. Treasury wrapped token inspired by olympus and safemoon.
Visit:
https://dragoncult.xyz to explore.

## How It Work
![diagram](https://user-images.githubusercontent.com/127600210/225184015-96e75e9e-2230-4f88-9205-6f640c7001cc.png)

## Total Supply of $XYZ Token
$XYZ token is mintable and burnable ERC20 token. It can be minted only by treasury contract, but can be burned by the owner. 
The supply set by formula: 
```
supply = treasury_assets_value / cult_swap_price
``` 
By the same formula: *cult_swap_price = treasury_assets_value / supply* this mean price will increase if *treasury_assets_value* increase or *supply* decrease.

## Distribution of $XYZ Token

![meta-chart](https://user-images.githubusercontent.com/127600210/225186230-7cdcc358-08b0-469a-a685-c08f6491dd56.png)

Every 24 hours 30% / 365 = 0.082% XYZ will be minted based on existing supply. 1/3 transfered to cult free claim, 2/3 transfered to cult vault. 
Distribution percentage may change later, after vote by nft implemented. 

After alpha test over, the percentage will be reduced from 30% to 14% (7%/7% for daily reward/vault reward)

## Price of $XYZ Token
Price of $XYZ token soft pegged to assets value within treasury. In theory if treasury value always increase, the price always increase.

Treasury value ⬆️ on:
- cult $CFX staking interest used to buy $XYZ
- bought $XYZ got burned
- trading fee from cult-only swap to treasury
- arbitrage profit between cult-only swap & swappi

Treasury value ⬇️ on:
- cult only $XYZ daily claim
- reward on cult only vault

Protocol designed to ensure value increase > value decrease.

## Requirement to Become Cult Member
To mint membership NFT, user need to deposit 1000 $CFX to NFT contract. User can withdraw his deposits by burning the NFT. There are 14 days for burn function to be enabled, and 2 days to withdraw $CFX.

$CFX deposits from cult member will be staked in conflux pos pool, and every hour the interest will be used to buy $XYZ. Bought $XYZ will be burned.

1000 $CFX is minimal requirement to stake in pos pool, but there is chance the amount will be reduced at the future as DAO decision.

## Arbitrage Between Swappi and Cult Swap
Sometimes price between cult swap and swappi differ too much. This happen because swappi currently have low liquidity. This is bad for the cult if lack liquidity make $XYZ easy to be pumped and later dumped in swappi.

The cult currently running a bot to ensure the price between cult swap and swappi always in synch.
It simply work like these:
- if cult swap price cheaper, bot will buy in cult swap and sell in swappi.
- if swappi price cheaper, bot will buy from swappi and sell in cult swap.
- profit from this arbitrage opportunity added to treasury, automatically increase price.

Every cult member also can do this arbitrage without bot, by doing the steps above manually.

## How to Start
- ordinary user just need to trade or buy and hold on swappi, or become cult member..
- go to https://dragoncult.xyz
- have 1000 $CFX staked to mint cult nft
- leave the cult by burn the nft. User will receive 1000 $CFX back

## What To Do as Ordinary User
- buy $XYZ in swappi
- get XYZ-USDT LP token from swappi
- stake on cult vault (opened to public)

## What To Do as Cult Member
- claim free $XYZ every 24 hour
- trade $XYZ in cult-only swap. it is cheaper than swappi
- stake in cult-only vault for high APY
- attach avatar on your NFT
- calling all $CFX believer to join our cult!

