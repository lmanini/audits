# My findings

- Multiple calls to SingleSidedLiquidityVault#claimRewards() allow user to extract more tokens than they are rewarded: [issue](https://github.com/sherlock-audit/2023-02-olympus-judging/issues/74)
- Amount of exiting tokens isn't checked when calling SingleSidedLiquidityVault#claimRewards(): [issue](https://github.com/sherlock-audit/2023-02-olympus-judging/issues/73)