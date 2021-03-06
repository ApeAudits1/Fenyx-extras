## SÅ«rya's Description Report

### Files Description Table


|  File Name  |
|-------------|
| Fenyx.sol |


### Contracts Description Table


|  Contract  |         Type        |       Bases      |                  |                 |
|:----------:|:-------------------:|:----------------:|:----------------:|:---------------:|
|     â      |  **Function Name**  |  **Visibility**  |  **Mutability**  |  **Modifiers**  |
||||||
| **Context** | Implementation |  |||
| â | _msgSender | Internal ð |   | |
| â | _msgData | Internal ð |   | |
||||||
| **IERC20** | Interface |  |||
| â | totalSupply | External âï¸ |   |NOâï¸ |
| â | balanceOf | External âï¸ |   |NOâï¸ |
| â | transfer | External âï¸ | ð  |NOâï¸ |
| â | allowance | External âï¸ |   |NOâï¸ |
| â | approve | External âï¸ | ð  |NOâï¸ |
| â | transferFrom | External âï¸ | ð  |NOâï¸ |
||||||
| **SafeMath** | Library |  |||
| â | add | Internal ð |   | |
| â | sub | Internal ð |   | |
| â | sub | Internal ð |   | |
| â | mul | Internal ð |   | |
| â | div | Internal ð |   | |
| â | div | Internal ð |   | |
| â | mod | Internal ð |   | |
| â | mod | Internal ð |   | |
||||||
| **Address** | Library |  |||
| â | isContract | Internal ð |   | |
| â | sendValue | Internal ð | ð  | |
| â | functionCall | Internal ð | ð  | |
| â | functionCall | Internal ð | ð  | |
| â | functionCallWithValue | Internal ð | ð  | |
| â | functionCallWithValue | Internal ð | ð  | |
| â | _functionCallWithValue | Private ð | ð  | |
||||||
| **Ownable** | Implementation | Context |||
| â | <Constructor> | Public âï¸ | ð  |NOâï¸ |
| â | owner | Public âï¸ |   |NOâï¸ |
| â | renounceOwnership | Public âï¸ | ð  | onlyOwner |
| â | transferOwnership | Public âï¸ | ð  | onlyOwner |
| â | getUnlockTime | Public âï¸ |   |NOâï¸ |
| â | getTime | Public âï¸ |   |NOâï¸ |
| â | lock | Public âï¸ | ð  | onlyOwner |
| â | unlock | Public âï¸ | ð  |NOâï¸ |
||||||
| **IUniswapV2Factory** | Interface |  |||
| â | feeTo | External âï¸ |   |NOâï¸ |
| â | feeToSetter | External âï¸ |   |NOâï¸ |
| â | getPair | External âï¸ |   |NOâï¸ |
| â | allPairs | External âï¸ |   |NOâï¸ |
| â | allPairsLength | External âï¸ |   |NOâï¸ |
| â | createPair | External âï¸ | ð  |NOâï¸ |
| â | setFeeTo | External âï¸ | ð  |NOâï¸ |
| â | setFeeToSetter | External âï¸ | ð  |NOâï¸ |
||||||
| **IUniswapV2Pair** | Interface |  |||
| â | name | External âï¸ |   |NOâï¸ |
| â | symbol | External âï¸ |   |NOâï¸ |
| â | decimals | External âï¸ |   |NOâï¸ |
| â | totalSupply | External âï¸ |   |NOâï¸ |
| â | balanceOf | External âï¸ |   |NOâï¸ |
| â | allowance | External âï¸ |   |NOâï¸ |
| â | approve | External âï¸ | ð  |NOâï¸ |
| â | transfer | External âï¸ | ð  |NOâï¸ |
| â | transferFrom | External âï¸ | ð  |NOâï¸ |
| â | DOMAIN_SEPARATOR | External âï¸ |   |NOâï¸ |
| â | PERMIT_TYPEHASH | External âï¸ |   |NOâï¸ |
| â | nonces | External âï¸ |   |NOâï¸ |
| â | permit | External âï¸ | ð  |NOâï¸ |
| â | MINIMUM_LIQUIDITY | External âï¸ |   |NOâï¸ |
| â | factory | External âï¸ |   |NOâï¸ |
| â | token0 | External âï¸ |   |NOâï¸ |
| â | token1 | External âï¸ |   |NOâï¸ |
| â | getReserves | External âï¸ |   |NOâï¸ |
| â | price0CumulativeLast | External âï¸ |   |NOâï¸ |
| â | price1CumulativeLast | External âï¸ |   |NOâï¸ |
| â | kLast | External âï¸ |   |NOâï¸ |
| â | burn | External âï¸ | ð  |NOâï¸ |
| â | swap | External âï¸ | ð  |NOâï¸ |
| â | skim | External âï¸ | ð  |NOâï¸ |
| â | sync | External âï¸ | ð  |NOâï¸ |
| â | initialize | External âï¸ | ð  |NOâï¸ |
||||||
| **IUniswapV2Router01** | Interface |  |||
| â | factory | External âï¸ |   |NOâï¸ |
| â | WETH | External âï¸ |   |NOâï¸ |
| â | addLiquidity | External âï¸ | ð  |NOâï¸ |
| â | addLiquidityETH | External âï¸ |  ðµ |NOâï¸ |
| â | removeLiquidity | External âï¸ | ð  |NOâï¸ |
| â | removeLiquidityETH | External âï¸ | ð  |NOâï¸ |
| â | removeLiquidityWithPermit | External âï¸ | ð  |NOâï¸ |
| â | removeLiquidityETHWithPermit | External âï¸ | ð  |NOâï¸ |
| â | swapExactTokensForTokens | External âï¸ | ð  |NOâï¸ |
| â | swapTokensForExactTokens | External âï¸ | ð  |NOâï¸ |
| â | swapExactETHForTokens | External âï¸ |  ðµ |NOâï¸ |
| â | swapTokensForExactETH | External âï¸ | ð  |NOâï¸ |
| â | swapExactTokensForETH | External âï¸ | ð  |NOâï¸ |
| â | swapETHForExactTokens | External âï¸ |  ðµ |NOâï¸ |
| â | quote | External âï¸ |   |NOâï¸ |
| â | getAmountOut | External âï¸ |   |NOâï¸ |
| â | getAmountIn | External âï¸ |   |NOâï¸ |
| â | getAmountsOut | External âï¸ |   |NOâï¸ |
| â | getAmountsIn | External âï¸ |   |NOâï¸ |
||||||
| **IUniswapV2Router02** | Interface | IUniswapV2Router01 |||
| â | removeLiquidityETHSupportingFeeOnTransferTokens | External âï¸ | ð  |NOâï¸ |
| â | removeLiquidityETHWithPermitSupportingFeeOnTransferTokens | External âï¸ | ð  |NOâï¸ |
| â | swapExactTokensForTokensSupportingFeeOnTransferTokens | External âï¸ | ð  |NOâï¸ |
| â | swapExactETHForTokensSupportingFeeOnTransferTokens | External âï¸ |  ðµ |NOâï¸ |
| â | swapExactTokensForETHSupportingFeeOnTransferTokens | External âï¸ | ð  |NOâï¸ |
||||||
| **FENYX** | Implementation | Context, IERC20, Ownable |||
| â | tradingStatus | Public âï¸ |   |NOâï¸ |
| â | liquiditystatus | Public âï¸ |   |NOâï¸ |
| â | <Constructor> | Public âï¸ | ð  |NOâï¸ |
| â | name | Public âï¸ |   |NOâï¸ |
| â | symbol | Public âï¸ |   |NOâï¸ |
| â | decimals | Public âï¸ |   |NOâï¸ |
| â | totalSupply | Public âï¸ |   |NOâï¸ |
| â | balanceOf | Public âï¸ |   |NOâï¸ |
| â | transfer | Public âï¸ | ð  |NOâï¸ |
| â | allowance | Public âï¸ |   |NOâï¸ |
| â | approve | Public âï¸ | ð  |NOâï¸ |
| â | transferFrom | Public âï¸ | ð  |NOâï¸ |
| â | increaseAllowance | Public âï¸ | ð  |NOâï¸ |
| â | decreaseAllowance | Public âï¸ | ð  |NOâï¸ |
| â | isExcludedFromReward | Public âï¸ |   |NOâï¸ |
| â | totalFees | Public âï¸ |   |NOâï¸ |
| â | minimumTokensBeforeSwapAmount | Public âï¸ |   |NOâï¸ |
| â | buyBackUpperLimitAmount | Public âï¸ |   |NOâï¸ |
| â | deliver | Public âï¸ | ð  |NOâï¸ |
| â | reflectionFromToken | Public âï¸ |   |NOâï¸ |
| â | tokenFromReflection | Public âï¸ |   |NOâï¸ |
| â | excludeFromReward | Public âï¸ | ð  | onlyOwner |
| â | includeInReward | External âï¸ | ð  | onlyOwner |
| â | _approve | Private ð | ð  | |
| â | _transfer | Private ð | ð  | |
| â | callPyroBlast | External âï¸ | ð  | onlyOwner |
| â | swapTokens | Private ð | ð  | lockTheSwap |
| â | buyBackTokens | Private ð | ð  | lockTheSwap |
| â | swapTokensForEth | Private ð | ð  | |
| â | swapETHForTokens | Private ð | ð  | |
| â | addLiquidity | Private ð | ð  | |
| â | _tokenTransfer | Private ð | ð  | |
| â | _transferStandard | Private ð | ð  | |
| â | _transferToExcluded | Private ð | ð  | |
| â | _transferFromExcluded | Private ð | ð  | |
| â | _transferBothExcluded | Private ð | ð  | |
| â | _reflectFee | Private ð | ð  | |
| â | _getValues | Private ð |   | |
| â | _getTValues | Private ð |   | |
| â | _getRValues | Private ð |   | |
| â | _getRate | Private ð |   | |
| â | _getCurrentSupply | Private ð |   | |
| â | _takeLiquidity | Private ð | ð  | |
| â | calculateTaxFee | Private ð |   | |
| â | calculateLiquidityFee | Private ð |   | |
| â | removeAllFee | Private ð | ð  | |
| â | restoreAllFee | Private ð | ð  | |
| â | isExcludedFromFee | Public âï¸ |   |NOâï¸ |
| â | excludeFromFee | Public âï¸ | ð  | onlyOwner |
| â | includeInFee | Public âï¸ | ð  | onlyOwner |
| â | setTaxFeePercent | External âï¸ | ð  | onlyOwner |
| â | setLiquidityFeePercent | External âï¸ | ð  | onlyOwner |
| â | setMaxTxAmount | External âï¸ | ð  | onlyOwner |
| â | setMarketingDivisor | External âï¸ | ð  | onlyOwner |
| â | setNumTokensSellToAddToLiquidity | External âï¸ | ð  | onlyOwner |
| â | setBuybackUpperLimit | External âï¸ | ð  | onlyOwner |
| â | setMarketingAddress | External âï¸ | ð  | onlyOwner |
| â | setSwapAndLiquifyEnabled | Public âï¸ | ð  | onlyOwner |
| â | LiqudityAdded | Public âï¸ | ð  | onlyOwner |
| â | Topen | Public âï¸ | ð  | onlyOwner |
| â | setBuyBackEnabled | Public âï¸ | ð  | onlyOwner |
| â | prepareForPreSale | External âï¸ | ð  | onlyOwner |
| â | afterPreSale | External âï¸ | ð  | onlyOwner |
| â | transferToAddressETH | Private ð | ð  | |
| â | <Receive Ether> | External âï¸ |  ðµ |NOâï¸ |


### Legend

|  Symbol  |  Meaning  |
|:--------:|-----------|
|    ð    | Function can modify state |
|    ðµ    | Function is payable |
