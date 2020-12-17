# {{companyName}}

{{offerDate as "MMMM DD YYYY"}}  
  
{{#clause offerClause}}  
Dear {{applicantName}}  
  
We’re delighted to offer for Internship position of {{internshipPosition}} with {{companyName}}. Please review this summary of terms and conditions for your anticipated position with us.  
  
If you accept this offer, your full-time internship work will start on {{internshipStartDate  as "MMMM DD YYYY"}} and ends on {{internshipEndDate  as "MMMM DD YYYY"}}  
{{/clause}}  
  
{{#clause responsibilitiesClause}}  
### Responsibilities  
{{#join responsibilities}}  
    {{responsibility}}  
{{/join}}  
{{/clause}}  
  
{{#clause cashCompensationClause}}
### Cash Compensation and Other Benefits.  
The Company will pay you {{fullTimeStipend as "K 0,0.00"}} for Full-time ({{%cashCompensationClause.fullTimeDuration.workingHours%}} per day, {{%cashCompensationClause.fullTimeDuration.workingDays%}} a week) and {{partTimeStipend as "K 0,0.00"}} for part-time (minimum {{%cashCompensationClause.partTimeDuration.workingHours%}} per day, {{%cashCompensationClause.partTimeDuration.workingDays%}} a week)  
{{/clause}}  
  
{{#clause proprietaryInformationClause}}
### Proprietary Information and Inventions Agreement.  
You will be required, as a condition of this position with the Company, to sign the Company’s standard Proprietary Information and Inventions Agreement. This will be provided during your 1st week of work.
{{/clause}}  
  
{{#clause offerExpirationClause}}  
You may indicate your agreement with these terms and accept this offer by signing and dating this agreement on or before {{offerExpirationDate  as "MMMM DD YYYY HH:ssZ"}}. Upon your acceptance of this offer, {{companyName}} will provide you with the necessary tools, access to systems to begin your work.  
{{/clause}}  
  
Sincerely,  
  
Signatures:

___________________________________________________
Company Representative (Sign and Date)

___________________________________________________
Company Representative (Sign and Date)

___________________________________________________
Applicant (Sign and Date)