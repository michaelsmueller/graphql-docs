# Schema Types

<details>
  <summary><strong>Table of Contents</strong></summary>

- [Schema Types](#schema-types)
  - [Query](#query)
  - [Objects](#objects)
    - [Account](#account)
    - [Asset](#asset)
    - [Global](#global)
    - [Loan](#loan)
    - [LoanPosition](#loanposition)
    - [Maple](#maple)
    - [MplRewards](#mplrewards)
    - [Pool](#pool)
    - [PoolPosition](#poolposition)
    - [Repayment](#repayment)
    - [Subscription](#subscription)
    - [Transaction](#transaction)
    - [Tx](#tx)
    - [_Block_](#block)
    - [_Meta_](#meta)
    - [\_loanMap](#_loanmap)
    - [\_loanPositionMap](#_loanpositionmap)
    - [\_poolMap](#_poolmap)
    - [\_poolPositionMap](#_poolpositionmap)
    - [\_priceFeedAssetMap](#_pricefeedassetmap)
    - [\_stakeLockerPoolMap](#_stakelockerpoolmap)
  - [Inputs](#inputs)
    - [Account_filter](#account_filter)
    - [Asset_filter](#asset_filter)
    - [Block_height](#block_height)
    - [Global_filter](#global_filter)
    - [LoanPosition_filter](#loanposition_filter)
    - [Loan_filter](#loan_filter)
    - [Maple_filter](#maple_filter)
    - [MplRewards_filter](#mplrewards_filter)
    - [PoolPosition_filter](#poolposition_filter)
    - [Pool_filter](#pool_filter)
    - [Repayment_filter](#repayment_filter)
    - [Transaction_filter](#transaction_filter)
    - [Tx_filter](#tx_filter)
    - [\_loanMap_filter](#_loanmap_filter)
    - [\_loanPositionMap_filter](#_loanpositionmap_filter)
    - [\_poolMap_filter](#_poolmap_filter)
    - [\_poolPositionMap_filter](#_poolpositionmap_filter)
    - [\_priceFeedAssetMap_filter](#_pricefeedassetmap_filter)
    - [\_stakeLockerPoolMap_filter](#_stakelockerpoolmap_filter)
  - [Enums](#enums)
    - [Account_orderBy](#account_orderby)
    - [Asset_orderBy](#asset_orderby)
    - [Global_orderBy](#global_orderby)
    - [LoanPosition_orderBy](#loanposition_orderby)
    - [LoanState](#loanstate)
    - [Loan_orderBy](#loan_orderby)
    - [Maple_orderBy](#maple_orderby)
    - [MplRewards_orderBy](#mplrewards_orderby)
    - [OrderDirection](#orderdirection)
    - [PoolPosition_orderBy](#poolposition_orderby)
    - [PoolState](#poolstate)
    - [Pool_orderBy](#pool_orderby)
    - [Repayment_orderBy](#repayment_orderby)
    - [Transaction_orderBy](#transaction_orderby)
    - [TxType](#txtype)
    - [Tx_orderBy](#tx_orderby)
    - [_SubgraphErrorPolicy_](#subgrapherrorpolicy)
    - [\_loanMap_orderBy](#_loanmap_orderby)
    - [\_loanPositionMap_orderBy](#_loanpositionmap_orderby)
    - [\_poolMap_orderBy](#_poolmap_orderby)
    - [\_poolPositionMap_orderBy](#_poolpositionmap_orderby)
    - [\_priceFeedAssetMap_orderBy](#_pricefeedassetmap_orderby)
    - [\_stakeLockerPoolMap_orderBy](#_stakelockerpoolmap_orderby)
  - [Scalars](#scalars)
    - [BigDecimal](#bigdecimal)
    - [BigInt](#bigint)
    - [Boolean](#boolean)
    - [Bytes](#bytes)
    - [ID](#id)
    - [Int](#int)
    - [String](#string)

</details>

## Query

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong>global</strong></td>
<td valign="top"><a href="#global">Global</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>globals</strong></td>
<td valign="top">[<a href="#global">Global</a>!]!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">skip</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderBy</td>
<td valign="top"><a href="#global_orderby">Global_orderBy</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderDirection</td>
<td valign="top"><a href="#orderdirection">OrderDirection</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">where</td>
<td valign="top"><a href="#global_filter">Global_filter</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>maple</strong></td>
<td valign="top"><a href="#maple">Maple</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>maples</strong></td>
<td valign="top">[<a href="#maple">Maple</a>!]!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">skip</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderBy</td>
<td valign="top"><a href="#maple_orderby">Maple_orderBy</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderDirection</td>
<td valign="top"><a href="#orderdirection">OrderDirection</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">where</td>
<td valign="top"><a href="#maple_filter">Maple_filter</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>asset</strong></td>
<td valign="top"><a href="#asset">Asset</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>assets</strong></td>
<td valign="top">[<a href="#asset">Asset</a>!]!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">skip</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderBy</td>
<td valign="top"><a href="#asset_orderby">Asset_orderBy</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderDirection</td>
<td valign="top"><a href="#orderdirection">OrderDirection</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">where</td>
<td valign="top"><a href="#asset_filter">Asset_filter</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool</strong></td>
<td valign="top"><a href="#pool">Pool</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pools</strong></td>
<td valign="top">[<a href="#pool">Pool</a>!]!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">skip</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderBy</td>
<td valign="top"><a href="#pool_orderby">Pool_orderBy</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderDirection</td>
<td valign="top"><a href="#orderdirection">OrderDirection</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">where</td>
<td valign="top"><a href="#pool_filter">Pool_filter</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loan</strong></td>
<td valign="top"><a href="#loan">Loan</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loans</strong></td>
<td valign="top">[<a href="#loan">Loan</a>!]!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">skip</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderBy</td>
<td valign="top"><a href="#loan_orderby">Loan_orderBy</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderDirection</td>
<td valign="top"><a href="#orderdirection">OrderDirection</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">where</td>
<td valign="top"><a href="#loan_filter">Loan_filter</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>mplRewards</strong></td>
<td valign="top"><a href="#mplrewards">MplRewards</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>mplRewards</strong></td>
<td valign="top">[<a href="#mplrewards">MplRewards</a>!]!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">skip</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderBy</td>
<td valign="top"><a href="#mplrewards_orderby">MplRewards_orderBy</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderDirection</td>
<td valign="top"><a href="#orderdirection">OrderDirection</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">where</td>
<td valign="top"><a href="#mplrewards_filter">MplRewards_filter</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolPosition</strong></td>
<td valign="top"><a href="#poolposition">PoolPosition</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolPositions</strong></td>
<td valign="top">[<a href="#poolposition">PoolPosition</a>!]!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">skip</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderBy</td>
<td valign="top"><a href="#poolposition_orderby">PoolPosition_orderBy</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderDirection</td>
<td valign="top"><a href="#orderdirection">OrderDirection</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">where</td>
<td valign="top"><a href="#poolposition_filter">PoolPosition_filter</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loanPosition</strong></td>
<td valign="top"><a href="#loanposition">LoanPosition</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loanPositions</strong></td>
<td valign="top">[<a href="#loanposition">LoanPosition</a>!]!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">skip</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderBy</td>
<td valign="top"><a href="#loanposition_orderby">LoanPosition_orderBy</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderDirection</td>
<td valign="top"><a href="#orderdirection">OrderDirection</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">where</td>
<td valign="top"><a href="#loanposition_filter">LoanPosition_filter</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>repayment</strong></td>
<td valign="top"><a href="#repayment">Repayment</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>repayments</strong></td>
<td valign="top">[<a href="#repayment">Repayment</a>!]!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">skip</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderBy</td>
<td valign="top"><a href="#repayment_orderby">Repayment_orderBy</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderDirection</td>
<td valign="top"><a href="#orderdirection">OrderDirection</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">where</td>
<td valign="top"><a href="#repayment_filter">Repayment_filter</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>account</strong></td>
<td valign="top"><a href="#account">Account</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>accounts</strong></td>
<td valign="top">[<a href="#account">Account</a>!]!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">skip</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderBy</td>
<td valign="top"><a href="#account_orderby">Account_orderBy</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderDirection</td>
<td valign="top"><a href="#orderdirection">OrderDirection</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">where</td>
<td valign="top"><a href="#account_filter">Account_filter</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>tx</strong></td>
<td valign="top"><a href="#tx">Tx</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>txes</strong></td>
<td valign="top">[<a href="#tx">Tx</a>!]!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">skip</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderBy</td>
<td valign="top"><a href="#tx_orderby">Tx_orderBy</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderDirection</td>
<td valign="top"><a href="#orderdirection">OrderDirection</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">where</td>
<td valign="top"><a href="#tx_filter">Tx_filter</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction</strong></td>
<td valign="top"><a href="#transaction">Transaction</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transactions</strong></td>
<td valign="top">[<a href="#transaction">Transaction</a>!]!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">skip</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderBy</td>
<td valign="top"><a href="#transaction_orderby">Transaction_orderBy</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderDirection</td>
<td valign="top"><a href="#orderdirection">OrderDirection</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">where</td>
<td valign="top"><a href="#transaction_filter">Transaction_filter</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeLockerPoolMap</strong></td>
<td valign="top"><a href="#_stakelockerpoolmap">_stakeLockerPoolMap</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeLockerPoolMaps</strong></td>
<td valign="top">[<a href="#_stakelockerpoolmap">_stakeLockerPoolMap</a>!]!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">skip</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderBy</td>
<td valign="top"><a href="#_stakelockerpoolmap_orderby">_stakeLockerPoolMap_orderBy</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderDirection</td>
<td valign="top"><a href="#orderdirection">OrderDirection</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">where</td>
<td valign="top"><a href="#_stakelockerpoolmap_filter">_stakeLockerPoolMap_filter</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>priceFeedAssetMap</strong></td>
<td valign="top"><a href="#_pricefeedassetmap">_priceFeedAssetMap</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>priceFeedAssetMaps</strong></td>
<td valign="top">[<a href="#_pricefeedassetmap">_priceFeedAssetMap</a>!]!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">skip</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderBy</td>
<td valign="top"><a href="#_pricefeedassetmap_orderby">_priceFeedAssetMap_orderBy</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderDirection</td>
<td valign="top"><a href="#orderdirection">OrderDirection</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">where</td>
<td valign="top"><a href="#_pricefeedassetmap_filter">_priceFeedAssetMap_filter</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loanPositionMap</strong></td>
<td valign="top"><a href="#_loanpositionmap">_loanPositionMap</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loanPositionMaps</strong></td>
<td valign="top">[<a href="#_loanpositionmap">_loanPositionMap</a>!]!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">skip</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderBy</td>
<td valign="top"><a href="#_loanpositionmap_orderby">_loanPositionMap_orderBy</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderDirection</td>
<td valign="top"><a href="#orderdirection">OrderDirection</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">where</td>
<td valign="top"><a href="#_loanpositionmap_filter">_loanPositionMap_filter</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loanMap</strong></td>
<td valign="top"><a href="#_loanmap">_loanMap</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loanMaps</strong></td>
<td valign="top">[<a href="#_loanmap">_loanMap</a>!]!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">skip</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderBy</td>
<td valign="top"><a href="#_loanmap_orderby">_loanMap_orderBy</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderDirection</td>
<td valign="top"><a href="#orderdirection">OrderDirection</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">where</td>
<td valign="top"><a href="#_loanmap_filter">_loanMap_filter</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolPositionMap</strong></td>
<td valign="top"><a href="#_poolpositionmap">_poolPositionMap</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolPositionMaps</strong></td>
<td valign="top">[<a href="#_poolpositionmap">_poolPositionMap</a>!]!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">skip</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderBy</td>
<td valign="top"><a href="#_poolpositionmap_orderby">_poolPositionMap_orderBy</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderDirection</td>
<td valign="top"><a href="#orderdirection">OrderDirection</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">where</td>
<td valign="top"><a href="#_poolpositionmap_filter">_poolPositionMap_filter</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolMap</strong></td>
<td valign="top"><a href="#_poolmap">_poolMap</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolMaps</strong></td>
<td valign="top">[<a href="#_poolmap">_poolMap</a>!]!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">skip</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderBy</td>
<td valign="top"><a href="#_poolmap_orderby">_poolMap_orderBy</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderDirection</td>
<td valign="top"><a href="#orderdirection">OrderDirection</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">where</td>
<td valign="top"><a href="#_poolmap_filter">_poolMap_filter</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>_meta</strong></td>
<td valign="top"><a href="#_meta_">_Meta_</a></td>
<td>

Access to subgraph metadata

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
</tbody>
</table>

## Objects

### Account

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong>id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalPoolTokenBalance</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalPoolTokensStaked</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalRewardPaid</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalClaimableInterest</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalInterestEarned</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalStake</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalStakeLockerTokensStaked</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalStakeRewardPaid</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalClaimableFees</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalFeesEarned</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>txes</strong></td>
<td valign="top">[<a href="#tx">Tx</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">skip</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderBy</td>
<td valign="top"><a href="#tx_orderby">Tx_orderBy</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderDirection</td>
<td valign="top"><a href="#orderdirection">OrderDirection</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">where</td>
<td valign="top"><a href="#tx_filter">Tx_filter</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loans</strong></td>
<td valign="top">[<a href="#loan">Loan</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">skip</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderBy</td>
<td valign="top"><a href="#loan_orderby">Loan_orderBy</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderDirection</td>
<td valign="top"><a href="#orderdirection">OrderDirection</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">where</td>
<td valign="top"><a href="#loan_filter">Loan_filter</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolPositions</strong></td>
<td valign="top">[<a href="#poolposition">PoolPosition</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">skip</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderBy</td>
<td valign="top"><a href="#poolposition_orderby">PoolPosition_orderBy</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderDirection</td>
<td valign="top"><a href="#orderdirection">OrderDirection</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">where</td>
<td valign="top"><a href="#poolposition_filter">PoolPosition_filter</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>managedPools</strong></td>
<td valign="top">[<a href="#pool">Pool</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">skip</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderBy</td>
<td valign="top"><a href="#pool_orderby">Pool_orderBy</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderDirection</td>
<td valign="top"><a href="#orderdirection">OrderDirection</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">where</td>
<td valign="top"><a href="#pool_filter">Pool_filter</a></td>
<td></td>
</tr>
</tbody>
</table>

### Asset

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong>id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>decimals</strong></td>
<td valign="top"><a href="#int">Int</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>isValidCollateralAsset</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>isValidLiquidityAsset</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>isValidStakeAsset</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>amount</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>amountAsLiquidity</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>price</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>priceFeed</strong></td>
<td valign="top"><a href="#bytes">Bytes</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lastPriceUpdateTimestamp</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### Global

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong>id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>defaultGracePeriod</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>swapOutRequired</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>fundingPeriod</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>investorFee</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>treasuryFee</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>maxSwapSlippage</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>minLoanEquity</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakerCooldownPeriod</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lpCooldownPeriod</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakerUnstakeWindow</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lpWithdrawWindow</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### Loan

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong>id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>version</strong></td>
<td valign="top"><a href="#int">Int</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>state</strong></td>
<td valign="top"><a href="#loanstate">LoanState</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>name</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>borrower</strong></td>
<td valign="top"><a href="#account">Account</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityAsset</strong></td>
<td valign="top"><a href="#asset">Asset</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralAsset</strong></td>
<td valign="top"><a href="#asset">Asset</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>fundingLocker</strong></td>
<td valign="top"><a href="#bytes">Bytes</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralLocker</strong></td>
<td valign="top"><a href="#bytes">Bytes</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>apr</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>interestRate</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>termDays</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>paymentIntervalDays</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>requestAmount</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralRatio</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralRequired</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>fundingPeriodDays</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>interestCalc</strong></td>
<td valign="top"><a href="#bytes">Bytes</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lateFeeCalc</strong></td>
<td valign="top"><a href="#bytes">Bytes</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>premiumCalc</strong></td>
<td valign="top"><a href="#bytes">Bytes</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralAmount</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>amountFunded</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>drawdownAmount</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>drawdownDate</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>fundingDate</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>maturityDate</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>claimableAmount</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>principalOwed</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>nextPayment</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>nextPaymentDue</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>paymentsRemaining</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>interestPaid</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>numLenders</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>treasuryFees</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction</strong></td>
<td valign="top"><a href="#transaction">Transaction</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralSwapped</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityAssetReturned</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidationExcess</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>defaultSuffered</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### LoanPosition

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong>id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>owner</strong></td>
<td valign="top"><a href="#bytes">Bytes</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool</strong></td>
<td valign="top"><a href="#pool">Pool</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loan</strong></td>
<td valign="top"><a href="#loan">Loan</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>amount</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>principalOwed</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>state</strong></td>
<td valign="top"><a href="#loanstate">LoanState</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction</strong></td>
<td valign="top"><a href="#transaction">Transaction</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### Maple

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong>id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>governor</strong></td>
<td valign="top"><a href="#bytes">Bytes</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLiquidity</strong></td>
<td valign="top"><a href="#bigdecimal">BigDecimal</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalValueLocked</strong></td>
<td valign="top"><a href="#bigdecimal">BigDecimal</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalPools</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLoans</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalActiveLoans</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLiquidityCap</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLiquidityProvided</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLoanOriginations</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalInterestEarned</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalTreasuryFees</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>mpl</strong></td>
<td valign="top"><a href="#asset">Asset</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>global</strong></td>
<td valign="top"><a href="#global">Global</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalCurrentLoaned</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>aggregateLpApy</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### MplRewards

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong>id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>periodFinish</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>reward</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>rewardRate</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>rewardsDuration</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>paused</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### Pool

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong>id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolName</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>state</strong></td>
<td valign="top"><a href="#poolstate">PoolState</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>name</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityAsset</strong></td>
<td valign="top"><a href="#asset">Asset</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityCap</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeAsset</strong></td>
<td valign="top"><a href="#asset">Asset</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolDelegate</strong></td>
<td valign="top"><a href="#account">Account</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lockupPeriod</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakingFee</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>delegateFee</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>ongoingFee</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityLocker</strong></td>
<td valign="top"><a href="#bytes">Bytes</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeLocker</strong></td>
<td valign="top"><a href="#bytes">Bytes</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolTokenTotalSupply</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>numActiveLoans</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lpApy</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lendingApy</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakingApy</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>farmingApy</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeRewardsApy</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>mplRewards</strong></td>
<td valign="top"><a href="#mplrewards">MplRewards</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeRewards</strong></td>
<td valign="top"><a href="#mplrewards">MplRewards</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalPoolTokensStaked</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalStakeLockerTokensStaked</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>balance</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidity</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stake</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeLockerLiquidity</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeLockupPeriod</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLoaned</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>currentLoaned</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>defaultsTotal</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityAssetRecoveredTotal</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLoanOriginations</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalInterestEarned</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalPrincipalRepaid</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalFees</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeLockerFees</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolDelegateFees</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>numLoans</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>numPositions</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>txCount</strong></td>
<td valign="top"><a href="#int">Int</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction</strong></td>
<td valign="top"><a href="#transaction">Transaction</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>allowedLPs</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>allowedSLs</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>openToPublic</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeLockerOpenToPublic</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### PoolPosition

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong>id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>account</strong></td>
<td valign="top"><a href="#account">Account</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool</strong></td>
<td valign="top"><a href="#pool">Pool</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolTokenBalance</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolTokensStaked</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>claimableInterest</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>interestEarned</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>rewardPaid</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>custodyAllowance</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>depositDate</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>withdrawCooldown</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stake</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeLockerTokensStaked</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>claimableFees</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>feesEarned</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeRewardPaid</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeCustodyAllowance</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeDate</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>unstakeCooldown</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction</strong></td>
<td valign="top"><a href="#transaction">Transaction</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### Repayment

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong>id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>account</strong></td>
<td valign="top"><a href="#account">Account</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loan</strong></td>
<td valign="top"><a href="#loan">Loan</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>principal</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>interest</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>total</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>late</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction</strong></td>
<td valign="top"><a href="#transaction">Transaction</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### Subscription

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong>global</strong></td>
<td valign="top"><a href="#global">Global</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>globals</strong></td>
<td valign="top">[<a href="#global">Global</a>!]!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">skip</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderBy</td>
<td valign="top"><a href="#global_orderby">Global_orderBy</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderDirection</td>
<td valign="top"><a href="#orderdirection">OrderDirection</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">where</td>
<td valign="top"><a href="#global_filter">Global_filter</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>maple</strong></td>
<td valign="top"><a href="#maple">Maple</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>maples</strong></td>
<td valign="top">[<a href="#maple">Maple</a>!]!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">skip</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderBy</td>
<td valign="top"><a href="#maple_orderby">Maple_orderBy</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderDirection</td>
<td valign="top"><a href="#orderdirection">OrderDirection</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">where</td>
<td valign="top"><a href="#maple_filter">Maple_filter</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>asset</strong></td>
<td valign="top"><a href="#asset">Asset</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>assets</strong></td>
<td valign="top">[<a href="#asset">Asset</a>!]!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">skip</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderBy</td>
<td valign="top"><a href="#asset_orderby">Asset_orderBy</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderDirection</td>
<td valign="top"><a href="#orderdirection">OrderDirection</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">where</td>
<td valign="top"><a href="#asset_filter">Asset_filter</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool</strong></td>
<td valign="top"><a href="#pool">Pool</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pools</strong></td>
<td valign="top">[<a href="#pool">Pool</a>!]!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">skip</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderBy</td>
<td valign="top"><a href="#pool_orderby">Pool_orderBy</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderDirection</td>
<td valign="top"><a href="#orderdirection">OrderDirection</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">where</td>
<td valign="top"><a href="#pool_filter">Pool_filter</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loan</strong></td>
<td valign="top"><a href="#loan">Loan</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loans</strong></td>
<td valign="top">[<a href="#loan">Loan</a>!]!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">skip</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderBy</td>
<td valign="top"><a href="#loan_orderby">Loan_orderBy</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderDirection</td>
<td valign="top"><a href="#orderdirection">OrderDirection</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">where</td>
<td valign="top"><a href="#loan_filter">Loan_filter</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>mplRewards</strong></td>
<td valign="top"><a href="#mplrewards">MplRewards</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>mplRewards</strong></td>
<td valign="top">[<a href="#mplrewards">MplRewards</a>!]!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">skip</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderBy</td>
<td valign="top"><a href="#mplrewards_orderby">MplRewards_orderBy</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderDirection</td>
<td valign="top"><a href="#orderdirection">OrderDirection</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">where</td>
<td valign="top"><a href="#mplrewards_filter">MplRewards_filter</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolPosition</strong></td>
<td valign="top"><a href="#poolposition">PoolPosition</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolPositions</strong></td>
<td valign="top">[<a href="#poolposition">PoolPosition</a>!]!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">skip</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderBy</td>
<td valign="top"><a href="#poolposition_orderby">PoolPosition_orderBy</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderDirection</td>
<td valign="top"><a href="#orderdirection">OrderDirection</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">where</td>
<td valign="top"><a href="#poolposition_filter">PoolPosition_filter</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loanPosition</strong></td>
<td valign="top"><a href="#loanposition">LoanPosition</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loanPositions</strong></td>
<td valign="top">[<a href="#loanposition">LoanPosition</a>!]!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">skip</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderBy</td>
<td valign="top"><a href="#loanposition_orderby">LoanPosition_orderBy</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderDirection</td>
<td valign="top"><a href="#orderdirection">OrderDirection</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">where</td>
<td valign="top"><a href="#loanposition_filter">LoanPosition_filter</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>repayment</strong></td>
<td valign="top"><a href="#repayment">Repayment</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>repayments</strong></td>
<td valign="top">[<a href="#repayment">Repayment</a>!]!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">skip</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderBy</td>
<td valign="top"><a href="#repayment_orderby">Repayment_orderBy</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderDirection</td>
<td valign="top"><a href="#orderdirection">OrderDirection</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">where</td>
<td valign="top"><a href="#repayment_filter">Repayment_filter</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>account</strong></td>
<td valign="top"><a href="#account">Account</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>accounts</strong></td>
<td valign="top">[<a href="#account">Account</a>!]!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">skip</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderBy</td>
<td valign="top"><a href="#account_orderby">Account_orderBy</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderDirection</td>
<td valign="top"><a href="#orderdirection">OrderDirection</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">where</td>
<td valign="top"><a href="#account_filter">Account_filter</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>tx</strong></td>
<td valign="top"><a href="#tx">Tx</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>txes</strong></td>
<td valign="top">[<a href="#tx">Tx</a>!]!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">skip</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderBy</td>
<td valign="top"><a href="#tx_orderby">Tx_orderBy</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderDirection</td>
<td valign="top"><a href="#orderdirection">OrderDirection</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">where</td>
<td valign="top"><a href="#tx_filter">Tx_filter</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction</strong></td>
<td valign="top"><a href="#transaction">Transaction</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transactions</strong></td>
<td valign="top">[<a href="#transaction">Transaction</a>!]!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">skip</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderBy</td>
<td valign="top"><a href="#transaction_orderby">Transaction_orderBy</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderDirection</td>
<td valign="top"><a href="#orderdirection">OrderDirection</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">where</td>
<td valign="top"><a href="#transaction_filter">Transaction_filter</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeLockerPoolMap</strong></td>
<td valign="top"><a href="#_stakelockerpoolmap">_stakeLockerPoolMap</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeLockerPoolMaps</strong></td>
<td valign="top">[<a href="#_stakelockerpoolmap">_stakeLockerPoolMap</a>!]!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">skip</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderBy</td>
<td valign="top"><a href="#_stakelockerpoolmap_orderby">_stakeLockerPoolMap_orderBy</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderDirection</td>
<td valign="top"><a href="#orderdirection">OrderDirection</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">where</td>
<td valign="top"><a href="#_stakelockerpoolmap_filter">_stakeLockerPoolMap_filter</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>priceFeedAssetMap</strong></td>
<td valign="top"><a href="#_pricefeedassetmap">_priceFeedAssetMap</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>priceFeedAssetMaps</strong></td>
<td valign="top">[<a href="#_pricefeedassetmap">_priceFeedAssetMap</a>!]!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">skip</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderBy</td>
<td valign="top"><a href="#_pricefeedassetmap_orderby">_priceFeedAssetMap_orderBy</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderDirection</td>
<td valign="top"><a href="#orderdirection">OrderDirection</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">where</td>
<td valign="top"><a href="#_pricefeedassetmap_filter">_priceFeedAssetMap_filter</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loanPositionMap</strong></td>
<td valign="top"><a href="#_loanpositionmap">_loanPositionMap</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loanPositionMaps</strong></td>
<td valign="top">[<a href="#_loanpositionmap">_loanPositionMap</a>!]!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">skip</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderBy</td>
<td valign="top"><a href="#_loanpositionmap_orderby">_loanPositionMap_orderBy</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderDirection</td>
<td valign="top"><a href="#orderdirection">OrderDirection</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">where</td>
<td valign="top"><a href="#_loanpositionmap_filter">_loanPositionMap_filter</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loanMap</strong></td>
<td valign="top"><a href="#_loanmap">_loanMap</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loanMaps</strong></td>
<td valign="top">[<a href="#_loanmap">_loanMap</a>!]!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">skip</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderBy</td>
<td valign="top"><a href="#_loanmap_orderby">_loanMap_orderBy</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderDirection</td>
<td valign="top"><a href="#orderdirection">OrderDirection</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">where</td>
<td valign="top"><a href="#_loanmap_filter">_loanMap_filter</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolPositionMap</strong></td>
<td valign="top"><a href="#_poolpositionmap">_poolPositionMap</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolPositionMaps</strong></td>
<td valign="top">[<a href="#_poolpositionmap">_poolPositionMap</a>!]!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">skip</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderBy</td>
<td valign="top"><a href="#_poolpositionmap_orderby">_poolPositionMap_orderBy</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderDirection</td>
<td valign="top"><a href="#orderdirection">OrderDirection</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">where</td>
<td valign="top"><a href="#_poolpositionmap_filter">_poolPositionMap_filter</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolMap</strong></td>
<td valign="top"><a href="#_poolmap">_poolMap</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">id</td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolMaps</strong></td>
<td valign="top">[<a href="#_poolmap">_poolMap</a>!]!</td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">skip</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">first</td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderBy</td>
<td valign="top"><a href="#_poolmap_orderby">_poolMap_orderBy</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">orderDirection</td>
<td valign="top"><a href="#orderdirection">OrderDirection</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">where</td>
<td valign="top"><a href="#_poolmap_filter">_poolMap_filter</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">subgraphError</td>
<td valign="top"><a href="#_subgrapherrorpolicy_">_SubgraphErrorPolicy_</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>_meta</strong></td>
<td valign="top"><a href="#_meta_">_Meta_</a></td>
<td>

Access to subgraph metadata

</td>
</tr>
<tr>
<td colspan="2" align="right" valign="top">block</td>
<td valign="top"><a href="#block_height">Block_height</a></td>
<td></td>
</tr>
</tbody>
</table>

### Transaction

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong>id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>block</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>timestamp</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>gasLimit</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>gasPrice</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### Tx

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong>id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool</strong></td>
<td valign="top"><a href="#pool">Pool</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>account</strong></td>
<td valign="top"><a href="#account">Account</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>type</strong></td>
<td valign="top"><a href="#txtype">TxType</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>amount</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>decimals</strong></td>
<td valign="top"><a href="#int">Int</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>value</strong></td>
<td valign="top"><a href="#bigint">BigInt</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction</strong></td>
<td valign="top"><a href="#transaction">Transaction</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### _Block_

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong>hash</strong></td>
<td valign="top"><a href="#bytes">Bytes</a></td>
<td>

The hash of the block

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>number</strong></td>
<td valign="top"><a href="#int">Int</a>!</td>
<td>

The block number

</td>
</tr>
</tbody>
</table>

### _Meta_

The type for the top-level \_meta field

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong>block</strong></td>
<td valign="top"><a href="#_block_">_Block_</a>!</td>
<td>

Information about a specific subgraph block. The hash of the block
will be null if the \_meta field has a block constraint that asks for
a block number. It will be filled if the \_meta field has no block constraint
and therefore asks for the latest block

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>deployment</strong></td>
<td valign="top"><a href="#string">String</a>!</td>
<td>

The deployment ID

</td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>hasIndexingErrors</strong></td>
<td valign="top"><a href="#boolean">Boolean</a>!</td>
<td>

If `true`, the subgraph encountered indexing errors at some past block

</td>
</tr>
</tbody>
</table>

### \_loanMap

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong>id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loan</strong></td>
<td valign="top"><a href="#loan">Loan</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### \_loanPositionMap

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong>id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loanPosition</strong></td>
<td valign="top"><a href="#loanposition">LoanPosition</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### \_poolMap

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong>id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool</strong></td>
<td valign="top"><a href="#pool">Pool</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### \_poolPositionMap

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong>id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolPosition</strong></td>
<td valign="top"><a href="#poolposition">PoolPosition</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### \_priceFeedAssetMap

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong>id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>asset</strong></td>
<td valign="top"><a href="#asset">Asset</a>!</td>
<td></td>
</tr>
</tbody>
</table>

### \_stakeLockerPoolMap

<table>
<thead>
<tr>
<th align="left">Field</th>
<th align="right">Argument</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong>id</strong></td>
<td valign="top"><a href="#id">ID</a>!</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool</strong></td>
<td valign="top"><a href="#pool">Pool</a>!</td>
<td></td>
</tr>
</tbody>
</table>

## Inputs

### Account_filter

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong>id</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_not</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_gt</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_lt</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_gte</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_lte</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_in</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_not_in</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalPoolTokenBalance</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalPoolTokenBalance_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalPoolTokenBalance_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalPoolTokenBalance_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalPoolTokenBalance_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalPoolTokenBalance_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalPoolTokenBalance_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalPoolTokenBalance_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalPoolTokensStaked</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalPoolTokensStaked_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalPoolTokensStaked_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalPoolTokensStaked_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalPoolTokensStaked_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalPoolTokensStaked_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalPoolTokensStaked_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalPoolTokensStaked_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalRewardPaid</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalRewardPaid_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalRewardPaid_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalRewardPaid_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalRewardPaid_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalRewardPaid_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalRewardPaid_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalRewardPaid_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalClaimableInterest</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalClaimableInterest_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalClaimableInterest_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalClaimableInterest_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalClaimableInterest_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalClaimableInterest_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalClaimableInterest_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalClaimableInterest_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalInterestEarned</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalInterestEarned_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalInterestEarned_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalInterestEarned_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalInterestEarned_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalInterestEarned_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalInterestEarned_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalInterestEarned_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalStake</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalStake_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalStake_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalStake_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalStake_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalStake_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalStake_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalStake_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalStakeLockerTokensStaked</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalStakeLockerTokensStaked_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalStakeLockerTokensStaked_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalStakeLockerTokensStaked_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalStakeLockerTokensStaked_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalStakeLockerTokensStaked_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalStakeLockerTokensStaked_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalStakeLockerTokensStaked_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalStakeRewardPaid</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalStakeRewardPaid_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalStakeRewardPaid_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalStakeRewardPaid_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalStakeRewardPaid_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalStakeRewardPaid_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalStakeRewardPaid_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalStakeRewardPaid_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalClaimableFees</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalClaimableFees_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalClaimableFees_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalClaimableFees_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalClaimableFees_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalClaimableFees_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalClaimableFees_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalClaimableFees_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalFeesEarned</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalFeesEarned_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalFeesEarned_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalFeesEarned_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalFeesEarned_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalFeesEarned_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalFeesEarned_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalFeesEarned_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
</tbody>
</table>

### Asset_filter

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong>id</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_not</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_gt</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_lt</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_gte</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_lte</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_in</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_not_in</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol_not</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol_gt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol_lt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol_gte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol_lte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol_not_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol_not_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol_not_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol_not_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>decimals</strong></td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>decimals_not</strong></td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>decimals_gt</strong></td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>decimals_lt</strong></td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>decimals_gte</strong></td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>decimals_lte</strong></td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>decimals_in</strong></td>
<td valign="top">[<a href="#int">Int</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>decimals_not_in</strong></td>
<td valign="top">[<a href="#int">Int</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>isValidCollateralAsset</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>isValidCollateralAsset_not</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>isValidCollateralAsset_in</strong></td>
<td valign="top">[<a href="#boolean">Boolean</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>isValidCollateralAsset_not_in</strong></td>
<td valign="top">[<a href="#boolean">Boolean</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>isValidLiquidityAsset</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>isValidLiquidityAsset_not</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>isValidLiquidityAsset_in</strong></td>
<td valign="top">[<a href="#boolean">Boolean</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>isValidLiquidityAsset_not_in</strong></td>
<td valign="top">[<a href="#boolean">Boolean</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>isValidStakeAsset</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>isValidStakeAsset_not</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>isValidStakeAsset_in</strong></td>
<td valign="top">[<a href="#boolean">Boolean</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>isValidStakeAsset_not_in</strong></td>
<td valign="top">[<a href="#boolean">Boolean</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>amount</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>amount_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>amount_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>amount_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>amount_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>amount_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>amount_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>amount_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>amountAsLiquidity</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>amountAsLiquidity_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>amountAsLiquidity_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>amountAsLiquidity_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>amountAsLiquidity_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>amountAsLiquidity_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>amountAsLiquidity_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>amountAsLiquidity_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>price</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>price_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>price_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>price_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>price_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>price_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>price_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>price_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>priceFeed</strong></td>
<td valign="top"><a href="#bytes">Bytes</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>priceFeed_not</strong></td>
<td valign="top"><a href="#bytes">Bytes</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>priceFeed_in</strong></td>
<td valign="top">[<a href="#bytes">Bytes</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>priceFeed_not_in</strong></td>
<td valign="top">[<a href="#bytes">Bytes</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>priceFeed_contains</strong></td>
<td valign="top"><a href="#bytes">Bytes</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>priceFeed_not_contains</strong></td>
<td valign="top"><a href="#bytes">Bytes</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lastPriceUpdateTimestamp</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lastPriceUpdateTimestamp_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lastPriceUpdateTimestamp_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lastPriceUpdateTimestamp_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lastPriceUpdateTimestamp_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lastPriceUpdateTimestamp_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lastPriceUpdateTimestamp_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lastPriceUpdateTimestamp_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
</tbody>
</table>

### Block_height

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong>hash</strong></td>
<td valign="top"><a href="#bytes">Bytes</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>number</strong></td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>number_gte</strong></td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
</tbody>
</table>

### Global_filter

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong>id</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_not</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_gt</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_lt</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_gte</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_lte</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_in</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_not_in</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>defaultGracePeriod</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>defaultGracePeriod_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>defaultGracePeriod_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>defaultGracePeriod_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>defaultGracePeriod_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>defaultGracePeriod_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>defaultGracePeriod_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>defaultGracePeriod_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>swapOutRequired</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>swapOutRequired_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>swapOutRequired_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>swapOutRequired_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>swapOutRequired_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>swapOutRequired_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>swapOutRequired_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>swapOutRequired_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>fundingPeriod</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>fundingPeriod_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>fundingPeriod_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>fundingPeriod_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>fundingPeriod_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>fundingPeriod_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>fundingPeriod_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>fundingPeriod_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>investorFee</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>investorFee_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>investorFee_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>investorFee_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>investorFee_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>investorFee_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>investorFee_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>investorFee_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>treasuryFee</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>treasuryFee_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>treasuryFee_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>treasuryFee_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>treasuryFee_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>treasuryFee_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>treasuryFee_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>treasuryFee_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>maxSwapSlippage</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>maxSwapSlippage_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>maxSwapSlippage_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>maxSwapSlippage_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>maxSwapSlippage_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>maxSwapSlippage_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>maxSwapSlippage_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>maxSwapSlippage_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>minLoanEquity</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>minLoanEquity_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>minLoanEquity_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>minLoanEquity_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>minLoanEquity_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>minLoanEquity_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>minLoanEquity_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>minLoanEquity_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakerCooldownPeriod</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakerCooldownPeriod_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakerCooldownPeriod_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakerCooldownPeriod_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakerCooldownPeriod_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakerCooldownPeriod_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakerCooldownPeriod_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakerCooldownPeriod_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lpCooldownPeriod</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lpCooldownPeriod_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lpCooldownPeriod_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lpCooldownPeriod_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lpCooldownPeriod_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lpCooldownPeriod_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lpCooldownPeriod_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lpCooldownPeriod_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakerUnstakeWindow</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakerUnstakeWindow_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakerUnstakeWindow_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakerUnstakeWindow_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakerUnstakeWindow_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakerUnstakeWindow_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakerUnstakeWindow_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakerUnstakeWindow_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lpWithdrawWindow</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lpWithdrawWindow_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lpWithdrawWindow_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lpWithdrawWindow_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lpWithdrawWindow_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lpWithdrawWindow_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lpWithdrawWindow_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lpWithdrawWindow_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
</tbody>
</table>

### LoanPosition_filter

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong>id</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_not</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_gt</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_lt</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_gte</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_lte</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_in</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_not_in</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>owner</strong></td>
<td valign="top"><a href="#bytes">Bytes</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>owner_not</strong></td>
<td valign="top"><a href="#bytes">Bytes</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>owner_in</strong></td>
<td valign="top">[<a href="#bytes">Bytes</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>owner_not_in</strong></td>
<td valign="top">[<a href="#bytes">Bytes</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>owner_contains</strong></td>
<td valign="top"><a href="#bytes">Bytes</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>owner_not_contains</strong></td>
<td valign="top"><a href="#bytes">Bytes</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_not</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_gt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_lt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_gte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_lte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_not_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_not_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_not_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_not_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loan</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loan_not</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loan_gt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loan_lt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loan_gte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loan_lte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loan_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loan_not_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loan_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loan_not_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loan_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loan_not_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loan_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loan_not_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>amount</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>amount_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>amount_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>amount_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>amount_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>amount_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>amount_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>amount_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>principalOwed</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>principalOwed_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>principalOwed_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>principalOwed_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>principalOwed_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>principalOwed_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>principalOwed_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>principalOwed_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>state</strong></td>
<td valign="top"><a href="#loanstate">LoanState</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>state_not</strong></td>
<td valign="top"><a href="#loanstate">LoanState</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>state_in</strong></td>
<td valign="top">[<a href="#loanstate">LoanState</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>state_not_in</strong></td>
<td valign="top">[<a href="#loanstate">LoanState</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_not</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_gt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_lt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_gte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_lte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_not_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_not_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_not_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_not_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
</tbody>
</table>

### Loan_filter

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong>id</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_not</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_gt</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_lt</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_gte</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_lte</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_in</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_not_in</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>version</strong></td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>version_not</strong></td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>version_gt</strong></td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>version_lt</strong></td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>version_gte</strong></td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>version_lte</strong></td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>version_in</strong></td>
<td valign="top">[<a href="#int">Int</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>version_not_in</strong></td>
<td valign="top">[<a href="#int">Int</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>state</strong></td>
<td valign="top"><a href="#loanstate">LoanState</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>state_not</strong></td>
<td valign="top"><a href="#loanstate">LoanState</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>state_in</strong></td>
<td valign="top">[<a href="#loanstate">LoanState</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>state_not_in</strong></td>
<td valign="top">[<a href="#loanstate">LoanState</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>name</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>name_not</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>name_gt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>name_lt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>name_gte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>name_lte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>name_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>name_not_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>name_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>name_not_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>name_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>name_not_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>name_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>name_not_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol_not</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol_gt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol_lt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol_gte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol_lte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol_not_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol_not_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol_not_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol_not_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>borrower</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>borrower_not</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>borrower_gt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>borrower_lt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>borrower_gte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>borrower_lte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>borrower_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>borrower_not_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>borrower_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>borrower_not_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>borrower_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>borrower_not_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>borrower_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>borrower_not_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityAsset</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityAsset_not</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityAsset_gt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityAsset_lt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityAsset_gte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityAsset_lte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityAsset_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityAsset_not_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityAsset_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityAsset_not_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityAsset_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityAsset_not_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityAsset_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityAsset_not_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralAsset</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralAsset_not</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralAsset_gt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralAsset_lt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralAsset_gte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralAsset_lte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralAsset_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralAsset_not_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralAsset_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralAsset_not_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralAsset_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralAsset_not_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralAsset_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralAsset_not_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>fundingLocker</strong></td>
<td valign="top"><a href="#bytes">Bytes</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>fundingLocker_not</strong></td>
<td valign="top"><a href="#bytes">Bytes</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>fundingLocker_in</strong></td>
<td valign="top">[<a href="#bytes">Bytes</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>fundingLocker_not_in</strong></td>
<td valign="top">[<a href="#bytes">Bytes</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>fundingLocker_contains</strong></td>
<td valign="top"><a href="#bytes">Bytes</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>fundingLocker_not_contains</strong></td>
<td valign="top"><a href="#bytes">Bytes</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralLocker</strong></td>
<td valign="top"><a href="#bytes">Bytes</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralLocker_not</strong></td>
<td valign="top"><a href="#bytes">Bytes</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralLocker_in</strong></td>
<td valign="top">[<a href="#bytes">Bytes</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralLocker_not_in</strong></td>
<td valign="top">[<a href="#bytes">Bytes</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralLocker_contains</strong></td>
<td valign="top"><a href="#bytes">Bytes</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralLocker_not_contains</strong></td>
<td valign="top"><a href="#bytes">Bytes</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>apr</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>apr_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>apr_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>apr_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>apr_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>apr_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>apr_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>apr_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>interestRate</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>interestRate_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>interestRate_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>interestRate_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>interestRate_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>interestRate_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>interestRate_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>interestRate_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>termDays</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>termDays_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>termDays_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>termDays_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>termDays_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>termDays_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>termDays_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>termDays_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>paymentIntervalDays</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>paymentIntervalDays_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>paymentIntervalDays_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>paymentIntervalDays_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>paymentIntervalDays_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>paymentIntervalDays_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>paymentIntervalDays_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>paymentIntervalDays_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>requestAmount</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>requestAmount_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>requestAmount_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>requestAmount_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>requestAmount_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>requestAmount_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>requestAmount_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>requestAmount_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralRatio</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralRatio_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralRatio_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralRatio_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralRatio_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralRatio_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralRatio_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralRatio_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralRequired</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralRequired_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralRequired_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralRequired_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralRequired_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralRequired_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralRequired_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralRequired_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>fundingPeriodDays</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>fundingPeriodDays_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>fundingPeriodDays_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>fundingPeriodDays_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>fundingPeriodDays_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>fundingPeriodDays_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>fundingPeriodDays_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>fundingPeriodDays_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>interestCalc</strong></td>
<td valign="top"><a href="#bytes">Bytes</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>interestCalc_not</strong></td>
<td valign="top"><a href="#bytes">Bytes</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>interestCalc_in</strong></td>
<td valign="top">[<a href="#bytes">Bytes</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>interestCalc_not_in</strong></td>
<td valign="top">[<a href="#bytes">Bytes</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>interestCalc_contains</strong></td>
<td valign="top"><a href="#bytes">Bytes</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>interestCalc_not_contains</strong></td>
<td valign="top"><a href="#bytes">Bytes</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lateFeeCalc</strong></td>
<td valign="top"><a href="#bytes">Bytes</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lateFeeCalc_not</strong></td>
<td valign="top"><a href="#bytes">Bytes</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lateFeeCalc_in</strong></td>
<td valign="top">[<a href="#bytes">Bytes</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lateFeeCalc_not_in</strong></td>
<td valign="top">[<a href="#bytes">Bytes</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lateFeeCalc_contains</strong></td>
<td valign="top"><a href="#bytes">Bytes</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lateFeeCalc_not_contains</strong></td>
<td valign="top"><a href="#bytes">Bytes</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>premiumCalc</strong></td>
<td valign="top"><a href="#bytes">Bytes</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>premiumCalc_not</strong></td>
<td valign="top"><a href="#bytes">Bytes</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>premiumCalc_in</strong></td>
<td valign="top">[<a href="#bytes">Bytes</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>premiumCalc_not_in</strong></td>
<td valign="top">[<a href="#bytes">Bytes</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>premiumCalc_contains</strong></td>
<td valign="top"><a href="#bytes">Bytes</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>premiumCalc_not_contains</strong></td>
<td valign="top"><a href="#bytes">Bytes</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralAmount</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralAmount_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralAmount_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralAmount_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralAmount_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralAmount_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralAmount_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralAmount_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>amountFunded</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>amountFunded_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>amountFunded_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>amountFunded_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>amountFunded_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>amountFunded_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>amountFunded_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>amountFunded_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>drawdownAmount</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>drawdownAmount_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>drawdownAmount_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>drawdownAmount_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>drawdownAmount_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>drawdownAmount_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>drawdownAmount_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>drawdownAmount_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>drawdownDate</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>drawdownDate_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>drawdownDate_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>drawdownDate_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>drawdownDate_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>drawdownDate_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>drawdownDate_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>drawdownDate_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>fundingDate</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>fundingDate_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>fundingDate_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>fundingDate_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>fundingDate_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>fundingDate_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>fundingDate_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>fundingDate_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>maturityDate</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>maturityDate_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>maturityDate_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>maturityDate_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>maturityDate_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>maturityDate_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>maturityDate_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>maturityDate_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>claimableAmount</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>claimableAmount_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>claimableAmount_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>claimableAmount_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>claimableAmount_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>claimableAmount_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>claimableAmount_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>claimableAmount_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>principalOwed</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>principalOwed_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>principalOwed_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>principalOwed_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>principalOwed_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>principalOwed_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>principalOwed_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>principalOwed_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>nextPayment</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>nextPayment_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>nextPayment_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>nextPayment_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>nextPayment_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>nextPayment_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>nextPayment_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>nextPayment_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>nextPaymentDue</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>nextPaymentDue_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>nextPaymentDue_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>nextPaymentDue_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>nextPaymentDue_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>nextPaymentDue_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>nextPaymentDue_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>nextPaymentDue_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>paymentsRemaining</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>paymentsRemaining_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>paymentsRemaining_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>paymentsRemaining_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>paymentsRemaining_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>paymentsRemaining_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>paymentsRemaining_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>paymentsRemaining_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>interestPaid</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>interestPaid_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>interestPaid_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>interestPaid_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>interestPaid_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>interestPaid_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>interestPaid_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>interestPaid_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>numLenders</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>numLenders_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>numLenders_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>numLenders_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>numLenders_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>numLenders_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>numLenders_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>numLenders_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>treasuryFees</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>treasuryFees_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>treasuryFees_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>treasuryFees_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>treasuryFees_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>treasuryFees_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>treasuryFees_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>treasuryFees_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_not</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_gt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_lt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_gte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_lte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_not_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_not_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_not_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_not_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralSwapped</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralSwapped_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralSwapped_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralSwapped_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralSwapped_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralSwapped_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralSwapped_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>collateralSwapped_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityAssetReturned</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityAssetReturned_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityAssetReturned_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityAssetReturned_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityAssetReturned_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityAssetReturned_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityAssetReturned_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityAssetReturned_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidationExcess</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidationExcess_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidationExcess_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidationExcess_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidationExcess_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidationExcess_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidationExcess_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidationExcess_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>defaultSuffered</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>defaultSuffered_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>defaultSuffered_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>defaultSuffered_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>defaultSuffered_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>defaultSuffered_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>defaultSuffered_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>defaultSuffered_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
</tbody>
</table>

### Maple_filter

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong>id</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_not</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_gt</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_lt</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_gte</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_lte</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_in</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_not_in</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>governor</strong></td>
<td valign="top"><a href="#bytes">Bytes</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>governor_not</strong></td>
<td valign="top"><a href="#bytes">Bytes</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>governor_in</strong></td>
<td valign="top">[<a href="#bytes">Bytes</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>governor_not_in</strong></td>
<td valign="top">[<a href="#bytes">Bytes</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>governor_contains</strong></td>
<td valign="top"><a href="#bytes">Bytes</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>governor_not_contains</strong></td>
<td valign="top"><a href="#bytes">Bytes</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLiquidity</strong></td>
<td valign="top"><a href="#bigdecimal">BigDecimal</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLiquidity_not</strong></td>
<td valign="top"><a href="#bigdecimal">BigDecimal</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLiquidity_gt</strong></td>
<td valign="top"><a href="#bigdecimal">BigDecimal</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLiquidity_lt</strong></td>
<td valign="top"><a href="#bigdecimal">BigDecimal</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLiquidity_gte</strong></td>
<td valign="top"><a href="#bigdecimal">BigDecimal</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLiquidity_lte</strong></td>
<td valign="top"><a href="#bigdecimal">BigDecimal</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLiquidity_in</strong></td>
<td valign="top">[<a href="#bigdecimal">BigDecimal</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLiquidity_not_in</strong></td>
<td valign="top">[<a href="#bigdecimal">BigDecimal</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalValueLocked</strong></td>
<td valign="top"><a href="#bigdecimal">BigDecimal</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalValueLocked_not</strong></td>
<td valign="top"><a href="#bigdecimal">BigDecimal</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalValueLocked_gt</strong></td>
<td valign="top"><a href="#bigdecimal">BigDecimal</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalValueLocked_lt</strong></td>
<td valign="top"><a href="#bigdecimal">BigDecimal</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalValueLocked_gte</strong></td>
<td valign="top"><a href="#bigdecimal">BigDecimal</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalValueLocked_lte</strong></td>
<td valign="top"><a href="#bigdecimal">BigDecimal</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalValueLocked_in</strong></td>
<td valign="top">[<a href="#bigdecimal">BigDecimal</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalValueLocked_not_in</strong></td>
<td valign="top">[<a href="#bigdecimal">BigDecimal</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalPools</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalPools_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalPools_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalPools_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalPools_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalPools_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalPools_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalPools_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLoans</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLoans_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLoans_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLoans_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLoans_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLoans_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLoans_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLoans_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalActiveLoans</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalActiveLoans_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalActiveLoans_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalActiveLoans_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalActiveLoans_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalActiveLoans_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalActiveLoans_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalActiveLoans_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLiquidityCap</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLiquidityCap_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLiquidityCap_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLiquidityCap_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLiquidityCap_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLiquidityCap_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLiquidityCap_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLiquidityCap_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLiquidityProvided</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLiquidityProvided_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLiquidityProvided_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLiquidityProvided_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLiquidityProvided_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLiquidityProvided_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLiquidityProvided_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLiquidityProvided_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLoanOriginations</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLoanOriginations_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLoanOriginations_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLoanOriginations_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLoanOriginations_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLoanOriginations_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLoanOriginations_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLoanOriginations_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalInterestEarned</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalInterestEarned_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalInterestEarned_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalInterestEarned_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalInterestEarned_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalInterestEarned_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalInterestEarned_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalInterestEarned_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalTreasuryFees</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalTreasuryFees_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalTreasuryFees_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalTreasuryFees_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalTreasuryFees_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalTreasuryFees_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalTreasuryFees_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalTreasuryFees_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>mpl</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>mpl_not</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>mpl_gt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>mpl_lt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>mpl_gte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>mpl_lte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>mpl_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>mpl_not_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>mpl_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>mpl_not_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>mpl_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>mpl_not_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>mpl_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>mpl_not_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>global</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>global_not</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>global_gt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>global_lt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>global_gte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>global_lte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>global_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>global_not_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>global_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>global_not_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>global_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>global_not_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>global_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>global_not_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalCurrentLoaned</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalCurrentLoaned_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalCurrentLoaned_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalCurrentLoaned_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalCurrentLoaned_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalCurrentLoaned_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalCurrentLoaned_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalCurrentLoaned_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>aggregateLpApy</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>aggregateLpApy_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>aggregateLpApy_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>aggregateLpApy_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>aggregateLpApy_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>aggregateLpApy_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>aggregateLpApy_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>aggregateLpApy_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
</tbody>
</table>

### MplRewards_filter

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong>id</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_not</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_gt</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_lt</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_gte</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_lte</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_in</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_not_in</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>periodFinish</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>periodFinish_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>periodFinish_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>periodFinish_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>periodFinish_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>periodFinish_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>periodFinish_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>periodFinish_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>reward</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>reward_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>reward_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>reward_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>reward_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>reward_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>reward_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>reward_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>rewardRate</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>rewardRate_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>rewardRate_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>rewardRate_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>rewardRate_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>rewardRate_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>rewardRate_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>rewardRate_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>rewardsDuration</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>rewardsDuration_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>rewardsDuration_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>rewardsDuration_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>rewardsDuration_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>rewardsDuration_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>rewardsDuration_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>rewardsDuration_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>paused</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>paused_not</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>paused_in</strong></td>
<td valign="top">[<a href="#boolean">Boolean</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>paused_not_in</strong></td>
<td valign="top">[<a href="#boolean">Boolean</a>!]</td>
<td></td>
</tr>
</tbody>
</table>

### PoolPosition_filter

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong>id</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_not</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_gt</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_lt</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_gte</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_lte</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_in</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_not_in</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>account</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>account_not</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>account_gt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>account_lt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>account_gte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>account_lte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>account_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>account_not_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>account_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>account_not_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>account_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>account_not_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>account_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>account_not_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_not</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_gt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_lt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_gte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_lte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_not_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_not_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_not_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_not_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolTokenBalance</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolTokenBalance_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolTokenBalance_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolTokenBalance_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolTokenBalance_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolTokenBalance_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolTokenBalance_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolTokenBalance_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolTokensStaked</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolTokensStaked_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolTokensStaked_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolTokensStaked_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolTokensStaked_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolTokensStaked_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolTokensStaked_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolTokensStaked_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>claimableInterest</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>claimableInterest_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>claimableInterest_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>claimableInterest_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>claimableInterest_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>claimableInterest_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>claimableInterest_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>claimableInterest_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>interestEarned</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>interestEarned_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>interestEarned_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>interestEarned_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>interestEarned_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>interestEarned_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>interestEarned_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>interestEarned_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>rewardPaid</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>rewardPaid_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>rewardPaid_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>rewardPaid_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>rewardPaid_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>rewardPaid_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>rewardPaid_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>rewardPaid_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>custodyAllowance</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>custodyAllowance_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>custodyAllowance_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>custodyAllowance_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>custodyAllowance_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>custodyAllowance_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>custodyAllowance_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>custodyAllowance_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>depositDate</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>depositDate_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>depositDate_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>depositDate_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>depositDate_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>depositDate_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>depositDate_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>depositDate_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>withdrawCooldown</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>withdrawCooldown_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>withdrawCooldown_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>withdrawCooldown_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>withdrawCooldown_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>withdrawCooldown_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>withdrawCooldown_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>withdrawCooldown_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stake</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stake_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stake_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stake_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stake_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stake_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stake_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stake_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeLockerTokensStaked</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeLockerTokensStaked_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeLockerTokensStaked_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeLockerTokensStaked_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeLockerTokensStaked_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeLockerTokensStaked_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeLockerTokensStaked_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeLockerTokensStaked_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>claimableFees</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>claimableFees_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>claimableFees_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>claimableFees_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>claimableFees_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>claimableFees_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>claimableFees_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>claimableFees_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>feesEarned</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>feesEarned_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>feesEarned_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>feesEarned_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>feesEarned_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>feesEarned_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>feesEarned_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>feesEarned_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeRewardPaid</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeRewardPaid_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeRewardPaid_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeRewardPaid_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeRewardPaid_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeRewardPaid_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeRewardPaid_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeRewardPaid_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeCustodyAllowance</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeCustodyAllowance_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeCustodyAllowance_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeCustodyAllowance_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeCustodyAllowance_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeCustodyAllowance_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeCustodyAllowance_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeCustodyAllowance_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeDate</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeDate_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeDate_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeDate_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeDate_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeDate_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeDate_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeDate_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>unstakeCooldown</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>unstakeCooldown_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>unstakeCooldown_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>unstakeCooldown_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>unstakeCooldown_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>unstakeCooldown_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>unstakeCooldown_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>unstakeCooldown_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_not</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_gt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_lt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_gte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_lte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_not_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_not_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_not_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_not_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
</tbody>
</table>

### Pool_filter

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong>id</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_not</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_gt</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_lt</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_gte</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_lte</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_in</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_not_in</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolName</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolName_not</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolName_gt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolName_lt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolName_gte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolName_lte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolName_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolName_not_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolName_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolName_not_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolName_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolName_not_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolName_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolName_not_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>state</strong></td>
<td valign="top"><a href="#poolstate">PoolState</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>state_not</strong></td>
<td valign="top"><a href="#poolstate">PoolState</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>state_in</strong></td>
<td valign="top">[<a href="#poolstate">PoolState</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>state_not_in</strong></td>
<td valign="top">[<a href="#poolstate">PoolState</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>name</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>name_not</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>name_gt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>name_lt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>name_gte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>name_lte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>name_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>name_not_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>name_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>name_not_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>name_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>name_not_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>name_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>name_not_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol_not</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol_gt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol_lt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol_gte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol_lte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol_not_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol_not_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol_not_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol_not_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityAsset</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityAsset_not</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityAsset_gt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityAsset_lt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityAsset_gte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityAsset_lte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityAsset_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityAsset_not_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityAsset_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityAsset_not_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityAsset_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityAsset_not_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityAsset_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityAsset_not_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityCap</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityCap_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityCap_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityCap_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityCap_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityCap_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityCap_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityCap_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeAsset</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeAsset_not</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeAsset_gt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeAsset_lt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeAsset_gte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeAsset_lte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeAsset_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeAsset_not_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeAsset_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeAsset_not_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeAsset_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeAsset_not_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeAsset_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeAsset_not_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolDelegate</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolDelegate_not</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolDelegate_gt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolDelegate_lt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolDelegate_gte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolDelegate_lte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolDelegate_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolDelegate_not_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolDelegate_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolDelegate_not_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolDelegate_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolDelegate_not_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolDelegate_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolDelegate_not_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lockupPeriod</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lockupPeriod_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lockupPeriod_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lockupPeriod_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lockupPeriod_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lockupPeriod_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lockupPeriod_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lockupPeriod_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakingFee</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakingFee_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakingFee_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakingFee_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakingFee_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakingFee_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakingFee_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakingFee_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>delegateFee</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>delegateFee_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>delegateFee_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>delegateFee_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>delegateFee_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>delegateFee_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>delegateFee_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>delegateFee_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>ongoingFee</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>ongoingFee_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>ongoingFee_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>ongoingFee_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>ongoingFee_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>ongoingFee_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>ongoingFee_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>ongoingFee_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityLocker</strong></td>
<td valign="top"><a href="#bytes">Bytes</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityLocker_not</strong></td>
<td valign="top"><a href="#bytes">Bytes</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityLocker_in</strong></td>
<td valign="top">[<a href="#bytes">Bytes</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityLocker_not_in</strong></td>
<td valign="top">[<a href="#bytes">Bytes</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityLocker_contains</strong></td>
<td valign="top"><a href="#bytes">Bytes</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityLocker_not_contains</strong></td>
<td valign="top"><a href="#bytes">Bytes</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeLocker</strong></td>
<td valign="top"><a href="#bytes">Bytes</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeLocker_not</strong></td>
<td valign="top"><a href="#bytes">Bytes</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeLocker_in</strong></td>
<td valign="top">[<a href="#bytes">Bytes</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeLocker_not_in</strong></td>
<td valign="top">[<a href="#bytes">Bytes</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeLocker_contains</strong></td>
<td valign="top"><a href="#bytes">Bytes</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeLocker_not_contains</strong></td>
<td valign="top"><a href="#bytes">Bytes</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolTokenTotalSupply</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolTokenTotalSupply_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolTokenTotalSupply_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolTokenTotalSupply_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolTokenTotalSupply_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolTokenTotalSupply_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolTokenTotalSupply_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolTokenTotalSupply_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>numActiveLoans</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>numActiveLoans_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>numActiveLoans_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>numActiveLoans_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>numActiveLoans_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>numActiveLoans_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>numActiveLoans_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>numActiveLoans_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lpApy</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lpApy_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lpApy_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lpApy_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lpApy_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lpApy_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lpApy_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lpApy_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lendingApy</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lendingApy_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lendingApy_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lendingApy_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lendingApy_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lendingApy_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lendingApy_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>lendingApy_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakingApy</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakingApy_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakingApy_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakingApy_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakingApy_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakingApy_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakingApy_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakingApy_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>farmingApy</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>farmingApy_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>farmingApy_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>farmingApy_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>farmingApy_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>farmingApy_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>farmingApy_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>farmingApy_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeRewardsApy</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeRewardsApy_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeRewardsApy_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeRewardsApy_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeRewardsApy_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeRewardsApy_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeRewardsApy_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeRewardsApy_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>mplRewards</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>mplRewards_not</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>mplRewards_gt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>mplRewards_lt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>mplRewards_gte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>mplRewards_lte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>mplRewards_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>mplRewards_not_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>mplRewards_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>mplRewards_not_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>mplRewards_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>mplRewards_not_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>mplRewards_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>mplRewards_not_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeRewards</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeRewards_not</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeRewards_gt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeRewards_lt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeRewards_gte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeRewards_lte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeRewards_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeRewards_not_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeRewards_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeRewards_not_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeRewards_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeRewards_not_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeRewards_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeRewards_not_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalPoolTokensStaked</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalPoolTokensStaked_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalPoolTokensStaked_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalPoolTokensStaked_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalPoolTokensStaked_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalPoolTokensStaked_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalPoolTokensStaked_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalPoolTokensStaked_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalStakeLockerTokensStaked</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalStakeLockerTokensStaked_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalStakeLockerTokensStaked_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalStakeLockerTokensStaked_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalStakeLockerTokensStaked_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalStakeLockerTokensStaked_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalStakeLockerTokensStaked_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalStakeLockerTokensStaked_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>balance</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>balance_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>balance_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>balance_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>balance_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>balance_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>balance_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>balance_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidity</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidity_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidity_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidity_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidity_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidity_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidity_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidity_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stake</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stake_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stake_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stake_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stake_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stake_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stake_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stake_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeLockerLiquidity</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeLockerLiquidity_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeLockerLiquidity_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeLockerLiquidity_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeLockerLiquidity_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeLockerLiquidity_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeLockerLiquidity_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeLockerLiquidity_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeLockupPeriod</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeLockupPeriod_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeLockupPeriod_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeLockupPeriod_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeLockupPeriod_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeLockupPeriod_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeLockupPeriod_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeLockupPeriod_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLoaned</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLoaned_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLoaned_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLoaned_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLoaned_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLoaned_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLoaned_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLoaned_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>currentLoaned</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>currentLoaned_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>currentLoaned_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>currentLoaned_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>currentLoaned_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>currentLoaned_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>currentLoaned_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>currentLoaned_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>defaultsTotal</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>defaultsTotal_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>defaultsTotal_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>defaultsTotal_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>defaultsTotal_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>defaultsTotal_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>defaultsTotal_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>defaultsTotal_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityAssetRecoveredTotal</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityAssetRecoveredTotal_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityAssetRecoveredTotal_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityAssetRecoveredTotal_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityAssetRecoveredTotal_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityAssetRecoveredTotal_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityAssetRecoveredTotal_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>liquidityAssetRecoveredTotal_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLoanOriginations</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLoanOriginations_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLoanOriginations_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLoanOriginations_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLoanOriginations_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLoanOriginations_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLoanOriginations_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalLoanOriginations_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalInterestEarned</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalInterestEarned_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalInterestEarned_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalInterestEarned_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalInterestEarned_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalInterestEarned_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalInterestEarned_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalInterestEarned_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalPrincipalRepaid</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalPrincipalRepaid_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalPrincipalRepaid_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalPrincipalRepaid_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalPrincipalRepaid_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalPrincipalRepaid_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalPrincipalRepaid_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalPrincipalRepaid_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalFees</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalFees_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalFees_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalFees_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalFees_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalFees_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalFees_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>totalFees_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeLockerFees</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeLockerFees_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeLockerFees_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeLockerFees_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeLockerFees_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeLockerFees_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeLockerFees_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeLockerFees_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolDelegateFees</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolDelegateFees_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolDelegateFees_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolDelegateFees_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolDelegateFees_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolDelegateFees_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolDelegateFees_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolDelegateFees_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>numLoans</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>numLoans_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>numLoans_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>numLoans_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>numLoans_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>numLoans_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>numLoans_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>numLoans_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>numPositions</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>numPositions_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>numPositions_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>numPositions_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>numPositions_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>numPositions_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>numPositions_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>numPositions_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>txCount</strong></td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>txCount_not</strong></td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>txCount_gt</strong></td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>txCount_lt</strong></td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>txCount_gte</strong></td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>txCount_lte</strong></td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>txCount_in</strong></td>
<td valign="top">[<a href="#int">Int</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>txCount_not_in</strong></td>
<td valign="top">[<a href="#int">Int</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_not</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_gt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_lt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_gte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_lte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_not_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_not_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_not_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_not_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>allowedLPs</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>allowedLPs_not</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>allowedLPs_contains</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>allowedLPs_not_contains</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>allowedSLs</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>allowedSLs_not</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>allowedSLs_contains</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>allowedSLs_not_contains</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>openToPublic</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>openToPublic_not</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>openToPublic_in</strong></td>
<td valign="top">[<a href="#boolean">Boolean</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>openToPublic_not_in</strong></td>
<td valign="top">[<a href="#boolean">Boolean</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeLockerOpenToPublic</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeLockerOpenToPublic_not</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeLockerOpenToPublic_in</strong></td>
<td valign="top">[<a href="#boolean">Boolean</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>stakeLockerOpenToPublic_not_in</strong></td>
<td valign="top">[<a href="#boolean">Boolean</a>!]</td>
<td></td>
</tr>
</tbody>
</table>

### Repayment_filter

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong>id</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_not</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_gt</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_lt</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_gte</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_lte</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_in</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_not_in</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>account</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>account_not</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>account_gt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>account_lt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>account_gte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>account_lte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>account_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>account_not_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>account_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>account_not_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>account_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>account_not_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>account_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>account_not_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loan</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loan_not</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loan_gt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loan_lt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loan_gte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loan_lte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loan_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loan_not_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loan_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loan_not_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loan_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loan_not_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loan_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loan_not_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>principal</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>principal_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>principal_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>principal_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>principal_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>principal_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>principal_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>principal_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>interest</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>interest_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>interest_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>interest_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>interest_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>interest_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>interest_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>interest_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>total</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>total_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>total_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>total_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>total_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>total_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>total_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>total_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>late</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>late_not</strong></td>
<td valign="top"><a href="#boolean">Boolean</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>late_in</strong></td>
<td valign="top">[<a href="#boolean">Boolean</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>late_not_in</strong></td>
<td valign="top">[<a href="#boolean">Boolean</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_not</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_gt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_lt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_gte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_lte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_not_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_not_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_not_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_not_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
</tbody>
</table>

### Transaction_filter

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong>id</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_not</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_gt</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_lt</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_gte</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_lte</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_in</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_not_in</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>block</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>block_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>block_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>block_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>block_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>block_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>block_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>block_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>timestamp</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>timestamp_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>timestamp_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>timestamp_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>timestamp_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>timestamp_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>timestamp_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>timestamp_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>gasLimit</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>gasLimit_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>gasLimit_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>gasLimit_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>gasLimit_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>gasLimit_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>gasLimit_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>gasLimit_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>gasPrice</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>gasPrice_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>gasPrice_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>gasPrice_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>gasPrice_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>gasPrice_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>gasPrice_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>gasPrice_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
</tbody>
</table>

### Tx_filter

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong>id</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_not</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_gt</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_lt</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_gte</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_lte</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_in</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_not_in</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_not</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_gt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_lt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_gte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_lte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_not_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_not_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_not_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_not_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>account</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>account_not</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>account_gt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>account_lt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>account_gte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>account_lte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>account_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>account_not_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>account_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>account_not_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>account_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>account_not_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>account_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>account_not_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>type</strong></td>
<td valign="top"><a href="#txtype">TxType</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>type_not</strong></td>
<td valign="top"><a href="#txtype">TxType</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>type_in</strong></td>
<td valign="top">[<a href="#txtype">TxType</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>type_not_in</strong></td>
<td valign="top">[<a href="#txtype">TxType</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>amount</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>amount_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>amount_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>amount_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>amount_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>amount_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>amount_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>amount_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol_not</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol_gt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol_lt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol_gte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol_lte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol_not_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol_not_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol_not_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>symbol_not_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>decimals</strong></td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>decimals_not</strong></td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>decimals_gt</strong></td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>decimals_lt</strong></td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>decimals_gte</strong></td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>decimals_lte</strong></td>
<td valign="top"><a href="#int">Int</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>decimals_in</strong></td>
<td valign="top">[<a href="#int">Int</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>decimals_not_in</strong></td>
<td valign="top">[<a href="#int">Int</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>value</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>value_not</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>value_gt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>value_lt</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>value_gte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>value_lte</strong></td>
<td valign="top"><a href="#bigint">BigInt</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>value_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>value_not_in</strong></td>
<td valign="top">[<a href="#bigint">BigInt</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_not</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_gt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_lt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_gte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_lte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_not_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_not_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_not_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>transaction_not_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
</tbody>
</table>

### \_loanMap_filter

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong>id</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_not</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_gt</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_lt</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_gte</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_lte</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_in</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_not_in</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loan</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loan_not</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loan_gt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loan_lt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loan_gte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loan_lte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loan_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loan_not_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loan_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loan_not_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loan_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loan_not_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loan_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loan_not_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
</tbody>
</table>

### \_loanPositionMap_filter

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong>id</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_not</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_gt</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_lt</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_gte</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_lte</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_in</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_not_in</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loanPosition</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loanPosition_not</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loanPosition_gt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loanPosition_lt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loanPosition_gte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loanPosition_lte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loanPosition_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loanPosition_not_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loanPosition_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loanPosition_not_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loanPosition_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loanPosition_not_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loanPosition_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>loanPosition_not_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
</tbody>
</table>

### \_poolMap_filter

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong>id</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_not</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_gt</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_lt</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_gte</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_lte</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_in</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_not_in</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_not</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_gt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_lt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_gte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_lte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_not_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_not_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_not_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_not_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
</tbody>
</table>

### \_poolPositionMap_filter

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong>id</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_not</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_gt</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_lt</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_gte</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_lte</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_in</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_not_in</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolPosition</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolPosition_not</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolPosition_gt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolPosition_lt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolPosition_gte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolPosition_lte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolPosition_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolPosition_not_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolPosition_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolPosition_not_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolPosition_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolPosition_not_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolPosition_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>poolPosition_not_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
</tbody>
</table>

### \_priceFeedAssetMap_filter

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong>id</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_not</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_gt</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_lt</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_gte</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_lte</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_in</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_not_in</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>asset</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>asset_not</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>asset_gt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>asset_lt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>asset_gte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>asset_lte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>asset_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>asset_not_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>asset_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>asset_not_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>asset_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>asset_not_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>asset_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>asset_not_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
</tbody>
</table>

### \_stakeLockerPoolMap_filter

<table>
<thead>
<tr>
<th colspan="2" align="left">Field</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" valign="top"><strong>id</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_not</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_gt</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_lt</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_gte</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_lte</strong></td>
<td valign="top"><a href="#id">ID</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_in</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>id_not_in</strong></td>
<td valign="top">[<a href="#id">ID</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_not</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_gt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_lt</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_gte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_lte</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_not_in</strong></td>
<td valign="top">[<a href="#string">String</a>!]</td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_not_contains</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_not_starts_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
<tr>
<td colspan="2" valign="top"><strong>pool_not_ends_with</strong></td>
<td valign="top"><a href="#string">String</a></td>
<td></td>
</tr>
</tbody>
</table>

## Enums

### Account_orderBy

<table>
<thead>
<th align="left">Value</th>
<th align="left">Description</th>
</thead>
<tbody>
<tr>
<td valign="top"><strong>id</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>totalPoolTokenBalance</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>totalPoolTokensStaked</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>totalRewardPaid</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>totalClaimableInterest</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>totalInterestEarned</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>totalStake</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>totalStakeLockerTokensStaked</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>totalStakeRewardPaid</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>totalClaimableFees</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>totalFeesEarned</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>txes</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>loans</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>poolPositions</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>managedPools</strong></td>
<td></td>
</tr>
</tbody>
</table>

### Asset_orderBy

<table>
<thead>
<th align="left">Value</th>
<th align="left">Description</th>
</thead>
<tbody>
<tr>
<td valign="top"><strong>id</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>symbol</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>decimals</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>isValidCollateralAsset</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>isValidLiquidityAsset</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>isValidStakeAsset</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>amount</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>amountAsLiquidity</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>price</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>priceFeed</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>lastPriceUpdateTimestamp</strong></td>
<td></td>
</tr>
</tbody>
</table>

### Global_orderBy

<table>
<thead>
<th align="left">Value</th>
<th align="left">Description</th>
</thead>
<tbody>
<tr>
<td valign="top"><strong>id</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>defaultGracePeriod</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>swapOutRequired</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>fundingPeriod</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>investorFee</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>treasuryFee</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>maxSwapSlippage</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>minLoanEquity</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>stakerCooldownPeriod</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>lpCooldownPeriod</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>stakerUnstakeWindow</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>lpWithdrawWindow</strong></td>
<td></td>
</tr>
</tbody>
</table>

### LoanPosition_orderBy

<table>
<thead>
<th align="left">Value</th>
<th align="left">Description</th>
</thead>
<tbody>
<tr>
<td valign="top"><strong>id</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>owner</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>pool</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>loan</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>amount</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>principalOwed</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>state</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>transaction</strong></td>
<td></td>
</tr>
</tbody>
</table>

### LoanState

<table>
<thead>
<th align="left">Value</th>
<th align="left">Description</th>
</thead>
<tbody>
<tr>
<td valign="top"><strong>Ready</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>Active</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>Matured</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>Expired</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>Liquidated</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>LiquidatedAndClaimed</strong></td>
<td></td>
</tr>
</tbody>
</table>

### Loan_orderBy

<table>
<thead>
<th align="left">Value</th>
<th align="left">Description</th>
</thead>
<tbody>
<tr>
<td valign="top"><strong>id</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>version</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>state</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>name</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>symbol</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>borrower</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>liquidityAsset</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>collateralAsset</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>fundingLocker</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>collateralLocker</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>apr</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>interestRate</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>termDays</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>paymentIntervalDays</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>requestAmount</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>collateralRatio</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>collateralRequired</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>fundingPeriodDays</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>interestCalc</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>lateFeeCalc</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>premiumCalc</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>collateralAmount</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>amountFunded</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>drawdownAmount</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>drawdownDate</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>fundingDate</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>maturityDate</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>claimableAmount</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>principalOwed</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>nextPayment</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>nextPaymentDue</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>paymentsRemaining</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>interestPaid</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>numLenders</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>treasuryFees</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>transaction</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>collateralSwapped</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>liquidityAssetReturned</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>liquidationExcess</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>defaultSuffered</strong></td>
<td></td>
</tr>
</tbody>
</table>

### Maple_orderBy

<table>
<thead>
<th align="left">Value</th>
<th align="left">Description</th>
</thead>
<tbody>
<tr>
<td valign="top"><strong>id</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>governor</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>totalLiquidity</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>totalValueLocked</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>totalPools</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>totalLoans</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>totalActiveLoans</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>totalLiquidityCap</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>totalLiquidityProvided</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>totalLoanOriginations</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>totalInterestEarned</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>totalTreasuryFees</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>mpl</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>global</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>totalCurrentLoaned</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>aggregateLpApy</strong></td>
<td></td>
</tr>
</tbody>
</table>

### MplRewards_orderBy

<table>
<thead>
<th align="left">Value</th>
<th align="left">Description</th>
</thead>
<tbody>
<tr>
<td valign="top"><strong>id</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>periodFinish</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>reward</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>rewardRate</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>rewardsDuration</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>paused</strong></td>
<td></td>
</tr>
</tbody>
</table>

### OrderDirection

<table>
<thead>
<th align="left">Value</th>
<th align="left">Description</th>
</thead>
<tbody>
<tr>
<td valign="top"><strong>asc</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>desc</strong></td>
<td></td>
</tr>
</tbody>
</table>

### PoolPosition_orderBy

<table>
<thead>
<th align="left">Value</th>
<th align="left">Description</th>
</thead>
<tbody>
<tr>
<td valign="top"><strong>id</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>account</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>pool</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>poolTokenBalance</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>poolTokensStaked</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>claimableInterest</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>interestEarned</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>rewardPaid</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>custodyAllowance</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>depositDate</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>withdrawCooldown</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>stake</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>stakeLockerTokensStaked</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>claimableFees</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>feesEarned</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>stakeRewardPaid</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>stakeCustodyAllowance</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>stakeDate</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>unstakeCooldown</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>transaction</strong></td>
<td></td>
</tr>
</tbody>
</table>

### PoolState

<table>
<thead>
<th align="left">Value</th>
<th align="left">Description</th>
</thead>
<tbody>
<tr>
<td valign="top"><strong>Initialized</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>Finalized</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>Deactivated</strong></td>
<td></td>
</tr>
</tbody>
</table>

### Pool_orderBy

<table>
<thead>
<th align="left">Value</th>
<th align="left">Description</th>
</thead>
<tbody>
<tr>
<td valign="top"><strong>id</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>poolName</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>state</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>name</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>symbol</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>liquidityAsset</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>liquidityCap</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>stakeAsset</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>poolDelegate</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>lockupPeriod</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>stakingFee</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>delegateFee</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>ongoingFee</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>liquidityLocker</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>stakeLocker</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>poolTokenTotalSupply</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>numActiveLoans</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>lpApy</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>lendingApy</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>stakingApy</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>farmingApy</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>stakeRewardsApy</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>mplRewards</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>stakeRewards</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>totalPoolTokensStaked</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>totalStakeLockerTokensStaked</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>balance</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>liquidity</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>stake</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>stakeLockerLiquidity</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>stakeLockupPeriod</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>totalLoaned</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>currentLoaned</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>defaultsTotal</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>liquidityAssetRecoveredTotal</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>totalLoanOriginations</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>totalInterestEarned</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>totalPrincipalRepaid</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>totalFees</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>stakeLockerFees</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>poolDelegateFees</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>numLoans</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>numPositions</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>txCount</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>transaction</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>allowedLPs</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>allowedSLs</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>openToPublic</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>stakeLockerOpenToPublic</strong></td>
<td></td>
</tr>
</tbody>
</table>

### Repayment_orderBy

<table>
<thead>
<th align="left">Value</th>
<th align="left">Description</th>
</thead>
<tbody>
<tr>
<td valign="top"><strong>id</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>account</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>loan</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>principal</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>interest</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>total</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>late</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>transaction</strong></td>
<td></td>
</tr>
</tbody>
</table>

### Transaction_orderBy

<table>
<thead>
<th align="left">Value</th>
<th align="left">Description</th>
</thead>
<tbody>
<tr>
<td valign="top"><strong>id</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>block</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>timestamp</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>gasLimit</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>gasPrice</strong></td>
<td></td>
</tr>
</tbody>
</table>

### TxType

<table>
<thead>
<th align="left">Value</th>
<th align="left">Description</th>
</thead>
<tbody>
<tr>
<td valign="top"><strong>poolDeposit</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>poolWithdraw</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>poolWithdrawFunds</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>stakeLockerStake</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>stakeLockerUnstake</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>stakeLockerWithdrawFunds</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>lendingRewardsStake</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>lendingRewardsWithdraw</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>lendingRewardsGetReward</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>stakingRewardsStake</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>stakingRewardsWithdraw</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>stakingRewardsGetReward</strong></td>
<td></td>
</tr>
</tbody>
</table>

### Tx_orderBy

<table>
<thead>
<th align="left">Value</th>
<th align="left">Description</th>
</thead>
<tbody>
<tr>
<td valign="top"><strong>id</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>pool</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>account</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>type</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>amount</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>symbol</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>decimals</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>value</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>transaction</strong></td>
<td></td>
</tr>
</tbody>
</table>

### _SubgraphErrorPolicy_

<table>
<thead>
<th align="left">Value</th>
<th align="left">Description</th>
</thead>
<tbody>
<tr>
<td valign="top"><strong>allow</strong></td>
<td>

Data will be returned even if the subgraph has indexing errors

</td>
</tr>
<tr>
<td valign="top"><strong>deny</strong></td>
<td>

If the subgraph has indexing errors, data will be omitted. The default.

</td>
</tr>
</tbody>
</table>

### \_loanMap_orderBy

<table>
<thead>
<th align="left">Value</th>
<th align="left">Description</th>
</thead>
<tbody>
<tr>
<td valign="top"><strong>id</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>loan</strong></td>
<td></td>
</tr>
</tbody>
</table>

### \_loanPositionMap_orderBy

<table>
<thead>
<th align="left">Value</th>
<th align="left">Description</th>
</thead>
<tbody>
<tr>
<td valign="top"><strong>id</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>loanPosition</strong></td>
<td></td>
</tr>
</tbody>
</table>

### \_poolMap_orderBy

<table>
<thead>
<th align="left">Value</th>
<th align="left">Description</th>
</thead>
<tbody>
<tr>
<td valign="top"><strong>id</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>pool</strong></td>
<td></td>
</tr>
</tbody>
</table>

### \_poolPositionMap_orderBy

<table>
<thead>
<th align="left">Value</th>
<th align="left">Description</th>
</thead>
<tbody>
<tr>
<td valign="top"><strong>id</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>poolPosition</strong></td>
<td></td>
</tr>
</tbody>
</table>

### \_priceFeedAssetMap_orderBy

<table>
<thead>
<th align="left">Value</th>
<th align="left">Description</th>
</thead>
<tbody>
<tr>
<td valign="top"><strong>id</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>asset</strong></td>
<td></td>
</tr>
</tbody>
</table>

### \_stakeLockerPoolMap_orderBy

<table>
<thead>
<th align="left">Value</th>
<th align="left">Description</th>
</thead>
<tbody>
<tr>
<td valign="top"><strong>id</strong></td>
<td></td>
</tr>
<tr>
<td valign="top"><strong>pool</strong></td>
<td></td>
</tr>
</tbody>
</table>

## Scalars

### BigDecimal

### BigInt

### Boolean

### Bytes

### ID

### Int

### String
