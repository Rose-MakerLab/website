# Article VIII: Club Finances
## VIII.1) Records
The Treasurer is responsible for maintaining high quality financial records for the organization. All financial records shall be held in the officer OneDrive/SharePoint folder and marked as a business record as the retention policy.
## VIII.2) Dues and membership fees
There shall be no dues or fees required to be a member of this organization. If a fee or due is needed, a written statement will be sent via email to all members with at least one week of anticipation to give sufficient time to submit the fee. The Treasurer will oversee collecting fees and recording such activity. The organization will receive a majority of its funding from the SGA and BIC, or outside grants, and will comply with all funding policies and procedures issued by the funding authority.
## VIII.3) Expenditures
1. All purchases shall be used exclusively to advance the mission and purpose of MakerLab.
2. All budget expenditures will be visible to all MakerLab officers.
3. Purchasing Process:
    - Purchases under $50 may be directly approved by the treasurer.
    - Budget expenditures between $50 and $500 dollars related to the Lab must be authorized by the Treasurer and the Lab Director.
    - All other purchases must be authorized by the Treasurer and President.
    - Before executing any expenditure, the Treasurer must give the Officers reasonable (at least 24h) notice of the future expenditure to allow for potential objections and discussion.
    - At any time, the Treasurer or a majority of the Officers may veto an expenditure.
    - The President may veto any expenditure that is not between $50 and $500 dollars and for the Lab. The veto process for these expenditures follows item 5.
    - In the case of either the President, Treasurer, or Lab Director denying or vetoing a purchase, after a thorough discussion with both sides presenting evidence, 2/3 of the Officers may vote to override the decision.

``` mermaid
graph TB
    A([Perform Purchase Request]); 
    A -->      B[[ Treasury Approval]];
    B -->|Yes| C{ Under $50?};
    B --> |No| D[[ Overturned by 2/3 of Officers?]];

    C --> |No| E{ Under $500 and a lab related purchase?};
    C -->|Yes| F[/ Presidential Veto?/];

    D -->|Yes| Z([ Item Purchase]);
    D --> |No| Y([ Denied]);

    E --> |No| G[[ Presidential Approval]];
    E -->|Yes| H[[ Lab Director Approval]];

    F --> |No| I[/ Veto by 2/3 Officers?/];
    F -->|Yes| D;

    G --> |No| D;
    G -->|Yes| I;

    H --> |No| D;
    H -->|Yes| I;

    I --> |No| Z;
    I -->|Yes| Y;
    
```

## VIII.4) Dissolution
Upon dissolution of the organization, all remaining funds and assets are to be folded into the BIC and KIC to be used at the discretion of the Innovation Center Leadership.