# 1. Business Process Reviews

## 1.1. Conduct BPR (Business Process Review)
# SUMMARY
Conduct BPR session to understand Riverview Research’s business processes and work flows. The information gathered during this meeting will serve as the basis for the system design and configuration changes.

## DELIVERABLES
This phase of the project actually requires deliverables from your company in order for me to understand the what, why, amd how of creating the implementation. However, to better describe the necessity of this phase, ive attached several examples in Exhibit 1.1.

# BUSINESS PROCESS EVALUATION 
This is something ive spent countless hours on-site putting together prior to starting the implementation. Like you said, you hired me because you guys didnt want to deal with the requirements i needed for the implementation. So i didnt have a problem gathering, evaluating, and delivering the foundation of requirements i needed for the implementation, but this type of work is clearly and obviously out of scope of what an implementation actually is. You would be paying a business process consultant hundreds of dollars an hour piecing this together for you, especially when you dont want to be involved.

# PROCESS REVIEW EVALUATION 
This is where you would argue that im overcomplicating things and this is where ive been telling you that im not. During The Business Process Review, theyre not sitting down with you and listening to detailed descriptions of disorganized methods for the way things are being done. Theyre taking the process flow charts that you already have and theyre converting them into the salesforce data model. Because you dont have this, its not only taken me longer to decipher certain processes, but also taken me longer in converting those deciphered processes into the salesforce data model.

# 1.2. Gather reporting requirements.
# SUMMARY
Gathering reporting requirements based off R2's processes and work flows. The information gathered during this meeting will serve as the basis for the capabilities and reporting output from the salesforce data model.

## DELIVERABLES
The deliverables from this section are outlined in Section 9: Reporting.

# REPORTING REQUIREMENTS EVALUATION 
This goes along with the previous step and is clearly something that, even in the process design phase of this whole thing, still requires executive input and collaboration on what will better help you run your business.

# FAMILY DISCOUNT SUMMARY
Im not just trying to be a dick or withholding information from Alex cause i dont want to "reveal" to him how easy my job is so he can just do it for you instead of me. Alex is not running your business for you regardless of what you try to have him believe. Hes not a project manager like you have him believe either, Danny makes $100k as a project manager and even small businesses require that type of project management consulting to put these types of projects together. So i think i clearly define my point that the work ive had to do even prior to beginning the actual implementation is costing you well over anything close to what ive been paid for this entire situation.


# 2. Lead Management

## 2.1. Add up to (15) custom Lead fields
1.	CreatedFromLead
2.	Employer
3.	ExpressedInterest
4.	Household
5.	PotentialValue
6.	ReferredByContact
7.	ReferredByUser
8.	RelatedAccount


## 2.2. Configure up to (3) Lead Views
1. All Leads
2. Current Leads
3. Potential Leads

## 2.3. Configure Page layouts
1. Edited Page Layouts for Standard Objects which included changing the look and feel of page layouts for standard Salesforce objects.
2. Edited Page Layouts for Custom and External Objects which included changing the look and feel of page layouts for custom and external objects.
3. Set Page Layouts and Field-Level Security
4. Assigned Page Layouts to Profiles and Record Types
5. Assigned Page Layouts from Customized Page Layouts and Record Type Pages
6. Built Page Layouts for Custom Objects
7. Added expanded lookups, components, and Visualforce pages to the Mobile Cards section of page layouts so that they will show up as mobile cards in the Salesforce mobile app.
8. Customized Related Lists
9. Customized Detail Page Buttons

Notes:
When you customize your page layouts in Salesforce Classic, those changes can affect the content of object record pages in Lightning Experience. However, in Lightning Experience, the page elements display differently, and some aren’t supported.


# 3. Contacts

## 3.1. Add/modify up to (10) Individual fields
1.	AnnualIncome
2.	Citizenship
3.	CountryOfResidence
4.	CreatedFromLead
5.	CurrentEmployer
6.	EmployedSince
7.	Facebook
8.	Gender
9.	IndividualType
10.	LanguagesSpoken
11.	LinkedIn
12.	MaritalStatus
13.	NumberOfDependents
14.	Occupation
15.	PrimaryAddressIsBilling
16.	PrimaryAddressIsMailing
17.	PrimaryAddressIsOther
18.	PrimaryAddressIsShipping
19.	SourceSystemId
20.	TaxBracket
21.	TaxId
22.	Twitter
23.	WeddingAnniversary
24.	CountryOfBirth
25.	PreferredName
26.	PrimaryLanguage
27.	SecondaryLanguage
28.	Affiliations
29.	CommunicationPreferences
30.	ContactPreference
31.	CustomerTimezone
32.	EmailVerified
33.	FaxVerified
34.	HomeOwnership
35.	HomePhoneVerified
36.	LastFourDigitSSN
37.	MarketingOptOut
38.	MobileVerified
39.	MostUsedChannel
40.	MotherMaidenName
41.	NextLifeEvent
42.	NumberOfChildren
43.	PrimaryCitizenship
44.	ReferredByContact
45.	ReferredByUser
46.	ReferrerScore
47.	SecondaryCitizenship


## 3.2. Configure up to (3) Individual Views
1. All Contacts
2. Client Contacts
3. Vendor Contacts

## 3.3. Configure Page layouts
1. Edited Page Layouts for Standard Objects which included changing the look and feel of page layouts for standard Salesforce objects.
2. Edited Page Layouts for Custom and External Objects which included changing the look and feel of page layouts for custom and external objects.
3. Set Page Layouts and Field-Level Security
4. Assigned Page Layouts to Profiles and Record Types
5. Assigned Page Layouts from Customized Page Layouts and Record Type Pages
6. Built Page Layouts for Custom Objects
7. Added expanded lookups, components, and Visualforce pages to the Mobile Cards section of page layouts so that they will show up as mobile cards in the Salesforce mobile app.
8. Customized Related Lists
9. Customized Detail Page Buttons

Notes:
When you customize your page layouts in Salesforce Classic, those changes can affect the content of object record pages in Lightning Experience. However, in Lightning Experience, the page elements display differently, and some aren’t supported.

## 3.4. Configure Validation Rules to ensure data integrity and record completion
Notes:
Validation rules verify that the data a user enters in a record meets the standards you specify before the user can save the record. A validation rule can contain a formula or expression that evaluates the data in one or more fields and returns a value of “True” or “False”. Validation rules also include an error message to display to the user when the rule returns a value of “True” due to an invalid value. Review these considerations before implementing validation rules in your organization.


# 4. Accounts

## 4.1. Add/modify up to (10) Household fields

1.	ClientCategory
2.	FinancialInterests
3.	IndividualId
4.	IndividualType
5.	InvestmentExperience
6.	InvestmentObjectives
7.	LastInteraction
8.	LastReview
9.	MarketingSegment
10.	NetWorth
11.	NextInteraction
12.	NextReview
13.	Notes
14.	PersonalInterests
15.	PrimaryContact
16.	ReviewFrequency
17.	RiskTolerance
18.	ServiceModel
19.	SourceSystemId
20.	Status
21.	TimeHorizon
22.	TotalAUMJointOwner
23.	TotalAUMPrimaryOwner
24.	TotalBankDepositsJointOwner
25.	TotalBankDepositsPrimaryOwner
26.	TotalFinAcctsJointOwner
27.	TotalFinAcctsPrimaryOwner
28.	TotalHeldFinAcctsJointOwner
29.	TotalHeldFinAcctsPrimaryOwner
30.	TotalInsuranceJointOwner
31.	TotalInsurancePrimaryOwner
32.	TotalInvestmentsJointOwner
33.	TotalInvestmentsPrimaryOwner
34.	TotalLiabilitiesJointOwner
35.	TotalLiabilitiesPrimaryOwner
36.	TotalNonfinancialAssetsJointOwner
37.	TotalNonfinancialAssetsPrimaryOwner
38.	BankNumber
39.	BorrowingHistory
40.	BorrowingPriorities
41.	BranchCode
42.	BranchName
43.	ConversionDateTime
44.	CreditRating
45.	CreditScore
46.	CustomerID
47.	CustomerSegment
48.	CustomerType
49.	KYCDate
50.	KYCStatus
51.	LastTransactionDateJointOwner
52.	LastTransactionDatePrimaryOwner
53.	LastUsedChannel
54.	LifetimeValue
55.	ReferredByContact
56.	ReferredByUser
57.	RelationshipStartDate
58.	TotalNumberOfFinAccountsJointOwner
59.	TotalNumberOfFinAccountsPrimaryOwner
60.	TotalOutstandingCreditJointOwner
61.	TotalOutstandingCreditPrimaryOwner
62.	TotalRevenue
63.	TotalPremium


## 4.2. Configure up to (3) Household Views
1. All Households
2. Client Households
3. Household Value

## 4.3. Configure Page layouts
1. Edited Page Layouts for Standard Objects which included changing the look and feel of page layouts for standard Salesforce objects.
2. Edited Page Layouts for Custom and External Objects which included changing the look and feel of page layouts for custom and external objects.
3. Set Page Layouts and Field-Level Security
4. Assigned Page Layouts to Profiles and Record Types
5. Assigned Page Layouts from Customized Page Layouts and Record Type Pages
6. Built Page Layouts for Custom Objects
7. Added expanded lookups, components, and Visualforce pages to the Mobile Cards section of page layouts so that they will show up as mobile cards in the Salesforce mobile app.
8. Customized Related Lists
9. Customized Detail Page Buttons

Notes:
When you customize your page layouts in Salesforce Classic, those changes can affect the content of object record pages in Lightning Experience. However, in Lightning Experience, the page elements display differently, and some aren’t supported.


# 5. Financial Accounts

## 5.1. Add/modify up to (25) Financial Accounts fields on existing objects
1.	Address1
2.	Address2
3.	ApplicationDate
4.	AssetRebalance
5.	AverageBalance
6.	Balance
7.	CashBalance
8.	City
9.	CloseDate
10.	Country
11.	Description
12.	Discretionary
13.	FinancialAccountNumber
14.	FinancialAccountSource
15.	FinancialAccountType
16.	HeldAway
17.	Household
18.	InsuredAmount
19.	InvestmentObjectives
20.	JointOwner
21.	LastUpdated
22.	Managed
23.	MinimumBalance
24.	ModelPortfolio
25.	OpenDate
26.	OwnerType
27.	Ownership
28.	PaperlessDelivery
29.	Performance1Yr
30.	Performance3Yr
31.	PerformanceMTD
32.	PerformanceQTD
33.	PerformanceYTD
34.	PostalCode
35.	Premium
36.	PrimaryOwner
37.	RebalanceFrequency
38.	RenewalDate
39.	ServiceProvider
40.	SourceSystemId
41.	State
42.	Status
43.	TaxID
44.	TaxStatus
45.	TimeHorizon
46.	HoldingCount
47.	APY
48.	AvailableCredit
49.	BalanceLastStatement
50.	BookedDate
51.	CashLimit
52.	CollateralDesc
53.	CurrentPostedBalance
54.	DailyWithdrawalLimit
55.	DrawPeriodMonths
56.	EscrowBalance
57.	ExpectedCloseDate
58.	FinancialAccountChargesAndFees
59.	InterestRate
60.	LastTransactionDate
61.	LienHolder
62.	LoanAmount
63.	LoanEndDate
64.	LoanTermMonths
65.	MinimumPayment
66.	Nickname
67.	OverdraftAllowed
68.	OverdraftLinkedAccount
69.	PaymentAmount
70.	PaymentDueDate
71.	PaymentFrequency
72.	PendingDeposits
73.	PendingWithdrawals
74.	PrincipalBalance
75.	RepaymentPeriodMonths
76.	RoutingNumber
77.	Stage
78.	StatementFrequency
79.	TotalCreditLimit
80.	Type
81.	PolicyTerm
82.	ProductName

## 5.2. Add up to (2) custom Financial Accounts objects (e.g., Compliance) and (20) custom fields
1. Identify and Assess Risks
    Fields and Sub-Fields:
    1. Inventory
        1. PROPRIETARY INTERNAL DATA DESCRIPTOR
        2. PROPRIETARY INTERNAL DATA DESCRIPTOR
        3. PROPRIETARY INTERNAL DATA DESCRIPTOR
    2. Minimize Use
        1. PROPRIETARY INTERNAL DATA DESCRIPTOR
        2. PROPRIETARY INTERNAL DATA DESCRIPTOR
        3. PROPRIETARY INTERNAL DATA DESCRIPTOR
        4. PROPRIETARY INTERNAL DATA DESCRIPTOR
        5. PROPRIETARY INTERNAL DATA DESCRIPTOR
        6. PROPRIETARY INTERNAL DATA DESCRIPTOR
        7. PROPRIETARY INTERNAL DATA DESCRIPTOR
        8. PROPRIETARY INTERNAL DATA DESCRIPTOR
    3. Third Party
        1. PROPRIETARY INTERNAL DATA DESCRIPTOR
        2. PROPRIETARY INTERNAL DATA DESCRIPTOR
        3. PROPRIETARY INTERNAL DATA DESCRIPTOR
        4. PROPRIETARY INTERNAL DATA DESCRIPTOR
        5. PROPRIETARY INTERNAL DATA DESCRIPTOR
        6. PROPRIETARY INTERNAL DATA DESCRIPTOR
        7. PROPRIETARY INTERNAL DATA DESCRIPTOR
        8. PROPRIETARY INTERNAL DATA DESCRIPTOR
        9. PROPRIETARY INTERNAL DATA DESCRIPTOR
2. Protect
    1. Information Assets
        1. PROPRIETARY INTERNAL DATA DESCRIPTOR
        2. PROPRIETARY INTERNAL DATA DESCRIPTOR
        3. PROPRIETARY INTERNAL DATA DESCRIPTOR
        4. PROPRIETARY INTERNAL DATA DESCRIPTOR
        5. PROPRIETARY INTERNAL DATA DESCRIPTOR
        6. PROPRIETARY INTERNAL DATA DESCRIPTOR
        7. PROPRIETARY INTERNAL DATA DESCRIPTOR
        8. PROPRIETARY INTERNAL DATA DESCRIPTOR
        9. PROPRIETARY INTERNAL DATA DESCRIPTOR
        10. PROPRIETARY INTERNAL DATA DESCRIPTOR
    2.  System Assets
        1.  PROPRIETARY INTERNAL DATA DESCRIPTOR
        2.  PROPRIETARY INTERNAL DATA DESCRIPTOR
        3.  PROPRIETARY INTERNAL DATA DESCRIPTOR
        4.  PROPRIETARY INTERNAL DATA DESCRIPTOR
        5.  PROPRIETARY INTERNAL DATA DESCRIPTOR
        6.  PROPRIETARY INTERNAL DATA DESCRIPTOR
        7.  PROPRIETARY INTERNAL DATA DESCRIPTOR
        8.  PROPRIETARY INTERNAL DATA DESCRIPTOR
        9.  PROPRIETARY INTERNAL DATA DESCRIPTOR
    3.  Encryption
        1.  PROPRIETARY INTERNAL DATA DESCRIPTOR
        2.  PROPRIETARY INTERNAL DATA DESCRIPTOR
        3.  PROPRIETARY INTERNAL DATA DESCRIPTOR
        4.  PROPRIETARY INTERNAL DATA DESCRIPTOR
        5.  PROPRIETARY INTERNAL DATA DESCRIPTOR
        6.  PROPRIETARY INTERNAL DATA DESCRIPTOR
        7.  PROPRIETARY INTERNAL DATA DESCRIPTOR
        8.  PROPRIETARY INTERNAL DATA DESCRIPTOR
        9.  PROPRIETARY INTERNAL DATA DESCRIPTOR
        10. PROPRIETARY INTERNAL DATA DESCRIPTOR
        11. PROPRIETARY INTERNAL DATA DESCRIPTOR
    4.  Employee Devices
        1.  PROPRIETARY INTERNAL DATA DESCRIPTOR
        2.  PROPRIETARY INTERNAL DATA DESCRIPTOR
        3.  PROPRIETARY INTERNAL DATA DESCRIPTOR
        4.  PROPRIETARY INTERNAL DATA DESCRIPTOR
        5.  PROPRIETARY INTERNAL DATA DESCRIPTOR
        6.  PROPRIETARY INTERNAL DATA DESCRIPTOR
        7.  PROPRIETARY INTERNAL DATA DESCRIPTOR
        8.  PROPRIETARY INTERNAL DATA DESCRIPTOR
        9.  PROPRIETARY INTERNAL DATA DESCRIPTOR
        10. PROPRIETARY INTERNAL DATA DESCRIPTOR
        11. PROPRIETARY INTERNAL DATA DESCRIPTOR
        12. PROPRIETARY INTERNAL DATA DESCRIPTOR
    5.  Controls & Staff Training
        1.  PROPRIETARY INTERNAL DATA DESCRIPTOR
        2.  PROPRIETARY INTERNAL DATA DESCRIPTOR
        3.  PROPRIETARY INTERNAL DATA DESCRIPTOR
        4.  PROPRIETARY INTERNAL DATA DESCRIPTOR
        5.  PROPRIETARY INTERNAL DATA DESCRIPTOR
        6.  PROPRIETARY INTERNAL DATA DESCRIPTOR
3. Detect
    1. Penetration Testing
        1.  PROPRIETARY INTERNAL DATA DESCRIPTOR
        2.  PROPRIETARY INTERNAL DATA DESCRIPTOR
        3.  PROPRIETARY INTERNAL DATA DESCRIPTOR
        4.  PROPRIETARY INTERNAL DATA DESCRIPTOR
        5.  PROPRIETARY INTERNAL DATA DESCRIPTOR
        6.  PROPRIETARY INTERNAL DATA DESCRIPTOR
        7.  PROPRIETARY INTERNAL DATA DESCRIPTOR
        8.  PROPRIETARY INTERNAL DATA DESCRIPTOR
    2. Intrusion
        1.  PROPRIETARY INTERNAL DATA DESCRIPTOR
        2.  PROPRIETARY INTERNAL DATA DESCRIPTOR
        3.  PROPRIETARY INTERNAL DATA DESCRIPTOR
        4.  PROPRIETARY INTERNAL DATA DESCRIPTOR
        5.  PROPRIETARY INTERNAL DATA DESCRIPTOR
        6.  PROPRIETARY INTERNAL DATA DESCRIPTOR
        7.  PROPRIETARY INTERNAL DATA DESCRIPTOR
        8.  PROPRIETARY INTERNAL DATA DESCRIPTOR
        9.  PROPRIETARY INTERNAL DATA DESCRIPTOR
        10. PROPRIETARY INTERNAL DATA DESCRIPTOR
        11. PROPRIETARY INTERNAL DATA DESCRIPTOR
        12. PROPRIETARY INTERNAL DATA DESCRIPTOR
4. Response Plan
    1. PROPRIETARY INTERNAL DATA DESCRIPTOR
    2. PROPRIETARY INTERNAL DATA DESCRIPTOR
    3. PROPRIETARY INTERNAL DATA DESCRIPTOR
    4. PROPRIETARY INTERNAL DATA DESCRIPTOR
    5. PROPRIETARY INTERNAL DATA DESCRIPTOR
    6. PROPRIETARY INTERNAL DATA DESCRIPTOR
5. Recovery
    1. PROPRIETARY INTERNAL DATA DESCRIPTOR
    2. PROPRIETARY INTERNAL DATA DESCRIPTOR
    3. PROPRIETARY INTERNAL DATA DESCRIPTOR
    4. PROPRIETARY INTERNAL DATA DESCRIPTOR
    5. PROPRIETARY INTERNAL DATA DESCRIPTOR
    6. PROPRIETARY INTERNAL DATA DESCRIPTOR

## 5.3. Configure up to (3) Financial Accounts Views
1. All Financial Accounts
2. Primary Financial Accounts
3. Active Financial Accounts

## 5.4. Configure Page layouts
1. Edited Page Layouts for Standard Objects which included changing the look and feel of page layouts for standard Salesforce objects.
2. Edited Page Layouts for Custom and External Objects which included changing the look and feel of page layouts for custom and external objects.
3. Set Page Layouts and Field-Level Security
4. Assigned Page Layouts to Profiles and Record Types
5. Assigned Page Layouts from Customized Page Layouts and Record Type Pages
6. Built Page Layouts for Custom Objects
7. Added expanded lookups, components, and Visualforce pages to the Mobile Cards section of page layouts so that they will show up as mobile cards in the Salesforce mobile app.
8. Customized Related Lists
9. Customized Detail Page Buttons

Notes:
When you customize your page layouts in Salesforce Classic, those changes can affect the content of object record pages in Lightning Experience. However, in Lightning Experience, the page elements display differently, and some aren’t supported.


# 6. Opportunity Management

## 6.1. Add up to (15) custom Opportunity fields

## 6.2. Configure Page layouts
1. Edited Page Layouts for Standard Objects which included changing the look and feel of page layouts for standard Salesforce objects.
2. Edited Page Layouts for Custom and External Objects which included changing the look and feel of page layouts for custom and external objects.
3. Set Page Layouts and Field-Level Security
4. Assigned Page Layouts to Profiles and Record Types
5. Assigned Page Layouts from Customized Page Layouts and Record Type Pages
6. Edited Multi-Line Layouts for Opportunity Products
7. Built Page Layouts for Custom Objects
8. Added expanded lookups, components, and Visualforce pages to the Mobile Cards section of page layouts so that they will show up as mobile cards in the Salesforce mobile app.
9. Customized Related Lists
10. Customized Detail Page Buttons

Notes:
When you customize your page layouts in Salesforce Classic, those changes can affect the content of object record pages in Lightning Experience. However, in Lightning Experience, the page elements display differently, and some aren’t supported.

## 6.3. Configure up to (3) Opportunity Views
1. All Opportunities
2. Current Opportunities
3. Potential Opportunties

## 6.4. Configure Opportunity Stages to match your sales process
1.	Prospecting
2.	Qualification
3.	Needs Analysis
4.	Value Proposition
5.	Id. Decision Makers
6.	Perception Analysis 
7.	Proposal/Price Quote
8.	Negotiation/Review
9.	Closed Won
10.	Closed Lost


# 7. Data Migration

## 7.1. Import existing Wealthbox Companies and Contacts from (1) customer provided clean .csv file
1. Was never provided with a formatted upload file.
2. Spent 3 weeks customizing, cleaning, and sanitizing data in accordance with Salesforce Person Accounts and Addepar custom integration.
3. Data was fully imported on 06/27/2018.

# 8. Activity Management

## 8.1. Activities tracking process for management of Tasks, Events and Logged Calls

## 8.2. Create up to (5) custom task and event fields
1.	Expectations
2.	Household
3.	NextSteps
4.	Objectives
5.	Regarding



# 9. Reporting

## 9.1. Create up to (3) Opportunity reports
1. Opportunity pipeline
2. Opportunities by Amount
3. Opportunities by Prospect

## 9.2. Create up to (3) Activity reports
1. Tasks with Opportunities
2. Calls by person
3. Calls this week

## 9.3. Create up to (3) custom dashboards
1. Compliance: Identify and Assess Risks
2. Compliance: Protect
3. Compliance: Detect


# 10. Training

## 10.1. Prepare and deliver (1), 60-minute virtual training session for end users
https://resources.docs.salesforce.com/204/latest/en-us/sfdc/pdf/basics.pdf

# EXHIBITS

## EXHIBIT 1

### ATTACHMENTS
Basic examples of BPM simplified for smaller businesses

## EXHIBIT 2

### ATTACHMENTS
Custom lead fields created
Custom lead  views created
Custom lead page layouts created

## EXHIBIT 3

### ATTACHMENTS
Custom individual fields created
Custom individual  views created
Custom individual page layouts created
Custom individual validation rules created

## EXHIBIT 4

### ATTACHMENTS
Custom household fields created
Custom household  views created
Custom household page layouts created

## EXHIBIT 5

### ATTACHMENTS
Custom financial account fields created with list of standard objects modified
Custom financial account objects created with list of custom fields created
Custom financial account  views created
Custom financial account  page layouts created

## EXHIBIT 6

### ATTACHMENTS
Custom opportunity fields created
Custom opportunity  views created
Custom opportunity page layouts created
Examples of a sales process that would be required in order to deliver custom opportunity stages created

## EXHIBIT 7

### ATTACHMENTS
csv attachment of migrated Wealthbox data

## EXHIBIT 8

### ATTACHMENTS
Custom process for management of Tasks, Events and Logged Calls
Custom task and event fields created

## EXHIBIT 9

### ATTACHMENTS
Opportunity pipeline report
Opportunities by Amount report
Opportunities by Prospect report

## EXHIBIT 10

### ATTACHMENTS
Configuration workbook detailing salesforce instance architecture
