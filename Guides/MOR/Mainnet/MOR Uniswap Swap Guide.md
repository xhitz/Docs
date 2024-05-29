# MOR Uniswap Swap Guide

>[!WARNING]
> **Trading on decentralized exchanges like Uniswap involves inherent risks, including but not limited to slippage and liquidity risk, smart contract risk, impermanent loss, scams. It's advisable to do your research and understand the risks before engaging in any trading activities.**

---

## Introduction
This guide will familiarize you with the basic functions of the decentralized exchange Uniswap, particularly token management and swaps. The Metamask wallet is used as a reference in this guide, but the logic remains the same for other Web3 wallets.

---

## Table of contents
1) [Smart Contract Addresses](#smart-contract-addresses)
2) [Connect to Uniswap](#connect-wallet-to-uniswap)
3) [Prepare to swap](#prepare-to-swap)
4) [Swap tokens](#how-to-swap-tokens-on-uniswap)
5) [Add MOR to Metamask](#add-mor-to-metamask)
6) [Sell MOR tokens](#how-to-sell-mor-tokens-on-uniswap)
7) [Unwrap wETH into ETH](#how-to-unwrap-weth-into-eth)

---

## Smart Contract Addresses
Arbitrum mainnet:  

**MOR Token:** [0x092bAaDB7DEf4C3981454dD9c0A0D7FF07bCFc86](https://arbiscan.io/token/0x092bAaDB7DEf4C3981454dD9c0A0D7FF07bCFc86)  

**wETH Token** [0x82aF49447D8a07e3bd95BD0d56f35241523fBab1](https://arbiscan.io/token/0x82aF49447D8a07e3bd95BD0d56f35241523fBab1)

---

## Connect wallet to Uniswap
Go to the Uniswap web app https://app.uniswap.org and choose Arbitrum chain in the top right corner of the screen.


<img src="/Graphics/Docs%20Graphics/English/Uniswap%20Guide/arb.png" width=100% height=100%>

Click **"Connect"** button 

<img src="/Graphics/Docs%20Graphics/English/Uniswap%20Guide/connect1.png" width=100% height=100%>

Select the wallet you would like to connect and approve the connection.  

Once approved your wallet will be connected!

<img src="/Graphics/Docs%20Graphics/English/Uniswap%20Guide/connect2.png" width=100% height=100%>

---

## Prepare to swap
Go to the Uniswap web app SWAP page [https://app.uniswap.org/swap](https://app.uniswap.org/swap?chain=arbitrum), search for and select tokens you wish to swap.

> [!NOTE]
> **In the example below we will buy MOR with wETH, but the process is the same for swaps in both directions.**
> 
> **You can NOT swap MOR until 12:00 UTC May 8th**

Click on **You pay** (token you want to sell) field drop-down menu and select wETH token (or another token you want to swap to MOR)

<img src="/Graphics/Docs%20Graphics/English/Uniswap%20Guide/select%20weth.png" width=75% height=75%>

Perform the same actions with **You receive** (token you want to buy) field.  

You will not be able to find MOR token in the list, so we need to add it manually. 

For this, input MOR token smart contract address `0x092bAaDB7DEf4C3981454dD9c0A0D7FF07bCFc86` into the search field and click on **MOR** to add it.

<img src="/Graphics/Docs%20Graphics/English/Uniswap%20Guide/select%20mor.png" width=75% height=75%>

If the warning message pops up, read it and click **I understand**. That is the standard warning for new tokens.

<img src="/Graphics/Docs%20Graphics/English/Uniswap%20Guide/warning.png" width=45% height=45%>


## How to swap tokens on Uniswap?

Enter the amount of tokens you want to sell in **You pay** field, the amount of tokens **You receive** will calculate automatically accordingly to the current price.  

Check conditions, click **Swap.** 

<img src="/Graphics/Docs%20Graphics/English/Uniswap%20Guide/swap%20weth%20mor.png" width=45% height=45%>

Approve spendings for the token you are swapping, sign message and confirm swap.  

For more information on token approvals see this [article](https://support.uniswap.org/hc/en-us/articles/8120520483085-What-is-an-approval-transaction).

> [!TIP]
> The best cybersecurity practice is to approve only amount you want to spend.

<img src="/Graphics/Docs%20Graphics/English/Uniswap%20Guide/approve%20weth.png" width=40% height=40%>

After swap transaction is confirmed, you will see updated balances.  

<img src="/Graphics/Docs%20Graphics/English/Uniswap%20Guide/swap%20successs.png" width=50% height=50%>

---

## Add MOR to Metamask
To add MOR token to your Metamask wallet token list, you need to follow steps from the [guide](https://support.metamask.io/managing-my-tokens/custom-tokens/how-to-display-tokens-in-metamask/#how-to-add-a-custom-token) and add MOR smart contract address: 

`0x092baadb7def4c3981454dd9c0a0d7ff07bcfc86`

After performing these steps you will be able to see MOR token balance in the tokens section of your Metamask wallet. 

<img src="/Graphics/Docs%20Graphics/English/MOR%20Claim%20Test%20Guide/import%20MOR.png" width=45% height=45%>
  
---

## How to sell MOR tokens on Uniswap

### Prepare to sell MOR tokens

Go to the Uniswap web app SWAP page [https://app.uniswap.org/swap](https://app.uniswap.org/swap?chain=arbitrum) search for and select tokens you wish to swap.

> [!NOTE]
> **In the example below we will sale MOR for wETH, but the process is the same for swaps in both directions.**
> 

Click on **You pay** (token you want to sell) field drop-down menu and select **MOR** token.

<img alt="github" src="https://github.com/antonbosss/Docs/assets/4604698/329a7965-9500-43c4-aa9d-3007e84dd0da" width=75% height=75%>

Perform the same actions with **You receive** (token you want to buy) field. Select **wETH** token (or another token you want to receive).

<img alt="github_doc" src="https://github.com/antonbosss/Docs/assets/4604698/77650fa2-97d6-4bf4-bf4c-8f5b33c31400" width=75% height=75%>

### Selling MOR tokens

Enter the amount of MOR tokens you want to sell in **You pay** field, the amount of tokens **You receive** will calculate automatically according to the current price.

Check conditions, click **Swap**

<img alt="github_sale" src="https://github.com/antonbosss/Docs/assets/4604698/57cd2396-ed15-4ee1-9ba4-ff524adcfaa7" width=75% height=75%>

Approve spendings for the MOR token, and confirm the swap. 

<img alt="github_swap" src="https://github.com/antonbosss/Docs/assets/4604698/65111428-4c5a-4c94-82e5-d1671c748fbf" width=75% height=75%>

After the swap transaction is confirmed, you will see updated balances in your wallet. 

<img alt="github_sale4" src="https://github.com/antonbosss/Docs/assets/4604698/6a3b29d6-f2bb-4f0d-b3b5-3677c457e6f8" width=75% height=75%>

---

## How to unwrap wETH into ETH 

### Prepare to unwrap wETH 

Go to the Uniswap web app SWAP page [https://app.uniswap.org/swap](https://app.uniswap.org/swap?chain=arbitrum).

Click on **You pay** (token you want to sell) field drop-down menu and select **wETH** token.

<img alt="You_Pay_Unwrap" src="https://github.com/antonbosss/Docs/assets/4604698/4a3d6db8-c61e-47ac-90f6-74ac9d843ed0" width=75% height=75%>

Perform the same actions with **You receive** (token you want to buy) field and select ETH. 

<img alt="unwrap_3" src="https://github.com/antonbosss/Docs/assets/4604698/e5b33cf5-0388-46bc-b4a5-4d9427ed4aae" width=75% height=75%>

### How to unwrap wETH into ETH

Enter the amount of wETH you want to unwrap in **You pay** field, the amount of ETH you will receive will calculate automatically.

Check conditions, click **Unwrap.**

<img alt="unwrap_all" src="https://github.com/antonbosss/Docs/assets/4604698/192d10da-a6bf-4163-a7f5-4f57867fe3de" width=75% height=75%> 

Approve the spendings for the wETH token, and confirm the swap. 

After the transaction is confirmed, you will see updated ETH balance in your wallet. 

<img alt="unwrap_6" src="https://github.com/antonbosss/Docs/assets/4604698/6cb980f2-2326-48f8-9cb3-2ce16484a9d5" width=75% height=75%>

---

> [!TIP]  
> **In case you face difficulties, find something unclear, or have questions, you can get assistance in the** [**Morpheus Discord server**](https://discord.com/channels/1151741790408429580/1183666837460897832).
>
> **If you need more information about Uniswap exchange functions, please refer to the official Uniswap** [**support page.**](https://support.uniswap.org/hc/en-us ) 

## Beware of scams, Morpheus has no tech support team, no support tickets and will not commence any airdrops. Anyone who message you with proposal to help is likely a scammer.

