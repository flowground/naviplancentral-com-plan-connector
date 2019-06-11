# ![LOGO](logo.png) Published Plan Service **flow**ground Connector

## Description

A generated **flow**ground connector for the Published Plan Service API (version v1).

Generated from: https://api.apis.guru/v2/specs/naviplancentral.com/plan/v1/swagger.json<br/>
Generated at: 2019-06-06T16:12:53+03:00

## API Description

An API for accessing NaviPlan plan data for a client.

## Authorization

This API does not require authorization.

## Actions

### Retrieve Advisors

> This operation retrieves a list of all of the Advisors in the plan.

*Tags:* `Advisors`

### Retrieve an Advisor

> This operation retrieves an Advisor from the plan.

*Tags:* `Advisors`

#### Input Parameters
* `id` - _required_

### Retrieve plan assumptions

> This operation retrieves an object containing all assumptions for the specified plan.

*Tags:* `Assumptions`

#### Input Parameters
* `planId` - _optional_ - Id of the plan to retrieve data from (e.g. 1001-11-3). Default value is the first plan the user is authorized to access.
* `scenarioType` - _optional_ - Type of plan to retrieve data from (0:Current-default, 1:Recommended)

### Retrieve business entities

> This operation retrieves a list of all of the business entities in the plan.

*Tags:* `BusinessEntities`

#### Input Parameters
* `planId` - _optional_ - Id of the plan to retrieve data from (e.g. 1001-11-3). Default value is the first plan the user is authorized to access.
* `scenarioType` - _optional_ - Type of plan to retrieve data from (0:Current-default, 1:Recommended)

### Retrieve a business entity

> This operation retrieves a business entity from the plan.

*Tags:* `BusinessEntities`

#### Input Parameters
* `id` - _required_ - ID of business entity to retrieve
* `planId` - _optional_ - Id of the plan to retrieve data from (e.g. 1001-11-3). Default value is the first plan the user is authorized to access.
* `scenarioType` - _optional_ - Type of plan to retrieve data from (0:Current-default, 1:Recommended)

### Retrieve Monte Carlo results from standalone calc service

> Currently just stubbed out, POC in development

*Tags:* `Calculations`

#### Input Parameters
* `planId` - _optional_ - Id of the plan to retrieve data from (e.g. 1001-11-3). Default value is the first plan the user is authorized to access.
* `scenarioType` - _optional_ - Type of plan to retrieve data from (0:Current-default, 1:Recommended)

### Retrieve defined benefit pensions

> This operation retrieves a list of all of the defined benefit pensions in the plan.

*Tags:* `DefinedBenefitPensions`

#### Input Parameters
* `planId` - _optional_ - Id of the plan to retrieve data from (e.g. 1001-11-3). Default value is the first plan the user is authorized to access.
* `scenarioType` - _optional_ - Type of plan to retrieve data from (0:Current-default, 1:Recommended)

### Retrieve a definedBenefitPension

> This operation retrieves a defined benefit pension from the plan.

*Tags:* `DefinedBenefitPensions`

#### Input Parameters
* `id` - _required_ - ID of defined benefit pension to retrieve
* `planId` - _optional_ - Id of the plan to retrieve data from (e.g. 1001-11-3). Default value is the first plan the user is authorized to access.
* `scenarioType` - _optional_ - Type of plan to retrieve data from (0:Current-default, 1:Recommended)

### Accepts the EULA

*Tags:* `Eula`

### Retrieve family

> This operation retrieves an object containing all familymembers for the specified plan.

*Tags:* `Family`

#### Input Parameters
* `planId` - _optional_ - Id of the plan to retrieve data from (e.g. 1001-11-3). Default value is the first plan the user is authorized to access.
* `scenarioType` - _optional_ - Type of plan to retrieve data from (0:Current-default, 1:Recommended)

### Retrieve the adjustments

> This function retrieves a goal and the adjustments made to it

*Tags:* `GoalAdjustments`

#### Input Parameters
* `id` - _required_ - The id of the goal to retrieve adjustments for.
* `clientId` - _optional_ - The id of the client to retrieve adjustments for.
* `clientFileId` - _optional_ - The id of the client file to be operated on.

### Perform calculations

> This function returns the posted object and the adjusted calculation values

*Tags:* `GoalAdjustments`

#### Input Parameters
* `id` - _required_ - The id of the goal to retrieve adjustments for.

### Returns a list of goals with their relevant success rates.

*Tags:* `GoalAdjustments`

#### Input Parameters
* `clientId` - _optional_ - The id of the client to retrieve adjustments for.
* `clientFileId` - _optional_ - The id of the client file to be operated on.

### Retrieve the adjustments

> This function retrieves a goal and the adjustments made to it

*Tags:* `GoalAdjustments`

#### Input Parameters
* `id` - _required_ - The id of the goal to retrieve adjustments for.
* `clientId` - _optional_ - The id of the client to retrieve adjustments for.
* `clientFileId` - _optional_ - The id of the client file to be operated on.

### Perform calculations

> This function returns the posted object and the adjusted calculation values

*Tags:* `GoalAdjustments`

#### Input Parameters
* `id` - _required_ - The id of the goal to retrieve adjustments for.

### Returns a list of goal adjustment restrictions.

> This function returns a list of adjustment restrictions for all goals.

*Tags:* `GoalAdjustments`

#### Input Parameters
* `clientId` - _optional_ - The id of the client user to act upon.
* `clientFileId` - _optional_ - The id of the client file to act upon.

### Retrieve the adjustments

> This function retrieves a goal and the adjustments made to it for a particular client

*Tags:* `GoalAdjustments`

#### Input Parameters
* `id` - _required_ - The id of the goal to retrieve adjustments for.
* `clientId` - _optional_ - The id of the client to retrieve adjustments for.
* `clientFileId` - _optional_ - The id of the client file to be operated on.

### Perform calculations

> This function returns the posted object and the adjusted calculation values

*Tags:* `GoalAdjustments`

#### Input Parameters
* `id` - _required_ - The id of the goal to retrieve adjustments for.

### Retrieve goals

> This operation retrieves a list of all of the goals in the plan.

*Tags:* `Goals`

#### Input Parameters
* `planId` - _optional_ - Id of the plan to retrieve data from (e.g. 1001-11-3). Default value is the first plan the user is authorized to access.
* `scenarioType` - _optional_ - Type of plan to retrieve data from (0:Current-default, 1:Recommended)

### Retrieve goals

> This operation retrieves a goal from the plan.

*Tags:* `Goals`

#### Input Parameters
* `id` - _required_ - ID of goal to retrieve
* `planId` - _optional_ - Id of the plan to retrieve data from (e.g. 1001-11-3). Default value is the first plan the user is authorized to access.
* `scenarioType` - _optional_ - Type of plan to retrieve data from (0:Current-default, 1:Recommended)

### Retrieve holding companies

> This operation retrieves a list of all of the holding companies in the plan.

*Tags:* `HoldingCompanies`

#### Input Parameters
* `planId` - _optional_ - Id of the plan to retrieve data from (e.g. 1001-11-3). Default value is the first plan the user is authorized to access.
* `scenarioType` - _optional_ - Type of plan to retrieve data from (0:Current-default, 1:Recommended)

### Retrieve a holding company

> This operation retrieves a holding company from the plan.

*Tags:* `HoldingCompanies`

#### Input Parameters
* `id` - _required_ - ID of holding company to retrieve
* `planId` - _optional_ - Id of the plan to retrieve data from (e.g. 1001-11-3). Default value is the first plan the user is authorized to access.
* `scenarioType` - _optional_ - Type of plan to retrieve data from (0:Current-default, 1:Recommended)

### Retrieve liabilities

> This operation retrieves a list of all of the liabilities in the plan.

*Tags:* `Liabilities`

#### Input Parameters
* `planId` - _optional_ - Id of the plan to retrieve data from (e.g. 1001-11-3). Default value is the first plan the user is authorized to access.
* `scenarioType` - _optional_ - Type of plan to retrieve data from (0:Current-default, 1:Recommended)

### Retrieve a liability

> This operation retrieves a liability from the plan.

*Tags:* `Liabilities`

#### Input Parameters
* `id` - _required_ - ID of liability to retrieve
* `planId` - _optional_ - Id of the plan to retrieve data from (e.g. 1001-11-3). Default value is the first plan the user is authorized to access.
* `scenarioType` - _optional_ - Type of plan to retrieve data from (0:Current-default, 1:Recommended)

### Retrieve lifestyle assets

> This operation retrieves a list of all of the lifestyle assets in the plan.

*Tags:* `LifestyleAssets`

#### Input Parameters
* `planId` - _optional_ - Id of the plan to retrieve data from (e.g. 1001-11-3). Default value is the first plan the user is authorized to access.
* `scenarioType` - _optional_ - Type of plan to retrieve data from (0:Current-default, 1:Recommended)

### Retrieve lifestyle assets

> This operation retrieves a lifestyle asset from the plan.

*Tags:* `LifestyleAssets`

#### Input Parameters
* `id` - _required_ - ID of lifestyle asset to retrieve
* `planId` - _optional_ - Id of the plan to retrieve data from (e.g. 1001-11-3). Default value is the first plan the user is authorized to access.
* `scenarioType` - _optional_ - Type of plan to retrieve data from (0:Current-default, 1:Recommended)

### Retrieve net worth

> This operation retrieves an object containing net worth values for specific dates within the plan:<br/>
>               * Plan Start Date<br/>
>               * Retirement Date<br/>
>               * Plan End Date.

*Tags:* `NetWorth`

#### Input Parameters
* `planId` - _optional_ - Id of the plan to retrieve data from (e.g. 1001-11-3). Default value is the first plan the user is authorized to access.
* `scenarioType` - _optional_ - Type of plan to retrieve data from (0:Current-default, 1:Recommended)

### Determines if the currently logged in user has set their own password

*Tags:* `Password`

### Gets the password complexity requirements

*Tags:* `Password`

### Resets the password for the supplied user name

*Tags:* `Password`

### Sets the password for the currently logged in user

*Tags:* `Password`

### Retrieve plan information

> This operation retrieves the high level plan information for a given plan

*Tags:* `PlanInformation`

#### Input Parameters
* `planId` - _optional_ - Id of the plan to retrieve data from (e.g. 1001-11-3). Default value is the first plan the user is authorized to access.
* `scenarioType` - _optional_ - Type of plan to retrieve data from (0:Current-default, 1:Recommended)

### Retrieve portfolio accounts

> This operation retrieves a list of all of the portfolio accounts in the plan.

*Tags:* `PortfolioAccounts`

#### Input Parameters
* `planId` - _optional_ - Id of the plan to retrieve data from (e.g. 1001-11-3). Default value is the first plan the user is authorized to access.
* `scenarioType` - _optional_ - Type of plan to retrieve data from (0:Current-default, 1:Recommended)

### Retrieve a portfolio account

> This operation retrieves a portfolio account from the plan.

*Tags:* `PortfolioAccounts`

#### Input Parameters
* `id` - _required_ - ID of portfolio account to retrieve
* `planId` - _optional_ - Id of the plan to retrieve data from (e.g. 1001-11-3). Default value is the first plan the user is authorized to access.
* `scenarioType` - _optional_ - Type of plan to retrieve data from (0:Current-default, 1:Recommended)

### Retrieve projected annual summaries

> This operation retrieves an object containing annual summary information <br/>
>               for each year of the projected plan.

*Tags:* `ProjectedAnnualSummary`

#### Input Parameters
* `planId` - _optional_ - Id of the plan to retrieve data from (e.g. 1001-11-3). Default value is the first plan the user is authorized to access.
* `scenarioType` - _optional_ - Type of plan to retrieve data from (0:Current-default, 1:Recommended)

### Retrieve projected annual summary by id

> This operation retrieves an object containing annual summary information <br/>
>               for a single specified year of the projected plan.

*Tags:* `ProjectedAnnualSummary`

#### Input Parameters
* `id` - _required_ - Index into the list of annual projections
* `planId` - _optional_ - Id of the plan to retrieve data from (e.g. 1001-11-3). Default value is the first plan the user is authorized to access.
* `scenarioType` - _optional_ - Type of plan to retrieve data from (0:Current-default, 1:Recommended)

### Retrieve projected cash flow

> This operation retrieves an object containing cash flow information <br/>
>               for each year of the projected plan.

*Tags:* `ProjectedCashFlow`

#### Input Parameters
* `planId` - _optional_ - Id of the plan to retrieve data from (e.g. 1001-11-3). Default value is the first plan the user is authorized to access.
* `scenarioType` - _optional_ - Type of plan to retrieve data from (0:Current-default, 1:Recommended)

### Retrieve projected cash flow by id

> This operation retrieves an object containing cash flow information <br/>
>               for a single specified year of the projected plan.

*Tags:* `ProjectedCashFlow`

#### Input Parameters
* `id` - _required_ - Index into the list of annual projections
* `planId` - _optional_ - Id of the plan to retrieve data from (e.g. 1001-11-3). Default value is the first plan the user is authorized to access.
* `scenarioType` - _optional_ - Type of plan to retrieve data from (0:Current-default, 1:Recommended)

### Retrieve assets funding goals over time

> This operation retrieves the assets funding each goal throughout the plan years

*Tags:* `ProjectedGoals`

#### Input Parameters
* `planId` - _optional_ - Id of the plan to retrieve data from (e.g. 1001-11-3). Default value is the first plan the user is authorized to access.
* `scenarioType` - _optional_ - Type of plan to retrieve data from (0:Current-default, 1:Recommended)

### Retrieve needs vs abilities data

> This operation retrieves a needs and abilities data for all goals throughout<br/>
>               the plan years.

*Tags:* `ProjectedGoals`

#### Input Parameters
* `planId` - _optional_ - Id of the plan to retrieve data from (e.g. 1001-11-3). Default value is the first plan the user is authorized to access.
* `scenarioType` - _optional_ - Type of plan to retrieve data from (0:Current-default, 1:Recommended)

### Retrieve projected net worth

> This operation retrieves an object containing net worth information <br/>
>               for each year of the projected plan. These are EOY numbers.

*Tags:* `ProjectedNetWorth`

#### Input Parameters
* `planId` - _optional_ - Id of the plan to retrieve data from (e.g. 1001-11-3). Default value is the first plan the user is authorized to access.
* `scenarioType` - _optional_ - Type of plan to retrieve data from (0:Current-default, 1:Recommended)

### Retrieve projected net worth by id

> This operation retrieves an object containing net worth information <br/>
>               for a single specified year of the projected plan. These are EOY numbers.

*Tags:* `ProjectedNetWorth`

#### Input Parameters
* `id` - _required_ - Index into the list of annual projections
* `planId` - _optional_ - Id of the plan to retrieve data from (e.g. 1001-11-3). Default value is the first plan the user is authorized to access.
* `scenarioType` - _optional_ - Type of plan to retrieve data from (0:Current-default, 1:Recommended)

### Retrieve restricted stocks

> This operation retrieves a list of all of the restricted stocks in the plan.

*Tags:* `RestrictedStocks`

#### Input Parameters
* `planId` - _optional_ - Id of the plan to retrieve data from (e.g. 1001-11-3). Default value is the first plan the user is authorized to access.
* `scenarioType` - _optional_ - Type of plan to retrieve data from (0:Current-default, 1:Recommended)

### Retrieve a restricted stock

> This operation retrieves a restricted stock from the plan.

*Tags:* `RestrictedStocks`

#### Input Parameters
* `id` - _required_ - ID of restricted stock to retrieve
* `planId` - _optional_ - Id of the plan to retrieve data from (e.g. 1001-11-3). Default value is the first plan the user is authorized to access.
* `scenarioType` - _optional_ - Type of plan to retrieve data from (0:Current-default, 1:Recommended)

### This resource can be used to check the status of the service.

*Tags:* `ServiceInformation`

### Retrieve stock options

> This operation retrieves a list of all of the stock options in the plan.

*Tags:* `StockOptions`

#### Input Parameters
* `planId` - _optional_ - Id of the plan to retrieve data from (e.g. 1001-11-3). Default value is the first plan the user is authorized to access.
* `scenarioType` - _optional_ - Type of plan to retrieve data from (0:Current-default, 1:Recommended)

### Retrieve a stock option

> This operation retrieves a stock option from the plan.

*Tags:* `StockOptions`

#### Input Parameters
* `id` - _required_ - ID of stock option to retrieve
* `planId` - _optional_ - Id of the plan to retrieve data from (e.g. 1001-11-3). Default value is the first plan the user is authorized to access.
* `scenarioType` - _optional_ - Type of plan to retrieve data from (0:Current-default, 1:Recommended)

### Start a session with the DomainProviders user store

*Tags:* `Auth`

### Gets the login rules

*Tags:* `Auth`

### Auth_Logout

*Tags:* `Auth`

### Validate a session

*Tags:* `Auth`

## License

**flow**ground :- Telekom iPaaS / naviplancentral-com-plan-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
