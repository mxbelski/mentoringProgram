
***
# mqube-extract-service

Generates reports required for fince, then uploads them to a file share med Extract with a datetime stamp.

| AR Number | Column Descriptions                                   | Is Mapped |  Hardcoded Value |                                                           |
| --------- | ----------------------------------------------------- | --------- | --------------- | -- |
| AR1       | PoolCutOffDate                                        | &check;   |                 |                                                                     |
| AR2       | PoolIdentifier                                        | &check;   |                |                                                                     |
| AR3       | LoanIdentifier                                        | &check;   |               |                                                                     |
| AR4       | RegulatedLoan                                         | &cross;   |                 |                                                                     |
| AR5       | Origitor                                              | &check;   |                |                                                                     |
| AR6       | ServicerIdentifier <br> *What happens if we use another servicer?* | &check;   |LMSL01  |
| AR7       | BorrowerIdentifier <br> *Needs borrowerId generating for older users*  | &check;   |                
| AR8       | PropertyIdentifier                                    | &check;   |                  |                                                                     
| AR9       | Blank1                                                | &check;   |                 |                                                                     
| AR10      | Blank2                                                | &check;   |                 |                                                                    
| AR11      | Blank3                                                | &check;   |                 |                                                                    
| AR12      | Blank4                                                | &check;   |                 |                                                                     
| AR13      | Blank5                                                | &check;   |                  |                                                                     
| AR14      | Blank6                                                | &check;   |                 |                                                                     
| AR15      | BorrowerType                                          | &check;   |                 |                                                                     
| AR16      | Foreigntiol                                           | &cross;   |                |                                                                     
| AR17      | BorrowerCreditQuality                                 | &cross;   |                 |                                                                     
| AR18      | BorrowerYearOfBirth                                   | &cross;   |                 |                                                                     
| AR19      | NumberofDebtors <br> *Using initial questions (which we’re getting rid of)*   | &check; |                    
| AR20      | SecondApplicantYearofBirth                            | &cross;   |                |                                                                     
| AR21      | BorrowersEmploymentStatus                             | &check;   |                 |                                                                     
| AR22      | FirsttimeBuyer                                        | &cross;   |                 |                                                                     
| AR23      | RighttoBuy                                            | &cross;   |                 |                                                                     
| AR24      | RighttoBuyPrice                                       | &cross;   |                |                                                                     
| AR25      | ClassofBorrower                                       | &cross;   |                  |                                                                     |
| AR26      | PrimaryIncome                                         | &check;   |                 |                                                                     
| AR27      | IncomeVerificationforPrimaryIncome <br> *This doesn't look correct in the code*                  | &check;|          
| AR28      | SecondaryIncome                                       | &check;   | 0 |              |                                                                     
| AR29      | IncomeVerificationforSecondaryIncome                  | &cross;   |                       |                                                                     
| AR30      | Resident                                              | &cross;   |                       |                                                                     
| AR31      | NumberofCountyCourtJudgementsOrEquivalentSatisfied    | &check;   |                       |                                                                     
| AR32      | ValueofCountyCourtJudgementsOrEquivalentSatisfied     | &check;   |                       |                                                                     
| AR33      | NumberofCountyCourtJudgementsOrEquivalentUnsatisfied  | &check;   |                  |                                                                     
| AR34      | ValueofCountyCourtJudgementsOrEquivalentUnsatisfied   | &check;   |                 |                                                                     
| AR35      | LastCountyCourtJudgementsorequivalentDate             | &cross;   |                  |                                                                     
| AR36      | BankruptcyOrIndividualVoluntaryArrangementFlag        | &check;   |                 |                                                                     
| AR37      | BureauKredietRegistratie1to10CreditType               | &cross;   |                  |                                                                     
| AR38      | BureauKredietRegistratie1to10RegistrationDate         | &cross;   |                  |                                                                     
| AR39      | BureauKredietRegistratie1to10ArrearsCode              | &cross;   |                  |                                                                     
| AR40      | BureauKredietRegistratie1to10CreditAmount             | &cross;   |                  |                                                                     
| AR41      | BureauKredietRegistratie1to10IsCodingCured            | &cross;   |                  |                                                                     
| AR42      | BureauKredietRegistratie1to10NumberofMonthsSinceCured | &cross;   |                  |                                                                     
| AR43      | BureauScoreProvider                                   | &check;   |                 |                                                                     
| AR44      | BureauScoreType                                       | &check;   |                  |                                                                     
| AR45      | BureauScoreDate                                       | &check;   |                  |                                                                     
| AR46      | BureauScoreValue                                      | &check;   |                 |                                                                     
| AR47      | PriorRepossessions                                    | &cross;   |                  |                                                                     
| AR48      | PreviousMortgageArrears06Months                       | &cross;   |                 |                                                                     
| AR49      | PreviousMortgageArrears6Months                        | &cross;   |                 |                                                                     
| AR50      | InterlRating                                          | &cross;   |                  |                                                                     
| AR51      | Blank7                                                | &check;   |                |                                                                     
| AR52      | Blank8                                                | &check;   |              |                                                                     
| AR53      | Blank9                                                | &check;   |              |                                                                     
| AR54      | Blank10                                               | &check;   |             |                                                                     
| AR55      | LoanOrigitionDate                                     | &check;   |                  |                                                                     
| AR56      | DateofLoanMaturity                                    | &check;   |                 |                                                                     
| AR57      | AccountStatusDate                                     | &cross;   |                 |                                                                     
| AR58      | OrigitionChannelArrangingBankOrDivision               | &check;   | Broker |         |                                                                     
| AR59      | Purpose                                               | &check;   |                  |                                                                     
| AR60      | SharedOwnership                                       | &cross;   |                  |                                                                     
| AR61      | LoanTerm                                              | &check;   |                  |                                                                     
| AR62      | PrincipalGracePeriod                                  | &cross;   |                  |                                                                     
| AR63      | AmountGuaranteed                                      | &cross;   |                  |                                                                     
| AR64      | Subsidy                                               | &cross;   |                  |                                                                     
| AR65      | LoanCurrencyDenomition                                | &check;   |  GBP |            |                                                                     
| AR66      | OriginalBalance                                       | &check;   |                |                                                                     
| AR67      | CurrentBalance <br> *Is the same as original balance (do we need to pull this from lmsl)*                                       | &check; |  
| AR68      | FractionedSubrogatedLoans                             | &cross;   |                 |                                                                     
| AR69      | RepaymentMethod <br> *Pulls from initial questions*   | &check; |  |                                   
| AR70      | PaymentFrequency                                      | &check;   | Monthly |     
| AR71      | PaymentDue                                            | &cross;   |       |                                                                                  
| AR72      | PaymentType                                           | &check;   | Linear|             |                                                                     
| AR73      | DebttoIncome                                          | &cross;   |                |                                                                     
| AR74      | TypeofGuaranteeProvider                               | &cross;   |                  |                                                                     
| AR75      | GuaranteeProvider                                     | &cross;   |                 |                                                                     
| AR76      | IncomeGuarantor                                       | &cross;   |                 |                                                                     
| AR77      | SubsidyReceived                                       | &cross;   |              |                                                                     
| AR78      | MortgageIndemnityGuaranteeProvider                    | &cross;   |                  |                                                                     
| AR79      | MortgageIndemnityGuaranteeAttachmentPoint             | &cross;   |                  |                                                                     
| AR80      | PriorBalances                                         | &cross;   |                  |                                                                     
| AR81      | OtherPriorBalances                                    | &cross;   |                 |                                                                     
| AR82      | PariPassuLoans                                        | &cross;   |                  |                                                                     
| AR83      | SuborditedClaims                                      | &cross;   |                  |                                                                     
| AR84      | Lien <br> *No idea what this column is meant to be*    | &check;   | Lien |           |                              
| AR85      | RetainedAmount                                        | &cross; |  |                                                                   
| AR86      | RetainedAmountDate                                    | &cross;   |                 |                                                                     
| AR87      | MaximumBalance                                        | &cross;   |                  |                                                                     
| AR88      | FurtherLoadvance                                      | &cross;   |                  |                                                                     
| AR89      | FurtherLoadvanceDate                                  | &cross;   |                  |                                                                     
| AR90      | FlexibleLoamount                                      | &cross;   |                 |                                                                     
| AR91      | FurtherAdvances                                       | &cross;   |                  |                                                                     
| AR92      | LengthofPaymentHoliday                                | &cross;   |                  |                                                                     
| AR93      | SubsidyPeriod                                         | &cross;   |                |                                                                     
| AR94      | MortgageInscription                                   | &cross;   |                |                                                                     
| AR95      | MortgageMandate                                       | &cross;   |                |                                                                     
| AR96      | DeedOfPostponement                                    | &cross;   |                 |                                                                     
| AR97      | PrepaymentAmount                                      | &cross;   |                |                                                                     
| AR98      | PrepaymentDate                                        | &cross;   |               |                                                                     
| AR99      | PrepaymentPelties                                     | &cross;   |                |                                                                     
| AR100     | CumulativePrepayments                                 | &cross;   |                |                                                                     
| AR101     | AmountOfPrepaymentsAllowedPerYear                     | &cross;   |                  |                                                                     
| AR102     | OffsetSavingsBalance                                  | &cross;   |              |                                                                     
| AR103     | OrigilPercentageOwned                                 | &cross;   |                |                                                                     
| AR104     | CurrentPercentageOwned                                | &cross;   |                  |                                                                     
| AR105     | HelptoBuySchemeType                                   | &cross;   |               |                                                                     
| AR106     | Blank11                                               | &cross;   |                |                                                                     
| AR107     | InterestRateType                                      | &check;   |              |                                                                     
| AR108     | CurrentInterestRateIndex                              | &cross;   |                |                                                                     
| AR109     | CurrentInterestRate                                   | &check;   |                 |                                                                     
| AR110     | CurrentInterestRateMargin                             | &check;   |                 |                                                                     
| AR111     | InterestRateResetInterval                             | &cross;   |                  |                                                                     
| AR112     | InterestCapRate                                       | &cross;   |               |                                                                     
| AR113     | InterestRevisionDate1                                 | &check;   |                 |                                                                     
| AR114     | RevisionMargin2                                       | &cross;   |             |                                                                     
| AR115     | InterestRevisionDate2                                 | &cross;   |                |                                                                     |
| AR116     | RevisionMargin3                                       | &cross;   |                  |                                                                     
| AR117     | InterestRevisionDate3                                 | &cross;   |                 |                                                                     
| AR118     | RevisedInterestRateIndex                              | &check;   | BoEBaseRate |     |                                                                     
| AR119     | RevisedInterestRateMargin                             | &check;   |                  |                                                                     
| AR120     | FinalMargin                                           | &check;   |                 |                                                                     
| AR121     | FinalStepDate                                         | &cross;   |                 |                                                                     
| AR122     | RestructuringArrangement                              | &cross;   |                  |                                                                     
| AR123     | ForbearanceType                                       | &cross;   |                |                                                                     
| AR124     | Blank12                                               | &cross;   |                 |                                                                     
| AR125     | Blank13                                               | &cross;   |                  |                                                                     
| AR126     | Blank14                                               | &cross;   |                |                                                                     
| AR127     | Blank15                                               | &cross;   |                 |                                                                     
| AR128     | GeographicRegion                                      | &cross;   |                |                                                                     
| AR129     | PropertyPostcode                                      | &cross;   |                  |                                                                     
| AR130     | OccupancyType                                         | &check;   |                  |                                                                     
| AR131     | PropertyType                                          | &check;   |                 |                                                                     
| AR132     | NewProperty                                           | &cross;   |                 |                                                                     
| AR133     | ConstructionYear                                      | &cross;   |              |                                                                     
| AR134     | PropertyRating                                        | &cross;   |                  |                                                                     
| AR135     | OriginalLoantoValue                                   | &check;   |                  |                                                                     
| AR136     | ValuationAmount                                       | &check;   |                |                                                                     
| AR137     | OriginalValuationType                                 | &check;   | FullInternalAndExternalInspection |                                                   
| AR138     | ValuationDate                                         | &check;   |                 |                                                                     
| AR139     | ConfidenceIntervalforOriginalAutomatedValuationModelValuation| &cross;   |                   |                                                             
| AR140     | ProviderofOriginalAutomatedValuationModelValuation    | &cross;   |                       |                                                                     
| AR141     | CurrentLoantoValue                                    | &check;   |                     |                                                                     
| AR142     | PurchasePrice                                         | &cross;   |                     |                                                                     
| AR143     | CurrentValuationAmount                                | &check;   |                       |                                                                     
| AR144     | CurrentValuationType                                  | &check;   | FullInternalAndExternalInspection                 |                                   
| AR145     | CurrentValuationDate                                  | &check;   |                |                                                                     
| AR146     | ConfidenceIntervalforCurrentAutomatedValuationModelValuation| &cross;   |                 |                                                               
| AR147     | ProviderofCurrentAutomatedValuationModelValuation     | &cross;   |               |                                                                     
| AR148     | PropertyValueatTimeofLatestLoanAdvance                | &cross;   |                |                                                                     
| AR149     | IndexedForeclosureValue                               | &cross;   |                  |                                                                     
| AR150     | Ipoteca                                               | &cross;   |                  |                                                                     
| AR151     | DateofSale                                            | &cross;   |              |                                                                     
| AR152     | AdditionalCollateral                                  | &cross;   |                 |                                                                     
| AR153     | AdditionalCollateralProvider                          | &cross;   |               |                                                                     
| AR154     | GrossAnnualRentalIncome                               | &check;   |                 |                                                                     
| AR155     | NumberOfBuyToLetProperties                            | &check;   |              |                                                                     
| AR156     | DebtServiceCoverageRatio                              | &check;   |               |                                                                     
| AR157     | AdditionalCollateralValue                             | &cross;   |               |                                                                     
| AR158     | RealEstateOwned                                       | &cross;   |                |                                                                     
| AR159     | IsPropertyTransferabilityLimited                      | &cross;   |                |                                                                     
| AR160     | TimeUntilDeclassification                             | &cross;   |              |                                                                     
| AR161     | Blank16                                               | &cross;   |              |                                                                     
| AR162     | Blank17                                               | &cross;   |            |                                                                     
| AR163     | Blank18                                               | &cross;   |                 |                                                                     
| AR164     | Blank19                                               | &cross;   |                  |                                                                     
| AR165     | Blank20                                               | &cross;   |                 |                                                                     
| AR167     | DateLastCurrent                                       | &cross;   |                 |                                                                     
| AR168     | DateLastinArrears                                     | &cross;   |             |                                                                     
| AR169     | ArrearsBalance                                        | &cross;   |                 |                                                                     
| AR170     | NumberMonthsinArrears                                 | &cross;   |             |                                                                     
| AR171     | Arrears1MonthAgo                                      | &cross;   |               |                                                                     
| AR172     | Arrears2MonthsAgo                                     | &cross;   |                |                                                                     
| AR173     | PerformanceArrangement                                | &cross;   |                |                                                                     
| AR174     | Litigation                                            | &cross;   |                  |                                                                     
| AR175     | RedemptionDate                                        | &cross;   |                |                                                                     
| AR176     | MonthsinArrearsPrior                                  | &cross;   |               |                                                                     
| AR177     | DefaultOrForeclosure                                  | &cross;   |               |                                                                     
| AR178     | DateOfDefault                                         | &cross;   |                |                                                                     
| AR179     | SalePrice                                             | &cross;   |                |                                                                     
| AR180     | LossOnSale                                            | &cross;   |                  |                                                                     
| AR181     | CumulativeRecoveries                                  | &cross;   |             |                                                                     
| AR182     | ProfessionalNegligenceRecoveries                      | &cross;   |                 |                                                                     
| AR183     | LoanflaggedasContencioso                              | &cross;   |               |                                                                     
| AR184     | Blank21                                               | &cross;   |            |                                                                     
| AR185     | Blank22                                               | &cross;   |                  |                                                                     
| AR186     | Blank23                                               | &cross;   |                 |                                                                     
| AR187     | Blank24                                               | &cross;   |                 |                                                                     
| AR188     | Blank25                                               | &cross;   |                 |                                                                     
| AR189     | SecondBorrowerEmploymentStatus <br> *no primaryApplicant.IncomeTypes.SelfEmployedPartnerInLtd field*                       | &check;|                                        |                                                                     
| AR190     | ClassofSecondBorrower                                 | &cross;   |                     |                                                                     
| AR191     | ResidentSecondBorrower                                | &cross;   |                  |                                                                     
| AR192     | NumberofCountyCourtJudgementsOrEquivalentSatisfiedSecondBorrower                                | &check;   |                |                                                                     
| AR193     | ValueofCountyCourtJudgementsOrEquivalentSatisfiedSecondBorrower                                 | &check;   |                                                                                    
| AR194     | NumberofCountyCourtJudgementsOrEquivalentUnsatisfiedSecondBorrower                                 | &check;   |                                                                                    
| AR195     | ValueofCountyCourtJudgementsOrEquivalentUnsatisfiedSecondBorrower                                 | &check;   |                                                                                 
| AR196     | LastCountyCourtJudgementsOrEquivalentDateSecondBorrower                                 | &cross;   |                                                                                        
| AR197     | BankruptcyorIndividualVoluntaryArrangementFlagSecondBorrower                                 | &check;   |                                                                          |
| AR198     | BureauKredietRegistratie1to10CreditTypeSecondBorrower                                 | &cross;   |                                                                                       
| AR199     | BureauKredietRegistratie1to10RegistrationDateSecondBorrower                                 | &cross;   |                                                                         
| AR200     | BureauKredietRegistratie1to10ArrearsCodeSecondBorrower                                 | &cross;   |                                                     
| AR201     | BureauKredietRegistratie1to10CreditAmountSecondBorrower                                 | &cross;   |                    
| AR202     | BureauKredietRegistratie1to10IsCodingCuredSecondBorrower                                 | &cross;   |                   
| AR203     | BureauKredietRegistratie1to10NumberofMonthsSinceCuredSecondBorrower                                 | &cross;   |                                                                        
| AR204     | BureauScoreProviderSecondBorrower                                 | &check;   |                |                                                                  
| AR205     | BureauScoreTypeSecondBorrower                                 | &check;   | Other      |  |                                                                                                           
| AR206     | BureauScoreDateSecondBorrower                                 | &check;   |               |                                                                     
| AR207     | BureauScoreValueSecondBorrower                                 | &check;   |                  |                                                                     
| AR208     | PriorRepossessionsSecondBorrower                                 | &cross;   |                  |                                                                     
| AR209     | PreviousMortgageArrears06MonthsSecondBorrower                    | &cross;   |                 |                                                                     
| AR210     | PreviousMortgageArrears6MonthsSecondBorrower                                 | &cross;   |                |                                                                    
| AR211     | BureauKredietRegistratie1to10CreditTypePrimaryBorrowerAtOrigination                                 | &cross;   |                                                                      
| AR213     | BureauKredietRegistratie1to10ArrearsCodePrimaryBorrowerAtOrigination                                 | &cross;   |                                                                                       
| AR214     | BureauKredietRegistratie1to10CreditAmountPrimaryBorrowerAtOrigination                                 | &cross;   |                                                                         
| AR215     | BureauKredietRegistratie1to10IsCodingCuredPrimaryBorrowerAtOrigination                                 | &cross;   |                                                                      |
| AR216     | BureauKredietRegistratie1to10NumberofMonthsSinceCuredPrimaryBorrowerAtOrigination                                 | &cross;   |                                                                                 
| AR217     | BureauScoreProviderPrimaryBorrowerAtOrigination <br> *Repeat of AR43*                                | &check;|
| AR218     | BureauScoreTypePrimaryBorrowerAtOrigination <br> *Repeat of AR44*                                | &check;|                                                                                                                
| AR220     | BureauScoreValuePrimaryBorrowerAtOrigination <br> *Repeat of AR46*                                | &cross;   |                                                                                                                                           
| AR221     | BureauKredietRegistratie1to10CreditTypeSecondaryBorrowerAtOrigination                                 | &cross;   |                                                                     
| AR222     | BureauKredietRegistratie1to10RegistrationDateSecondaryBorrowerAtOrigination                                 | &cross;   |                 
| AR223     | BureauKredietRegistratie1to10ArrearsCodeSecondaryBorrowerAtOrigination                                 | &cross;   |                
| AR224     | BureauKredietRegistratie1to10CreditAmountSecondaryBorrowerAtOrigination                                 | &cross;   |                 
| AR225     | BureauKredietRegistratie1to10IsCodingCuredSecondaryBorrowerAtOrigination                                 | &cross;   | 
| AR226     | BureauKredietRegistratie1to10NumberofMonthsSinceCuredSecondaryBorrowerAtOrigination                                 | &cross;   |                  
| AR227     | BureauScoreProviderSecondaryBorrowerAtOrigination <br> *Repeat of AR204*                                | &check;   |   
| AR228      | BureauScoreTypeSecondaryBorrowerAtOrigination <br> *Repeat of AR205*                                    | &check;   |                                                               
| AR230      | BureauScoreValueSecondaryBorrowerAtOrigination  <br> *Repeat of AR207*                                          | &check;   |                                                                   
| AR231      | BorrowerTypeSecondaryBorrower                                           | &cross;   |        
| AR232      | ForeignNationalSecondaryBorrower                                           | &cross;  |         
| AR233      | BorrowerCreditQualitySecondaryBorrower                                           | &cross;  |       
| AR234      | FirstTimeBuyerSecondaryBorrower                                           | &cross;   |  
| AR235      | BankruptcyorIndividualVoluntaryArrangementFlagDupe <br> *repeat of AR036*                         | &check;   |                                                                   
| AR236      | BankruptcyOrIndividualVoluntaryArrangementFlagSecondBorrowerDupe <br> *repeat of AR197*           | &check;   |           
| AR237      | IOSwitch                                               | &cross;   |                                                                          
| AR238      | ArrangementEndDate                                     | &cross;|
| AR239      | CapitalisedArrears                                     | &cross;      |                                                                   
| AR240      | CapitalisedAmount                                      | &cross;   |            
| AR241      | CapitalisedDate                                        | &cross;   |        
| AR242      | Tenure                                                 | &check;   |       
| AR243      | Lease                                                  | &check;   |           
| AR244      | PrincipalBalance <br> *needs to be reviewed*           | &check;   |
| AR245      | OriginationFee <br> *TODO: waiting on calculation*      | &check; |       
| AR246      | CurrentCumulativeFees <br> *needs further clarification* | &cross;   |          
| AR247      | InterestChargedSinceMonthEnd                           | &cross;   |            
| AR248      | CaseReference                                          | &check;   |            
| AR249      | BrokerOrIntroducer                                     | &check;   |           
| AR250      | BrokerOrIntroducerFee <br> *entry.BrokerOrIntroducerFee = TODO*  | &cross;   |           
| AR251      | UnderwriterID                                          | &check;   |             
| AR252      | LoanException <br> *TODO needs futher clarification*   | &cross;   |             
| AR253      | ErrorLoan                                             | &cross;   |          
| AR254      | Valuer                                                | &check;   |          
| AR255      | EPCRating                                              | &check;   |           
| AR256      | HMOOrMUFB <br> *This runs off of product but there are no suitable fields to use*                                             | &check;|
| AR257      | ProductFee <br> *TODO CHANGED TO GET BY TYPE*  | &check;   |    
| AR258      | ProductCode                                           | &check;   |          
| AR259      | PropertyOverCommercial <br> *needs further clarification*  | &cross;   |    
| AR260      | PaymentHolidayAgreed                                   | &cross;   |         
| AR261      | MonthsAgreed                                           | &cross;   |          
| AR262      | PaymentHolidayStartDate                                | &cross;   |            
| AR263      | ERC1                                                   | &check;   |         
| AR264      | ERC2                                                   | &check;   |       
| AR265      | ERC3                                                   | &check;   |       
| AR266      | ERC4                                                   | &check;   |           
| AR267      | ERC5                                                   | &check;   |     
| AR268      | KanbanStage                                            | &check;   |         
| AR269      | KanbanStageGroupingLevel                               | &check;   |         
| AR270      | OfferDate                                              | &check;   |         
| AR271      | ApplicationDate                                        | &check;   |       
| AR272      | ProductDescription                                     | &check;   |           
